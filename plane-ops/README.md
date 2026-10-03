# plane-ops (Agent Plugins 1.0)

Plane Agile Ops knowledge plugin: sprint planning, task decomposition, estimation, backlog management, velocity tracking, retrospectives, standups, intake triage, modules, epics, initiatives, milestones, roadmaps, dependencies, burndown, pages (sprint reports, retros, release notes, ADRs, runbooks, specs, meeting notes), labels, workflow states, work item types, custom properties, comments, links, work logs, relations, history, bulk edits, search, members, and assignment. Written for Plane MCP 0.3.0 and later (one resource tool per entity with an `action` parameter, PQL filters, counts, releases); a bootstrap skill finds the tools under any server name and carries the fallback translation for older per-operation connectors. Ships no MCP server; the user connects Plane.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 17 skill(s) under `skills/`
- No MCP server
- agents/commands/hooks preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/plane-ops
