<div align="center">

# Marcio Krefta

### AI Infrastructure Engineer · Multi-Agent Systems · TypeScript Purist

*Building production-grade AI systems that don't hallucinate, don't crash, and don't lie about it.*

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com/)

</div>

---

## Who I Am

I design and build **multi-agent AI infrastructure** in TypeScript. Not wrappers around ChatGPT. Real systems: circuit breakers, DAG orchestration, schema-gated outputs, statistical evaluation pipelines, and RAG engines with honest retrieval semantics.

Every repo I ship has: strict types (zero `any`), tested CI, explicit failure modes, and documentation that explains *why*, not just *what*.

**Location:** Global (Remote)  
**Project:** [Q1 Digital](https://q1digital.com.br) · Global Pre-Seed AI Initiative · Multi-Agent Architectures & Enterprise Systems  
**Stack conviction:** TypeScript end-to-end. If it can't be typed, it can't be trusted.

---

## Featured Projects

### [`multi-agent-orchestrator`](https://github.com/kreftamarcio/multi-agent-orchestrator) ⭐

> Contract-first substrate for orchestrating cooperative LLM agents with fault tolerance.

| What it does | Why it matters |
|---|---|
| Sequential, parallel, DAG, and consensus execution strategies | One framework handles pipeline, fan-out, dependency graphs, and voting |
| Rolling-window circuit breaker | Prevents 429 storms against rate-limited providers |
| Zod schema gate with auto-repair | Untrusted model output never reaches application state |
| Multi-provider router with cost/latency/quality scoring | Automatic failover without vendor lock-in |
| MCP server + OpenTelemetry tracing | Observable from day one |

```bash
npm install multi-agent-orchestrator
```

---

### [`prompt-forge`](https://github.com/kreftamarcio/prompt-forge)

> Systematic prompt engineering with statistics-backed evaluation.

6 prompting techniques (CoT, ReAct, ToT, Constitutional, Self-Consistency, Few-Shot) · Wilson confidence intervals · Bayesian A/B testing via Monte Carlo · Regression detection · Zero hidden provider calls.

---

### [`rag-engine`](https://github.com/kreftamarcio/rag-engine)

> Production RAG: hybrid search, cross-encoder reranking, hallucination scoring.

Dense + sparse retrieval · Multi-strategy chunking · Query rewriting · Citation extraction · Grounding verification pipeline.

---

### [`eval-harness`](https://github.com/kreftamarcio/eval-harness)

> LLM evaluation that gates releases, not generates impressions.

Bootstrap percentile CIs (not t-tests) · Power analysis before paid inference · Paired comparison by case ID · Pareto cost-quality frontier with dominated configs eliminated.

---

<details>
<summary><strong>🔬 Infrastructure Modules (Private)</strong></summary>

| Module | Purpose |
|--------|--------|
| `hallucination-detector` | Claim extraction, source cross-referencing, entailment scoring |
| `context-window-optimizer` | Token budget management, priority truncation, cost-aware allocation |
| `agent-handoff` | Inter-agent context preservation, capability negotiation |
| `conversation-state-machine` | FSM for multi-turn dialogue, guard conditions, recovery |
| `distributed-queue` | Effectively-once processing, visibility timeout, deduplication |
| `saga-orchestrator` | Distributed saga pattern, compensation logic, partial failure recovery |
| `oauth-server` | Full OAuth 2.1 + OIDC: PKCE, DPoP, token exchange |
| `zero-trust-proxy` | Policy-as-code, continuous verification, microsegmentation |

*...and 160+ more TypeScript modules covering observability, data engineering, security, and ML ops.*

</details>

---

## Architecture Philosophy

```
┌─────────────────────────────────────────────────┐
│  CONTRACTS FIRST                                 │
│  Zod schemas define the boundary. Everything    │
│  else is implementation detail.                  │
├─────────────────────────────────────────────────┤
│  FAIL EXPLICITLY                                 │
│  Partial success > silent failure.              │
│  Every error has a code, a phase, and a cause.  │
├─────────────────────────────────────────────────┤
│  OBSERVE EVERYTHING                              │
│  If it's not in the trace, it didn't happen.    │
│  Structured spans, not console.log.             │
├─────────────────────────────────────────────────┤
│  ZERO ANY                                        │
│  strictTypeChecked ESLint. No escape hatches    │
│  in production code. Tests can be pragmatic.    │
└─────────────────────────────────────────────────┘
```

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kreftamarcio&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kreftamarcio&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

![Streak](https://github-readme-streak-stats.herokuapp.com?user=kreftamarcio&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=58a6ff&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)

</div>

---

<div align="center">

**Let's talk:** [kreftamarcio1@gmail.com](mailto:kreftamarcio1@gmail.com) · [q1digital.com.br](https://q1digital.com.br)

*Shipping AI infrastructure that earns trust through transparency, not marketing.*

</div>