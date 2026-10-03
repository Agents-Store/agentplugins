# nocodb-ops (Agent Plugins 1.0)

NocoDB ops plugin for Agents Store. Record management, filtering (structured filters, exactDate date filters), sorting, reports, search, webhooks (events, payload, conditions), and data import/export for business users via the NocoDB MCP server (writes in batches of up to 100 records; extra tools on Cloud/licensed through listTools/callTool) and curl on the v3 API.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 10 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/nocodb-ops
