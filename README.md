<div align="center">

# Muhammad Azfar

### AI Engineer · Agentic Systems · Software Engineering

**I build AI systems that reason, retrieve, use tools, recover from failure, and produce structured work.**

[![GitHub](https://img.shields.io/badge/GitHub-M--Azfar9-111827?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/M-Azfar9)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muhammad%20Azfar-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/muhammad-azfar-687304288/)
[![Focus](https://img.shields.io/badge/Focus-Agentic%20AI-00A67E?style=for-the-badge)](#03--current-focus)

</div>

---

## `01` · CURRENT STATE

> **Software Engineering student at NUST, building toward AI/ML and Agentic AI engineering.**

My work sits at the intersection of **LLMs + software engineering + autonomous workflows**.

I am especially interested in what comes after "call an LLM":

* stateful agent workflows
* supervisor / subagent architectures
* RAG and evidence-grounded generation
* MCP and tool-enabled AI systems
* structured outputs and validation
* retries, backoff, timeouts and failure recovery
* observability and evaluation
* turning prototypes into maintainable systems

I started with application development and Flutter. Today, most of my exploration is focused on **AI systems engineering**.

---

## `02` · THE WAY I THINK ABOUT AI SYSTEMS

I don't think of an AI application as just a chatbot.

I think of it as a **software system with a reasoning layer**:

```text
User Intent
     ↓
Route / Decompose
     ↓
Plan
     ↓
Execute ───────→ Tools / MCP / RAG / Web
     ↓
Observe
     ↓
Validate
     ↓
Recover if needed
     ↓
Structured Output
     ↓
Evaluate
```

The goal is not simply to make an agent **smart**.

The goal is to make it **bounded, observable, testable and reliable**.

---

## `03` · CURRENT FOCUS

| Area                    | What I'm exploring                                               |
| ----------------------- | ---------------------------------------------------------------- |
| **Agentic AI**          | Supervisors, subagents, routing, HITL, stateful workflows        |
| **LangGraph**           | StateGraph, reducers, Send(), interrupts, persistence            |
| **RAG**                 | Code RAG, retrieval pipelines, grounding, evaluation             |
| **MCP**                 | Tool servers, resources, agent-tool interoperability             |
| **LLM Engineering**     | Structured output, prompts, model routing, fallbacks             |
| **Reliability**         | Retries, exponential backoff, jitter, timeouts, circuit breakers |
| **Evaluation**          | Tracing, datasets, faithfulness, relevancy, correctness          |
| **ML / DL**             | ML foundations, neural networks, CNNs, transfer learning         |
| **Backend**             | Python, FastAPI, APIs, async workflows                           |
| **Product Engineering** | Flutter, Firebase, PostgreSQL, production architecture           |

---

## `04` · FLAGSHIP BUILDS

### 🧠 Doxer AI

**Autonomous documentation + engineering intelligence**

A hierarchical multi-agent system for technical Q&A, live research, repository analysis, developer documentation, and requirements-driven SRS generation.

```text
Supervisor
    │
    ├── QA Agent
    │
    ├── Documentation Agent
    │
    └── SRS Agent
```

**Built around:**

* LangGraph multi-agent orchestration
* GitHub + filesystem + web research
* code-aware RAG
* AST-based symbol extraction
* HITL requirements gathering
* IEEE 830-oriented SRS generation
* parallel document / diagram generation
* grounding critique and bounded refinement
* LangSmith tracing and evaluation
* production-style resilience patterns

→ **[Explore Doxer AI](https://github.com/M-Azfar9/Doxer-AI)**

---

### ⚙️ ZeroLM AgentMesh

**A model/tool orchestration experiment**

A cognitive orchestration layer that routes different tasks toward specialized AI capabilities instead of forcing one general-purpose model to do everything.

```text
LLM
 ↓
Intent Detection
 ↓
Tool / Model Selection
 ↓
Specialized Execution
 ↓
Synthesis
```

→ **[Explore ZeroLM AgentMesh](https://github.com/M-Azfar9/ZeroLM-AgentMesh)**

---

### 🇵🇰 ForiKaam

**Reverse-auction marketplace for skilled work**

A product concept built around real-time bidding between customers and skilled workers.

```text
Job
 ↓
Broadcast
 ↓
Counter Bids
 ↓
Selection
 ↓
Verification
 ↓
Fulfillment
```

The project combines product engineering, real-time systems, marketplace logic and practical mobile application architecture.

→ **[Explore ForiKaam](https://github.com/M-Azfar9/forikaam-marketplace)**

---

### 🔌 Browser History MCP

**Local browser intelligence through MCP**

A privacy-focused MCP server exposing local browser history and bookmarks to AI assistants through structured tools.

Examples:

* search history
* search bookmarks
* inspect recent visits
* discover top domains
* summarize page visits
* keep processing local

→ **[Explore Browser History MCP](https://github.com/M-Azfar9/mcp-browser-insights)**

---

### 🧪 Agentic AI Lab

A hands-on repository where I implement agentic patterns instead of only reading about them.

```text
Sequential
    ↓
Parallel
    ↓
Conditional
    ↓
Iterative
    ↓
Persistent
    ↓
Tool Calling
    ↓
Agents
```

→ **[Explore the Agentic AI Lab](https://github.com/M-Azfar9/agentic-ai-langgraph)**

---

## `05` · TOOLBOX

### AI / Agent Engineering

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square\&logo=langchain\&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square\&logo=langchain\&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-6B5B95?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-0EA5E9?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square\&logo=huggingface\&logoColor=black)

### ML / Data

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikit-learn\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square\&logo=tensorflow\&logoColor=white)

### Software Engineering

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square\&logo=firebase\&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square\&logo=flutter\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square\&logo=dart\&logoColor=white)

---

## `06` · HOW I LIKE TO ENGINEER AGENTS

I care about the engineering details that make an agent **predictable**, not just impressive in a demo.

### 01 — Bound the agent

Loops need exit conditions.

Retries need limits.

Exploration needs sufficiency criteria.

### 02 — Make state explicit

If the workflow matters, represent it instead of hiding everything inside prompts.

### 03 — Separate reasoning from execution

Let the model decide **what** should happen.

Let deterministic code handle what can be deterministic.

### 04 — Design for failure

429s, malformed structured output, tool failures, timeouts and unavailable providers are normal engineering cases.

### 05 — Evaluate the system, not only the model

Routing accuracy, retrieval quality, grounding, correctness, latency and cost all matter.

---

## `07` · MY LEARNING TRAJECTORY

```text
LLMs
 │
 ├── Structured Output
 │
 ├── RAG
 │
 ├── Tool Calling
 │
 ├── Agentic Workflows
 │
 ├── Multi-Agent Systems
 │
 ├── MCP
 │
 ├── Reliability
 │
 ├── Evaluation
 │
 └── Production AI Systems
```

### Exploring next

* LLM fine-tuning
* LLM evaluation and observability
* model routing
* agent security
* MCP architecture
* production RAG
* scalable agent orchestration
* reliable AI systems beyond a single prompt

---

## `08` · SELECTED REPOSITORIES

| Repository                                                                       | Theme                             |
| -------------------------------------------------------------------------------- | --------------------------------- |
| **[Doxer AI](https://github.com/M-Azfar9/Doxer-AI)**                             | Multi-agent engineering assistant |
| **[ZeroLM AgentMesh](https://github.com/M-Azfar9/ZeroLM-AgentMesh)**             | AI / model orchestration          |
| **[ForiKaam](https://github.com/M-Azfar9/forikaam-marketplace)**                 | Marketplace product engineering   |
| **[Browser History MCP](https://github.com/M-Azfar9/mcp-browser-insights)**      | MCP + local AI tooling            |
| **[Agentic AI LangGraph](https://github.com/M-Azfar9/agentic-ai-langgraph)**     | Agent workflow experiments        |
| **[Model Context Protocol](https://github.com/M-Azfar9/Model-Context-Protocol)** | MCP learning / experimentation    |
| **[Deep Learning](https://github.com/M-Azfar9/Deep-Learning)**                   | Deep learning foundations         |
| **[Supervised ML](https://github.com/M-Azfar9/Supervised-Machine-Learning)**     | ML foundations                    |

<details>
<summary><b>More repositories →</b></summary>

I also maintain experiments around EDA, feature engineering, computer vision, APIs, Flutter applications, data analysis, and smaller software engineering projects.

→ **[Browse all repositories](https://github.com/M-Azfar9?tab=repositories)**

</details>

---

## `09` · GITHUB SIGNAL

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=M-Azfar9&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" height="165" alt="GitHub statistics" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=M-Azfar9&layout=compact&hide_border=true&theme=transparent" height="165" alt="Most used languages" />

</div>

---

## `10` · A LITTLE MORE HUMAN

Outside the code, I like learning by **building**, breaking things, debugging them, and rebuilding them properly.

I don't want to only know *what* a framework does.

I want to understand:

> **Why was it designed this way?**
> **What happens when it fails?**
> **How does it scale?**
> **How do we evaluate it?**
> **And how would I build it myself?**

That's the direction I'm taking with AI engineering.

---

## `11` · LET'S BUILD

I'm interested in connecting with people working on:

**Agentic AI · LLM Applications · RAG · MCP · AI Infrastructure · Developer Tools · AI Startups · ML Engineering**

<div align="center">

### Build systems. Understand the failure modes. Ship better AI.

**[GitHub](https://github.com/M-Azfar9) · [LinkedIn](https://www.linkedin.com/in/muhammad-azfar-687304288/)**

<br>

<sub>AI systems, not AI demos.</sub>

</div>
