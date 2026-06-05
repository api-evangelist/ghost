# Ghost (ghost)

Ghost is an open-source publishing platform with hosted (Ghost(Pro)) and self-hosted options. It exposes a write-capable Admin API and a read-only Content API plus webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml)

## Tags

- Publishing
- Newsletters
- Memberships
- Content
- Open Source

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Ghost Admin API

The Ghost Admin API provides full read/write access to posts, pages, tags, tiers, newsletters, offers, members, users, images, themes, webhooks, and site configuration. Authentication uses short-lived JWTs derived from an admin API key, staff access tokens, or session cookies. Requests must include an Accept-Version header.

- **Human URL:** [https://docs.ghost.org/admin-api](https://docs.ghost.org/admin-api)
- **Base URL:** `https://{admin_domain}/ghost/api/admin`

#### Tags

- Publishing
- Content Management
- Members
- Newsletters
- Webhooks

#### Properties

- [Documentation](https://docs.ghost.org/admin-api)
- [Authentication](https://docs.ghost.org/admin-api#token-authentication)
- [Webhooks](https://docs.ghost.org/webhooks)
- [SDK](https://github.com/TryGhost/SDK/tree/main/packages/admin-api)
- [Postman Collection](collections/ghost-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ghost-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ghost-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ghost-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ghost Content API

The Ghost Content API is a read-only RESTful API for delivering published content (posts, pages, tags, authors, tiers, settings) to clients. It uses query-parameter Content API keys, is fully cacheable, and is intended to be safe for browser use.

- **Human URL:** [https://docs.ghost.org/content-api](https://docs.ghost.org/content-api)
- **Base URL:** `https://{admin_domain}/ghost/api/content`

#### Tags

- Publishing
- Content
- Read Only
- Public

#### Properties

- [Documentation](https://docs.ghost.org/content-api)
- [Authentication](https://docs.ghost.org/content-api#key)
- [SDK](https://github.com/TryGhost/SDK/tree/main/packages/content-api)
- [Postman Collection](collections/ghost-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ghost-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ghost-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ghost-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ghost-foundation)
- [Website](https://ghost.org/)
- [Portal](https://docs.ghost.org/)
- [GitHub Organization](https://github.com/TryGhost)
- [Source Code](https://github.com/TryGhost/Ghost)
- [Forums](https://forum.ghost.org/)
- [Pricing](https://ghost.org/pricing/)
- [Plans](plans/ghost-plans-pricing.yml)
- [Rate Limits](rate-limits/ghost-rate-limits.yml)
- [Fin Ops](finops/ghost-finops.yml)
- [Integrations](https://ghost.org/integrations)
- [L L Ms Txt](https://docs.ghost.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
