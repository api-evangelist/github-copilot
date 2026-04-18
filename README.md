# GitHub Copilot (github-copilot)
APIs and resources for GitHub Copilot, an AI pair programmer that helps you write code faster.

**URL:** [Visit APIs.json URL](https://api.github.com/apis.yaml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agents, AI, Artificial Intelligence, Code Generation, Code Review, Coding Agent, Custom Instructions, Developer Tools, Extensions, IDE, Machine Learning, MCP, Metrics, Model Context Protocol, Productivity

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### GitHub Copilot API
REST API for managing GitHub Copilot seats, usage, and organization settings.

**Human URL:** [https://docs.github.com/en/copilot](https://docs.github.com/en/copilot)

#### Tags:

 - AI, Code Completion, Developer Tools, Machine Learning

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot)
- [OpenAPI](https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [GettingStarted](https://docs.github.com/en/copilot/quickstart)
- [Features](https://docs.github.com/en/copilot/get-started/features)
- [Plans](https://docs.github.com/en/copilot/get-started/plans)
- [OpenAPI](openapi/github-copilot-openapi.yml)
- [JSONSchema](json-schema/github-copilot-seat-schema.json)
- [JSONSchema](json-schema/github-copilot-metrics-schema.json)
- [JSONLD](json-ld/github-copilot-context.jsonld)

### GitHub Copilot for Business API
Manage Copilot for Business subscriptions, seat assignments, and usage metrics.

**Human URL:** [https://docs.github.com/en/copilot/managing-copilot-for-business](https://docs.github.com/en/copilot/managing-copilot-for-business)

#### Tags:

 - Enterprise, Seat Management, Usage Analytics

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-for-business)
- [Pricing](https://github.com/features/copilot#pricing)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](openapi/github-copilot-openapi.yml)
- [JSONSchema](json-schema/github-copilot-seat-schema.json)

### GitHub Copilot User Management API
REST API for managing GitHub Copilot seat assignments, billing information, and subscription details for organizations including adding and removing users and teams.

**Human URL:** [https://docs.github.com/en/rest/copilot/copilot-user-management](https://docs.github.com/en/rest/copilot/copilot-user-management)

#### Tags:

 - Billing, Organizations, Seat Management, User Management

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-user-management)
- [OpenAPI](openapi/github-copilot-openapi.yml)
- [JSONSchema](json-schema/github-copilot-seat-schema.json)
- [JSONLD](json-ld/github-copilot-context.jsonld)

### GitHub Copilot Metrics API
REST API for retrieving aggregated Copilot usage metrics at the organization and team level, including data on active users, engaged users, and breakdowns by language and editor.

**Human URL:** [https://docs.github.com/en/rest/copilot/copilot-metrics](https://docs.github.com/en/rest/copilot/copilot-metrics)

#### Tags:

 - Analytics, Metrics, Organizations, Usage

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-metrics)
- [OpenAPI](openapi/github-copilot-openapi.yml)
- [JSONSchema](json-schema/github-copilot-metrics-schema.json)
- [JSONLD](json-ld/github-copilot-context.jsonld)

### GitHub Copilot Usage Metrics API
REST API for retrieving detailed Copilot usage metrics reports at the enterprise and organization level, including daily and 28-day aggregated reports for both entity-level and user-level data.

**Human URL:** [https://docs.github.com/en/rest/copilot/copilot-usage-metrics](https://docs.github.com/en/rest/copilot/copilot-usage-metrics)

#### Tags:

 - Analytics, Enterprise, Reporting, Usage Metrics

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-usage-metrics)
- [OpenAPI](openapi/github-copilot-openapi.yml)
- [JSONSchema](json-schema/github-copilot-metrics-schema.json)
- [JSONLD](json-ld/github-copilot-context.jsonld)

### GitHub Copilot Content Exclusion API
REST API for programmatically managing Copilot content exclusion path rules at both the organization and enterprise level, enabling automation and governance of which content Copilot can access.

**Human URL:** [https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management](https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management)

#### Tags:

 - Content Exclusion, Governance, Policy, Security

#### Properties

- [Documentation](https://docs.github.com/en/rest/copilot/copilot-content-exclusion-management)
- [OpenAPI](openapi/github-copilot-openapi.yml)
- [JSONLD](json-ld/github-copilot-context.jsonld)

### GitHub Copilot Extensions API
Platform for building Copilot Extensions that integrate third-party tools, services, and custom agents into GitHub Copilot Chat, using GitHub Apps with agent or skillset configurations.

**Human URL:** [https://docs.github.com/en/copilot/building-copilot-extensions](https://docs.github.com/en/copilot/building-copilot-extensions)

#### Tags:

 - Agents, Extensions, Integrations, Skillsets

#### Properties

- [Documentation](https://docs.github.com/en/copilot/building-copilot-extensions/about-building-copilot-extensions)
- [GettingStarted](https://docs.github.com/en/copilot/building-copilot-extensions/creating-a-copilot-extension)
- [SDK](https://github.com/github/copilot-sdk)
- [GitHubOrganization](https://github.com/copilot-extensions)
- [CodeExamples](https://github.com/copilot-extensions/skillset-example)

### GitHub Copilot Coding Agent
Autonomous coding agent that works in the background to complete tasks, spinning up secure development environments powered by GitHub Actions to explore code, make changes, run tests, and open pull requests.

**Human URL:** [https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent)

#### Tags:

 - Agents, Automation, Code Generation, GitHub Actions, Pull Requests

#### Properties

- [Documentation](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent)

### GitHub Copilot Code Review
AI-powered code review agent that analyzes pull requests for issues, suggests fixes, and provides feedback across any programming language with agentic context gathering capabilities.

**Human URL:** [https://docs.github.com/en/copilot/concepts/agents/code-review](https://docs.github.com/en/copilot/concepts/agents/code-review)

#### Tags:

 - Agents, Code Quality, Code Review, Pull Requests

#### Properties

- [Documentation](https://docs.github.com/en/copilot/concepts/agents/code-review)

### GitHub MCP Server
GitHub official Model Context Protocol server that enables AI tools to interact with GitHub repositories, issues, pull requests, and other resources through a standardized protocol.

**Human URL:** [https://docs.github.com/en/copilot/concepts/context/mcp](https://docs.github.com/en/copilot/concepts/context/mcp)

#### Tags:

 - Agents, Context, Integrations, MCP, Model Context Protocol

#### Properties

- [Documentation](https://docs.github.com/en/copilot/concepts/context/mcp)
- [GitHubRepository](https://github.com/github/github-mcp-server)
- [GettingStarted](https://docs.github.com/en/copilot/how-tos/provide-context/use-mcp/set-up-the-github-mcp-server)

### GitHub Copilot Custom Instructions
Configuration system for providing repository-level, path-specific, and organization-level custom instructions to guide Copilot behavior, code style, and response formatting.

**Human URL:** [https://docs.github.com/en/copilot/how-tos/configure-custom-instructions](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions)

#### Tags:

 - Configuration, Customization, Instructions, Organizations

#### Properties

- [Documentation](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions)

## Common Properties

- [Portal](https://github.com/features/copilot)
- [StatusPage](https://www.githubstatus.com/)
- [TermsOfService](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service)
- [PrivacyPolicy](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)
- [GettingStarted](https://docs.github.com/en/copilot/quickstart)
- [Blog](https://github.blog/tag/github-copilot/)
- [SignUp](https://github.com/github-copilot/signup)
- [Pricing](https://github.com/features/copilot/plans)
- [ChangeLog](https://github.blog/changelog/label/copilot/)
- [Support](https://support.github.com)
- [SDK](https://github.com/github/copilot-sdk)
- [TrustCenter](https://copilot.github.trust.page/)
- [RateLimits](https://docs.github.com/en/rest/overview/rate-limits-for-the-rest-api)
- [Authentication](https://docs.github.com/en/rest/authentication)
- [OpenAPI](https://github.com/github/rest-api-description)
- [Documentation](https://docs.github.com/en/copilot)
- [Marketplace](https://github.com/marketplace?type=apps&copilot_app=true)

## Features

| Name | Description |
|------|-------------|
| Code Completion | AI-powered inline code suggestions that complete lines, functions, and entire blocks as you type in your IDE. |
| Chat | Conversational AI assistant for asking questions about code, generating solutions, and debugging directly in your editor. |
| Coding Agent | Autonomous agent that explores code, makes changes, runs tests, and opens pull requests from issue assignments. |
| Code Review | AI-powered pull request review that analyzes changes, identifies issues, and suggests fixes across any language. |
| Extensions | Third-party integrations that extend Copilot Chat with custom tools, services, and domain-specific agents. |
| Custom Instructions | Repository-level and organization-level configuration to guide Copilot behavior, code style, and conventions. |
| MCP Server | Model Context Protocol server enabling AI tools to interact with GitHub repositories, issues, and pull requests. |
| Content Exclusion | Governance controls to specify which files and repositories Copilot can access at organization and enterprise level. |
| Usage Metrics | Detailed analytics on Copilot adoption, usage patterns, and productivity impact across organizations and enterprises. |
| Seat Management | Programmatic management of Copilot seat assignments, billing, and subscription details for organizations and teams. |

## Use Cases

| Name | Description |
|------|-------------|
| Developer Productivity | Accelerate software development with AI-powered code completions, chat assistance, and automated code review. |
| Enterprise Copilot Governance | Manage Copilot deployments at scale with seat management, content exclusion, usage metrics, and compliance controls. |
| Custom AI Tooling | Build domain-specific Copilot Extensions and agents that integrate third-party tools and services into the developer workflow. |
| Code Quality Automation | Automate code review, identify potential issues, and enforce coding standards using the Copilot Code Review agent. |

## Integrations

| Name | Description |
|------|-------------|
| Visual Studio Code | Full Copilot integration in VS Code including code completion, chat, code review, and MCP support. |
| JetBrains IDEs | Copilot code completion and chat support across IntelliJ, PyCharm, WebStorm, and other JetBrains IDEs. |
| GitHub.com | Copilot Chat, code review, and coding agent capabilities directly in the GitHub web interface. |
| GitHub Actions | Copilot coding agent uses GitHub Actions to spin up secure environments for autonomous coding tasks. |
| Model Context Protocol | Standard protocol integration enabling AI tools to access GitHub data through the official MCP server. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [GitHub Copilot REST API](openapi/github-copilot-openapi.yml)

### JSON Schema

- [GitHub Copilot Seat Schema](json-schema/github-copilot-seat-schema.json)
- [GitHub Copilot Metrics Schema](json-schema/github-copilot-metrics-schema.json)

### JSON-LD

- [GitHub Copilot Context](json-ld/github-copilot-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
