# Contributing to Awesome Harness Engineering

Thank you for contributing! This list aims to be the most comprehensive and information-dense resource collection for harness engineering.

## What belongs here

Resources that directly address one or more of these harness engineering primitives:

- **Context engineering** — managing what goes into the context window
- **Constraints & guardrails** — keeping agents safe and controlled
- **Evaluation** — measuring whether agents actually work
- **Observability** — tracing, monitoring, and debugging agent behavior
- **State & memory** — persisting knowledge across sessions and context windows
- **Orchestration** — coordinating single or multi-agent systems
- **Runtime infrastructure** — sandboxing, execution, and durability
- **Agent instruction standards** — CLAUDE.md, AGENTS.md, specs, etc.

## What does NOT belong here

- Generic AI/LLM news or commentary
- Model announcements without harness relevance
- Prompt engineering guides (unless they bridge into context/harness engineering)
- Marketing pages without technical depth

## Entry format

### For articles and blog posts

```markdown
| ![Source](https://img.shields.io/badge/Source-Color?style=flat) | [Title](URL) | One-line description that explains the key insight or contribution |
```

### For tools and projects

```markdown
| [Project Name](URL) | One-line description of what it does and why it's relevant to harness engineering |
```

### For academic papers

```markdown
| [Paper Title](URL) | Venue/Date | Key contribution in one line |
```

## Quality bar

Before submitting, ask:

1. **Is this a primary source?** Prefer original articles over summaries or commentary.
2. **Is this specific?** Does it say something concrete about harness design?
3. **Is this actionable?** Could a practitioner use this to improve their harness?
4. **Is this current?** Published in 2024 or later, or a timeless reference?

## How to submit

1. Fork this repository
2. Add your entry in the appropriate section
3. Ensure the entry follows the format above
4. Submit a pull request with a clear description of what you're adding and why

## Deduplication

If two links cover the same ground, we keep the more primary, practical, and implementation-oriented one. If you think a new resource supersedes an existing one, note that in your PR description.
