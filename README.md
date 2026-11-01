# Spring Boot Admin Console

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

Spring Boot Admin is a community project by codecentric AG that provides a web-based administration UI for managing and monitoring Spring Boot applications. It visualizes Spring Boot Actuator endpoints in a graphical interface and provides application registration, health monitoring, log level management, metric graphs, instance lifecycle event tracking, and notification integrations (email, Slack, PagerDuty, OpsGenie, Hipchat, Teams, Telegram).

**Areas:** Actuators · Administration · Java · Microservices · Monitoring · Spring Boot

## Spring Boot Admin Console on APIs.io

Everything profiled for Spring Boot Admin Console is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/spring-boot-admin-console/](https://apis.io/providers/spring-boot-admin-console/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Applications API](https://apis.io/apis/spring-boot-admin-console/applications-api/) — Manage registered Spring Boot applications. Applications are logical groupings of instances sharing the same name and management URL base.
- [Instances API](https://apis.io/apis/spring-boot-admin-console/instances-api/) — Manage individual application instances. Each instance represents a running Spring Boot application registered with the Admin server. Supports health…
- [Events API](https://apis.io/apis/spring-boot-admin-console/events-api/) — Lifecycle event stream for application instances using Server-Sent Events (SSE). Events include status changes, registration, deregistration, and info updates.
- [Notifications API](https://apis.io/apis/spring-boot-admin-console/notifications-api/) — Configure and trigger notification channels for application lifecycle events. Supports email, Slack, PagerDuty, OpsGenie, Microsoft Teams, Telegram, and…
- [Spring Boot Admin Console Applications API](https://apis.io/apis/spring-boot-admin-console/spring-boot-admin-console-applications-api/) — Application registration and management
- [Spring Boot Admin Console Events API](https://apis.io/apis/spring-boot-admin-console/spring-boot-admin-console-events-api/) — Instance lifecycle event stream
- [Spring Boot Admin Console Instances API](https://apis.io/apis/spring-boot-admin-console/spring-boot-admin-console-instances-api/) — Application instance monitoring and management

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Spring Boot Admin Console Agentic Access](https://apis.io/agentic-access/spring-boot-admin-console/spring-boot-admin-console-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Spring Boot Admin Instance Event](https://apis.io/schemas/spring-boot-admin-console/spring-boot-admin-console-event/)
- [Spring Boot Admin Instance](https://apis.io/schemas/spring-boot-admin-console/spring-boot-admin-console-instance/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Spring Boot Admin Console Structure](https://apis.io/json-structure/spring-boot-admin-console/spring-boot-admin-console-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Spring Boot Admin Console Context](https://apis.io/jsonld/spring-boot-admin-console/spring-boot-admin-console-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Spring Boot Admin Console Vocabulary](https://apis.io/vocabularies/spring-boot-admin-console/spring-boot-admin-console-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Spring Boot Admin Console Get Instance Health Example](https://apis.io/examples/spring-boot-admin-console/spring-boot-admin-console-get-instance-health-example/)
- [Spring Boot Admin Console List Applications Example](https://apis.io/examples/spring-boot-admin-console/spring-boot-admin-console-list-applications-example/)
- [Spring Boot Admin Console Register Application Example](https://apis.io/examples/spring-boot-admin-console/spring-boot-admin-console-register-application-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [Spring Boot Admin Server API](https://apis.io/collections/spring-boot-admin-console/open-spring-boot-admin-console/)
- [Spring Boot Admin Server Applications API](https://apis.io/collections/spring-boot-admin-console/open-spring-boot-admin-console-applications-api/)
- [Spring Boot Admin Server Applications Events API](https://apis.io/collections/spring-boot-admin-console/open-spring-boot-admin-console-events-api/)
- [Spring Boot Admin Server Applications Instances API](https://apis.io/collections/spring-boot-admin-console/open-spring-boot-admin-console-instances-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Spring Boot Admin Console — jsonschema rules](https://apis.io/rules/spring-boot-admin-console/spring-boot-admin-console-jsonschema-spectral-rules/)
- [Spring Boot Admin Console API Rules](https://apis.io/rules/spring-boot-admin-console/spring-boot-admin-console-rules/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Spring Boot Admin Console Plans Pricing](https://apis.io/plans/spring-boot-admin-console/spring-boot-admin-console-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Spring Boot Admin Console Rate Limits](https://apis.io/rate-limits/spring-boot-admin-console/spring-boot-admin-console-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Spring Boot Admin Console Finops](https://apis.io/finops/spring-boot-admin-console/spring-boot-admin-console-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Blog](https://blog.codecentric.de/feed/)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Spring Boot Admin Console: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/spring-boot-admin-console/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
