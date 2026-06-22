# Codex Integration Goals

MENTIS is intended to work with Codex-style coding workflows.

## Goals

- make coding tasks structured and reviewable
- keep repository boundaries explicit
- separate planning, implementation, testing, and review
- avoid uncontrolled autonomous edits
- produce clear diffs and validation notes
- support human approval gates

## Planned workflow shape

1. Understand project state.
2. Define scope.
3. Draft plan.
4. Apply minimal patch.
5. Run tests or provide test instructions.
6. Review for regressions.
7. Summarize changes.
8. Ask for human approval before risky actions.

## Why this matters

AI coding tools are powerful, but they can become chaotic when they lack:

- file boundaries
- risk checks
- role separation
- test discipline
- transparent reasoning summaries
- safe execution policy

MENTIS aims to provide that structure around AI coding workflows.
