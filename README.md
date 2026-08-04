# GitHub Copilot (github-copilot)

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

APIs and resources for GitHub Copilot, an AI pair programmer that helps you write code faster.

**APIs.json:** [https://api.github.com/apis.yaml](https://api.github.com/apis.yaml)

## Scope

- **Access:** 3rd-Party

## Tags

- Agents
- AI
- Artificial Intelligence
- Code Generation
- Code Review
- Coding Agent
- Custom Instructions
- Developer Tools
- Extensions
- IDE
- Machine Learning
- MCP
- Metrics
- Model Context Protocol
- Productivity

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### GitHub Copilot API

REST API for managing GitHub Copilot seats, usage, and organization settings.

- **Human URL:** [https://docs.github.com/en/copilot](https://docs.github.com/en/copilot)
- **Base URL:** `https://api.github.com`

#### Tags

- AI
- Code Completion
- Developer Tools
- Machine Learning

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [Getting Started](https://docs.github.com/en/copilot/quickstart)
- [Features](https://docs.github.com/en/copilot/get-started/features)
- [Plans](https://docs.github.com/en/copilot/get-started/plans)
- [OpenAPI](openapi/github-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/github-copilot-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/github-copilot-metrics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/github-copilot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### GitHub Copilot for Business API

Manage Copilot for Business subscriptions, seat assignments, and usage metrics.

- **Human URL:** [https://docs.github.com/en/copilot/managing-copilot-for-business](https://docs.github.com/en/copilot/managing-copilot-for-business)
- **Base URL:** `https://api.github.com`

#### Tags

- Enterprise
- Seat Management
- Usage Analytics

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-for-business)
- [Pricing](https://github.com/features/copilot#pricing)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/github-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/github-copilot-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)

### GitHub Copilot Chat API

API for GitHub Copilot Chat interactions and conversations.

- **Human URL:** [https://docs.github.com/en/copilot/github-copilot-chat](https://docs.github.com/en/copilot/github-copilot-chat)
- **Base URL:** `https://api.github.com`

#### Tags

- Chat
- Conversational AI
- IDE Integration

#### Properties

- [Documentation](https://docs.github.com/en/copilot/github-copilot-chat)
- [Getting Started](https://docs.github.com/en/copilot/quickstart)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitHub Copilot User Management API

REST API for managing GitHub Copilot seat assignments, billing information, and subscription details for organizations including adding and removing users and teams.

- **Human URL:** [https://docs.github.com/en/rest/copilot/copilot-user-management](https://docs.github.com/en/rest/copilot/copilot-user-management)
- **Base URL:** `https://api.github.com`

#### Tags

- Billing
- Organizations
- Seat Management
- User Management

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-user-management)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](openapi/github-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/github-copilot-seat-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/github-copilot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### GitHub Copilot Metrics API

REST API for retrieving aggregated Copilot usage metrics at the organization and team level, including data on active users, engaged users, and breakdowns by language and editor.

- **Human URL:** [https://docs.github.com/en/rest/copilot/copilot-metrics](https://docs.github.com/en/rest/copilot/copilot-metrics)
- **Base URL:** `https://api.github.com`

#### Tags

- Analytics
- Metrics
- Organizations
- Usage

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-metrics)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](openapi/github-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/github-copilot-metrics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/github-copilot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### GitHub Copilot Usage Metrics API

REST API for retrieving detailed Copilot usage metrics reports at the enterprise and organization level, including daily and 28-day aggregated reports for both entity-level and user-level data.

- **Human URL:** [https://docs.github.com/en/rest/copilot/copilot-usage-metrics](https://docs.github.com/en/rest/copilot/copilot-usage-metrics)
- **Base URL:** `https://api.github.com`

#### Tags

- Analytics
- Enterprise
- Reporting
- Usage Metrics

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-usage-metrics)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](openapi/github-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/github-copilot-metrics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/github-copilot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### GitHub Copilot Content Exclusion API

REST API for programmatically managing Copilot content exclusion path rules at both the organization and enterprise level, enabling automation and governance of which content Copilot can access.

- **Human URL:** [https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management](https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management)
- **Base URL:** `https://api.github.com`

#### Tags

- Content Exclusion
- Governance
- Policy
- Security

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](openapi/github-copilot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/github-copilot-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### GitHub Copilot Extensions API

Platform for building Copilot Extensions that integrate third-party tools, services, and custom agents into GitHub Copilot Chat, using GitHub Apps with agent or skillset configurations.

- **Human URL:** [https://docs.github.com/en/copilot/building-copilot-extensions](https://docs.github.com/en/copilot/building-copilot-extensions)
- **Base URL:** `https://api.github.com`

#### Tags

- Agents
- Extensions
- Integrations
- Skillsets

#### Properties

- [Documentation](https://docs.github.com/en/copilot/building-copilot-extensions/about-building-copilot-extensions)
- [Getting Started](https://docs.github.com/en/copilot/building-copilot-extensions/creating-a-copilot-extension)
- [SDK](https://github.com/github/copilot-sdk)
- [GitHub Organization](https://github.com/copilot-extensions)
- [Code Examples](https://github.com/copilot-extensions/skillset-example)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitHub Copilot Coding Agent

Autonomous coding agent that works in the background to complete tasks, spinning up secure development environments powered by GitHub Actions to explore code, make changes, run tests, and open pull requests.

- **Human URL:** [https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent)
- **Base URL:** `https://api.github.com`

#### Tags

- Agents
- Automation
- Code Generation
- GitHub Actions
- Pull Requests

#### Properties

- [Documentation](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitHub Copilot Code Review

AI-powered code review agent that analyzes pull requests for issues, suggests fixes, and provides feedback across any programming language with agentic context gathering capabilities.

- **Human URL:** [https://docs.github.com/en/copilot/concepts/agents/code-review](https://docs.github.com/en/copilot/concepts/agents/code-review)
- **Base URL:** `https://api.github.com`

#### Tags

- Agents
- Code Quality
- Code Review
- Pull Requests

#### Properties

- [Documentation](https://docs.github.com/en/copilot/concepts/agents/code-review)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitHub MCP Server

GitHub official Model Context Protocol server that enables AI tools to interact with GitHub repositories, issues, pull requests, and other resources through a standardized protocol.

- **Human URL:** [https://docs.github.com/en/copilot/concepts/context/mcp](https://docs.github.com/en/copilot/concepts/context/mcp)
- **Base URL:** `https://api.github.com`

#### Tags

- Agents
- Context
- Integrations
- MCP
- Model Context Protocol

#### Properties

- [Documentation](https://docs.github.com/en/copilot/concepts/context/mcp)
- [GitHub Repository](https://github.com/github/github-mcp-server)
- [Getting Started](https://docs.github.com/en/copilot/how-tos/provide-context/use-mcp/set-up-the-github-mcp-server)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitHub Copilot Custom Instructions

Configuration system for providing repository-level, path-specific, and organization-level custom instructions to guide Copilot behavior, code style, and response formatting.

- **Human URL:** [https://docs.github.com/en/copilot/how-tos/configure-custom-instructions](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions)
- **Base URL:** `https://api.github.com`

#### Tags

- Configuration
- Customization
- Instructions
- Organizations

#### Properties

- [Documentation](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions)
- [Postman Collection](collections/github-copilot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/github-copilot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://github.com/features/copilot)
- [Status Page](https://www.githubstatus.com/)
- [Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service)
- [Privacy Policy](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)
- [Getting Started](https://docs.github.com/en/copilot/quickstart)
- [Blog](https://github.blog/tag/github-copilot/)
- [Sign Up](https://github.com/github-copilot/signup)
- [Pricing](https://github.com/features/copilot/plans)
- [Changelog](https://github.blog/changelog/label/copilot/)
- [Support](https://support.github.com)
- [SDK](https://github.com/github/copilot-sdk)
- [Trust Center](https://copilot.github.trust.page/)
- [Rate Limits](https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](https://github.com/github/rest-api-description) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.github.com/en/copilot)
- [Marketplace](https://github.com/marketplace?type=apps&copilot_app=true)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.github.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
