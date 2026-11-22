   # Bildad Mwangi
    **AI/ML Systems Engineer & Full-Stack Architect**
    *Engineering autonomous agentic loops, statistical machine learning pipelines, and resilient full-stack distributed systems.*

    [GitHub](https://github.com/JB7-creator) • [Portfolio](https://JB7-creator.github.io) • [Email](mailto:billyelcie7@gmail.com) • Nairobi, Kenya

    ```yaml
    specialization: ["Autonomous Agent Architectures", "Grounded RAG Pipelines", "Statistical ML Modeling", "Full-Stack MVPs"]
    primary_stack: ["Python", "PyTorch", "XGBoost", "LangChain", "FastAPI", "TypeScript", "React 19", "Next.js", "Solidity"]
    engineering_ethos: "Zero bloat. High signal-to-noise. Provable mathematics & deterministic systems."
    focus_area: "Building scalable AI solutions addressing real-world operational and societal challenges."
  ──────
  🏗 Production Architecture: Grounded Multi-Agent RAG & Inference  Pipeline

  Native system design illustrating how I bridge raw model serving and vector retrieval with high-reliability client interfaces.

  │ Diagram exceeds terminal width (255 > 190 cols)
  │ Displayed as code block. Widen terminal to view inline.

    flowchart LR
        subgraph ClientLayer ["Client & Interface Tier"]
            UI["React 19 / Next.js Client (Streaming SSE)"]
            WS["Async Event Listener"]
        end

        subgraph GatewayTier ["Ingress & Routing Tier"]
            API["FastAPI Gateway (Rate Limiting, JWT Auth)"]
            TaskQueue[("Redis Priority Queue & Task State")]
        end

        subgraph AgentCore ["Autonomous Agent & RAG Core"]
            Agent["LangChain / Python Tool Orchestrator"]
            HybridSearch["Hybrid Retrieval (Dense + BM25)"]
            VectorStore[("PostgreSQL + pgvector / Vector DB")]
        end

        subgraph ModelRuntime ["Model & Statistical Inference Engine"]
            LLM["Claude Sonnet / Gemini Inference"]
            MLModel["Statistical Poisson & XGBoost Regressors"]
        end

        UI -->|HTTP/2 Stream| API
        WS <-->|Task State Sync| API
        API --> TaskQueue
        TaskQueue --> Agent
        Agent --> HybridSearch
        HybridSearch <--> VectorStore
        Agent --> LLM
        Agent --> MLModel
  ──────
  🔬 Machine Learning Systems & Quantitative Case Studies

  1. BetEdge Pro — Statistical Sports Value Engine & ML Classifier

  An AI-driven predictive modeling system combining probabilistic distribution functions with ensemble machine learning.

  • Mathematical Core: Implements bivariate Poisson probability density modeling to derive true goal distributions against implied bookmaker probabilities, isolating market alpha.
  • Inference Pipeline: Secondary XGBoost classifier trained on historical match metrics to prune negative EV predictions.
  • Stack: Python 3.10+, Scikit-Learn, XGBoost, NumPy, Streamlit.
  • Repository: JB7-creator/betting-bot https://github.com/JB7-creator/betting-bot

   Architecture Component             │ Statistical Methodology            │ Pipeline Latency                  │ Validation Metric                 │ Target Objective
  ────────────────────────────────────┼────────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼────────────────────────────────────────
   Poisson Density Estimator          │ Bivariate Poisson distribution     │ < 8ms / match                     │ Log-loss minimization             │ Expected goal (xG) distribution
   Ensemble Classifier                │ Gradient-boosted trees (XGBoost)   │ < 15ms / inference                │ AUC-ROC: 0.74                     │ Positive expected value identification
   Interactive Dashboard              │ In-memory vectorized analytics     │ < 50ms reactive update            │ Zero memory leaks                 │ Real-time parameter recalibration
  ──────
  2. DeVote — Tamper-Proof Decentralized Voting Platform

  A cryptographic election platform eliminating centralized fraud through immutable blockchain execution.

  • Systems Architecture: Smart contracts audited for reentrancy and integer overflow; decouples voting identity verification from on-chain voter anonymization.
  • Consensus & State: State transitions verified via EVM execution; reactive web interface provides cryptographic receipt verification.
  • Stack: Solidity 0.8.20, Hardhat, Ethers.js, React 18, Tailwind CSS.
  • Repository: JB7-creator/blockchain-voting-system https://github.com/JB7-creator/blockchain-voting-system
  ──────
  3. Autonomous RAG Agent — Grounded Retrieval & Tool Orchestrator (Active R&D)

  A multi-modal document intelligence platform built on deterministic agentic loops.

  • Retrieval Architecture: Hybrid dense embedding retrieval (pgvector) combined with lexical keyword matching, routed through a re-ranking cross-encoder.
  • Hallucination Mitigation: Grounded citation verification where claims are strictly conditioned on retrieved source spans.
  • Stack: Python 3.11, LangChain, FastAPI, pgvector, PostgreSQL, Docker.
  ──────
  🚀 Full-Stack Production Products in the Real World

  Rukwaro Autospares — Enterprise Automotive Inventory Platform

  Modern high-throughput commercial storefront and parts catalog platform.

  • Frontend Architecture: Built with React 19, TypeScript, Vite, and Tailwind CSS. Implements instantaneous client-side faceted filtering over hundreds of SKUs.
  • Backend & Relational Schema: Supabase PostgreSQL backend with row-level security (RLS) policies and asset delivery pipelines.
  • Repository: JB7-creator/Rukwaroautospares https://github.com/JB7-creator/Rukwaroautospares
  ──────
  🛠 Systems & Technical Competency Matrix

     AI / ML & INFERENCE     : PyTorch, Scikit-Learn, XGBoost, LangChain, RAG, Prompt Engineering
     BACKEND & AGENTS        : Python (FastAPI, Asyncio), Node.js, REST APIs, WebSockets, Task Queues
     DATA & VECTOR STORAGE   : PostgreSQL, Supabase, pgvector, Redis, Vector Embeddings
     DISTRIBUTED & WEB3      : Solidity, Hardhat, Ethers.js, Smart Contract Security, Docker
     FRONTEND ARCHITECTURE   : TypeScript, React 19, Next.js (App Router), Vite, Tailwind CSS
     ENVIRONMENTS & TOOLING  : Linux (Bash), Git/GitHub CI/CD, Postman, Supabase CLI
  ──────
  📌 Engineering Objectives

  [ ] Benchmarking custom hybrid search rerankers for low-latency agent tool calling.
  [ ] Deploying self-hosted open-weights inference nodes with p99 response times < 200ms.
  [ ] Expanding decentralized governance and statistical transparency tools for emerging markets.
