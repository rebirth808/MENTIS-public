# MENTIS

**Modular Executive Neural Tooling Intelligence System**

MENTIS is a local-first AI orchestration and developer tooling project focused on coordinating AI models, coding agents, project memory, command workflows, safety checks, and terminal-based execution.

This repository is the **public project overview** for MENTIS.

The full working repository is currently private while it is being cleaned, audited, and prepared for a staged open-source release. This public repository intentionally does **not** include private implementation code, local environment files, API keys, logs, personal memory, experimental artifacts, or unreleased internal tooling.

## What MENTIS aims to become

MENTIS is designed as a transparent control layer for AI-assisted development.

Instead of relying on one opaque assistant, MENTIS aims to provide a structured workspace where builders can:

- route tasks to the right model or specialist agent
- coordinate coding, research, review, testing, and planning workflows
- manage project context and long-running development state
- keep humans in control of tool execution
- enforce safety policies before commands or file changes run
- build reliable terminal-first AI workflows
- compare local models and cloud models through one interface

## Current status

MENTIS is in early private development.

The current focus is on:

- terminal user experience
- model routing
- agent-role orchestration
- Codex/OpenAI workflow integration
- safe command execution
- project memory boundaries
- public documentation and open-source release planning

## Why this repository exists

This public repository provides a clean, non-sensitive overview of the project while the core implementation is prepared for release.

It exists to:

- explain the project publicly
- document the roadmap
- collect feedback
- prepare community contribution guidelines
- provide a stable link for programs, grants, and open-source review
- avoid exposing private or unsafe development artifacts too early

## Planned open-source release

The planned public release will happen in stages:

1. **Project overview and roadmap**  
   Public documentation, goals, architecture, contribution model, and safety policy.

2. **Minimal developer preview**  
   A small, auditable CLI/TUI skeleton with no private keys, no personal memory, and no hidden automation.

3. **Model routing layer**  
   Public implementation of provider abstraction, routing policies, and configurable model departments.

4. **Codex/OpenAI workflow integration**  
   Reproducible examples for using Codex/OpenAI models in developer workflows.

5. **Agent orchestration modules**  
   Specialist role coordination for coding, review, testing, research, and safety checks.

6. **Community-ready package**  
   Documentation, examples, tests, security policy, and contributor workflow.

## Non-goals

MENTIS is not intended to be:

- a malware framework
- an autonomous system that acts without user review
- a tool for credential theft, unauthorized access, or unsafe automation
- a black-box assistant that hides tool calls or model decisions
- a repository for private logs, secrets, or personal memory

## Project principles

- **Local-first where possible**
- **Human-in-the-loop by default**
- **Transparent model routing**
- **No secret leakage**
- **Safety gates before risky actions**
- **Useful terminal UX**
- **Practical developer workflows over hype**
- **Open-source release only after cleanup and audit**

## Repository scope

This repository currently contains documentation only.

The implementation is intentionally excluded until it can be released safely.

See:

- [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md)
- [`docs/ROADMAP.md`](docs/ROADMAP.md)
- [`docs/OPEN_SOURCE_RELEASE_PLAN.md`](docs/OPEN_SOURCE_RELEASE_PLAN.md)
- [`docs/API_CREDITS_USE.md`](docs/API_CREDITS_USE.md)
- [`SECURITY.md`](SECURITY.md)

## License

The documentation in this repository is released under the MIT License unless otherwise noted.

Future source-code licensing may be finalized before the first public implementation release.
