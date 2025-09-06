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

## Enhanced MCP Integration Guidelines

5. **Revolutionary Three-Layer Intelligence System**: All agents now operate using a sophisticated three-layer architecture for unprecedented code intelligence:

   **LAYER 1: SERENA SEMANTIC INTELLIGENCE**
   - Use Serena MCP for all code operations: `find_symbol`, `get_symbols_overview`, `search_for_pattern`, `find_referencing_symbols`
   - Maintain project memory with `write_memory`/`read_memory` for persistent knowledge
   - Extract precise code context before any analysis or modification
   - Map system dependencies and architectural relationships semantically

   **LAYER 2: ZEN AI-POWERED ANALYSIS (16 Sophisticated Tools)**
   - **Deep Analysis Suite**: `thinkdeep` (multi-stage investigation), `analyze` (comprehensive), `debug` (root cause), `refactor` (optimization)
   - **Collaborative Intelligence**: `consensus` (multi-model validation), `planner` (interactive planning), `chat` (thinking partner)
   - **Quality & Security**: `codereview` (systematic), `precommit` (validation), `secaudit` (OWASP), `testgen` (comprehensive)
   - **Code Intelligence**: `tracer` (execution flow), `docgen` (documentation)
   - **Advanced Reasoning**: `challenge` (critical thinking), `sequential-thinking` (complex decomposition)

   **LAYER 3: SEQUENTIAL THINKING COMPLEX REASONING**
   - Automatically activate for problems requiring ≥3 steps or complex decision trees
   - Use for multi-faceted analysis, hypothesis development, and systematic solution synthesis
   - Combine with Zen consensus for critical decision validation

6. **Sophisticated Intelligence Cascades**: Use systematic workflows that leverage all three layers:
   
   **Standard Intelligence Cascade:**
   ```
   Serena (semantic context) → Zen analysis (AI-powered) → Sequential Thinking (complex reasoning) → Zen consensus (multi-model validation) → Zen challenge (assumption testing)
   ```
   
   **Debugging Intelligence Cascade:**
   ```
   Serena (bug context mapping) → Zen thinkdeep (multi-hypothesis investigation) → Sequential Thinking (root cause analysis) → Zen consensus (solution validation) → Zen testgen (regression prevention)
   ```

7. **Advanced Model Selection with 28+ Models**: Use context-aware model orchestration:
   - **Deep Analysis**: `gemini-2.5-pro` (1M context, thinking mode) + `anthropic/claude-opus-4.1` + `openai/o3` consensus
   - **Security Analysis**: `anthropic/claude-opus-4.1` primary + `deepseek/deepseek-r1-0528` (thinking mode) + `openai/o3` validation
   - **Performance Optimization**: `openai/o3` primary + `gemini-2.5-flash` + `anthropic/claude-opus-4.1` validation
   - **Complex Reasoning**: `deepseek/deepseek-r1-0528` + `gemini-2.5-pro` for advanced reasoning scenarios

8. **Assumption Challenge Workflows**: Use Zen's `challenge` tool to systematically validate:
   - Architectural decisions and design assumptions
   - Implementation approaches and technical choices
   - Security strategies and threat assessments
   - Performance optimization strategies

9. **Multi-Model Consensus Validation**: For critical decisions, always use Zen's `consensus` tool with 2-3 specialized models to ensure thorough validation and prevent single-model bias.

## Additional Guidelines

- **MANDATORY**: Always check if a task matches any specialized agent before attempting it directly
- **PROACTIVE MCP ORCHESTRATION**: Automatically activate three-layer intelligence for complex problems (≥3 steps, architectural decisions, security concerns, performance issues)
- **SEMANTIC-FIRST APPROACH**: Always use Serena for code context before any analysis or modification
- **ASSUMPTION VALIDATION**: Use Zen challenge tool to test critical assumptions and prevent confirmation bias
- Consider parallel execution of independent tasks using multiple agents
- Always maintain code quality and follow project conventions
- Ensure all commits include proper attribution and review declaration
- Use ast-grep for structural code analysis when syntax understanding is beneficial
