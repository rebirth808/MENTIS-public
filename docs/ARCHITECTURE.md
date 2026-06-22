# MENTIS Architecture Overview

MENTIS is planned as a modular AI orchestration layer for developer workflows.

This document describes the intended architecture at a high level. It does not contain private implementation details.

## Core layers

### 1. Terminal Interface

The terminal interface is intended to provide a premium command-line/TUI experience for builders.

Planned features:

- compact home screen
- dashboard view
- command palette
- settings wizards
- model/provider selectors
- status line
- task progress indicators
- safe command previews
- reduced-motion mode
- theme system

### 2. Intent Router

The intent router classifies user requests into task categories.

Example departments:

- global chat
- fast assistant
- coding
- reasoning
- critic/reviewer
- research
- security review
- test engineering
- integration/tools
- vision
- audio
- video
- embeddings
- reranking

The goal is to route work to the most appropriate model, tool, or specialist agent instead of treating every prompt as generic chat.

### 3. Model Broker

The model broker manages model/provider selection.

Planned provider types:

- local models
- OpenAI models
- Codex workflows
- hosted model APIs
- fallback providers

The broker should support:

- per-department model settings
- provider health checks
- fallback routing
- cost-aware routing
- latency-aware routing
- safety-aware routing

### 4. Agent Orchestrator

The orchestrator coordinates specialist roles.

Example role flow:

1. analyst
2. implementer
3. test engineer
4. critic
5. integrator

The orchestrator is intended to keep work structured, auditable, and reviewable.

### 5. Security Gateway

The security gateway checks proposed actions before execution.

Planned checks:

- command risk classification
- secret detection
- destructive command blocking
- network/tool policy checks
- file-scope boundaries
- human confirmation gates
- audit logging without leaking secrets

### 6. Project Memory Boundary

MENTIS should distinguish between:

- project facts
- session notes
- public documentation
- private user memory
- secrets
- temporary logs
- local-only configuration

Public releases must never include private memory, API keys, local environment files, or personal logs.

## Design goal

The architecture is built around a simple idea:

> AI tools should be powerful, but their decisions, routes, tool calls, and risks should remain visible and controllable.
