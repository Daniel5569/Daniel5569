# Daniel5569

Full-Stack AI Infrastructure Engineer focused on asynchronous agent systems, distributed runtimes, and production-shaped AI tooling.

I build public proof-of-work projects that emphasize system boundaries, execution safety, queue-driven architecture, relational integrity, and testable operational behavior.

## Featured Case Study

### Stateful Agentic Sandbox Orchestrator

[![CI](https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator/actions/workflows/ci.yml/badge.svg)](https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator/actions/workflows/ci.yml)
[![Repository](https://img.shields.io/badge/repository-public-blue)](https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator)

An async Node.js + Python control plane for stateful agent sandbox execution.

Core architecture:

- Next.js / TypeScript API gateway for admission control and policy validation
- Python / FastAPI engine for sandbox execution, delta workspace hydration, and audit events
- Redis Streams for cross-runtime asynchronous job dispatch
- PostgreSQL for relational run state, policies, and execution evidence
- Docker Compose with internal service isolation
- GitHub Actions CI with Node, Python, PostgreSQL, and Redis checks

The project is designed as a technical case study for AI-native infrastructure teams building terminal-use agents, code-executing sandboxes, and long-running asynchronous workflows.

Repository:

https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator

## Current Portfolio Direction

- Agentic infrastructure and sandbox orchestration
- Async queue-based systems across Node.js and Python runtimes
- LLM-adjacent backend systems with verifiable execution and audit trails
- PostgreSQL-first data modeling and integrity constraints
- Dockerized developer environments and CI-tested workflows

