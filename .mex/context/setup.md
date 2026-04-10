---
name: setup
description: Edit / commit / push workflow.
triggers:
  - "setup"
last_updated: 2026-04-10
---

# Setup

## Prerequisites

- Git push access to `Seaforged/seaforged-github`
- A markdown-aware editor (VS Code recommended for GitHub preview)

## Workflow

1. Clone or pull
2. Edit `profile/README.md`
3. Preview in VS Code or a markdown previewer
4. Commit: `git commit -am "update product status"`
5. Push: `git push origin main`
6. Verify at github.com/Seaforged

## Common Issues

**Badges broken:** Check shields.io URL encoding. Spaces and special characters need `%20`, `%3A`, etc.

**Product link broken:** The repo may be private or renamed. Update the link or note the repo as `(private)` in the table.
