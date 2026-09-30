# vercel-dev (Agent Plugins 1.0)

Vercel ecosystem plugin. Deployment, AI SDK, Edge Functions, storage, routing, performance optimization. Includes CLI deploy troubleshooting for non-Git projects, Hobby plan fixes, standalone output handling. Based on official vercel-plugin v0.51.0 by Vercel Labs; telemetry is opt-in (VERCEL_PLUGIN_TELEMETRY=on).

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 38 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents/commands/hooks preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/vercel-dev
