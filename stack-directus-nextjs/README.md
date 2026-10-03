# stack-directus-nextjs (Agent Plugins 1.0)

Directus + Next.js architecture plugin. How Directus (content, files, access) and a Next.js App Router frontend fit together: who holds the token, how the cache is invalidated, how assets and types cross the boundary, who owns the session, and a production checklist. Tool knowledge comes from its dependencies.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 6 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/stack-directus-nextjs
