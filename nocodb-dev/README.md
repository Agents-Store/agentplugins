# nocodb-dev (Agent Plugins 1.0)

NocoDB schema development plugin. Full Meta API v3 coverage — tables, fields (30+ types), views, filters, sorts, hooks (HookV3), comments, scripts, dashboards & widgets, workflows, plus workspaces / members / teams / tokens. Bundles both Data API and Meta API OpenAPI specs.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 12 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/nocodb-dev
