# n8n (Agent Plugins 1.0)

DEPRECATED — superseded by n8n-dev (building, validating and debugging workflows against both current n8n MCP servers) and n8n-provision (template discovery and batch import). Use those two instead. n8n workflow automation plugin. Manage workflows, execute automations, configure nodes, handle credentials, monitor executions, expression syntax, node configuration patterns, and code node best practices via MCP tools.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 8 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/n8n
