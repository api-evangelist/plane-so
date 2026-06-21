# Plane (plane-so)

Plane is an open-source project and product management tool for planning, tracking, and shipping work across workspaces, projects, cycles, and modules. It is available as a self-hosted Community Edition (AGPL v3.0) and as Plane Cloud, and exposes a REST API at https://api.plane.so/api/v1 secured with an X-API-Key header for managing projects, work items, cycles, modules, states, labels, and members.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/plane-so/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/plane-so/refs/heads/main/apis.yml)

## Tags

- Project Management
- Issue Tracking
- Work Management
- Open Source
- Productivity

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Plane Projects API

Create, list, retrieve, update, and delete projects within a workspace, the top-level containers that hold work items, cycles, modules, states, and labels.

- **Human URL:** [https://developers.plane.so/api-reference/project/overview](https://developers.plane.so/api-reference/project/overview)
- **Base URL:** `https://api.plane.so/api/v1`

#### Tags

- Projects
- Workspaces

#### Properties

- [Documentation](https://developers.plane.so/api-reference/project/overview)
- [API Reference](https://developers.plane.so/api-reference/introduction)
- [OpenAPI](openapi/plane-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plane-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plane-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plane Issues API

Manage work items (issues) and their nested comments and links — create, list, retrieve, update, and delete issues, attach threaded comments, and associate external links.

- **Human URL:** [https://developers.plane.so/api-reference/issue/overview](https://developers.plane.so/api-reference/issue/overview)
- **Base URL:** `https://api.plane.so/api/v1`

#### Tags

- Issues
- Work Items
- Comments
- Links

#### Properties

- [Documentation](https://developers.plane.so/api-reference/issue/overview)
- [API Reference](https://developers.plane.so/api-reference/introduction)
- [OpenAPI](openapi/plane-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plane-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plane-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plane Cycles API

Manage time-boxed cycles (sprints), archive and unarchive them, and add, list, remove, and transfer the work items assigned to each cycle.

- **Human URL:** [https://developers.plane.so/api-reference/cycle/overview](https://developers.plane.so/api-reference/cycle/overview)
- **Base URL:** `https://api.plane.so/api/v1`

#### Tags

- Cycles
- Sprints

#### Properties

- [Documentation](https://developers.plane.so/api-reference/cycle/overview)
- [API Reference](https://developers.plane.so/api-reference/introduction)
- [OpenAPI](openapi/plane-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plane-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plane-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plane Modules API

Manage modules — focused groupings of work items with a lead, members, and start/target dates — including archive/unarchive and assigning work items.

- **Human URL:** [https://developers.plane.so/api-reference/module/overview](https://developers.plane.so/api-reference/module/overview)
- **Base URL:** `https://api.plane.so/api/v1`

#### Tags

- Modules
- Grouping

#### Properties

- [Documentation](https://developers.plane.so/api-reference/module/overview)
- [API Reference](https://developers.plane.so/api-reference/introduction)
- [OpenAPI](openapi/plane-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plane-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plane-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plane States & Labels API

Define the workflow states (grouped backlog, unstarted, started, completed, cancelled) and the labels used to categorize work items within a project.

- **Human URL:** [https://developers.plane.so/api-reference/state/overview](https://developers.plane.so/api-reference/state/overview)
- **Base URL:** `https://api.plane.so/api/v1`

#### Tags

- States
- Labels
- Workflow

#### Properties

- [Documentation](https://developers.plane.so/api-reference/state/overview)
- [API Reference](https://developers.plane.so/api-reference/label/overview)
- [OpenAPI](openapi/plane-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plane-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plane-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plane Members API

List the members of a project, returning the people who can be assigned to work items, cycles, and modules along with their roles.

- **Human URL:** [https://developers.plane.so/api-reference/member/overview](https://developers.plane.so/api-reference/member/overview)
- **Base URL:** `https://api.plane.so/api/v1`

#### Tags

- Members
- Teams

#### Properties

- [Documentation](https://developers.plane.so/api-reference/member/overview)
- [API Reference](https://developers.plane.so/api-reference/introduction)
- [OpenAPI](openapi/plane-so-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/plane-so.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plane-so.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/makeplane)
- [LinkedIn](https://www.linkedin.com/company/planepowers)
- [Website](https://plane.so)
- [Documentation](https://developers.plane.so)
- [Plans](plans/plane-so-plans-pricing.yml)
- [Rate Limits](rate-limits/plane-so-rate-limits.yml)
- [Fin Ops](finops/plane-so-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
