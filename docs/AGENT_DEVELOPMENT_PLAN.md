# Claude Sub-Agents Development Plan

## Project Overview
This document outlines the comprehensive plan for developing specialized Claude sub-agents to assist with software architecture, Elixir Phoenix development, data architecture, semantic data work, and various UI/UX development platforms.

## Phase Structure

```
Phase 1: Infrastructure Setup
    └── Create agents/ directory
    └── Establish naming conventions
    
Phase 2: Core Agent Development - Backend & Architecture
    ├── architecture-solutions
    ├── elixir-phoenix
    ├── data-architecture
    ├── semantic-data
    └── documentation-technical
    
Phase 3: UI/UX Agent Development
    ├── ux-ui-design (Master UX/UI specialist)
    ├── web-frontend (HTML/JS/Tailwind)
    ├── sveltekit-developer
    ├── flutter-developer
    └── reactnative-developer
    
Phase 4: Testing & Code Quality Agent Development
    ├── test-architect (Test planning & stub generation)
    ├── test-implementer (Test implementation)
    └── code-quality-analyzer (Compiler/lint warnings)
    
Phase 5: API Development Agent Suite
    ├── api-designer (REST API design & OpenAPI)
    ├── api-implementer (Phoenix API implementation)
    └── api-documenter (API documentation)
    
Phase 6: Testing & Validation
    └── Test each agent with real tasks
    
Phase 7: Documentation & Evolution
    └── Usage guidelines
    └── Feedback mechanism
```

## Detailed Implementation Plan

### Phase 1: Infrastructure Setup

1. **Create Project Structure**
   - Establish `agents/` directory
   - Define naming convention: `category-purpose.md`
   - Set up version control for agents

### Phase 2: Core Agent Development - Backend & Architecture

2. **Create Brainstormer Agent** (NEW)
   - File: `brainstormer.md`
   - Expertise: Creative ideation, technology exploration, innovative problem-solving
   - Special: Integrates with zen MCP tools for enhanced analysis

3. **Create Architecture Solutions Agent**
   - File: `architecture-solutions.md`
   - Expertise: Design patterns, cloud architectures, microservices, C4 diagrams, ADRs
   
4. **Create Specifications Writer Agent** (NEW)
   - File: `specifications-writer.md`
   - Expertise: PRDs, technical specifications, implementation plans
   
5. **Create Elixir Phoenix Agent**
   - File: `elixir-phoenix.md`
   - Expertise: OTP principles, LiveView, Ash Framework, GenServers, Phoenix best practices

6. **Create Database Specialist Agent** (NEW)
   - File: `database-specialist.md`
   - Expertise: PostgreSQL mastery, Ash/Ecto optimization, query tuning, index strategies
   
7. **Create Data Architecture Agent**
   - File: `data-architecture.md`
   - Expertise: Data modeling, ETL/ELT, data governance, flow diagrams
   
8. **Create Semantic Data Agent**
   - File: `semantic-data.md`
   - Expertise: RDF, SPARQL, OWL, knowledge graphs, ontology engineering

9. **Create DevOps Engineer Agent** (NEW)
   - File: `devops-engineer.md`
   - Expertise: AWS, Terraform, GitHub Actions, AWS Copilot, CI/CD pipelines
   
10. **Create Documentation Technical Agent**
    - File: `documentation-technical.md`
    - Expertise: Technical writing, API docs, architecture documentation

### Phase 3: UI/UX Agent Development

11. **Create UX/UI Design Agent (Master)**
    - File: `ux-ui-design.md`
    - Expertise: UX principles, UI design patterns, accessibility, user research, design systems
   
12. **Create Web Frontend Agent**
    - File: `web-frontend.md`
    - Expertise: HTML5, JavaScript/TypeScript, TailwindCSS, responsive design, web standards
   
13. **Create SvelteKit Developer Agent**
    - File: `sveltekit-developer.md`
    - Expertise: SvelteKit, Svelte, reactive programming, SSR/SSG, Vite
   
14. **Create Flutter Developer Agent**
    - File: `flutter-developer.md`
    - Expertise: Flutter, Dart, widget architecture, GetX state management, cross-platform development
    
15. **Create React Native Developer Agent**
    - File: `reactnative-developer.md`
    - Expertise: React Native, React, mobile development, native modules, performance optimization

### Phase 4: Testing & Code Quality Agent Development

16. **Create Test Architect Agent**
    - File: `test-architect.md`
    - Expertise: Test planning, TDD/BDD, test strategy, coverage analysis, stub generation for Elixir/ExUnit, JavaScript/TypeScript, Flutter, and React Native testing frameworks
    
17. **Create Test Implementer Agent**
    - File: `test-implementer.md`
    - Expertise: ExUnit, Jest, Vitest, Cypress, Playwright, Flutter test framework, React Native Testing Library, test implementation, mocking, fixtures
    
18. **Create Code Quality Analyzer Agent**
    - File: `code-quality-analyzer.md`
    - Expertise: Elixir compiler warnings, Credo, ESLint, TypeScript compiler, Dart analyzer, code smell detection, refactoring suggestions

### Phase 5: API Development Agent Suite

19. **Create API Designer Agent**
    - File: `api-designer.md`
    - Expertise: REST API design, OpenAPI/Swagger specification, API versioning, resource modeling, HTTP standards, API security patterns
    
20. **Create API Implementer Agent**
    - File: `api-implementer.md`
    - Expertise: Phoenix controllers, plugs, contexts, Ash resources, authentication/authorization, API rate limiting, error handling
    
21. **Create API Documenter Agent**
    - File: `api-documenter.md`
    - Expertise: API documentation, OpenAPI generation, Postman collections, API examples, changelog management, developer guides

### Phase 6: Operations & Management Agent Development (NEW)

22. **Create Security Specialist Agent**
    - File: `security-specialist.md`
    - Expertise: Application security, OWASP Top 10, penetration testing, vulnerability assessment, compliance

23. **Create Performance Optimizer Agent**
    - File: `performance-optimizer.md`
    - Expertise: Performance profiling, optimization strategies, caching, load testing, scalability patterns

24. **Create Project Coordinator Agent**
    - File: `project-coordinator.md`
    - Expertise: Agile project management, sprint planning, task coordination, team collaboration, stakeholder management

### Phase 7: Testing & Validation

25. **Test Each Agent**
    - Architecture: Create microservices design
    - Elixir: Implement LiveView feature
    - Data: Design warehouse schema
    - Semantic: Create domain ontology
    - Documentation: Write API documentation
    - UX/UI: Design a complete user flow
    - Web Frontend: Build responsive component
    - SvelteKit: Create full-stack feature
    - Flutter: Build cross-platform screen
    - React Native: Implement native integration
    - Test Architect: Design test plan for a module
    - Test Implementer: Complete test implementation
    - Code Quality: Analyze and fix warnings
    - API Designer: Design REST API with OpenAPI spec
    - API Implementer: Build Phoenix API endpoints
    - API Documenter: Create comprehensive API docs

### Phase 8: Documentation & Evolution

26. **Create Usage Documentation**
    - When to use each agent
    - How agents complement each other
    - Example workflows
    - UI/UX collaboration patterns
   
27. **Establish Feedback Loop**
    - Track agent usage patterns
    - Identify improvement opportunities
    - Plan for agent evolution

## Agent Specifications

**Note**: As of version 0.2.0, agents no longer have explicit tool specifications in their frontmatter. Agents can use any tools available in the main thread context, allowing for greater flexibility and tool reuse.

## Implementation Strategy

- Start with one agent (architecture-solutions) as proof of concept
- Test thoroughly before creating others
- Iterate based on real usage
- Keep agents focused and specialized
- Ensure clear boundaries between agents

## Success Metrics

- Each agent handles domain tasks expertly
- Clear separation of concerns
- High-quality specialized outputs
- Easy agent selection for users
- Evolving based on usage patterns

## Claude Sub-Agent Format

Each agent is a markdown file with YAML frontmatter:

```markdown
---
name: Agent Name
description: Brief description of agent's purpose and expertise
color: "#HEX_COLOR"
model: opus (optional)
---
System prompt defining the agent's expertise and behavior
```

## Progress Tracking

- [x] Phase 1: Infrastructure Setup ✅
- [x] Phase 2: Core Agent Development - Backend & Architecture ✅
  - [x] brainstormer (NEW - added for creative ideation)
  - [x] architecture-solutions
  - [x] specifications-writer
  - [x] elixir-phoenix
  - [x] database-specialist (NEW - PostgreSQL/Ash/Ecto expert)
  - [x] data-architecture
  - [x] semantic-data
  - [x] devops-engineer (NEW - AWS/Terraform/GitHub Actions)
  - [x] documentation-technical
- [x] Phase 3: UI/UX Agent Development ✅
  - [x] ux-ui-design (Master)
  - [x] web-frontend
  - [x] sveltekit-developer
  - [x] flutter-developer
  - [x] reactnative-developer
- [x] Phase 4: Testing & Code Quality Agent Development ✅
  - [x] test-architect
  - [x] test-implementer
  - [x] code-quality-analyzer
- [x] Phase 5: API Development Agent Suite ✅
  - [x] api-designer
  - [x] api-implementer
  - [x] api-documenter
- [x] Phase 6: Operations & Management (NEW PHASE) ✅
  - [x] security-specialist
  - [x] performance-optimizer
  - [x] project-coordinator
- [ ] Phase 7: Testing & Validation (In Progress)
- [ ] Phase 8: Documentation & Evolution

## Agent Collaboration Patterns

### UI/UX Master Agent Coordination
The UX/UI Design agent serves as the master coordinator for all UI-related work:
- Establishes design systems and patterns
- Ensures consistency across platforms
- Guides platform-specific agents on UX principles
- Reviews and validates UI implementations

### Cross-Platform Development Flow
1. UX/UI Design agent creates the design system
2. Platform-specific agents implement according to guidelines
3. Web Frontend handles Phoenix LiveView integration
4. Mobile agents (Flutter, React Native) ensure native feel
5. SvelteKit agent manages full-stack features

### Testing & Quality Workflow
1. **Test Architect** analyzes codebase and creates:
   - Comprehensive test plans
   - Test strategy documentation
   - Failing test stubs with proper assertions
   - Coverage targets
   - Supports: Elixir/ExUnit, JS/TS, Flutter, React Native
   
2. **Test Implementer** takes stubs and:
   - Implements actual test logic
   - Creates mocks and fixtures
   - Ensures tests pass
   - Frameworks: ExUnit, Jest, Vitest, Flutter test, React Native Testing Library
   
3. **Code Quality Analyzer** continuously:
   - Monitors compiler warnings (Elixir, TypeScript, Dart)
   - Analyzes Credo (Elixir) output
   - Reviews ESLint/TSLint results
   - Dart analyzer for Flutter
   - Suggests fixes and improvements

### API Development Workflow
1. **API Designer** creates:
   - RESTful API designs
   - OpenAPI/Swagger specifications
   - Resource modeling and versioning strategies
   - Security and authentication patterns
   
2. **API Implementer** builds:
   - Phoenix controllers and routes
   - Ash resources and contexts
   - Authentication/authorization logic
   - Error handling and validation
   
3. **API Documenter** produces:
   - Interactive API documentation
   - Integration guides
   - Code examples and SDKs
   - Postman collections

### Agent Specialization Rationale
- **Test Architect**: Focuses on planning and strategy across all platforms
- **Test Implementer**: Deep knowledge of testing frameworks and implementation
- **Code Quality Analyzer**: Specialized in static analysis tools across languages
- **API Designer**: REST principles and API architecture expertise
- **API Implementer**: Phoenix-specific implementation knowledge
- **API Documenter**: Technical writing and developer experience focus