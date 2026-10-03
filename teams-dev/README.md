# teams-dev (Agent Plugins 1.0)

Microsoft Teams SDK dev plugin for Agents Store. TypeScript guidance for building Teams bots, message extensions, tabs, dialogs and AI agents on Teams SDK 2.1 and Teams Developer CLI 3. Vendors the official microsoft/teams-sdk skill (scaffold, bot registration, SSO setup) and adds skills for the App framework and turn state, Adaptive Cards, openai/MCP/A2A agents, Microsoft Graph, SSO with addOAuthFlow, deployment, sovereign clouds and the Agents Playground.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 17 skill(s) under `skills/`
- No MCP server
- agents/commands preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/teams-dev
