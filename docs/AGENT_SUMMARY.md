# Prometheus Agents - Complete Agent Summary

## Overview
This document provides a comprehensive summary of all 23 specialized Claude SubAgents in the Prometheus Agents project, version 0.3.0.

## Agent Statistics
- **Total Agents**: 23
- **Categories**: 6
- **Opus-Recommended Agents**: 6
- **Color-Coded Groups**: Yes

## Agent Categories by Color

### 🔵 Backend & Architecture (Blue - #2196F3)
8 agents focused on system design, backend development, and infrastructure

### 🟢 UI/UX Development (Green - #4CAF50)
5 agents specialized in frontend development and user experience

### 🟣 Testing & Quality (Purple - #9C27B0)
3 agents dedicated to testing, quality assurance, and code analysis

### 🔷 API Development (Cyan - #00BCD4)
3 agents for API design, implementation, and documentation

### 🔘 Documentation (Blue-Grey - #607D8B)
1 agent for technical documentation

### 🟠 Operations & Management (Deep Orange - #FF5722)
3 agents for security, performance, and project management

## Complete Agent Listing

### Backend & Architecture Agents

| Agent | Description | Opus Recommended |
|-------|-------------|------------------|
| **brainstormer** | Creative ideation, technology exploration, innovative problem-solving | ✅ Yes |
| **architecture-solutions** | System design, architecture patterns, technical decision-making | ✅ Yes |
| **specifications-writer** | PRDs, technical specifications, implementation plans | No |
| **elixir-developer** | Phoenix framework, LiveView, Elixir best practices | No |
| **database-specialist** | PostgreSQL master, Ash/Ecto optimization, query tuning | ✅ Yes |
| **data-architecture** | Data schema design, database architecture, data flows | No |
| **ontology-specialist** | RDF, SPARQL, OWL, semantic web technologies | No |
| **devops-engineer** | AWS, Terraform, GitHub Actions, Copilot, CI/CD | No |

### UI/UX Development Agents

| Agent | Description | Opus Recommended |
|-------|-------------|------------------|
| **ux-designer** | Master UX/UI specialist, design systems, accessibility | No |
| **web-developer** | HTML, JavaScript, TailwindCSS, Phoenix LiveView | No |
| **sveltekit-developer** | SvelteKit, Svelte, reactive programming, SSR/SSG | No |
| **flutter-developer** | Flutter, Dart, cross-platform mobile/web apps | No |
| **reactnative-developer** | React Native, mobile development, Expo | No |

### Testing & Quality Agents

| Agent | Description | Opus Recommended |
|-------|-------------|------------------|
| **test-architect** | Test planning, strategy, test case design, TDD/BDD | ✅ Yes |
| **test-implementer** | Test implementation, automation, mocking | No |
| **code-reviewer** | Static analysis, linting, code quality metrics | No |

### API Development Agents

| Agent | Description | Opus Recommended |
|-------|-------------|------------------|
| **api-designer** | REST API design, OpenAPI specs, versioning | No |
| **api-implementer** | Phoenix API implementation, authentication | No |
| **api-documenter** | API documentation, examples, integration guides | No |

### Documentation Agent

| Agent | Description | Opus Recommended |
|-------|-------------|------------------|
| **documentation-technical** | Technical docs, architecture documentation, guides | No |

### Operations & Management Agents

| Agent | Description | Opus Recommended |
|-------|-------------|------------------|
| **security-specialist** | Application security, OWASP, penetration testing | ✅ Yes |
| **performance-optimizer** | Performance profiling, optimization, caching | ✅ Yes |
| **project-coordinator** | Agile management, sprint planning, coordination | No |

## Agent Collaboration Patterns

### Innovation & Design Flow
```
brainstormer → architecture-solutions → specifications-writer → implementation agents
```

### Full-Stack Development Flow
```
specifications-writer → elixir-developer + database-specialist → frontend agents → test agents
```

### API Development Flow
```
api-designer → api-implementer → api-documenter → test-implementer
```

### Quality Assurance Flow
```
test-architect → test-implementer + code-reviewer → performance-optimizer
```

### Security & Operations Flow
```
security-specialist + performance-optimizer → devops-engineer → project-coordinator
```

## When to Use Opus

Consider using the Opus model for these agents when dealing with:

1. **brainstormer**: Complex ideation sessions, exploring novel solutions
2. **architecture-solutions**: Large-scale system design, complex architectural decisions
3. **database-specialist**: Complex query optimization, performance tuning
4. **test-architect**: Comprehensive test strategy for large systems
5. **security-specialist**: Deep security analysis, threat modeling
6. **performance-optimizer**: Complex bottleneck analysis, system-wide optimization

## Technology Coverage

### Backend Technologies
- Elixir/Phoenix, OTP, LiveView
- PostgreSQL, Ecto, Ash Framework
- AWS, Terraform, Docker, Kubernetes
- GraphQL, REST APIs

### Frontend Technologies
- HTML5, CSS3, JavaScript/TypeScript
- TailwindCSS, Phoenix LiveView
- SvelteKit, Flutter, React Native
- Responsive design, PWA

### Testing Frameworks
- ExUnit (Elixir)
- Jest, Vitest, Cypress, Playwright (JavaScript)
- Flutter test framework
- React Native Testing Library

### DevOps & Infrastructure
- GitHub Actions, CI/CD pipelines
- AWS services (EC2, RDS, Lambda, etc.)
- Terraform, AWS Copilot
- Monitoring, logging, observability

### Security & Compliance
- OWASP Top 10
- GDPR, HIPAA, PCI DSS, SOC 2
- Authentication/Authorization patterns
- Encryption, key management

## Agent Selection Guide

### For Starting a New Project
1. Start with **brainstormer** for ideation
2. Move to **architecture-solutions** for system design
3. Use **specifications-writer** to document requirements
4. Engage **project-coordinator** for planning

### For Backend Development
1. **elixir-developer** for Phoenix applications
2. **database-specialist** for database design and optimization
3. **api-designer** → **api-implementer** for APIs
4. **devops-engineer** for deployment

### For Frontend Development
1. **ux-designer** for design specifications
2. Choose platform-specific agent:
   - **web-developer** for web applications
   - **sveltekit-developer** for SvelteKit
   - **flutter-developer** for mobile/web
   - **reactnative-developer** for React Native

### For Quality & Testing
1. **test-architect** for test strategy
2. **test-implementer** for test creation
3. **code-reviewer** for code review
4. **performance-optimizer** for optimization

### For Operations
1. **security-specialist** for security review
2. **performance-optimizer** for performance
3. **devops-engineer** for infrastructure
4. **project-coordinator** for management

## Version History

| Version | Date | Changes |
|---------|------|---------|
| **v0.1.0** | 2025-08-03 | Initial 17 agents |
| **v0.1.3** | 2025-08-03 | Documentation updates |
| **v0.2.0** | 2025-08-03 | Added 6 new agents (brainstormer, database-specialist, devops-engineer, security-specialist, performance-optimizer, project-coordinator), standardized colors, added Opus recommendations |
| **v0.3.0** | 2025-08-05 | Renamed agents to person actors (elixir-developer, ontology-specialist, ux-designer, web-developer), updated all descriptions to use "Use PROACTIVELY for:" for better automatic delegation |

## Future Considerations
The agent collection is now comprehensive, covering all major aspects of software development. Future updates may include:
- Specialized agents for emerging technologies
- Domain-specific agents (fintech, healthcare, etc.)
- Integration with external tools and services
- Enhanced collaboration protocols between agents