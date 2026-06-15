# Microsoft Planner (microsoft-planner)

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
