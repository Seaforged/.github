---
name: architecture
description: Profile structure.
triggers:
  - "architecture"
  - "structure"
last_updated: 2026-04-10
---

# Architecture

## System Overview

Single file: `profile/README.md`. Rendered by GitHub as the org landing page. Product table links to each product's repo. Badges at top show brand identity. Brand colors and typography are enforced by the `seaforged-brand` skill.

## Key Components

- **`profile/README.md`** — the only file that matters
- **Product table** — 6 products, links to each repo
- **Badge block** — NDAA, veteran-owned, FAA Part 107, Made in USA

## What Does NOT Exist Here

- No build pipeline — GitHub renders markdown directly
- No CI — no tests, no linting
- No website frontend code — this is markdown only
