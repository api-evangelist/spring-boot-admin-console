# Spring Boot Admin Console (spring-boot-admin-console)

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
