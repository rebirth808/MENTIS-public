# Open-source Release Plan

The full MENTIS implementation is currently private.

This is intentional.

Before public release, the project needs a cleanup and safety review so that no private data, secrets, local logs, personal memory, or unstable automation behavior is exposed.

## Release requirements

Before source code is published, the following must be checked:

- no `.env` files
- no API keys or tokens
- no local machine paths that reveal private context unnecessarily
- no private logs
- no personal memory dumps
- no unpublished third-party code
- no generated artifacts that do not belong in source control
- no unsafe default automation
- no destructive command execution without confirmation
- no misleading claims about capabilities
- clear license
- clear contribution policy
- reproducible setup instructions

## Planned release stages

### Stage 1 — Documentation-only public repository

This repository.

Purpose:

- explain the project
- create a public project anchor
- collect early feedback
- prepare for grants/programs
- document safety boundaries

### Stage 2 — Minimal safe skeleton

A small public implementation with:

- CLI shell
- mock provider
- settings structure
- basic tests
- no real secrets
- no private integrations

### Stage 3 — Provider and routing layer

Public model broker and routing logic.

### Stage 4 — Codex/OpenAI workflow examples

Public examples showing useful developer workflows.

### Stage 5 — Agent orchestration and security gateway

Release of reviewed modules for multi-step workflows, command safety, and human-in-the-loop execution.

## Current public statement

MENTIS is not yet a complete open-source code release.

This repository is a public overview and release-preparation repository.
