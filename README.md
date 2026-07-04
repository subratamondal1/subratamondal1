<div align="center">
  <h1>Subrata Mondal</h1>
  <h3>Founding AI Engineer | Primitive-Level Architecture & Hyperscale Infrastructure</h3>
  <p><em>Raw Async Python · LiteLLM · DBOS · Multi-Agent Swarms · DSPy Evals · Kubernetes (KEDA)</em></p>

  <p>
    <a href="https://subrata.cloud/" target="_blank">Portfolio</a> •
    <a href="https://github.com/subratamondal1" target="_blank">GitHub</a> •
    <a href="https://www.linkedin.com/in/subratamondal1/" target="_blank">LinkedIn</a> •
    <a href="mailto:subratasubha2@gmail.com">Email</a>
  </p>
</div>

---

### 🟢 Status
**Open to Founding / Senior AI Engineer roles.** Most recently the Founding AI Engineer at **Smart AI Technology Solutions (LawWorld)** (Aug 2024 - Jun 2026), where I served as the sole AI and backend engineer, shipping 5 production backends and a 170K-document legal RAG system serving 2,000+ users.

---

### 🧠 The Engineering Philosophy
I do not build fragile AI wrappers using high-level frameworks like LangChain or LangGraph. I specialize in **primitive-level orchestration**, engineering the entire hyperscale stack from the ground up—from global edge routing and TCP optimization down to custom LLM orchestration and Pydantic-enforced structured outputs. 

> *"Frameworks obscure the cost ledger; primitives expose it."*

My work focuses on abandoning opaque multi-agent frameworks in favor of raw async Python, LiteLLM, and durable execution to enforce highly deterministic, transparent, and scalable ReAct loops with bounded iterations.

---

### 🚀 Production & Open-Source Architecture

#### 1. [Bare Agent](https://github.com/subratamondal1/bare-agent) | Framework-Free Multi-Agent Runtime
A zero-lock-in agent runtime published to PyPI, built on exactly 8 core primitives and zero dependencies. At LawWorld, I replaced a production LangGraph orchestration layer with this custom 8-primitive runtime, **cutting prompt token overhead by 27%** and eliminating schema drift entirely. Features a Next.js drag-and-drop studio that compiles visual node graphs directly into raw, high-performance async Python code.

#### 2. [Argus](https://github.com/subratamondal1/argus) | Multi-Agent Deep-Research Engine
A framework-free ReAct orchestration swarm built on Python, LiteLLM, PostgreSQL (pgvector), FastAPI, Kubernetes (KEDA), and DBOS.
*   **Cognitive Routing:** Dynamically routes extraction tasks to fast models (Llama 3/Flash) and reserves frontier models (Claude 3.5 Sonnet) strictly for synthesis, yielding **$0.149/turn unit economics**.
*   **Reliability:** Gates deployments on a strict **Cohen's Kappa >= 0.90** threshold against a human-labeled golden dataset.
*   **Durable State:** DBOS execution for crash-resumable state recovery on long-running research loops.
*   **Scale:** KEDA scale-from-zero searcher pods on an ARQ Redis queue.

#### 3. [Agents Eval Framework](https://github.com/subratamondal1/agents-eval-framework) | Autonomous Prompt Optimization
An automated prompt-calibration CI/CD suite built on DSPy and GEPA loops. Iterated a DSPy voice-agent benchmark from a Cohen's Kappa of 0.12 to 0.9261 across 5 architecture versions.

---

### ⚙️ The Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages & Core** | Python 3.12+ (Async, Pydantic, LiteLLM), TypeScript |
| **Agentic Systems** | MCP, Planner-Worker Swarms, Framework-Free Runtimes, Contextual RAG |
| **Evaluation** | LLM-as-a-judge, Cohen's Kappa, DSPy, RAGAS, Golden-Set Replay |
| **Infra & State** | DBOS Durable Execution, Redis ARQ, Docker, Kubernetes + KEDA, Azure Container Apps, Terraform |
| **Databases** | PostgreSQL (pgvector), MongoDB Atlas |
| **Observability** | OpenTelemetry (OTel), structlog |

---

### 📈 At a Glance

```yaml
role: Founding / Sole AI Engineer (Smart AI Technology Solutions, Aug 2024 to Jun 2026)
status: Open to Senior / Founding AI Engineer roles ($200K+)
model_preferences: Claude 3.5 Sonnet (Synthesis), Llama 3 / Flash (Extraction)
focus: Agentic Systems, Applied LLMs, Production Backends, LLM Evals, Durable Execution
timezone: IST (UTC+5:30) | Async-First Remote
contact: subratasubha2@gmail.com
```
