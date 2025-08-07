# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.1] - 2025-08-07

### Changed
- Renamed `code-fixer` to `code-reviewer` for better clarity of purpose
- Updated all documentation references

## [0.4.0] - 2025-08-07

### Changed
- Renamed agents for brevity and clarity:
  - `code-quality-analyzer.md` → `code-fixer.md`
  - `semantic-data-specialist.md` → `ontology-specialist.md`
- Enhanced all agents with "ALWAYS use this agent when..." directives for better proactive invocation
- Added specific proactive triggers to 15 key agents to ensure automatic usage in relevant contexts
- Updated all documentation to reflect new agent names

### Improved
- Agent proactivity: All agents now have clear triggers for when they should be automatically invoked
- Documentation consistency: All references updated across CLAUDE.md, README.md, and docs/

## [0.3.0] - 2025-08-05

### Changed
- Renamed agents to represent person actors for better clarity:
  - `elixir-phoenix.md` → `elixir-developer.md`
  - `semantic-data.md` → `semantic-data-specialist.md`
  - `ux-ui-design.md` → `ux-designer.md`
  - `web-frontend.md` → `web-developer.md`
  - Also previously renamed: `architecture-solutions.md` → `solutions-architect.md`, `data-architecture.md` → `data-architect.md`, `documentation-technical.md` → `technical-writer.md`
- Updated all agent descriptions to use "Use PROACTIVELY for:" instead of "Use for:" for better automatic delegation with Claude Code
- Updated all documentation to reflect new agent names

## [0.2.1] - 2025-08-03

### Changed
- Updated agent frontmatter format: replaced `model_recommendation` with `model` field for cleaner syntax
- Agents that recommend Opus model now use `model: opus` instead of verbose recommendation text
- Affected agents: brainstormer, architecture-solutions, database-specialist, performance-optimizer, security-specialist, test-architect

## [0.2.0] - Previous Release

### Added
- Added 6 new specialized agents
- Standardized documentation across all agents
- Improved agent collaboration patterns

## [0.1.3] - Previous Release

### Added
- MIT License
- Initial version updates

## [0.1.0] - Initial Release

### Added
- Initial release of Prometheus Agents
- 17 specialized Claude SubAgents
- Core documentation and structure