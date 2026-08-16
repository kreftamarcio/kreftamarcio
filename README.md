<div align="center">

# Hi there, I'm Marcio Krefta

### AI Engineer | TypeScript Developer | Open Source Enthusiast

[![GitHub followers](https://img.shields.io/github/followers/kreftamarcio?style=social)](https://github.com/kreftamarcio)

</div>

---

## About Me

- I'm currently working on **AI Agent Infrastructure** and **RAG Systems**
- I'm passionate about building intelligent systems that scale
- I love creating tools that make AI more accessible and reliable

## Contact

| | |
|---|---|
| **Business** | contato@q1digital.com.br |
| **Personal** | kreftamarcio1@gmail.com |
| **Location** | Florianópolis, Brazil |

---

## Tech Stack

| Category | Technologies |
|----------|-------------|
| **Languages** | TypeScript, JavaScript, Python |
| **AI/ML** | LLMs, RAG, Vector Search, Embeddings |
| **Backend** | Node.js, Express, Fastify |
| **Databases** | PostgreSQL, Redis, Pinecone, Weaviate |
| **DevOps** | Docker, GitHub Actions, AWS |
| **Tools** | Git, VS Code, Vitest, ESLint |

---

## Featured Projects

### [multi-agent-orchestrator](https://github.com/kreftamarcio/multi-agent-orchestrator)

Contract-first substrate for orchestrating cooperative LLM agents.

- Execution strategies: sequential, parallel, consensus (majority / supermajority / unanimous / weighted voting), DAG
- Reliability primitives: rolling-window circuit breaker, Zod schema gate, explicit failure policies (fail-fast / best-effort / require-all)
- Multi-provider router (feasibility filtering + normalized cost/latency/quality scoring) and per-inference cost attribution with context-growth analysis
- MCP (Model Context Protocol) server, structured tracing, eval CLI
- Strict TypeScript, unit-tested, CI gating on typecheck, tests, and coverage

### [prompt-forge](https://github.com/kreftamarcio/prompt-forge)

Prompt engineering toolkit with a statistics-backed evaluation core.

- 6 prompting techniques: chain-of-thought, constitutional, few-shot, ReAct, self-consistency, tree-of-thought
- Statistical toolkit: Wilson and normal confidence intervals, Cohen's d, two-sided z-scores, power analysis
- Bayesian A/B testing via Monte Carlo simulation
- Green CI on Node 20 and 22: typecheck, tests, build

### [eval-harness](https://github.com/kreftamarcio/eval-harness)

LLM evaluation that gates releases instead of producing impressions.

- Bootstrap percentile intervals rather than t-tests, because agent scores are bounded and frequently bimodal
- Judge calibration with Cohen's kappa, plus bias separated from noise so the remedy is identifiable
- Power analysis before any paid inference, including per-slice detection
- Pareto cost-quality frontier with dominated configurations eliminated

### [distributed-queue](https://github.com/kreftamarcio/distributed-queue)

Task queue with honest delivery semantics.

- Effectively-once processing, not "exactly-once delivery", which is impossible across an unreliable network
- Visibility timeout with bounded heartbeat extension, so a crashed consumer loses no messages and a stuck one cannot hold them forever
- Windowed deduplication with a bloom pre-filter and periodic rebuild
- Weighted lane scheduling with a starvation bound

### Early-stage projects

*Concept / scaffolding stage — implementations in progress, not production-ready.*

| Project | Direction |
|---------|-----------|
| [agent-runtime](https://github.com/kreftamarcio/agent-runtime) | Bounded agent loops with structural loop detection |
| [agent-memory](https://github.com/kreftamarcio/agent-memory) | Long-term memory for AI agents (episodic, semantic, procedural) |
| [agent-debugger](https://github.com/kreftamarcio/agent-debugger) | Step-through debugger for agent reasoning chains |
| [agent-handoff](https://github.com/kreftamarcio/agent-handoff) | Inter-agent handoff protocol with context preservation |
| [mcp-toolkit](https://github.com/kreftamarcio/mcp-toolkit) | MCP server framework: schema derivation, rate limiting, error sanitization |
| [rag-engine](https://github.com/kreftamarcio/rag-engine) | Hybrid retrieval, reranking, query rewriting, grounding checks |
| [guardrails-core](https://github.com/kreftamarcio/guardrails-core) | I/O validation, PII redaction with checksum verification, injection detection |
| [inference-gateway](https://github.com/kreftamarcio/inference-gateway) | Multi-provider routing with circuit breakers and stream normalization |
| [function-calling-engine](https://github.com/kreftamarcio/function-calling-engine) | Tool-use orchestration with DAG waves and idempotency-aware retry |
| [hybrid-search](https://github.com/kreftamarcio/hybrid-search) | Dense + sparse + keyword hybrid retrieval |
| [graph-rag](https://github.com/kreftamarcio/graph-rag) | Graph-enhanced RAG with entity relationships |
| [hallucination-detector](https://github.com/kreftamarcio/hallucination-detector) | Factual grounding verification for LLM outputs |

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kreftamarcio&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kreftamarcio&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Building the future of AI, one commit at a time*

</div>
