# taiga-ops (Agent Plugins 1.0)

Taiga project-management ops plugin. Drive the full Taiga REST API by curl — projects, memberships, roles, milestones (sprints), epics, user stories, tasks, issues (with statuses, types, priorities, severities, points, custom attributes), wiki, history, attachments, comments, webhooks, notify policies, search, resolver, stats, and import/export. Authenticates with TAIGA_ADMIN_USERNAME + TAIGA_ADMIN_PASSWORD to obtain TAIGA_AUTH_TOKEN against TAIGA_API_URL.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 5 skill(s) under `skills/`
- No MCP server
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/taiga-ops
