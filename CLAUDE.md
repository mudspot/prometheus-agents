# Prometheus Agents - Claude SubAgents Project

**Version: 0.3.0**

## Project Overview
This project provides 23 specialized Claude SubAgents to assist with all aspects of software development, from architecture and backend development to UI/UX, testing, DevOps, and project management. Each agent has deep expertise in their domain and can collaborate effectively with other agents.

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

### 1. Backend & Architecture Agents (8 agents) - 🔵 Blue (#2196F3)
- **brainstormer** - Creative ideation, technology exploration, and innovative problem-solving *(defaults to Opus)*
- **solutions-architect** - System design, architecture patterns, and technical decision-making *(defaults to Opus)*
- **specifications-writer** - PRDs, technical specifications, and implementation plans
- **elixir-developer** - Phoenix framework development, LiveView, and Elixir best practices
- **database-specialist** - PostgreSQL master, Ash/Ecto optimization, query and index tuning *(defaults to Opus)*
- **data-architect** - Data schema design, database architecture, and data flow optimization
- **semantic-data-specialist** - RDF, SPARQL, OWL, and semantic web technologies
- **devops-engineer** - AWS, Terraform, GitHub Actions, Copilot, CI/CD pipelines

### 2. UI/UX Development Agents (5 agents) - 🟢 Green (#4CAF50)
- **ux-designer** - Master agent for UX/UI design principles and user experience
- **web-developer** - HTML, JavaScript, and TailwindCSS development for Phoenix
- **sveltekit-developer** - SvelteKit and Svelte component development
- **flutter-developer** - Flutter mobile and web application development
- **reactnative-developer** - React Native cross-platform mobile development

### 3. Testing & Quality Agents (3 agents) - 🟣 Purple (#9C27B0)
- **test-architect** - Test planning, strategy, and test case design *(defaults to Opus)*
- **test-implementer** - Test implementation and automation
- **code-quality-analyzer** - Static analysis, linting, and code quality metrics

### 4. API Development Agents (3 agents) - 🔷 Cyan (#00BCD4)
- **api-designer** - REST API design, OpenAPI specifications, and API architecture
- **api-implementer** - Phoenix API implementation and best practices
- **api-documenter** - API documentation, examples, and integration guides

### 5. Documentation Agents (1 agent) - 🔘 Blue-Grey (#607D8B)
- **technical-writer** - Technical documentation, design docs, and architecture decisions

### 6. Operations & Management Agents (3 agents) - 🟠 Deep Orange (#FF5722)
- **security-specialist** - Application security, OWASP, penetration testing, compliance *(defaults to Opus)*
- **performance-optimizer** - Performance profiling, optimization, caching, scalability *(defaults to Opus)*
- **project-coordinator** - Agile project management, sprint planning, team coordination

## Project Structure
- `/agents/` - SubAgent implementations (23 agents)
  - Backend & architecture agents (8)
  - UI/UX development agents (5)
  - Testing & quality agents (3)
  - API development agents (3)
  - Documentation agents (1)
  - Operations & management agents (3)
- `/docs/` - Design documents and specifications
  - `AGENT_DEVELOPMENT_PLAN.md` - Comprehensive development roadmap
  - `AGENT_SUMMARY.md` - Complete overview of all 23 agents
  - `AGENT_USAGE_GUIDE.md` - Detailed usage guide with examples
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

### Innovation & Design Flow
1. **brainstormer** explores possibilities and generates innovative approaches
2. **solutions-architect** formalizes the best ideas into system design
3. **specifications-writer** translates into PRDs and technical specs
4. Platform-specific agents use specs for implementation
5. **technical-writer** creates end-user documentation

### UI/UX Development Flow
1. **ux-designer** creates design specifications and wireframes
2. Platform-specific agents implement the designs:
   - **web-developer** for Phoenix LiveView/HTML
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

### Operations & Management Flow
1. **security-specialist** performs security assessment and threat modeling
2. **performance-optimizer** identifies and resolves performance bottlenecks
3. **devops-engineer** implements infrastructure and deployment solutions
4. **project-coordinator** manages timelines and team coordination

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