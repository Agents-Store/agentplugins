# multi-bank (Agent Plugins 1.0)

Multi-Bank Account Manager with broadcast architecture pattern. Aggregates financial data from Monobank and PrivatBank via MCP tools, broadcasts balance updates and budget alerts to subscribed components, categorizes transactions, and exports financial reports in CSV/PDF.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 15 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/multi-bank
