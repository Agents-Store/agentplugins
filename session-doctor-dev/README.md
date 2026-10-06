# session-doctor-dev (Agent Plugins 1.0)

Read-only audit of a Claude Code session: where it runs, what context it loaded, which model and effort it used, the skills it invoked, every HTTP request with its status code, and the status of each API token seen in the session — with concrete fixes.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 2 skill(s) under `skills/`
- No MCP server

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/session-doctor-dev
