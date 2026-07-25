# Marcio Krefta

```
🚀 Building AI-native tooling — from problem to deploy.
   Focus: Loop Engineering · Multi-Agent Systems · Prompt Infrastructure
```

**I design self-correcting AI systems that improve themselves without human intervention.**

Most AI engineers build pipelines that run once. I build **loops**: systems that evaluate their own output, detect degradation, retry with alternative strategies, and converge on correct answers autonomously. This is Loop Engineering: the discipline of making AI systems that get better every iteration without touching the code.

## What I build

I work on AI-native tooling under the **Q1 Digital** name — an early-stage, pre-launch initiative exploring how self-correcting agents can handle business workflows with high consistency.

**Focus areas:**
- Conversational agents for lead qualification and booking
- B2B intelligence tooling with multi-source lead enrichment
- Multi-agent orchestration frameworks for complex business workflows
- Prompt evaluation infrastructure for production LLM reliability

## The Loop Engineering Paradigm

```
┌─────────────────────────────────────────────────┐
│              THE CONVERGENCE LOOP                    │
│                                                     │
│   Execute ──▶ Evaluate ──▶ Detect Failure            │
│      ▲                           │                    │
│      │                           ▼                    │
│   Improve ◀── Adapt Strategy ◀── Classify Root Cause  │
│                                                     │
│   Exit condition: quality threshold met              │
│   Safety: max iterations + circuit breaker           │
└─────────────────────────────────────────────────┘
```

Traditional AI: `input → model → output` (hope for the best)
Loop Engineering: `input → model → evaluate → not good enough? → retry with adaptation → converge`

## Where I apply this

→ **Multi-Agent Orchestration**: Agents that detect their own failures, trip circuit breakers, and route to fallback strategies automatically.

→ **Prompt Evaluation Loops**: Prompts that are continuously tested, regression-detected, and auto-optimized through evaluation pipelines.

→ **Self-Healing Systems**: Conversational bots that reconnect, re-authenticate, filter stale messages, and maintain state across crashes.

→ **B2B Data Pipelines**: Multi-source ingestion with quality scoring gates that prevent bad data from entering the system.

## Proof of Work

### [`multi-agent-orchestrator`](https://github.com/kreftamarcio/multi-agent-orchestrator) 🧠
> Framework where agents self-correct through convergence loops.
>
> Circuit breakers detect failures → Retry with backoff → Fallback to alternative provider → Validate output against schema → Only then pass downstream.
>
> TypeScript · 4 execution strategies · 3 LLM providers · Full observability

### [`prompt-forge`](https://github.com/kreftamarcio/prompt-forge) 🔥
> The evaluation loop for prompts: version → test → detect regression → optimize → redeploy.
>
> Bayesian A/B testing · Self-Consistency (multi-path voting) · Statistical significance (Wilson intervals, Cohen's d) · Token compression with quality preservation
>
> TypeScript · 5 techniques · Research-backed methodology · Power analysis

> 🔒 Additional projects (conversational agents, B2B intelligence tooling, and a
> concurrency-safe reservation system built on PostgreSQL `EXCLUDE USING GIST`) are
> currently in private repositories. Happy to walk through them on request.

## What makes Loop Engineering different

| Traditional AI Engineering | Loop Engineering |
|---|---|
| Build pipeline, deploy, pray | Build loop, define exit criteria, guarantee convergence |
| Failures are bugs to fix | Failures are expected states the system handles |
| Quality checked by humans | Quality enforced by automated evaluation gates |
| One model, one attempt | Multiple strategies, adaptive selection |

## Technical Philosophy

```text
1. Every AI output must pass through an evaluation gate before reaching users.
2. Systems that can't self-correct aren't production-ready.
3. Convergence > single-shot accuracy. A system that retries intelligently
   beats a system that's 5% more accurate on the first try.
4. Prompts are code. They get versioned, tested, and regression-detected.
5. If the loop doesn't have an exit condition, it's not engineering, it's a while(true).
```

## Stack

**Core**: TypeScript (primary), JavaScript, Node.js
**AI/LLM**: Groq, OpenAI, Anthropic, Multi-agent orchestration, Prompt evaluation
**Loop Primitives**: Circuit breakers, Retry with backoff, Schema validation gates, Convergence criteria, Self-consistency voting
**Infrastructure**: Vercel, Docker, PostgreSQL, Redis
**Data & Automation**: n8n, BullMQ, Puppeteer

---

<details>
<summary>📊 GitHub Stats</summary>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=kreftamarcio&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=kreftamarcio&theme=github-dark-blue&hide_border=true" />
</details>

---

## Links & Contact

- 💼 **LinkedIn** — [marcio-krefta](https://www.linkedin.com/in/marcio-krefta-184a4b2b6/)
- 🚀 **F6S** — [krefta-marcio](https://www.f6s.com/krefta-marcio)
- 👼 **Wellfound** — [marcio-krefta-fontella](https://wellfound.com/u/marcio-krefta-fontella/)
- 🐙 **GitHub** — [kreftamarcio](https://github.com/kreftamarcio)
- 📧 kreftamarcio1@gmail.com

**Location**: Florianópolis, Brazil
