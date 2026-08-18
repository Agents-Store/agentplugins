# mattermost-ops (Agent Plugins 1.0)

Mattermost collaboration ops plugin. Drive the full Mattermost REST API v4 by curl — users, teams, channels (public/private/DM/group), posts & threads, reactions, files, custom emoji, webhooks, slash commands, bots, OAuth apps, plus system administration: config, RBAC roles & schemes, LDAP/SAML groups, compliance, data retention, plugins, jobs, and analytics. Authenticates with MATTERMOST_ADMIN_USERNAME + MATTERMOST_ADMIN_PASSWORD to obtain a session token against MATTERMOST_API_URL.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 5 skill(s) under `skills/`
- No MCP server
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/mattermost-ops
