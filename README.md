# Sonatype Nexus

Sonatype Nexus Repository Manager provides a comprehensive REST API for managing software artifacts, repositories, and components across the software development lifecycle. It supports popular formats including Maven, npm, Docker, PyPI, NuGet, RubyGems, Go, Helm, APT, Yum, Cargo, Terraform, R, Swift, and more.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml)

## Tags

Artifact Management, DevOps, Package Management, Repository, Maven, npm, Docker, Software Supply Chain

## APIs

### Nexus Repository API

REST API for Sonatype Nexus Repository Manager (v3.91.0) with 238 endpoints covering repositories (15+ formats), components, assets, blob stores (file, S3, Azure, GCS), security (users, roles, privileges, LDAP, SAML), search, tasks, cleanup policies, staging, and system administration.

**Human URL:** [https://help.sonatype.com/en/api-reference.html](https://help.sonatype.com/en/api-reference.html)

#### Tags

Artifact Management, Components, Repository, Security, Search, Tasks, Blob Store, Maven, npm, Docker

#### Properties

- [Documentation](https://help.sonatype.com/en/api-reference.html)
- [Reference](https://help.sonatype.com/en/rest-and-integration-api.html)
- [OpenAPI](openapi/sonatype-nexus-repository-openapi.yml)
- [JSON Schema - Component](json-schema/sonatype-nexus-component-schema.json)
- [JSON Schema - Repository](json-schema/sonatype-nexus-repository-schema.json)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [sonatype-nexus-repository-openapi.yml](openapi/sonatype-nexus-repository-openapi.yml) | Nexus Repository Manager REST API v3.91.0 (238 paths) |

### JSON Schema

| File | Description |
|---|---|
| [sonatype-nexus-component-schema.json](json-schema/sonatype-nexus-component-schema.json) | Schema for Nexus component objects |
| [sonatype-nexus-repository-schema.json](json-schema/sonatype-nexus-repository-schema.json) | Schema for Nexus repository objects |

### JSON Structure

| File | Description |
|---|---|
| [sonatype-nexus-component-structure.json](json-structure/sonatype-nexus-component-structure.json) | Component structure documentation |

### JSON-LD

| File | Description |
|---|---|
| [sonatype-nexus-context.jsonld](json-ld/sonatype-nexus-context.jsonld) | JSON-LD context for Nexus entities |

### Examples

| File | Description |
|---|---|
| [sonatype-nexus-list-repositories-example.json](examples/sonatype-nexus-list-repositories-example.json) | List repositories example |
| [sonatype-nexus-search-components-example.json](examples/sonatype-nexus-search-components-example.json) | Search components example |

### Spectral Rules

| File | Description |
|---|---|
| [sonatype-nexus-rules.yml](rules/sonatype-nexus-rules.yml) | Spectral ruleset for Nexus API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|---|---|
| [shared/nexus-repository.yaml](capabilities/shared/nexus-repository.yaml) | Per-API capability definition for Nexus Repository API |

#### Workflow Capabilities

| File | Description | Tools |
|---|---|---|
| [artifact-management.yaml](capabilities/artifact-management.yaml) | Artifact lifecycle management for DevOps teams | 12 tools |
| [security-administration.yaml](capabilities/security-administration.yaml) | Security and user administration for platform teams | 8 tools |

### Vocabulary

| File | Description |
|---|---|
| [sonatype-nexus-vocabulary.yml](vocabulary/sonatype-nexus-vocabulary.yml) | Nexus Repository vocabulary and domain terms |

## Common Properties

- [Portal](https://www.sonatype.com/products/sonatype-nexus-repository)
- [Documentation](https://help.sonatype.com/en/sonatype-nexus-repository.html)
- [Website](https://www.sonatype.com/)
- [GitHub](https://github.com/sonatype-nexus-community)
- [Blog](https://www.sonatype.com/blog)
- [Changelog](https://help.sonatype.com/en/release-notes.html)
- [Support](https://support.sonatype.com/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
