# Microsoft Planner (microsoft-planner)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Microsoft Planner is a task management tool that helps teams organize work, assign tasks, share files, and collaborate on projects within Microsoft 365.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-planner/refs/heads/main/apis.yml)

## Tags

- Collaboration
- Microsoft 365
- Productivity
- Project Management
- Task Management

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Microsoft Planner API

RESTful API for accessing and managing tasks, plans, and buckets in Microsoft Planner through Microsoft Graph.

- **Human URL:** [https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/planner_overview](https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/planner_overview)
- **Base URL:** `https://graph.microsoft.com/v1.0/planner`

#### Tags

- Assignments
- Buckets
- Microsoft Graph
- Plans
- Tasks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/planner-overview)
- [OpenAPI](openapi/microsoft-planner-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-planner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-planner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/microsoft-planner-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-planner-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Pricing](https://www.microsoft.com/en-us/microsoft-365/enterprise/microsoft365-plans-and-pricing)
- [Rate Limits](https://learn.microsoft.com/en-us/graph/throttling)
- [SDK](https://github.com/microsoftgraph/msgraph-sdk-dotnet)
- [SDK](https://github.com/microsoftgraph/msgraph-sdk-javascript)
- [SDK](https://github.com/microsoftgraph/msgraph-sdk-python)
- [SDK](https://github.com/microsoftgraph/msgraph-sdk-java)
- [SDK](https://github.com/microsoftgraph/msgraph-sdk-go)
- [SDK](https://github.com/microsoftgraph/msgraph-sdk-php)
- [Support](https://developer.microsoft.com/en-us/graph/support)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)
- [Getting Started](https://learn.microsoft.com/en-us/graph/planner-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-1.0)
- [Quickstart](https://developer.microsoft.com/en-us/graph/quick-start)

### Microsoft Graph Plans API

API for creating, reading, updating, and deleting plans in Microsoft Planner through Microsoft Graph. Plans are the containers for tasks and are owned by groups or other containers.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/plannerplan?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/plannerplan?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/planner/plans`

#### Tags

- Microsoft Graph
- Planner
- Plans

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/plannerplan?view=graph-rest-1.0)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/planner-post-plans?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-planner-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-planner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-planner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/planner-concept-overview)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)

### Microsoft Graph Tasks API

API for creating, reading, updating, and deleting tasks in Microsoft Planner through Microsoft Graph. Tasks are contained in plans and can be assigned to buckets and users.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/plannertask?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/plannertask?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/planner/tasks`

#### Tags

- Assignments
- Microsoft Graph
- Planner
- Tasks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/plannertask?view=graph-rest-1.0)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/planner-post-tasks?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-planner-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-planner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-planner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/microsoft-planner-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/planner-concept-overview)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)

### Microsoft Graph Buckets API

API for creating, reading, updating, and deleting buckets in Microsoft Planner through Microsoft Graph. Buckets represent custom columns for organizing tasks within a plan.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/plannerbucket?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/plannerbucket?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/planner/buckets`

#### Tags

- Buckets
- Microsoft Graph
- Organization
- Planner

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/plannerbucket?view=graph-rest-1.0)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/planner-post-buckets?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-planner-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-planner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-planner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/planner-concept-overview)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)

### Microsoft Graph Planner API (Beta)

Beta version of the Planner API in Microsoft Graph providing access to preview features including plannerRoster resources, business scenarios integration, and expanded container type support.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta](https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta)
- **Base URL:** `https://graph.microsoft.com/beta/planner`

#### Tags

- Beta
- Microsoft Graph
- Planner
- Preview
- Rosters

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/planner-overview?view=graph-rest-beta)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/planner-concept-overview)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)
- [Postman Collection](collections/microsoft-planner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-planner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Business Scenarios Planner API (Beta)

Beta API for integrating external business processes with Microsoft Planner through business scenarios, allowing creation of scenario-controlled Planner tasks and plans.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-planner-overview?view=graph-rest-beta](https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-planner-overview?view=graph-rest-beta)
- **Base URL:** `https://graph.microsoft.com/beta/solutions/businessScenarios`

#### Tags

- Beta
- Business Scenarios
- Integration
- Microsoft Graph
- Planner

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-planner-overview?view=graph-rest-beta)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/businessscenario-overview?view=graph-rest-beta)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)
- [Postman Collection](collections/microsoft-planner.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-planner.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.microsoft.com/en-us/graph)
- [Terms of Service](https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Getting Started](https://learn.microsoft.com/en-us/graph/planner-concept-overview)
- [Blog](https://developer.microsoft.com/en-us/graph/blogs/)
- [Status Page](https://developer.microsoft.com/en-us/graph/status)
- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/planner-overview)
- [Login](https://planner.cloud.microsoft)
- [Support](https://support.microsoft.com/en-us/planner)
- [F A Q](https://support.microsoft.com/en-us/office/frequently-asked-questions-about-microsoft-planner-d1a2d4e6-a4d7-408c-a48a-31caaa267de5)
- [GitHub Organization](https://github.com/microsoftgraph)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Sign Up](https://developer.microsoft.com/en-us/microsoft-365/dev-program)
- [Sandbox](https://developer.microsoft.com/en-us/graph/graph-explorer)
- [Rate Limits](https://learn.microsoft.com/en-us/graph/throttling)
- [OpenAPI](openapi/microsoft-planner-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/microsoft-planner-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-planner-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/microsoft-planner-spectral-rules.yml)
- [Vocabulary](vocabulary/microsoft-planner-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
