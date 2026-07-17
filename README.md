# Marcio Krefta

```
⚠️ Currently evaluating 2 offers. Open to exceptional opportunities only.
   Specialization: Loop Engineering · Multi-Agent Systems · Prompt Infrastructure
```

**I design self-correcting AI systems that improve themselves without human intervention.**

Most AI engineers build pipelines that run once. I build **loops**: systems that evaluate their own output, detect degradation, retry with alternative strategies, and converge on correct answers autonomously. This is Loop Engineering: the discipline of making AI systems that get better every iteration without touching the code.

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

→ **Self-Healing Production Systems**: WhatsApp bots that reconnect, re-authenticate, filter stale messages, and maintain conversation state across crashes.

## Proof of Work

### [`multi-agent-orchestrator`](https://github.com/kreftamarcio/multi-agent-orchestrator) 🧠
> Framework where agents self-correct through convergence loops.
>
> Circuit breakers detect failures → Retry with backoff → Fallback to alternative provider → Validate output against schema → Only then pass downstream.
>
> **3500+ lines of TypeScript** · 4 execution strategies · 3 LLM providers · Full observability · 35+ files

### [`prompt-forge`](https://github.com/kreftamarcio/prompt-forge) 🔥
> The evaluation loop for prompts: version → test → detect regression → optimize → redeploy.
>
> Bayesian A/B testing · Self-Consistency (multi-path voting) · Statistical significance (Wilson intervals, Cohen's d) · Token compression with quality preservation
>
> **2800+ lines** · 5 techniques · Research-backed methodology · Power analysis

### [`botzap`](https://github.com/kreftamarcio/botzap) 🤖
> Self-healing conversational agent: crashes → auto-reconnect → filter stale → resume.
>
> Running in production 24/7. Hybrid routing (deterministic + LLM) · Audio transcription · Conversation memory · Human handoff detection

### [`reservas`](https://github.com/kreftamarcio/reservas) 📅
> Concurrency loop solved at the database layer: attempt → constraint check → conflict? → reject atomically.
>
> PostgreSQL EXCLUDE USING GIST makes race conditions physically impossible. No application-level retry needed.

## What makes Loop Engineering different

| Traditional AI Engineering | Loop Engineering |
|---|---|
| Build pipeline, deploy, pray | Build loop, define exit criteria, guarantee convergence |
| Failures are bugs to fix | Failures are expected states the system handles |
| Quality checked by humans | Quality enforced by automated evaluation gates |
| One model, one attempt | Multiple strategies, adaptive selection |
| "Works on my machine" | Works in production for 30+ days unsupervised |

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

**Core**: TypeScript (primary), Python, Node.js
**AI/LLM**: Groq, OpenAI, Anthropic, Multi-agent orchestration, Prompt evaluation
**Loop Primitives**: Circuit breakers, Retry with backoff, Schema validation gates, Convergence criteria, Self-consistency voting
**Infrastructure**: Railway, Vercel, AWS, Docker, PostgreSQL, Redis

---

<details>
<summary>📊 GitHub Stats</summary>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=kreftamarcio&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=kreftamarcio&theme=github-dark-blue&hide_border=true" />
</details>

---

**Location**: Florianópolis, Brazil · **Open to**: Remote global roles in AI Engineering, Loop Engineering, Multi-Agent Systems
