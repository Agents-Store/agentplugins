# outline-ops (Agent Plugins 1.0)

Outline knowledge-base ops plugin. Drive the full Outline REST API by curl — documents (create, search, move, archive, trash, import/export, AI answers, memberships), collections (CRUD, archive, duplicate, import, user/group permissions, export), comments & reactions, pins, subscriptions, notifications, stars, views, shares & access requests, webhook subscriptions, users & groups, attachments & file operations, revisions, templates, events (audit log), API keys, OAuth clients, and data attributes (154 operations). Also points to Outline's built-in MCP server. Authenticates with a Bearer OUTLINE_API_KEY against OUTLINE_API_URL.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 5 skill(s) under `skills/`
- No MCP server
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/outline-ops
