# nocodb (Agent Plugins 1.0)

DEPRECATED — superseded by nocodb-dev (schema, fields, views, Meta API) and nocodb-ops (records, search, views, reports), which teach the current NocoDB MCP tool names; this plugin teaches tool names the server no longer exposes. NocoDB database development plugin. Manage tables, records, columns, views, relations, formulas, rollups, lookups, filtering, sorting, search, aggregation, webhooks, and filter/sort management via MCP tools.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 8 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/nocodb
