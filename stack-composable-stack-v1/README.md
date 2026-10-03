# stack-composable-stack-v1 (Agent Plugins 1.0)

Composable Stack v1 architecture plugin. How PostgreSQL (direct MCP + PostgREST API), NocoDB, n8n, Trigger.dev, and NocoBase (prod + dev sandbox) fit together for data-driven applications with low-code interfaces: layer roles, data-access selection, integration patterns between services, and project bootstrap. Tool knowledge comes from its dependencies.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 7 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/stack-composable-stack-v1
