# Agentic AI Foundation (agentic-ai-foundation)
The Agentic AI Foundation (AAIF) is a Linux Foundation project formed in December 2025 that brings together critical open standards and projects for AI agents under neutral governance. It hosts Anthropic's Model Context Protocol (MCP), Block's goose AI agent, and OpenAI's AGENTS.md to enable interoperable, open AI agent ecosystems. The foundation drives standardization of agent communication protocols, tool interfaces, and cross-platform agent portability.

**URL:** [https://lfaidata.foundation/](https://lfaidata.foundation/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI Agents, Linux Foundation, Open Source, Standards, MCP, Agentic AI, Interoperability

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Model Context Protocol (MCP)
The Model Context Protocol (MCP) is an open-source standard for connecting AI applications to external systems including data sources, tools, and workflows. Originally developed by Anthropic and donated to the Agentic AI Foundation, MCP enables agents to discover and invoke tools, access resources, and use reusable prompt templates through a standardized protocol.

**Human URL:** [https://modelcontextprotocol.io/introduction](https://modelcontextprotocol.io/introduction)

#### Tags:

 - MCP, Model Context Protocol, Open Standard, Tool Use, AI Agents

#### Properties

- [Documentation](https://modelcontextprotocol.io/introduction)
- [GettingStarted](https://modelcontextprotocol.io/docs/develop/build-server)
- [GitHubRepository](https://github.com/modelcontextprotocol/specification)

### Goose AI Agent
Goose is a general-purpose, open-source AI agent that runs locally on your machine. Originally from Block and now under AAIF governance, goose supports 15+ LLM providers, 70+ MCP extensions, and provides a native desktop app, CLI, and API. Built in Rust for cross-platform portability across macOS, Linux, and Windows.

**Human URL:** [https://github.com/block/goose](https://github.com/block/goose)

#### Tags:

 - AI Agent, Open Source, MCP, CLI, Desktop App, Rust

#### Properties

- [Documentation](https://block.github.io/goose/)
- [GitHubRepository](https://github.com/block/goose)

## Common Properties

- [GitHubOrganization](https://github.com/agentic-ai-foundation)
- [Portal](https://lfaidata.foundation/)
- [Documentation](https://modelcontextprotocol.io/introduction)
- [JSONSchema - MCP Tool Schema](https://raw.githubusercontent.com/api-evangelist/agentic-ai-foundation/refs/heads/main/json-schema/agentic-ai-foundation-mcp-tool-schema.json)
- [JSONSchema - MCP Resource Schema](https://raw.githubusercontent.com/api-evangelist/agentic-ai-foundation/refs/heads/main/json-schema/agentic-ai-foundation-mcp-resource-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agentic-ai-foundation/refs/heads/main/json-ld/agentic-ai-foundation-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agentic-ai-foundation/refs/heads/main/vocabulary/agentic-ai-foundation-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Neutral Open Governance | All AAIF projects operate under Linux Foundation neutral governance, ensuring no single vendor controls the direction of AI agent standards. |
| Model Context Protocol (MCP) | MCP is a universal adapter standard enabling AI agents to connect to any external tool, data source, or workflow through a consistent protocol. |
| Cross-Platform Agent Portability | AAIF standards enable AI agents to run consistently across different platforms, environments, and LLM providers without vendor lock-in. |
| Tool and Extension Ecosystem | The MCP standard enables a rich ecosystem of 70+ tools and extensions that any compliant agent can discover and invoke. |
| Multi-LLM Provider Support | AAIF projects support 15+ LLM providers including Anthropic, OpenAI, Google, Azure, and Ollama through standardized provider interfaces. |
| Open Agent Communication | The Agent Communication Protocol (ACP) enables agents to authenticate and communicate with each other and LLM providers through open standards. |

## Use Cases

| Name | Description |
|------|-------------|
| Interoperable AI Tool Development | Build MCP-compatible tools once and make them available to any AI agent or client that supports the MCP standard, eliminating integration silos. |
| Enterprise Agent Standardization | Organizations adopt AAIF standards to ensure their AI agent infrastructure is portable, auditable, and not locked to a single AI vendor. |
| Multi-Agent Workflow Orchestration | Use AAIF protocols to connect specialized AI agents that collaborate on complex tasks, each contributing domain-specific capabilities. |
| Open-Source Agent Development | Developers build and extend open-source AI agents like goose using the AAIF ecosystem of standards and extensions. |

## Integrations

| Name | Description |
|------|-------------|
| Claude (Anthropic) | Native MCP support via the Anthropic Messages API, the originating implementation of the MCP standard. |
| ChatGPT (OpenAI) | MCP tool integration via the OpenAI Responses API, enabling ChatGPT to invoke MCP-compatible tools. |
| VS Code | GitHub Copilot in VS Code supports MCP servers for AI-assisted development through the AAIF MCP standard. |
| Cursor | Cursor IDE integrates MCP tool support for AI-assisted coding agents. |
| Linux Foundation | AAIF operates under Linux Foundation governance alongside related projects in the LF AI & Data portfolio. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [MCP Tool Schema](json-schema/agentic-ai-foundation-mcp-tool-schema.json)
- [MCP Resource Schema](json-schema/agentic-ai-foundation-mcp-resource-schema.json)

### JSON Structure

- [MCP Tool Structure](json-structure/agentic-ai-foundation-mcp-tool-structure.json)
- [MCP Resource Structure](json-structure/agentic-ai-foundation-mcp-resource-structure.json)

### JSON-LD

- [Agentic AI Foundation Context](json-ld/agentic-ai-foundation-context.jsonld)

## Vocabulary

- [Agentic AI Foundation Vocabulary](vocabulary/agentic-ai-foundation-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 6 actions, 2 workflows, and 2 personas across the MCP and goose ecosystems

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
