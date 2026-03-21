# Ghost (ghost)
Ghost is an open-source, professional publishing platform built on Node.js that powers blogs, newsletters, and membership-driven content businesses. Their developer platform offers a comprehensive set of APIs including a read-only Content API for delivering published content, a full-featured Admin API for managing all aspects of a publication, webhooks for event-driven integrations, and a Handlebars-based theming system for building custom front-ends.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Content Management, Publishing, Headless CMS, Blogging, Newsletters, Memberships

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Ghost Content API
The Ghost Content API is a RESTful, read-only API that delivers published content from a Ghost site to any client. It provides access to posts, pages, tags, authors, tiers, and settings resources. Access is controlled via a Content API key, and all responses are returned in JSON format. The API supports browse and read request types with powerful filtering using the NQL query language, making it ideal for building custom front-ends, static sites, mobile apps, and other content-driven applications powered by Ghost as a headless CMS.

**Human URL:** [https://ghost.org/docs/content-api/](https://ghost.org/docs/content-api/)


#### Tags:

 - Content Management, Publishing, Headless CMS, Posts, Pages, Tags, Authors

#### Properties

- [Documentation](https://ghost.org/docs/content-api/)
- [OpenAPI](openapi/ghost-content-api-openapi.yml)

### Ghost Admin API
The Ghost Admin API provides full read and write access to all content and configuration within a Ghost publication. It enables developers to create, update, and delete posts, pages, tags, members, tiers, newsletters, and offers programmatically. Authentication is handled via JSON Web Tokens generated from an Admin API key, integration tokens, or staff access tokens. The Admin API supports everything the Ghost Admin interface can do and more, making it suitable for building custom publishing workflows, content automation, member management systems, and advanced integrations.

**Human URL:** [https://ghost.org/docs/admin-api/](https://ghost.org/docs/admin-api/)


#### Tags:

 - Content Management, Publishing, Administration, Members, Newsletters, Tiers, Offers

#### Properties

- [Documentation](https://ghost.org/docs/admin-api/)
- [OpenAPI](openapi/ghost-admin-api-openapi.yml)

### Ghost Webhooks
Ghost Webhooks allow developers to receive real-time HTTP notifications when specific events occur within a Ghost publication, such as publishing a new post, updating a page, or gaining a new member. Webhooks can be configured through the Ghost Admin interface under custom integrations or created programmatically via the Admin API. By combining webhooks with the Content and Admin APIs, developers can build event-driven integrations that automate content distribution, trigger external workflows, and respond immediately to changes in publication activity without polling.

**Human URL:** [https://ghost.org/docs/webhooks/](https://ghost.org/docs/webhooks/)


#### Tags:

 - Webhooks, Events, Notifications, Automation, Integrations

#### Properties

- [Documentation](https://ghost.org/docs/webhooks/)
- [AsyncAPI](asyncapi/ghost-webhooks-asyncapi.yml)

### Ghost Content API JavaScript Client
The Ghost Content API JavaScript Client is an official promise-based JavaScript library published as @tryghost/content-api on npm. It abstracts the complexity of authenticating and interacting with the Ghost Content API, providing a clean interface for fetching posts, pages, tags, authors, and settings. The library works in both client-side and server-side JavaScript environments and supports the full NQL filtering syntax. It is commonly used to build custom front-ends, JAMstack sites with frameworks like Gatsby or Next.js, and other applications that consume Ghost content.

**Human URL:** [https://ghost.org/docs/content-api/javascript/](https://ghost.org/docs/content-api/javascript/)


#### Tags:

 - JavaScript, SDK, Client Library, Content Management, Node.js

#### Properties

- [Documentation](https://ghost.org/docs/content-api/javascript/)

### Ghost Themes API
The Ghost Themes API provides a Handlebars-based templating system for building custom front-end themes for Ghost publications. It includes a comprehensive set of helpers including data helpers for fetching content, functional helpers for logic and formatting, and utility helpers for common tasks. Themes have access to all Ghost content through template variables and the get helper, which queries the Content API internally. The Themes API supports custom templates, partials, asset management, and member-aware content gating, giving developers full control over the presentation and user experience of a Ghost-powered site.

**Human URL:** [https://ghost.org/docs/themes/](https://ghost.org/docs/themes/)


#### Tags:

 - Themes, Handlebars, Templates, Frontend, Customization

#### Properties

- [Documentation](https://ghost.org/docs/themes/)

## Common Properties

- [Portal](https://ghost.org/docs/)
- [Documentation](https://ghost.org/docs/introduction/)
- [Website](https://ghost.org/)
- [PrivacyPolicy](https://ghost.org/privacy/)
- [TermsOfService](https://ghost.org/terms/)
- [Support](https://ghost.org/help/)
- [Blog](https://ghost.org/blog/)
- [Login](https://ghost.org/login/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
