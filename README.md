<div align="center">

# Marcio Krefta

**Self-taught software and AI developer building reliability infrastructure in TypeScript.**

[TypeScript](https://www.typescriptlang.org/) · [Node.js](https://nodejs.org/) · [Q1 Digital](https://q1digital.com.br) · Florianópolis, Brazil

</div>

## What I build

My work focuses on the failure modes around agentic systems: orchestration, evidence, evaluation, memory, retrieval, cancellation, cost control, and safe tool execution.

I am not presenting myself as a formally credentialed engineer. The useful proof is in the repositories, tests, CI, design decisions, and documented limitations.

## Start with these

| Project | Why it exists |
|---|---|
| [multi-agent-orchestrator](https://github.com/kreftamarcio/multi-agent-orchestrator) | Sequential, parallel, DAG, and strict-quorum agent workflows |
| [q1-agent-stack](https://github.com/kreftamarcio/q1-agent-stack) | Versioned skills, agent roles, MCP setup, and verification workflow |
| [rag-engine](https://github.com/kreftamarcio/rag-engine) | Hybrid retrieval, citations, and contradiction-aware grounding |
| [eval-harness](https://github.com/kreftamarcio/eval-harness) | Bootstrap intervals, paired regressions, power, and Pareto analysis |
| [prompt-forge](https://github.com/kreftamarcio/prompt-forge) | Versioned prompts with provider-injected evaluation |
| [guardrails-core](https://github.com/kreftamarcio/guardrails-core) | PII, injection, schemas, topic boundaries, and audit integrity |
| [agent-runtime](https://github.com/kreftamarcio/agent-runtime) | Bounded loops, cancellation, permissions, and execution traces |
| [inference-gateway](https://github.com/kreftamarcio/inference-gateway) | Health, capability, cost, and latency-aware provider routing |

## How I work

```text
source -> contract -> implementation -> adversarial verification -> explicit status
```

- Strict TypeScript at system boundaries
- No hidden provider calls in evaluation libraries
- Partial failure represented explicitly
- Missing evidence remains missing
- Planned work labeled as roadmap, not shipped functionality

## Current status

Many repositories are active prototypes or work in progress. Read each README's status and verify its exported API, tests, and CI before adoption. I prefer an honest limitation over a polished fake guarantee.

## Contact

[Website](https://q1digital.com.br) · [Email](mailto:kreftamarcio1@gmail.com)

If a repository saves you time or gives you a useful idea, a star helps other developers find it.
