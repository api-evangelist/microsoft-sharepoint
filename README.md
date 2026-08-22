# Microsoft SharePoint (microsoft-sharepoint)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Microsoft SharePoint is a web-based collaboration platform that provides document management, content management, and team collaboration capabilities. It offers REST APIs, Microsoft Graph integration, and the SharePoint Framework for customization and extension.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-sharepoint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-sharepoint/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Collaboration
- Content Management
- Microsoft
- Microsoft 365
- SharePoint

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### SharePoint REST API

The SharePoint REST API provides direct access to SharePoint sites, lists, libraries, items, and other resources using OData endpoints. Developers can perform CRUD operations on SharePoint content, manage site structures, work with content types, and interact with search and taxonomy services.

- **Human URL:** [https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service)
- **Base URL:** `https://{tenant}.sharepoint.com/_api/`

#### Tags

- Collaboration
- Content Management
- SharePoint

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service)
- [Reference](https://learn.microsoft.com/en-us/sharepoint/dev/apis/sharepoint-rest-graph)
- [OpenAPI](openapi/microsoft-sharepoint-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-sharepoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sharepoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph SharePoint Sites API

The Microsoft Graph SharePoint Sites API provides access to SharePoint sites, lists, and document libraries through the unified Microsoft Graph endpoint. It enables developers to manage site content, list items, drive items, and site permissions using a consistent REST interface alongside other Microsoft 365 services.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/sharepoint](https://learn.microsoft.com/en-us/graph/api/resources/sharepoint)
- **Base URL:** `https://graph.microsoft.com/v1.0/`

#### Tags

- Microsoft Graph
- SharePoint
- Sites

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/sharepoint)
- [Postman Collection](collections/microsoft-sharepoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sharepoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SharePoint Webhooks API

The SharePoint Webhooks API enables applications to subscribe to change notifications on SharePoint lists and libraries. When items are created, updated, or deleted, SharePoint sends notifications to registered webhook endpoints, enabling real-time event-driven integrations without polling.

- **Human URL:** [https://learn.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks](https://learn.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks)
- **Base URL:** `https://{tenant}.sharepoint.com/_api/`

#### Tags

- Events
- SharePoint
- Webhooks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks)
- [Postman Collection](collections/microsoft-sharepoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sharepoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SharePoint Search REST API

The SharePoint Search REST API provides full-text search capabilities across SharePoint content including sites, lists, libraries, and documents. It supports keyword query language, query refinement, result sorting, and content source targeting for comprehensive enterprise search scenarios.

- **Human URL:** [https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-search-rest-api-overview](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-search-rest-api-overview)
- **Base URL:** `https://{tenant}.sharepoint.com/_api/search/`

#### Tags

- Content Discovery
- Search
- SharePoint

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-search-rest-api-overview)
- [Postman Collection](collections/microsoft-sharepoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sharepoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SharePoint Framework (SPFx)

The SharePoint Framework (SPFx) is a development model for building client-side web parts, extensions, and adaptive card extensions for SharePoint and Microsoft Teams. It uses modern web technologies including TypeScript, React, and Node.js to create customizations that run in the context of SharePoint pages.

- **Human URL:** [https://learn.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview](https://learn.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview)

#### Tags

- Extensions
- Framework
- SharePoint
- Web Parts

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview)
- [Postman Collection](collections/microsoft-sharepoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-sharepoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Website](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration)
- [Documentation](https://learn.microsoft.com/en-us/sharepoint/dev/)
- [Developer  Portal](https://developer.microsoft.com/en-us/sharepoint)
- [Authentication](https://learn.microsoft.com/en-us/sharepoint/dev/solution-guidance/security-apponly-azureacs)
- [S D Ks](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-rest-endpoints)
- [GitHub Organization](https://github.com/SharePoint)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
