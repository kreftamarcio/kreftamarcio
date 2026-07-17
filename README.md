# Marcio Krefta

**I build autonomous AI systems that replace manual business workflows.**

Not another full-stack developer who "also does AI." I architect multi-agent systems, prompt engineering infrastructure, and production-grade LLM integrations that run unsupervised. My work sits at the intersection of distributed systems engineering and applied AI reasoning.

## What I'm known for

→ **Multi-Agent Orchestration**: Designing systems where multiple LLM agents collaborate, self-correct, and produce reliable outputs without human-in-the-loop.

→ **Prompt Engineering as a Discipline**: Building tooling that treats prompts as first-class engineering artifacts: versioned, tested, regression-detected, and optimized systematically.

→ **Production AI Automation**: Turning chaotic business processes into deterministic AI pipelines that handle edge cases at scale.

## Featured Work

### [`multi-agent-orchestrator`](https://github.com/kreftamarcio/multi-agent-orchestrator) 🧠
> TypeScript framework for orchestrating cooperative LLM agents with fault tolerance, circuit breakers, and observable state machines.
>
> **Highlights**: 4 execution strategies (sequential, parallel, DAG, consensus) · 3 provider adapters · Circuit breakers · Zod schema validation · Full observability (traces, metrics, events)
>
> **Stack**: TypeScript · Node.js · Groq/OpenAI/Anthropic · Redis · Vitest

### [`prompt-forge`](https://github.com/kreftamarcio/prompt-forge) 🔥
> Systematic prompt engineering toolkit. Version prompts like code, evaluate with statistical rigor, detect regressions before they reach users.
>
> **Highlights**: Prompt versioning · Evaluation pipelines with assertions · Regression detection · Technique library (CoT, Few-Shot, Self-Consistency) · A/B testing
>
> **Stack**: TypeScript · Zod · Statistical analysis

### [`botzap`](https://github.com/kreftamarcio/botzap) 🤖
> Production WhatsApp AI agent handling conversations 24/7 with multi-modal input (text, audio, images), conversation memory, and autonomous escalation.
>
> **Architecture**: Hybrid routing (keyword flows + LLM) · Whisper transcription · TTS · Silence manager for human handoff
>
> **Stack**: Node.js · whatsapp-web.js · Groq LLM · Railway

### [`reservas`](https://github.com/kreftamarcio/reservas) 📅
> Real-time reservation engine with database-level double-booking prevention using PostgreSQL EXCLUDE USING GIST constraints.
>
> **Engineering highlight**: TOCTOU race condition solved at storage layer · Dual caching strategy · Prisma + strict TypeScript
>
> **Stack**: TypeScript · Next.js 16 · PostgreSQL · Docker

## Technical Philosophy

```text
1. AI systems must fail gracefully, not silently.
2. Prompts are engineering artifacts. Version them. Test them. Measure them.
3. If it can't run unsupervised for 30 days, it's not production-ready.
4. Type safety isn't optional when LLMs produce unpredictable outputs.
5. Documentation is architecture. Trade-offs > descriptions.
```

## Stack

**Languages**: TypeScript (primary), Python, JavaScript
**AI/LLM**: Groq, OpenAI, Anthropic, Multi-agent patterns, Prompt Engineering
**Backend**: Node.js, Next.js, Prisma, PostgreSQL, Redis, Docker
**Infrastructure**: Railway, Vercel, AWS (RDS, Lambda), Supabase
**Practices**: Event-driven architecture, Circuit breakers, Observability, CI/CD

## Current Focus

Building open-source tooling for **reliable AI systems**: multi-agent orchestration, prompt evaluation pipelines, and production observability for LLM applications.

## Contact

**Location**: Florianópolis, SC, Brazil
**GitHub**: [github.com/kreftamarcio](https://github.com/kreftamarcio)
**Agency**: [Q1 Digital](https://github.com/kreftamarcio/q1-digital) — AI-first digital products
