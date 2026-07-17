# Marcio Krefta

**I build autonomous AI systems that replace manual business workflows.**

Not another full-stack developer who "also does AI." I architect multi-agent systems, cognitive automation pipelines, and production-grade LLM integrations that run unsupervised. My work sits at the intersection of distributed systems engineering and applied AI reasoning.

## What I'm known for

→ **Multi-Agent Orchestration**: Designing systems where multiple LLM agents collaborate, self-correct, and produce reliable outputs without human-in-the-loop.

→ **Production AI Automation**: Turning chaotic business processes into deterministic AI pipelines (WhatsApp automation, lead qualification, reservation engines) that handle edge cases at scale.

→ **Full-Stack AI Products**: End-to-end SaaS products where the AI isn't a feature — it's the architecture.

## Featured Work

### [`multi-agent-orchestrator`](https://github.com/kreftamarcio/multi-agent-orchestrator) 🧠
> A TypeScript framework for orchestrating cooperative LLM agents with fault tolerance, retry logic, and observable state machines.
>
> **Stack**: TypeScript · Node.js · Groq/OpenAI · Redis · Event-driven architecture
>
> **Why it matters**: Most multi-agent frameworks fail silently. This one implements circuit breakers, agent health monitoring, and structured output validation.

### [`botzap`](https://github.com/kreftamarcio/botzap) 🤖
> Production WhatsApp AI agent handling 1000+ conversations/day with context-aware responses, intent routing, and business logic execution.
>
> **Stack**: Node.js · whatsapp-web.js · Groq LLM · Railway
>
> **Architecture**: Intent classifier → Context retriever → Response generator → Action executor (with fallback chains)

### [`reservas`](https://github.com/kreftamarcio/reservas) 📅
> Real-time reservation engine with pessimistic locking, conflict resolution, and multi-tenant isolation.
>
> **Stack**: TypeScript · Next.js 15 · Prisma · PostgreSQL · Docker
>
> **Engineering highlight**: `EXCLUDE USING GIST` constraints for temporal overlap prevention, connection pooling, and race condition handling.

### [`q1-digital`](https://github.com/kreftamarcio/q1-digital) ⚡
> AI-native digital agency platform with embedded cognitive agents for client interaction and project scoping.
>
> **Stack**: TypeScript · Next.js · Tailwind · Vercel Edge Functions

## Technical Philosophy

```text
1. AI systems must fail gracefully, not silently.
2. If it can't run unsupervised for 30 days, it's not production-ready.
3. Type safety isn't optional when LLMs produce unpredictable outputs.
4. Documentation is architecture. If you can't explain the trade-offs, you didn't make them consciously.
```

## Stack

**Languages**: TypeScript (primary), Python, JavaScript 
**AI/LLM**: Groq, OpenAI, LangChain, Multi-agent patterns, Prompt Engineering 
**Backend**: Node.js, Next.js, Prisma, PostgreSQL, Redis, Docker 
**Infrastructure**: Railway, Vercel, AWS (RDS, Lambda), Supabase 
**Practices**: Event-driven architecture, Circuit breakers, Observability, CI/CD

## Current Focus

Building open-source tooling for **reliable multi-agent systems** — specifically around agent health monitoring, structured output validation, and cooperative task decomposition.

## Contact

**Location**: Florianópolis, SC, Brazil 
**GitHub**: [github.com/kreftamarcio](https://github.com/kreftamarcio) 
**Agency**: [Q1 Digital](https://github.com/kreftamarcio/q1-digital) — AI-first digital products
