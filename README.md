# Spring Boot Admin Console (spring-boot-admin-console)

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

Spring Boot Admin is a community project by codecentric AG that provides a web-based administration UI for managing and monitoring Spring Boot applications. It visualizes Spring Boot Actuator endpoints in a graphical interface and provides application registration, health monitoring, log level management, metric graphs, instance lifecycle event tracking, and notification integrations (email, Slack, PagerDuty, OpsGenie, Hipchat, Teams, Telegram).

**APIs.json:** [https://github.com/codecentric/spring-boot-admin](https://github.com/codecentric/spring-boot-admin)

## Tags

- Actuator
- Administration
- Java
- Microservices
- Monitoring
- Spring Boot

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Spring Boot Admin Server API

REST API for the Spring Boot Admin server that manages application registration, retrieves application and instance information, proxies Actuator endpoints, and streams lifecycle events via Server-Sent Events.

- **Human URL:** [https://codecentric.github.io/spring-boot-admin/current/](https://codecentric.github.io/spring-boot-admin/current/)
- **Base URL:** `http://localhost:8080`

#### Tags

- Administration
- Monitoring
- Server

#### Properties

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/)
- [GitHub Repository](https://github.com/codecentric/spring-boot-admin)
- [OpenAPI](openapi/spring-boot-admin-console-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-boot-admin-console.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-admin-console.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/spring-boot-admin-console-rules.yml)
- [Maven  Central](https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin-server)
- [Release Notes](https://github.com/codecentric/spring-boot-admin/releases)

### Applications API

Manage registered Spring Boot applications. Applications are logical groupings of instances sharing the same name and management URL base.

- **Human URL:** [https://codecentric.github.io/spring-boot-admin/current/#_applications](https://codecentric.github.io/spring-boot-admin/current/#_applications)
- **Base URL:** `http://localhost:8080/applications`

#### Tags

- Applications
- Registration

#### Properties

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_applications)
- [Postman Collection](collections/spring-boot-admin-console.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-admin-console.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Instances API

Manage individual application instances. Each instance represents a running Spring Boot application registered with the Admin server. Supports health monitoring, Actuator endpoint proxying, and deregistration.

- **Human URL:** [https://codecentric.github.io/spring-boot-admin/current/#_instances](https://codecentric.github.io/spring-boot-admin/current/#_instances)
- **Base URL:** `http://localhost:8080/instances`

#### Tags

- Actuator
- Instances
- Monitoring

#### Properties

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_instances)
- [Postman Collection](collections/spring-boot-admin-console.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-admin-console.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Events API

Lifecycle event stream for application instances using Server-Sent Events (SSE). Events include status changes, registration, deregistration, and info updates.

- **Human URL:** [https://codecentric.github.io/spring-boot-admin/current/#_event-store](https://codecentric.github.io/spring-boot-admin/current/#_event-store)
- **Base URL:** `http://localhost:8080/instances/events`

#### Tags

- Events
- Notifications
- SSE

#### Properties

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_event-store)
- [Postman Collection](collections/spring-boot-admin-console.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-admin-console.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Notifications API

Configure and trigger notification channels for application lifecycle events. Supports email, Slack, PagerDuty, OpsGenie, Microsoft Teams, Telegram, and custom webhook notifications.

- **Human URL:** [https://codecentric.github.io/spring-boot-admin/current/#_notifications](https://codecentric.github.io/spring-boot-admin/current/#_notifications)
- **Base URL:** `http://localhost:8080`

#### Tags

- Alerts
- Notifications
- Webhooks

#### Properties

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_notifications)
- [Postman Collection](collections/spring-boot-admin-console.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-boot-admin-console.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/codecentric/spring-boot-admin)
- [Issue  Tracker](https://github.com/codecentric/spring-boot-admin/issues)
- [Getting  Started  Guide](https://codecentric.github.io/spring-boot-admin/current/#getting-started)
- [Reference  Documentation](https://codecentric.github.io/spring-boot-admin/current/)
- [Maven  Central](https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin)
- [License](https://github.com/codecentric/spring-boot-admin/blob/master/LICENSE)
- [Community](https://gitter.im/codecentric/spring-boot-admin)

## Maintainers

**Email:** info@codecentric.de
**URL:** https://www.codecentric.de/
