---
name: router
description: Session bootstrap.
edges:
  - target: context/architecture.md
    condition: when changing the profile structure
  - target: context/conventions.md
    condition: when editing the README
  - target: context/decisions.md
    condition: when updating the product roster
last_updated: 2026-04-10
---

# Session Bootstrap

Read `AGENTS.md` first.

## Current Project State

**Working:**
- `profile/README.md` renders the Seaforged org landing page
- Product roster table with 6 products (BS Tuner, D-TECT-R, TIDENET, TRIDENT, SENTRY-RF, JUH-MAK-IN JAMMER)
- Brand identity lines (veteran-owned, NDAA, FAA Part 107, Made in USA)

**Not yet built:**
- Automated status sync from product repos
- Featured project rotation

**Known issues:**
- Product statuses drift — need manual updates when underlying repos change

## Routing Table

| Task | Load |
|------|------|
| Changing profile structure | `context/architecture.md` |
| Editing the README copy | `context/conventions.md` |
| Updating the product roster | `context/decisions.md` |
| Running anything | `context/setup.md` |

## Behavioural Contract

Standard CONTEXT → BUILD → VERIFY → DEBUG → GROW. VERIFY here means: brand colors unchanged, product table renders, badges still at the top, identity lines preserved.
