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

2. **Create Architecture Solutions Agent**
   - File: `architecture-solutions.md`
   - Tools: Read, Write, Edit, WebSearch, TodoWrite
   - Expertise: Design patterns, cloud architectures, microservices, C4 diagrams, ADRs
   
3. **Create Elixir Phoenix Agent**
   - File: `elixir-phoenix.md`
   - Tools: Read, Write, Edit, Bash, Grep, TodoWrite
   - Expertise: OTP principles, LiveView, Ecto, GenServers, Phoenix best practices
   
4. **Create Data Architecture Agent**
   - File: `data-architecture.md`
   - Tools: Read, Write, Edit, WebSearch
   - Expertise: Data modeling, ETL/ELT, data governance, flow diagrams
   
5. **Create Semantic Data Agent**
   - File: `semantic-data.md`
   - Tools: Read, Write, Edit, WebSearch
   - Expertise: RDF, SPARQL, OWL, knowledge graphs, ontology engineering
   
6. **Create Documentation Technical Agent**
   - File: `documentation-technical.md`
   - Tools: Read, Write, Edit, WebSearch, TodoWrite
   - Expertise: Technical writing, API docs, architecture documentation

### Phase 3: UI/UX Agent Development

7. **Create UX/UI Design Agent (Master)**
   - File: `ux-ui-design.md`
   - Tools: Read, Write, Edit, WebSearch, TodoWrite
   - Expertise: UX principles, UI design patterns, accessibility, user research, design systems
   
8. **Create Web Frontend Agent**
   - File: `web-frontend.md`
   - Tools: Read, Write, Edit, Bash, WebSearch, TodoWrite
   - Expertise: HTML5, JavaScript/TypeScript, TailwindCSS, responsive design, web standards
   
9. **Create SvelteKit Developer Agent**
   - File: `sveltekit-developer.md`
   - Tools: Read, Write, Edit, Bash, Grep, TodoWrite
   - Expertise: SvelteKit, Svelte, reactive programming, SSR/SSG, Vite
   
10. **Create Flutter Developer Agent**
    - File: `flutter-developer.md`
    - Tools: Read, Write, Edit, Bash, Grep, TodoWrite
    - Expertise: Flutter, Dart, widget architecture, state management, cross-platform development
    
11. **Create React Native Developer Agent**
    - File: `reactnative-developer.md`
    - Tools: Read, Write, Edit, Bash, Grep, TodoWrite
    - Expertise: React Native, React, mobile development, native modules, performance optimization

### Phase 4: Testing & Code Quality Agent Development

12. **Create Test Architect Agent**
    - File: `test-architect.md`
    - Tools: Read, Write, Edit, Grep, WebSearch, TodoWrite
    - Expertise: Test planning, TDD/BDD, test strategy, coverage analysis, stub generation for Elixir/ExUnit, JavaScript/TypeScript, Flutter, and React Native testing frameworks
    
13. **Create Test Implementer Agent**
    - File: `test-implementer.md`
    - Tools: Read, Write, Edit, Bash, Grep, TodoWrite
    - Expertise: ExUnit, Jest, Vitest, Cypress, Playwright, Flutter test framework, React Native Testing Library, test implementation, mocking, fixtures
    
14. **Create Code Quality Analyzer Agent**
    - File: `code-quality-analyzer.md`
    - Tools: Read, Edit, Bash, Grep, TodoWrite
    - Expertise: Elixir compiler warnings, Credo, ESLint, TypeScript compiler, Dart analyzer, code smell detection, refactoring suggestions

### Phase 5: API Development Agent Suite

15. **Create API Designer Agent**
    - File: `api-designer.md`
    - Tools: Read, Write, Edit, WebSearch, TodoWrite
    - Expertise: REST API design, OpenAPI/Swagger specification, API versioning, resource modeling, HTTP standards, API security patterns
    
16. **Create API Implementer Agent**
    - File: `api-implementer.md`
    - Tools: Read, Write, Edit, Bash, Grep, TodoWrite
    - Expertise: Phoenix controllers, plugs, contexts, Ecto schemas, authentication/authorization, API rate limiting, error handling
    
17. **Create API Documenter Agent**
    - File: `api-documenter.md`
    - Tools: Read, Write, Edit, WebSearch, TodoWrite
    - Expertise: API documentation, OpenAPI generation, Postman collections, API examples, changelog management, developer guides

### Phase 6: Testing & Validation

18. **Test Each Agent**
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

### Phase 7: Documentation & Evolution

19. **Create Usage Documentation**
    - When to use each agent
    - How agents complement each other
    - Example workflows
    - UI/UX collaboration patterns
   
20. **Establish Feedback Loop**
    - Track agent usage patterns
    - Identify improvement opportunities
    - Plan for agent evolution

## Agent Specifications

### Tool Assignments
```
┌─────────────────────┬──────────────────────────────────────┐
│ Agent               │ Tools                                │
├─────────────────────┼──────────────────────────────────────┤
│ architecture        │ Read, Write, Edit, WebSearch,        │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ elixir-phoenix      │ Read, Write, Edit, Bash, Grep,       │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ data-architecture   │ Read, Write, Edit, WebSearch         │
├─────────────────────┼──────────────────────────────────────┤
│ semantic-data       │ Read, Write, Edit, WebSearch         │
├─────────────────────┼──────────────────────────────────────┤
│ documentation       │ Read, Write, Edit, WebSearch,        │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ ux-ui-design        │ Read, Write, Edit, WebSearch,        │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ web-frontend        │ Read, Write, Edit, Bash, WebSearch,  │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ sveltekit           │ Read, Write, Edit, Bash, Grep,       │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ flutter             │ Read, Write, Edit, Bash, Grep,       │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ reactnative         │ Read, Write, Edit, Bash, Grep,       │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ test-architect      │ Read, Write, Edit, Grep, WebSearch,  │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ test-implementer    │ Read, Write, Edit, Bash, Grep,       │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ code-quality        │ Read, Edit, Bash, Grep, TodoWrite    │
├─────────────────────┼──────────────────────────────────────┤
│ api-designer        │ Read, Write, Edit, WebSearch,        │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ api-implementer     │ Read, Write, Edit, Bash, Grep,       │
│                     │ TodoWrite                            │
├─────────────────────┼──────────────────────────────────────┤
│ api-documenter      │ Read, Write, Edit, WebSearch,        │
│                     │ TodoWrite                            │
└─────────────────────┴──────────────────────────────────────┘
```

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
name: agent-name
description: Brief description of agent's purpose
tools: Tool1, Tool2, Tool3
---
System prompt defining the agent's expertise and behavior
```

## Progress Tracking

- [ ] Phase 1: Infrastructure Setup
- [ ] Phase 2: Core Agent Development - Backend & Architecture
  - [ ] architecture-solutions
  - [ ] elixir-phoenix
  - [ ] data-architecture
  - [ ] semantic-data
  - [ ] documentation-technical
- [ ] Phase 3: UI/UX Agent Development
  - [ ] ux-ui-design (Master)
  - [ ] web-frontend
  - [ ] sveltekit-developer
  - [ ] flutter-developer
  - [ ] reactnative-developer
- [ ] Phase 4: Testing & Code Quality Agent Development
  - [ ] test-architect
  - [ ] test-implementer
  - [ ] code-quality-analyzer
- [ ] Phase 5: API Development Agent Suite
  - [ ] api-designer
  - [ ] api-implementer
  - [ ] api-documenter
- [ ] Phase 6: Testing & Validation
- [ ] Phase 7: Documentation & Evolution

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
   - Ecto schemas and contexts
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