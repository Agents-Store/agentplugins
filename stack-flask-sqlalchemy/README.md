# stack-flask-sqlalchemy (Agent Plugins 1.0)

Flask + SQLAlchemy architecture plugin. How the application factory, the Flask-SQLAlchemy session, Alembic migrations and Jinja2 templates fit together: where db is created, the app context, the transaction boundary, expire_on_commit, N+1 at the route-to-template edge, and a full-feature recipe. Tool knowledge comes from its dependencies flask-dev and sqlalchemy-dev.

## Install

Vendor-neutral plugin per the [Agent Plugins 1.0](https://agent-plugins.org) standard — supported by ChatGPT, Codex, Cursor, GitHub Copilot, Kiro, and VS Code. Follow your client's plugin-install flow and point it at this directory.

## Components

- 2 skill(s) under `skills/`
- No MCP server
- agents preserved verbatim under `com.anthropic.claude-code/` (outside Agent Plugins v1 — only clients that understand this namespace will use them)

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/stack-flask-sqlalchemy
