# stack-directus-nextjs-trigger (Agent Plugins 1.0)

Directus + Next.js + Trigger.dev architecture plugin. How Directus (content, files, access), a Next.js App Router frontend and self-hosted Trigger.dev (durable and scheduled work) fit together: who holds which token, how the cache is invalidated, how a Directus change reaches a task and the result reaches the page, who owns the session, and a production checklist. Tool knowledge comes from its dependencies.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 8 skill(s) under `skills/`
- MCP server config in `mcp.json`
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/stack-directus-nextjs-trigger
