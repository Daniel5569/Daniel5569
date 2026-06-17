# Daniel — AI Infrastructure Engineer

Full-stack engineer building **production-shaped AI infrastructure**: async agent systems, human-in-the-loop workflows, compliance ops, and AI-native back-office tooling.

Every project here is a public proof of work — small enough to inspect end-to-end, but built with the same control-plane boundaries used in production AI companies.

---

## Portfolio

### 1. Stateful Agentic Sandbox Orchestrator
[![CI](https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator/actions/workflows/ci.yml/badge.svg)](https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator/actions/workflows/ci.yml)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Async control plane for terminal-use and code-executing agents. Gateway → Redis Streams → Python FastAPI engine → PostgreSQL. Includes delta workspace hydration, policy admission, dead-letter handling, and CI with real Postgres/Redis containers.

**Stack:** Node.js · Next.js · TypeScript · Python · FastAPI · Redis Streams · PostgreSQL · Docker  
[→ Repository](https://github.com/Daniel5569/stateful-agentic-sandbox-orchestrator)

---

### 2. Multichannel Document Intelligence Platform
[![CI](https://github.com/Daniel5569/multichannel-document-intelligence-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/Daniel5569/multichannel-document-intelligence-platform/actions/workflows/ci.yml)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Async document ingestion for contracts, claims, and invoices. Typed extraction evidence, 3NF PostgreSQL model, XCLAIM-based dead-letter recovery, and human validation events — no flat JSON blobs.

**Stack:** Node.js · Next.js · TypeScript · Python · FastAPI · Redis Streams · PostgreSQL · Docker  
[→ Repository](https://github.com/Daniel5569/multichannel-document-intelligence-platform)

---

### 3. CRM Revenue Ops Agent Workflow
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Policy-gated CRM automation: SHA-256 content-addressed idempotency, three-tier action classification (auto_safe / requires_approval / blocked), and an immutable pre-response audit log. 12 passing tests.

**Stack:** Next.js · TypeScript · Python · PostgreSQL · Redis  
[→ Repository](https://github.com/Daniel5569/revenue-ops-agent-workflow) · [→ Live Demo](https://revenue-ops-agent-workflow-web.vercel.app)

---

### 4. LLM Evaluation & Observability Platform
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Release-gate dashboard for prompt quality: pass rates, regression detection, severity classification, latency, cost, human review queue, and deployment recommendations — all as pure functions with Vitest coverage.

**Stack:** Next.js 15 · React 19 · TypeScript · Tailwind CSS · Vitest  
[→ Repository](https://github.com/Daniel5569/llm-evaluation-observability-platform) · [→ Live Demo](https://llm-evaluation-observability-platfo.vercel.app)

---

### 5. Security Compliance Evidence Automation (EvidenceOps)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

SOC 2 / ISO 27001 / customer review ops console: reviewer workflow, gap analysis, hash-chained tamper-evident audit trail, and package builder. Designed for compliance teams managing multiple frameworks simultaneously.

**Stack:** Next.js 15 · TypeScript · Drizzle ORM · PostgreSQL  
[→ Repository](https://github.com/Daniel5569/security-compliance-evidence-automation) · [→ Live Demo](https://security-compliance-evidence-automa.vercel.app)

---

### 6. Ops Workflow Automation Platform
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Centralized queue for vendor approvals, customer escalations, and invoice exceptions. AI recommendations, human review gate, Zod-validated API, and PostgreSQL audit log. Gateway → Redis Streams → Python FastAPI worker.

**Stack:** Next.js 15 · TypeScript · Prisma · Python · FastAPI · Redis Streams · PostgreSQL  
[→ Repository](https://github.com/Daniel5569/ops-workflow-automation-platform) · [→ Live Demo](https://ops-workflow-automation-platform.vercel.app)

---

### 7. Support Knowledge Agent Control Plane
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Governed AI support agent for B2B SaaS: deterministic retrieval (unit-assertable ranking), composable risk detection, JSON Schema cross-boundary contracts, and explicit action blocking for refunds and cancellations.

**Stack:** Next.js 15 · TypeScript · Python 3.12 · FastAPI  
[→ Repository](https://github.com/Daniel5569/support-knowledge-agent-control-plane)

---

### 8. Text-to-SQL Proactive Data Analyst Engine
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Safe text-to-SQL with semantic governance: business language → governed metrics → parser-validated SQL → read-only sandbox → chart generation. Rejects writes, unsafe tables, and malformed queries at the Python layer.

**Stack:** Next.js · TypeScript · Python · FastAPI · PostgreSQL · Redis Streams · Docker  
[→ Repository](https://github.com/Daniel5569/text-to-sql-proactive-data-analyst-engine)

---

### 9. AI Collections & Back-office Automation Console
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

Collections workflow automation: overdue account queue, risk scoring, AI-generated action proposals, human approval gate, dispute guardrails, and audit trail. Built for founder-led fintech and B2B SaaS teams.

**Stack:** Next.js 15 · TypeScript · React 19  
[→ Repository](https://github.com/Daniel5569/ai-collections-console)

---

## What runs through all of this

- **Async-first:** gateways return `202 Accepted`; Python workers consume from Redis Streams
- **Audit-first:** every decision is persisted before the response returns
- **Human-in-the-loop:** approval gates before any destructive or external action
- **CI-tested:** integration tests with real Postgres and Redis service containers
- **Inspectable:** small enough to read end-to-end in a technical review

---

## Stack across the portfolio

| Layer | Technologies |
|---|---|
| Frontend / Gateway | Next.js 15, React 19, TypeScript, Tailwind CSS |
| API validation | Zod, Prisma, Drizzle ORM |
| Async queue | Redis Streams (XREADGROUP + XCLAIM dead-letter) |
| Worker runtime | Python 3.12, FastAPI |
| Database | PostgreSQL (3NF models, audit events) |
| Infrastructure | Docker Compose, GitHub Actions CI |
| Testing | Vitest, Pytest, Ruff, Black |

---

## Contact

Open to roles and contracts in AI infrastructure, agentic backend systems, and production AI tooling.

Email: simbalanani@gmail.com · GitHub: [Daniel5569](https://github.com/Daniel5569)
