# atlassian-ops (Agent Plugins 1.0)

Atlassian Jira + Confluence Cloud ops plugin. Drive the full Jira Cloud REST API v3 and Confluence Cloud REST API v2 by curl — Jira: issues (create/edit/transition/assign, ADF bodies), JQL search, comments & worklogs, attachments & links, projects/versions/components, fields & screens, workflows/types/statuses, users & groups (accountId), permission/notification/security schemes, dashboards & filters, plans & teams; Confluence: pages & blog posts (versioned, storage/ADF bodies), spaces & permissions, comments & attachments, labels & content properties. Authenticates with Atlassian Cloud Basic auth (ATLASSIAN_EMAIL + ATLASSIAN_API_TOKEN) against ATLASSIAN_SITE_URL.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 6 skill(s) under `skills/`
- No MCP server
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/atlassian-ops
