# Global Claude Code Instructions

## Task Management and Delegation

1. **Proactively use subagents wherever possible**: ALWAYS delegate tasks to specialized agents when they match their capabilities. Do not attempt complex tasks directly when a specialized agent is available. Immediately identify and use the appropriate agent for:
   - `test-engineer` for testing and quality assurance
   - `quality-specialist` for security and performance optimization
   - `backend-developer` for Elixir/Phoenix/OTP development
   - `architect` for system design and architectural decisions
   - `api-specialist` for API development and documentation
   - `devops-engineer` for infrastructure and deployment
   - `data-engineer` for database and data architecture
   - `frontend-developer` for UI/UX development
   - `product-coordinator` for project management and documentation

2. **Spin off multiple subagents or subtasks where possible**: When facing multi-faceted problems, break them down and run multiple subagents in parallel to maximize efficiency. Use the Task tool with different subagent_type parameters to handle different aspects of complex problems simultaneously.

## Git Commit and Pull Request Requirements

3. **Always add reviewer declaration in commits and PRs**: When creating git commits or pull requests, always include a review declaration. Before creating any commit or PR, retrieve the user's name and email using:
   ```
   git config user.name
   git config user.email
   ```
   
   Then include the following declaration in the commit message or PR description:
   ```
   Reviewed-by: [Name from git config] <[Email from git config]>
   ```

   This declaration confirms that the user has reviewed and accepted the code changes. Include this after the main commit message but before the Claude Code attribution.

Example commit message format:
```
feat: Add new feature description

Detailed explanation of changes...

Reviewed-by: [Retrieved Name] <[Retrieved Email]>

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude <noreply@anthropic.com>
```

## Code Search and Analysis Tools

4. **Use ast-grep for structural code searches**: When performing code analysis, searching for patterns, or understanding code structure, prefer `ast-grep` over text-based grep tools when appropriate. `ast-grep` understands syntax and provides more accurate results for:
   - Finding function/method definitions and calls
   - Searching for specific code patterns or structures
   - Language-aware refactoring operations
   - Complex structural queries that require understanding of code semantics
   
   Use `ast-grep` via the Bash tool for these structural searches, falling back to the Grep tool only for simple text-based searches or when language syntax understanding isn't needed.

## Additional Guidelines

- **MANDATORY**: Always check if a task matches any specialized agent before attempting it directly
- Proactively identify opportunities to delegate to specialized agents
- Consider parallel execution of independent tasks using multiple agents
- Always maintain code quality and follow project conventions
- Ensure all commits include proper attribution and review declaration
- Use ast-grep for structural code analysis when syntax understanding is beneficial
