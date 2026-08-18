# nocobase-dev (Agent Plugins 1.0)

NocoBase v2 development plugin. Build, manage, and operate NocoBase through the `nb` CLI (primary) or REST API (fallback). Bundles 11 official upstream skills from nocobase/skills (auto-synced weekly via GitHub Action), 5 custom REST-API skills (overview, auth, cli-recipes, api-reference, examples), and the full OpenAPI 3.0.3 spec for NocoBase v2.1.0-beta.29 (272 endpoints across 19 tag groups). No MCP server. Env vars match upstream naming: NB_URL + NB_USER + NB_PASSWORD for sign-in flow, or NB_URL + NB_TOKEN for the long-lived API Key path.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 17 skill(s) under `skills/`
- No MCP server

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/nocobase-dev
