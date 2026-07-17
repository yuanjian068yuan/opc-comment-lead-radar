# Distribution status

This repository is the public distribution surface for OPC 评论线索雷达. The runtime package is `ppxc-leads-mcp`; the skill and plugin release is `1.0.18`.

| Surface | Artifact in this repository | Current state |
|---|---|---|
| Claude Code | `.claude-plugin/plugin.json`, `.claude-plugin/marketplace.json`, `.mcp.json` | Ready for repository install after this change reaches `main` |
| Cursor | `.cursor-plugin/plugin.json`, `.cursor-plugin/marketplace.json`, `.mcp.json` | Manifest ready; official marketplace listing still requires Cursor review |
| Gemini CLI | `gemini-extension.json`, `GEMINI.md`, `skills/` | Ready for repository install; gallery discovery requires the GitHub topic and crawler review |
| GitHub Copilot | `.github/skills/find-customers/` | Project-skill layout ready; personal installation remains a user-side copy/install step |
| skills.sh and Agent Skills hosts | `skills/ppxc-find-customers/` | Public source layout ready; third-party indexing is verified separately |
| SkillHub / WorkBuddy | `marketplace/skillhub/ppxc-find-customers/` | Adapter ready for the next SkillHub upload |
| MCP Registry | Runtime repository `server.json` plus npm package metadata | Prepared separately; npm publish and registry authentication are separate release gates |

“Ready” means the repository artifact validates locally. It does not mean a third-party marketplace has approved or indexed it.
