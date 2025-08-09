# Agent Consolidation Mapping

## Overview
This document provides detailed mapping of the current 23 agents to the proposed 9 consolidated agents.

## Mapping Table

| Current Agent | Consolidated Agent | Key Capabilities Preserved |
|--------------|-------------------|---------------------------|
| **brainstormer** | **architect** | Innovation, technology exploration, risk analysis, hypothesis generation |
| **solutions-architect** | **architect** | System design, architecture patterns, C4 diagrams, ADRs |
| **elixir-developer** | **backend-developer** | Elixir/Phoenix expertise, OTP, Ash Framework, LiveView |
| **database-specialist** | **data-engineer** | PostgreSQL optimization, query tuning, index strategies |
| **data-architect** | **data-engineer** | Data modeling, ETL/ELT, data flow design |
| **ontology-specialist** | **data-engineer** | RDF, SPARQL, semantic web, knowledge graphs |
| **devops-engineer** | **devops-engineer** | *No change - remains as is* |
| **ux-designer** | **frontend-developer** | UX principles, wireframing, design systems, accessibility |
| **web-developer** | **frontend-developer** | HTML/CSS/JS, TailwindCSS, Phoenix LiveView integration |
| **sveltekit-developer** | **frontend-developer** | SvelteKit, Svelte components, SSR/SSG |
| **flutter-developer** | **frontend-developer** | Flutter widgets, Dart, cross-platform mobile |
| **reactnative-developer** | **frontend-developer** | React Native, native modules, cross-platform |
| **test-architect** | **test-engineer** | Test planning, TDD/BDD, coverage analysis |
| **test-implementer** | **test-engineer** | Test implementation, automation, mocking |
| **code-reviewer** | **test-engineer** | Static analysis, linting, code quality metrics |
| **api-designer** | **api-specialist** | REST design, OpenAPI specs, versioning |
| **api-implementer** | **api-specialist** | Phoenix API implementation, GraphQL |
| **api-documenter** | **api-specialist** | API documentation, examples, SDK docs |
| **technical-writer** | **product-coordinator** | Technical documentation, user guides |
| **security-specialist** | **quality-specialist** | Security assessment, OWASP, penetration testing |
| **performance-optimizer** | **quality-specialist** | Performance profiling, optimization, caching |
| **project-coordinator** | **product-coordinator** | Agile management, sprint planning |
| **specifications-writer** | **product-coordinator** | PRDs, technical specifications |

## Detailed Capability Preservation

### 1. architect (Consolidates 2 agents)
**Preserves from brainstormer:**
- Creative ideation and divergent thinking
- Technology exploration and trend analysis
- Risk assessment and feasibility studies
- Hypothesis generation and validation
- "What if" scenarios and innovation patterns
- Zen MCP tool integration (consensus, thinkdeep, challenge)

**Preserves from solutions-architect:**
- System design patterns and best practices
- C4 diagrams and architectural documentation
- Architectural Decision Records (ADRs)
- Microservices and distributed systems design
- Technology stack evaluation
- Cross-system integration strategies

**New unified capabilities:**
- End-to-end architectural thinking from ideation to implementation
- Comprehensive risk and opportunity assessment
- Innovation-driven architecture design

### 2. backend-developer (Consolidates 1 agent, extends scope)
**Preserves from elixir-developer:**
- Deep Elixir/OTP expertise
- Phoenix Framework mastery
- Ash Framework specialization
- LiveView development
- Concurrent and fault-tolerant systems
- ExUnit testing patterns

**New extended capabilities:**
- General backend patterns applicable to other languages
- API backend implementation
- Microservices development
- Message queue and event systems
- Backend performance optimization

### 3. frontend-developer (Consolidates 5 agents)
**Preserves from ux-designer:**
- User experience principles
- Design systems and component libraries
- Wireframing and prototyping
- Accessibility standards (WCAG)
- User research and personas
- Cross-platform design coordination

**Preserves from web-developer:**
- HTML5, CSS3, JavaScript/TypeScript
- TailwindCSS expertise
- Phoenix LiveView integration
- Responsive design
- Web performance optimization

**Preserves from sveltekit-developer:**
- SvelteKit application development
- Svelte reactive components
- SSR/SSG implementation
- Vite configuration

**Preserves from flutter-developer:**
- Flutter widget architecture
- Dart programming
- Cross-platform mobile development
- GetX state management
- Native platform integration

**Preserves from reactnative-developer:**
- React Native components
- Native module bridges
- Cross-platform JavaScript
- React patterns and hooks

**New unified capabilities:**
- Framework-agnostic frontend architecture
- Unified component design across platforms
- Consistent UX across web and mobile

### 4. data-engineer (Consolidates 3 agents)
**Preserves from database-specialist:**
- PostgreSQL deep expertise
- Query optimization and analysis
- Index design and optimization
- Database performance tuning
- Ash/Ecto integration

**Preserves from data-architect:**
- Data modeling and schema design
- ETL/ELT pipeline design
- Data warehouse architecture
- Data governance strategies
- Cross-system data flows

**Preserves from ontology-specialist:**
- Semantic web technologies
- RDF and SPARQL expertise
- Knowledge graph design
- Ontology engineering
- Linked data principles

**New unified capabilities:**
- Comprehensive data strategy from storage to semantics
- Multi-paradigm data architecture (relational, graph, semantic)
- End-to-end data pipeline design

### 5. api-specialist (Consolidates 3 agents)
**Preserves from api-designer:**
- REST API design principles
- OpenAPI/Swagger specifications
- API versioning strategies
- Resource modeling
- API security patterns

**Preserves from api-implementer:**
- Phoenix API implementation
- GraphQL implementation
- Middleware development
- Authentication/authorization
- Rate limiting and throttling

**Preserves from api-documenter:**
- Comprehensive API documentation
- Interactive documentation (Swagger UI)
- Code examples and SDKs
- Integration guides
- Postman collections

**New unified capabilities:**
- Complete API lifecycle management
- API-first development approach
- API governance and standards

### 6. test-engineer (Consolidates 3 agents)
**Preserves from test-architect:**
- Test strategy and planning
- TDD/BDD methodologies
- Test pyramid design
- Coverage analysis
- Risk-based testing

**Preserves from test-implementer:**
- Multi-framework test implementation
- Test automation
- Mocking and stubbing
- E2E test development
- Performance testing

**Preserves from code-reviewer:**
- Static code analysis
- Linting configuration
- Code quality metrics
- Automated code review
- Security scanning

**New unified capabilities:**
- Comprehensive quality assurance
- Shift-left testing approach
- Continuous testing integration

### 7. devops-engineer (No consolidation)
**Maintains all current capabilities:**
- AWS cloud services
- Terraform infrastructure as code
- GitHub Actions workflows
- CI/CD pipelines
- Container orchestration
- Monitoring and observability
- AWS Copilot deployments

### 8. quality-specialist (Consolidates 2 agents)
**Preserves from security-specialist:**
- Security assessment and auditing
- OWASP Top 10 compliance
- Penetration testing
- Threat modeling
- Security architecture review
- Compliance requirements (SOC2, PCI DSS, HIPAA)

**Preserves from performance-optimizer:**
- Performance profiling and analysis
- Optimization strategies
- Caching implementation
- Load testing
- Scalability planning
- Frontend and backend performance

**New unified capabilities:**
- Holistic system quality assurance
- Security-performance trade-off analysis
- Compliance and performance standards

### 9. product-coordinator (Consolidates 3 agents)
**Preserves from project-coordinator:**
- Agile project management
- Sprint planning and tracking
- Team coordination
- Stakeholder communication
- Risk management
- Resource allocation

**Preserves from specifications-writer:**
- Product Requirements Documents (PRDs)
- Technical specifications
- User stories and acceptance criteria
- Implementation plans
- Business requirements translation

**Preserves from technical-writer:**
- Technical documentation
- User guides and tutorials
- Architecture documentation
- API documentation coordination
- Developer documentation

**New unified capabilities:**
- End-to-end product documentation
- Unified project and documentation management
- Single source of truth for requirements and specs

## Migration Guide

### For Users
1. **When you previously used:** `brainstormer` or `solutions-architect`
   **Now use:** `architect`

2. **When you previously used:** Any UI framework agent (`web-developer`, `flutter-developer`, etc.)
   **Now use:** `frontend-developer` (specify the framework in your request)

3. **When you previously used:** Any API agent (`api-designer`, `api-implementer`, `api-documenter`)
   **Now use:** `api-specialist` (specify the aspect: design, implementation, or documentation)

4. **When you previously used:** Any test agent (`test-architect`, `test-implementer`, `code-reviewer`)
   **Now use:** `test-engineer` (handles all testing aspects)

5. **When you previously used:** Any data agent (`database-specialist`, `data-architect`, `ontology-specialist`)
   **Now use:** `data-engineer` (covers all data aspects)

### Key Improvements
- **Fewer decisions**: Choose from 9 agents instead of 23
- **Complete expertise**: Each agent handles the full lifecycle of their domain
- **Better collaboration**: Agents have clearer boundaries and interfaces
- **Maintained quality**: All specialized knowledge is preserved in consolidated agents

## Compatibility Notes

### Breaking Changes
- Individual framework agents no longer exist separately
- API lifecycle is now handled by a single agent
- Testing and code review are unified

### Backward Compatibility
- Agent expertise and capabilities are fully preserved
- Quality of responses should improve due to integrated knowledge
- Collaboration patterns remain similar but simplified

## Rollback Plan
If consolidation causes issues:
1. Original agent files are preserved in `/agents/deprecated/`
2. Can quickly restore previous 23-agent structure
3. User feedback will guide any necessary adjustments