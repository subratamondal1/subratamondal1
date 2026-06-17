# Hi, I'm Subrata Mondal

**Founding AI Engineer | Agentic Systems · RAG · LLM Evals**

> 🟢 **Open to senior / founding AI Engineer roles, remote.** Most recently the founding / sole AI engineer at lawworld.ai (Aug 2024 to Jun 2026).

<p align="center"><em>Python · async · LiteLLM · multi-agent · RAG · evaluation · MCP</em></p>

<p align="center">
  <a href="https://www.subrata.cloud/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/i-am-subrata-mondal/">LinkedIn</a> ·
  <a href="mailto:subratasubha2@gmail.com">Email</a>
</p>

---

### What I do

Founding / sole AI engineer at **lawworld.ai** from Aug 2024 to Jun 2026. I built every agent and the surrounding infrastructure end to end across 5 production Python backends, covering agent architectures, prompt and context engineering, evaluation harnesses, durable execution, and deployment at scale, on call throughout. Now looking for the next senior or founding AI engineering role.

**Phase-aware framework choice.** LangGraph 5-node state-machine graphs on the earlier agentic drafting and chatbot domains where multi-step state earned its tax (late 2025 to 2026), then framework-free orchestration (LiteLLM, Pydantic, raw async) on the act-parser and the modular-monolith successor where production operating-pain made the framework tax visible. Two framework-free backends, the second confirms the first was not situational.

---

### Selected work

- **[bare-agent](https://github.com/subratamondal1/bare-agent)** — framework-free agent library + visual studio. Published a zero-lock-in agent runtime to PyPI (8 primitives, zero dependencies) for executing deterministic multi-agent chains, and engineered a Next.js drag-and-drop studio that compiles visual workflows into raw, framework-free Python code (Ollama at $0).
- **[Argus](https://github.com/subratamondal1/argus)** — a framework-free, multi-agent **deep-research engine** (Python, LiteLLM, PostgreSQL/pgvector, FastAPI, Kubernetes/KEDA, DBOS, MCP). Orchestrator-worker agent loops, contextual-RAG with hybrid HNSW and full-text retrieval fused with Reciprocal Rank Fusion, a **Cohen's-kappa-calibrated LLM-judge eval gate** on a curated benchmark with negative and abstention cases, **KEDA scale-from-zero** searcher pods on an ARQ-on-Redis queue, **DBOS durable execution** with crash-resumable research, and the tool registry exposed as an **MCP server**. Local-first ($0 on Ollama), multi-tenant, around 150 tests, MIT.

---

### Stack

- **Languages** — Python 3.12+ (expert: async, Pydantic, LiteLLM, framework-free runtimes) · TypeScript (working)
- **Agentic & Deep Research** — MCP tool calling · planner-worker swarms · contextual RAG · hybrid retrieval (RRF) · semantic caching · vector databases (MongoDB Atlas, pgvector)
- **Agentic Reliability** — LLM-as-judge eval gating · Cohen's-kappa calibration · golden-set replay · RAGAS metrics · agentic observability (OTel, structlog)
- **Distributed Systems & Infra** — durable execution (crash-resumable state) · FastAPI (SSE) · Redis ARQ · PostgreSQL · MongoDB · Docker · Kubernetes + KEDA · Azure Container Apps · Terraform

---

### Strengths

- **Agentic systems**: multi-agent orchestration, ReAct loops, planning, reflection, tool-calling, structured outputs
- **Framework judgment**: phase-aware decisions on when LangGraph earns its tax vs when raw async + LiteLLM wins, AGENTS.md governance from day 1
- **LLM reliability**: retries, fallback, multi-provider routing, prompt caching, cost and latency engineering
- **Evaluation**: golden datasets, LLM-as-judge graders, eval harness, metrics-driven iteration
- **Backend depth**: async Python, schema-first APIs, queue-based pipelines, observability, IaC
- **Durable orchestration**: long-running agent runtimes, event-driven choreography over message queues, per-step checkpointed crash-recovery, self-healing producer-worker pipelines
- **Production ownership**: incident response, on-call, deployment, cost attribution

---

### Currently exploring

- MCP servers, A2A protocol, agent-tool ecosystems
- Kubernetes-native deployment patterns (the lawworld production ran on Azure Container Apps + KEDA)

---

### At a glance

```yaml
role: Founding / Sole AI Engineer (lawworld.ai, Aug 2024 to Jun 2026)
status: open to senior / founding AI engineer roles, remote
focus: agentic systems, applied LLMs, production backends, LLM evals
stack: Python, async, FastAPI, LiteLLM, LangGraph, MCP, MongoDB, pgvector, Azure
timezone: IST (UTC+5:30), async-first remote
contact: subratasubha2@gmail.com
portfolio: https://www.subrata.cloud/
linkedin: https://www.linkedin.com/in/i-am-subrata-mondal/
```
