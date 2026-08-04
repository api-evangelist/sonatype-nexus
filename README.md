# Sonatype Nexus (sonatype-nexus)

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

Sonatype Nexus Repository Manager provides a comprehensive REST API for managing software artifacts, repositories, and components across the software development lifecycle. It supports popular formats including Maven, npm, Docker, PyPI, NuGet, RubyGems, Go, Helm, APT, Yum, Cargo, Terraform, R, Swift, and more. The API covers repository configuration, component and asset management, security, blob stores, search, tasks, cleanup policies, staging, and system administration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Artifact Management
- DevOps
- Package Management
- Repository
- Maven
- npm
- Docker
- Software Supply Chain

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Nexus Repository API

REST API for Sonatype Nexus Repository Manager (v3.91.0) providing 238 endpoints for managing repositories across many formats (Maven, npm, Docker, PyPI, NuGet, RubyGems, Go, Cargo, Helm, Terraform, R, APT, Yum, Raw, Swift, and more), components, assets, blob stores (file, S3, Azure, GCS), security (users, roles, privileges, LDAP, SAML, Crowd), search, tasks, cleanup policies, staging, and system administration. Authentication uses HTTP Basic Auth or User Tokens.

- **Human URL:** [https://help.sonatype.com/en/api-reference.html](https://help.sonatype.com/en/api-reference.html)
- **Base URL:** `https://{nexus-host}/service/rest`

#### Tags

- Artifact Management
- Components
- Repository
- Security
- Search
- Tasks
- Blob Store
- Maven
- npm
- Docker

#### Properties

- [Documentation](https://help.sonatype.com/en/api-reference.html)
- [Reference](https://help.sonatype.com/en/rest-and-integration-api.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/openapi/sonatype-nexus-repository-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/json-schema/sonatype-nexus-component-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/json-schema/sonatype-nexus-repository-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sonatype-nexus-repository.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sonatype-nexus-repository.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sonatype)
- [Portal](https://www.sonatype.com/products/sonatype-nexus-repository)
- [Documentation](https://help.sonatype.com/en/sonatype-nexus-repository.html)
- [Website](https://www.sonatype.com/)
- [Git Hub](https://github.com/sonatype-nexus-community)
- [Blog](https://www.sonatype.com/blog)
- [Changelog](https://help.sonatype.com/en/release-notes.html)
- [Support](https://support.sonatype.com/)
- [Pricing](https://www.sonatype.com/products/sonatype-nexus-repository/pricing)
- [Integrations](https://www.sonatype.com/products/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
