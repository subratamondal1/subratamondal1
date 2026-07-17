<div align="center">
  <h1>Subrata Mondal</h1>
  <h3>Founding AI Engineer | Agentic Systems · LangGraph → Hand-Built Primitives</h3>
  <p><em>Python 3.12+ (Async) · LiteLLM · MCP · DSPy Evals · Kubernetes (KEDA) · DBOS</em></p>

  <p>
    <a href="https://subrata.cloud/" target="_blank">Portfolio</a> •
    <a href="https://github.com/subratamondal1" target="_blank">GitHub</a> •
    <a href="https://www.linkedin.com/in/subratamondal1/" target="_blank">LinkedIn</a> •
    <a href="mailto:subratasubha2@gmail.com">Email</a>
  </p>
</div>

---

### 🟢 Status
**Open to Founding / Senior / AI Engineer roles, remote, hybrid, onsite.** I spent the last ~2 years as the sole AI and backend engineer at **lawworld.ai**, taking a legal-AI product from empty repo to production — architecture, agent orchestration, evals, CI/CD, cloud, the entire AI backend, solo — serving 2,000+ users today.

---

### 🧠 What I Know

I know the internals of the agent frameworks your team runs (LangGraph, CrewAI, AutoGen), not just the API surface — tool registry, prompt assembly, the loop, retry/fallback, state, permissions, observability, eval gate. Ran LangGraph in production for 4 months, then built those 8 primitives by hand. That's what lets me name which primitive is actually failing, not just which framework.

---

### 🏗️ Production — lawworld.ai

- **Reliability** — per-page MongoDB checkpointing + Azure Service Bus choreography, at-least-once execution, zero data loss on crashes. 7–8× Pass 1 wall-clock collapse (450–700s → 80–100s) via `asyncio.gather` + `Semaphore(6)`.
- **Cost engineering** — replaced a monolithic extraction pass with a bounded Agent 0 ReAct loop, cutting total token cost 27% on a 26-document stratified eval set (26/26 exact-match retained). Per-call cost-attribution middleware into MongoDB: 100.8M+ tokens processed, $296.75 total cost, 47.6% cache hit rate.
- **Scale** — 170K-document legal corpus, 2-stage retrieval (Atlas Vector Search ANN → Voyage rerank-2.5), Perplexity-style citations with a cited-only filter (~30× fewer persisted sources). ~2,000 registered users since the Jan 2026 launch.
- **Security** — multi-tenant JWT auth with per-request ownership gates that return 404, not 403, on unauthorized access, closing the enumeration side-channel most teams miss.
- **Eval discipline** — authored the eval-gating contract (ADR-005) before writing chat code: recall@5, phrase-overlap, and citation-accuracy thresholds as CI merge gates.

---

### ⚙️ Open-Source

#### [bare-agent](https://github.com/subratamondal1/bare-agent) — The 8-Primitive Agent Runtime
Zero-dependency agent runtime published to PyPI: strictly bounded ReAct loop, per-call cost ledgers, strict Pydantic V2 schema validation at every tool-call boundary, full transparency over the execution graph. Ships with a Next.js drag-and-drop studio that compiles visual node graphs into raw async Python.

#### [Argus](https://github.com/subratamondal1/argus) — Multi-Agent Deep-Research Engine
Permission-gated planner → parallel-searcher → synthesizer swarm (Python, LiteLLM, FastAPI, PostgreSQL/pgvector, Kubernetes + KEDA, DBOS). Cognitive routing sends extraction to fast/cheap models and reserves frontier reasoning models for synthesis, holding **$0.149/turn** unit economics. Clears 7 of 8 metrics on a curated eval benchmark behind a Cohen's-Kappa-calibrated LLM-judge gate. DBOS durable execution for crash-resumable research loops; KEDA scale-from-zero searcher pods on an ARQ/Redis queue.

#### [agents-eval-framework](https://github.com/subratamondal1/agents-eval-framework) — LLM-as-a-Judge Calibration Engine
DSPy Extractor-Judge calibration harness with an autonomous GEPA loop that reads failure traces and rewrites prompts. Drove Cohen's Kappa from 0.12 → 0.9261 across 5 architecture iterations on a 480-trace golden set.

---

### 🛠 Stack

| Domain | Technologies |
| :--- | :--- |
| **Agentic & LLM Systems** | Python 3.12+ (Async) · LiteLLM · MCP (Tool Calling) · DSPy · Hand-Built Agent Primitives · Hybrid RAG |
| **Evaluation** | LLM-as-a-Judge · Cohen's Kappa Calibration · Golden-Set Replay · RAGAS |
| **Distributed & Infra** | FastAPI · Docker · Kubernetes + KEDA · Azure Container Apps · Terraform · DBOS Durable Execution |
| **Databases & Brokers** | MongoDB Atlas · PostgreSQL (pgvector) · Redis · Kafka / Azure Service Bus |
| **Observability & Security** | OpenTelemetry · structlog · JWT Auth · Multi-Tenant Isolation |

---

### 📈 At a Glance

```yaml
role: Founding / Sole AI Engineer (lawworld.ai, Aug 2024 – Jun 2026)
status: open to Senior / Founding / AI Engineer roles, remote, hybrid, onsite
focus: Agentic Systems, Applied LLMs, Production Backends, LLM Evals, Durable Execution
timezone: IST (UTC+5:30)
contact: subratasubha2@gmail.com
```
