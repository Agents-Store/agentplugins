# nocobase (Agent Plugins 1.0)

DEPRECATED — superseded by nocobase-dev, which bundles the official nocobase/skills library and works through the nb CLI and REST API. Its MCP server package (@nocobase/mcp-server) was withdrawn from npm and is no longer wired; the MCP commands and agents work only if you register your own server named `nocobase`. NocoBase platform development plugin. Expert guidance on collections, fields, relations, workflows, UI blocks, plugin development, MCP-powered page management, data operations, and collection inspection for NocoBase applications.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 7 skill(s) under `skills/`
- No MCP server
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/nocobase
