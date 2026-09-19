# Q1 AI Infrastructure Stack
**End-to-End Production-Grade AI Ecosystem**

[![Strict TypeScript](https://img.shields.io/badge/TypeScript-Strict_Zero_Any-blue.svg)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20%2B-green.svg)](https://nodejs.org/)
[![Architecture](https://img.shields.io/badge/Architecture-Kahn_Layering-orange.svg)]()
[![Production Ready](https://img.shields.io/badge/Status-Production_Ready-success.svg)]()

> A robust, lock-free, and deterministic infrastructure for autonomous AI agents, multi-agent orchestration, and production RAG systems unified in **[q1-agent-stack](https://github.com/kreftamarcio/q1-agent-stack)**.

## 🏗️ Architecture Map

```mermaid
graph TD
    %% Core Orchestration
    subgraph Orchestration Layer
        MAO[multi-agent-orchestrator]
        AR[agent-runtime]
        FCE[function-calling-engine]
    end

    %% Infrastructure & RAG
    subgraph Infrastructure & Data Layer
        IG[inference-gateway]
        RAG[rag-engine]
        DQ[distributed-queue]
    end

    %% Safety & State
    subgraph Governance & State
        GC[guardrails-core]
        AM[agent-memory]
        MCP[mcp-toolkit]
    end

    %% Evaluation
    subgraph Evaluation Loop
        EH[eval-harness]
        PF[prompt-forge]
        AB[q1-agent-adversarial-bench]
    end

    %% Data Flow
    MAO -->|Spawns Sandboxed Agents| AR
    AR -->|Validates Tools| FCE
    FCE -->|Executes Actions| MCP
    
    AR -->|Routes LLM Calls| IG
    IG -->|Validates I/O| GC
    
    AR -->|Semantic Search| RAG
    AR -->|State Management| AM
    
    MAO -.->|Task Dispatch| DQ
    
    EH -.->|Continuous Benchmarking| MAO
    PF -.->|Prompt Versioning| MAO
    
    classDef core fill:#2a2a2a,stroke:#3b82f6,stroke-width:2px,color:#fff;
    classDef infra fill:#2a2a2a,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef safety fill:#2a2a2a,stroke:#f59e0b,stroke-width:2px,color:#fff;
    classDef eval fill:#2a2a2a,stroke:#8b5cf6,stroke-width:2px,color:#fff;
    
    class MAO,AR,FCE core;
    class IG,RAG,DQ infra;
    class GC,AM,MCP safety;
    class EH,PF,AB eval;
```

## 📦 Unified Monorepo Ecosystem

All core packages, agent runtimes, and RAG engines are unified in **[q1-agent-stack](https://github.com/kreftamarcio/q1-agent-stack)**:

- **Orchestration**: [`@q1digital/multi-agent-orchestrator`](https://github.com/kreftamarcio/q1-agent-stack/tree/main/packages/agents/multi-agent-orchestrator) · [`@q1digital/agent-runtime`](https://github.com/kreftamarcio/q1-agent-stack/tree/main/packages/agents/agent-runtime)
- **Governance & Safety**: [`@q1digital/guardrails-core`](https://github.com/kreftamarcio/q1-agent-stack/tree/main/packages/security) · [`@q1digital/agent-memory`](https://github.com/kreftamarcio/q1-agent-stack/tree/main/packages/agents/agent-memory)
- **Infrastructure & RAG**: [`@q1digital/rag-engine`](https://github.com/kreftamarcio/q1-agent-stack/tree/main/packages/rag) · [`@q1digital/inference-gateway`](https://github.com/kreftamarcio/q1-agent-stack/tree/main/packages/mlops)

---
*Architected and maintained by [Marcio Krefta Fontella](https://github.com/kreftamarcio)*
