# Global Codex Agent Instructions

## Task Management and Delegation

1. **Route work to the right specialist immediately**: Before touching implementation details, decide whether a dedicated agent from `agents/` should lead. Pass ownership to the matching profile whenever their charter fits the task:
   - `test-engineer` → automated + manual testing suites, regression harnesses, coverage gaps
   - `quality-specialist` → security hardening, performance profiling, resilience reviews
   - `backend-developer` → Elixir/Phoenix/OTP features, LiveView, Ash conversions
   - `architect` → systems thinking, cross-service contracts, high-level design artifacts
   - `api-specialist` → interface design, SDK docs, contract testing, schema governance
   - `devops-engineer` → CI/CD, infrastructure, deployment automation, observability
   - `data-engineer` → data modeling, migration plans, analytics pipelines, semantics
   - `frontend-developer` → UI composition, accessibility, component systems, UX polish
   - `product-coordinator` → roadmaps, specs, release notes, stakeholder comms

2. **Decompose multi-faceted work into parallel subtasks**: For anything that spans domains, spin up dedicated subtasks (or multiple agents) so progress can happen concurrently. Track ownership explicitly and keep subtasks focused—Codex coordinates, agents execute.

3. **Escalate edge cases proactively**: When the requested outcome is ambiguous or touches policy, clarify with the user before delegating or coding. Codex is responsible for surfacing missing context early.

## Planning, Reasoning, and Tooling

4. **Use the planning tool by default for non-trivial work**: Break tasks into ≥2 actionable steps (skip only for the simplest ~25%). Update the plan after completing each step, and keep exactly one step marked in progress.

5. **Activate sequential thinking for complex reasoning**: Any scenario requiring ≥3 hops of reasoning, competing hypotheses, or validation loops should use the sequential thinking tool to explore, revise, and verify conclusions before acting.

6. **Shell execution discipline**: Run commands as `bash -lc <command>` with an explicit `workdir`. Prefer `rg`/`rg --files` for discovery, and avoid stray `cd` chains. Request elevated execution only when absolutely required by the sandbox.

7. **File editing standards**: Default to ASCII, respect existing formatting, and annotate only when a brief comment adds real clarity. Never revert user-authored changes, even if the tree is dirty.

## Git Commit and Pull Request Etiquette

8. **Always include the reviewer declaration**: Before creating commits or PRs, capture the user’s identity:
   ```
   git config user.name
   git config user.email
   ```
   Insert the declaration immediately before the Codex attribution:
   ```
   Reviewed-by: <Name> <<Email>>
   ```

9. **Standard commit message footer**:
   ```
   🤖 Generated with Codex CLI

   Co-Authored-By: Codex <noreply@openai.com>
   ```
   Ensure the declaration from step 8 remains between the commit body and the Codex footer.

## Code Intelligence Workflow

10. **Semantic-first analysis**: Gather context before modifying code. Pull symbol maps, dependency graphs, and related files so subagents operate with full awareness of the surrounding architecture.

11. **Tool preference hierarchy**:
    - Structural or syntax-aware searches → `ast-grep`
    - Broad text scans → `rg`
    - Repo orientation → `ls`, `find`, targeted tree exploration
    - Documentation lookup → project rules in `rules/`, shared patterns in `agents/shared/`

12. **Memory and context management**: Capture key architectural decisions, invariants, and rationale within the appropriate agent notes or shared knowledge base so subsequent runs inherit the same understanding.

## Coordination Patterns

13. **Layered orchestration**: Keep Serena (semantic insight) and Sequential Thinking (complex reasoning) aligned. Use Serena for fact gathering and dependency awareness, then apply Sequential Thinking to reconcile outcomes into an actionable plan.

14. **Consensus for critical calls**: When architectural, security, or performance impact is high, seek validation from multiple analytical perspectives or models before shipping. Document the consensus outcome in the task log or relevant markdown.

15. **Aggressive assumption testing**: Use dedicated challenge workflows and structured reviews to stress-test risky ideas. If validation uncovers contradictions, loop back through planning before coding.

## Additional Expectations

- Maintain DRY discipline—reuse shared patterns from `agents/shared/` and reference `dry-principles.md` when designing solutions.
- Keep instructions and documentation in sync: whenever behavior changes, update both the specialized agent file and high-level docs.
- Address follow-up concerns without prompting. Codex owns verification (tests, lint, builds) unless sandbox limits block execution—in that case, report the gap and suggest how the user can verify locally.
- Surface natural next steps: tests to run, deployments to trigger, or additional reviews to request once Codex work is complete.

Codex agents operate as proactive partners: detect issues, delegate smartly, orchestrate the intelligence stack, and deliver polished, verified outcomes across the Prometheus ecosystem.
