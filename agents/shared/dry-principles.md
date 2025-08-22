# DRY Principles for Code Execution

## Core DRY Directives for All Agents

### 1. Pattern Recognition & Reuse
**BEFORE GENERATING ANY CODE:**
- Search for existing patterns in the codebase using Grep/Find tools
- Identify reusable components, modules, or functions
- Check for similar implementations that can be extended
- Look for established conventions and follow them

### 2. Component Extraction Rules
**WHEN DETECTING DUPLICATION:**
```yaml
duplication_threshold: 2  # If pattern appears 2+ times
action_sequence:
  1. Extract to shared module/component
  2. Create abstraction with parameters
  3. Replace all instances with references
  4. Document the shared pattern
```

### 3. Code Generation Guidelines
**FOLLOW THIS HIERARCHY:**
1. **Reuse Existing** → Find and extend existing code
2. **Extract & Share** → Create reusable components
3. **Generate Once** → New code only when necessary
4. **Reference Always** → Import/include shared code

### 4. Refactoring Patterns
**DRY REFACTORING CHECKLIST:**
- [ ] Identify repeated code blocks
- [ ] Extract common functionality to functions
- [ ] Create shared configuration files
- [ ] Use composition over duplication
- [ ] Implement inheritance where appropriate
- [ ] Apply mixins/traits/behaviors patterns

### 5. Design Pattern Library
**REUSABLE PATTERNS TO APPLY:**
```elixir
# Backend Patterns
- Repository Pattern for data access
- Service Pattern for business logic
- Factory Pattern for object creation
- Strategy Pattern for algorithms
- Observer Pattern for events
```

```typescript
// Frontend Patterns
- Component Composition
- Custom Hooks (React/Vue)
- Store Modules (State Management)
- Utility Functions Library
- Design System Tokens
```

### 6. Shared Code Structure
```
project/
├── shared/
│   ├── components/     # Reusable UI components
│   ├── services/       # Shared business logic
│   ├── utils/          # Common utilities
│   ├── patterns/       # Design patterns
│   ├── configs/        # Shared configurations
│   └── types/          # Shared type definitions
```

### 7. DRY Execution Steps
**FOR EVERY CODE TASK:**
1. **ANALYZE** → Search for existing similar code
2. **IDENTIFY** → Find patterns to reuse
3. **EXTRACT** → Pull out common functionality
4. **ABSTRACT** → Create flexible interfaces
5. **IMPLEMENT** → Use references, not copies
6. **DOCUMENT** → Record the pattern for future use

### 8. Anti-Pattern Detection
**NEVER DO THIS:**
- Copy-paste code blocks
- Duplicate business logic
- Repeat configuration values
- Create similar components
- Write redundant tests
- Duplicate error handling

### 9. MCP Integration for DRY
**USE THESE MCP TOOLS:**
- **Serena**: Find similar code patterns
- **Memory**: Store reusable patterns
- **Zen**: Analyze for duplication
- **Context7**: Find library solutions
- **Sequential Thinking**: Break down complex refactoring
- **MCP Orchestration**: Follow automated workflows (see ./mcp-orchestration.md)

### 10. Validation Checklist
**BEFORE SUBMITTING CODE:**
- [ ] No duplicated functions
- [ ] All constants extracted
- [ ] Shared utilities created
- [ ] Patterns documented
- [ ] Imports optimized
- [ ] Zero copy-paste code