# AGENTS.md

## Project

This repository owns the public ShioriCode website deployed to `shiori.codes`.
It is intentionally independent from the private Shiori application and the
ShioriCode desktop monorepo.

## Commands

- `bun install`
- `bun run build`
- `bun run typecheck`

Run both build and typecheck before considering changes complete.

## Boundaries

- Keep the site static and deployable on Vercel without private application secrets.
- Product account, billing, documentation, privacy, and authenticated app links belong on `shiori.ai`.
- Desktop binaries are resolved from public `shiorihq/ShioriCode` GitHub releases.

