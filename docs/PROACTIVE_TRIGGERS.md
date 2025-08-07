# Proactive Agent Triggers

This document lists all the "ALWAYS use this agent when..." triggers for automatic agent invocation in Claude Code.

## Backend & Architecture Agents

### brainstormer
**ALWAYS use when:** starting any new feature or facing complex problems that need creative solutions.

### solutions-architect  
**ALWAYS use when:** before implementing major features or system changes.

### specifications-writer
**ALWAYS use when:** needed for creating PRDs or technical specifications.

### elixir-developer
**ALWAYS use when:** implementing Elixir/Phoenix code.

### database-specialist
**ALWAYS use when:** designing database schemas or optimizing queries.

### data-architect
**ALWAYS use when:** designing data models or ETL pipelines.

### ontology-specialist
**ALWAYS use when:** working with RDF, SPARQL, or knowledge graphs.

### devops-engineer
**ALWAYS use when:** setting up deployment, CI/CD, or infrastructure.

## UI/UX Development Agents

### ux-designer
**ALWAYS use when:** before implementing any UI components or user-facing features.

### web-developer
**ALWAYS use when:** implementing Phoenix LiveView or HTML/JS/CSS code.

### sveltekit-developer
**ALWAYS use when:** implementing SvelteKit applications.

### flutter-developer
**ALWAYS use when:** implementing Flutter mobile or web apps.

### reactnative-developer
**ALWAYS use when:** implementing React Native mobile apps.

## Testing & Quality Agents

### test-architect
**ALWAYS use when:** implementing new features to ensure proper test coverage from the start.

### test-implementer
**ALWAYS use when:** after test-architect creates test plans.

### code-fixer
**ALWAYS use when:** after writing code to ensure quality standards are met.

## API Development Agents

### api-designer
**ALWAYS use when:** before implementing any new API endpoints.

### api-implementer
**ALWAYS use when:** building Phoenix API endpoints.

### api-documenter
**ALWAYS use when:** immediately after implementing or modifying API endpoints.

## Documentation Agents

### technical-writer
**ALWAYS use when:** creating user-facing documentation or API docs.

## Operations & Management Agents

### security-specialist
**ALWAYS use when:** implementing authentication, handling sensitive data, or designing public APIs.

### performance-optimizer
**ALWAYS use when:** working with database queries, implementing caching, or dealing with high-traffic features.

### project-coordinator
**ALWAYS use when:** planning sprints or coordinating team activities.

## Key Patterns

1. **Feature Development Flow:**
   - brainstormer → solutions-architect → specifications-writer → implementation agents

2. **API Development Flow:**
   - api-designer → api-implementer → api-documenter

3. **Testing Flow:**
   - test-architect → test-implementer → code-fixer

4. **UI Development Flow:**
   - ux-designer → platform-specific developer agents

5. **Quality Assurance:**
   - code-fixer (after any code changes)
   - security-specialist (for auth/security features)
   - performance-optimizer (for data-heavy features)