# Prometheus Agents - Claude SubAgents Project

**Version: 0.1.0**

## Project Overview
This project creates specialized Claude SubAgents to assist with software architecture, Elixir Phoenix development, data architecture, and semantic data work.

**Development Plan**: See [docs/AGENT_DEVELOPMENT_PLAN.md](docs/AGENT_DEVELOPMENT_PLAN.md) for the comprehensive development roadmap.

## Key Areas of Focus
- Software Solutions Architecture
- Elixir Phoenix Development
- Data Architecture & Schema Design
- Enterprise Data Flow Design
- Semantic Data
- Design Documentation
- Code Implementation

## SubAgent Categories

### 1. Backend & Architecture Agents
- **architecture-solutions** - System design, architecture patterns, and technical decision-making
- **specifications-writer** - PRDs, technical specifications, and implementation plans
- **elixir-phoenix** - Phoenix framework development, LiveView, and Elixir best practices
- **data-architecture** - Data schema design, database architecture, and data flow optimization
- **semantic-data** - RDF, SPARQL, OWL, and semantic web technologies

### 2. UI/UX Development Agents
- **ux-ui-design** - Master agent for UX/UI design principles and user experience
- **web-frontend** - HTML, JavaScript, and TailwindCSS development for Phoenix
- **sveltekit-developer** - SvelteKit and Svelte component development
- **flutter-developer** - Flutter mobile and web application development
- **reactnative-developer** - React Native cross-platform mobile development

### 3. Testing & Quality Agents
- **test-architect** - Test planning, strategy, and test case design (supports all platforms)
- **test-implementer** - Test implementation and automation (supports all platforms)
- **code-quality-analyzer** - Static analysis, linting, and code quality metrics

### 4. API Development Agents
- **api-designer** - REST API design, OpenAPI specifications, and API architecture
- **api-implementer** - Phoenix API implementation and best practices
- **api-documenter** - API documentation, examples, and integration guides

### 5. Documentation Agents
- **documentation-technical** - Technical documentation, design docs, and architecture decisions

## Project Structure
- `/agents/` - SubAgent implementations (to be created)
  - Backend & architecture agents
  - UI/UX development agents  
  - Testing & quality agents
  - API development agents
  - Documentation agents
- `/docs/` - Design documents and specifications
  - `AGENT_DEVELOPMENT_PLAN.md` - Comprehensive development roadmap
- `/rules/` - Framework and technology usage rules
  - Elixir/OTP rules
  - Ash framework rules
  - Memory and MCP rules
- `/examples/` - Example usage and test cases (to be created)
- `/lib/` - Shared libraries and utilities (to be created)

## Development Guidelines
- Focus on creating focused, specialized agents
- Each agent should excel at specific tasks
- Maintain clear interfaces between agents
- Document agent capabilities and limitations

## User Context
- Software Solutions Architect
- Elixir Phoenix Software Engineer
- Data Architect specializing in:
  - Data schemas design
  - Enterprise data flows between siloed data
  - Personal data servers
  - Semantic Data
- Full-stack developer working with:
  - Backend: Elixir/Phoenix, REST APIs
  - Frontend: HTML/JS/TailwindCSS, SvelteKit, Flutter, React Native
  - Testing: ExUnit, Jest/Vitest, Flutter test, React Native Testing Library
  - Quality: Credo, ESLint, TypeScript, Dart analyzer
- Creates design documents and code

## Agent Development Principles
- Each agent should be highly specialized
- Agents should understand domain-specific terminology
- Agents should follow best practices for their domain
- Clear communication between agents when needed
- Comprehensive documentation for each agent's capabilities

## Agent Collaboration Patterns

### Specification Development Flow
1. **architecture-solutions** creates high-level system design
2. **specifications-writer** translates into PRDs and technical specs
3. Platform-specific agents use specs for implementation
4. **documentation-technical** creates end-user documentation

### UI/UX Development Flow
1. **ux-ui-design** creates design specifications and wireframes
2. Platform-specific agents implement the designs:
   - **web-frontend** for Phoenix LiveView/HTML
   - **sveltekit-developer** for SvelteKit apps
   - **flutter-developer** for Flutter apps
   - **reactnative-developer** for React Native apps

### Testing Workflow
1. **test-architect** analyzes code and creates test plans
2. **test-implementer** writes test implementations
3. **code-quality-analyzer** reviews code quality and suggests improvements

### API Development Flow
1. **api-designer** creates OpenAPI specifications
2. **api-implementer** builds Phoenix API endpoints
3. **api-documenter** generates comprehensive documentation

### Cross-Agent Communication
- Agents share context through structured data formats
- Each agent maintains its domain expertise while collaborating
- Clear handoff points between agents for complex tasks

<!-- usage-rules-start -->
<!-- usage-rules-header -->
# Usage Rules

**IMPORTANT**: Consult these usage rules early and often when working with the packages listed below. 
Before attempting to use any of these packages or to discover if you should use them, review their 
usage rules to understand the correct patterns, conventions, and best practices.
<!-- usage-rules-header-end -->

<!-- memory-start -->
## memory
[memory rules](rules/memory.md)
<!-- memory-end -->
<!-- mcp-start -->
## mcp
[mcp rules](rules/mcp.md)
<!-- mcp-end -->

<!-- ash-start -->
## ash usage
_A declarative, extensible framework for building Elixir applications.
_

[ash usage rules](rules/ash.md)
<!-- ash-end -->
<!-- igniter-start -->
## igniter usage
_A code generation and project patching framework
_

[igniter usage rules](rules/igniter.md)
<!-- igniter-end -->
<!-- ash_phoenix-start -->
## ash_phoenix usage
_Utilities for integrating Ash and Phoenix
_

[ash_phoenix usage rules](rules/ash_phoenix.md)
<!-- ash_phoenix-end -->
<!-- usage_rules:elixir-start -->
## usage_rules:elixir usage
[usage_rules:elixir usage rules](rules/usage_rules_elixir.md)
<!-- usage_rules:elixir-end -->
<!-- usage_rules:otp-start -->
## usage_rules:otp usage
[usage_rules:otp usage rules](rules/usage_rules_otp.md)
<!-- usage_rules:otp-end -->
<!-- ash_postgres-start -->
## ash_postgres usage
_The PostgreSQL data layer for Ash Framework
_

[ash_postgres usage rules](rules/ash_postgres.md)
<!-- ash_postgres-end -->
<!-- usage-rules-end -->