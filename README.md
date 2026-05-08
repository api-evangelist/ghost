# Ghost (ghost)

Ghost is an open-source publishing platform with hosted (Ghost(Pro)) and self-hosted options. It exposes a write-capable Admin API and a read-only Content API plus webhooks.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ghost-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Ghost Admin API** — Full read/write at `https://{admin_domain}/ghost/api/admin`. JWT (5-min) from admin API key, staff tokens, or session. Posts, pages, tags, tiers, newsletters, offers, members, users, images, themes, webhooks. Docs: https://docs.ghost.org/admin-api
- **Ghost Content API** — Read-only at `https://{admin_domain}/ghost/api/content`. Query-param Content API key; cacheable. Posts, pages, tags, authors, tiers, settings. Docs: https://docs.ghost.org/content-api

## Tags
- Publishing, Newsletters, Memberships, Content, Open Source

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://ghost.org/)
- [Developer Portal](https://docs.ghost.org/)
- [Source Code (MIT)](https://github.com/TryGhost/Ghost)
- [Pricing](https://ghost.org/pricing/)
- [Plans](plans/ghost-plans-pricing.yml) — reconciled (Self-hosted FOSS, Starter $18, Publisher $29, Business $199, Custom)
- [RateLimits](rate-limits/ghost-rate-limits.yml) — partial (Content API cacheable, Admin JWT 5-min, no published throttle)
- [FinOps](finops/ghost-finops.yml) — FOCUS-aligned, reconciled

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
