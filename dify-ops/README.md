# dify-ops (Agent Plugins 1.0)

Dify self-hosted update operations plugin. Pre-flight the target release and the bundled Weaviate migration path, back up volumes with the stack down, merge a release tag into the local dev branch, sync .env variables, and pull and restart containers for Dify Docker deployments.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 4 skill(s) under `skills/`
- No MCP server
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/dify-ops
