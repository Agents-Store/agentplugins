# sqlalchemy-dev (Agent Plugins 1.0)

SQLAlchemy dev plugin for Agents Store. Typed SQLAlchemy 2.0 style (Mapped, mapped_column, select) with a SQLAlchemy 2.1 section: model definition patterns, relationship mapping, query optimization, Alembic migrations, and troubleshooting.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 6 skill(s) under `skills/`
- No MCP server
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/sqlalchemy-dev
