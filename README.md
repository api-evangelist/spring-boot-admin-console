# Spring Boot Admin Console

Spring Boot Admin is a community project by codecentric AG that provides a web-based administration UI for managing and monitoring Spring Boot applications. It visualizes Spring Boot Actuator endpoints in a graphical interface and supports application registration, health monitoring, log level management, metric graphs, instance lifecycle event tracking, and notification integrations (email, Slack, PagerDuty, Teams, Telegram).

- **URL:** https://github.com/codecentric/spring-boot-admin
- **Type:** Open Source
- **Tags:** Actuator, Administration, Java, Microservices, Monitoring, Spring Boot

## APIs

### Spring Boot Admin Server API

REST API for managing application registration, instance monitoring, Actuator endpoint proxying, and SSE lifecycle event streaming.

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/)
- [GitHub Repository](https://github.com/codecentric/spring-boot-admin)

### Applications API

Manage registered Spring Boot applications grouped by name.

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_applications)

### Instances API

Manage individual application instances, proxy Actuator endpoints, and monitor health.

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_instances)

### Events API

Server-Sent Events stream for instance lifecycle events (registered, status changed, etc.).

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_event-store)

### Notifications API

Configure notification channels for application status change events.

- [Documentation](https://codecentric.github.io/spring-boot-admin/current/#_notifications)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spring Boot Admin Server API | [openapi/spring-boot-admin-console-openapi.yml](openapi/spring-boot-admin-console-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spring Boot Admin Console Rules | [rules/spring-boot-admin-console-rules.yml](rules/spring-boot-admin-console-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Spring Boot Admin Server API | [capabilities/shared/spring-boot-admin-console.yaml](capabilities/shared/spring-boot-admin-console.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Microservice Fleet Management | Manage and monitor a fleet of Spring Boot microservices | [capabilities/microservice-fleet-management.yaml](capabilities/microservice-fleet-management.yaml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Instance | [json-schema/spring-boot-admin-console-instance-schema.json](json-schema/spring-boot-admin-console-instance-schema.json) |
| Instance Event | [json-schema/spring-boot-admin-console-event-schema.json](json-schema/spring-boot-admin-console-event-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Spring Boot Admin Domain Model | [json-structure/spring-boot-admin-console-structure.json](json-structure/spring-boot-admin-console-structure.json) |

## JSON-LD Contexts

| Context | File |
|---------|------|
| Spring Boot Admin Console | [json-ld/spring-boot-admin-console-context.jsonld](json-ld/spring-boot-admin-console-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| List Registered Applications | [examples/spring-boot-admin-console-list-applications-example.json](examples/spring-boot-admin-console-list-applications-example.json) |
| Register Application | [examples/spring-boot-admin-console-register-application-example.json](examples/spring-boot-admin-console-register-application-example.json) |
| Get Instance Health | [examples/spring-boot-admin-console-get-instance-health-example.json](examples/spring-boot-admin-console-get-instance-health-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spring Boot Admin Console Domain Terms | [vocabulary/spring-boot-admin-console-vocabulary.yml](vocabulary/spring-boot-admin-console-vocabulary.yml) |

## Common Properties

- [GitHub Repository](https://github.com/codecentric/spring-boot-admin)
- [Issue Tracker](https://github.com/codecentric/spring-boot-admin/issues)
- [Getting Started Guide](https://codecentric.github.io/spring-boot-admin/current/#getting-started)
- [Reference Documentation](https://codecentric.github.io/spring-boot-admin/current/)
- [Maven Central](https://mvnrepository.com/artifact/de.codecentric/spring-boot-admin)
- [License](https://github.com/codecentric/spring-boot-admin/blob/master/LICENSE)

## Maintainers

- codecentric AG — info@codecentric.de
