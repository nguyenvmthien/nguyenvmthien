<div align="center">

<br/>

# THIEN NGUYEN

### AI ENGINEER

<img
src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2600&pause=900&color=8B949E&center=true&vCenter=true&width=850&lines=RAG+%E2%80%A2+Agents+%E2%80%A2+Harnesses+%E2%80%A2+LLM+Systems;From+AI+applications+to+inference+infrastructure.;Build+%E2%86%92+Evaluate+%E2%86%92+Serve+%E2%86%92+Observe+%E2%86%92+Improve"
/>

<br/>

**Building production AI systems across the full stack —
from agent loops and retrieval pipelines to model serving and GPU infrastructure.**

<br/>

`RAG` · `Agents` · `LLM Systems` · `Backend` · `Inference` · `Infrastructure`

</div>

---

## `01 / AI ENGINEERING`

```text
┌───────────────────────────────────────────────────────────────┐
│                        AI PRODUCT                             │
│                                                               │
│             RAG · Agents · Multimodal · APIs                  │
└──────────────────────────────┬────────────────────────────────┘
                               │
                               ▼
┌───────────────────────────────────────────────────────────────┐
│                       AGENT SYSTEM                            │
│                                                               │
│  Harness · Loop · Tools · Context · Memory · State · Planning │
└──────────────────────────────┬────────────────────────────────┘
                               │
                               ▼
┌───────────────────────────────────────────────────────────────┐
│                        LLM SYSTEM                             │
│                                                               │
│   Retrieval · Routing · Evals · Guardrails · Observability    │
└──────────────────────────────┬────────────────────────────────┘
                               │
                               ▼
┌───────────────────────────────────────────────────────────────┐
│                      AI INFRASTRUCTURE                        │
│                                                               │
│    Serving · vLLM · SGLang · Distributed Systems · CUDA       │
└───────────────────────────────────────────────────────────────┘
```

I work across the layers required to turn a model into a **reliable AI product**.

My interests span both application-level AI engineering and the systems underneath it:

<table>
<tr>
<td width="50%" valign="top">

### AI Applications

* Retrieval-Augmented Generation
* Agentic applications
* Multimodal systems
* AI-native backend services
* Structured generation
* Knowledge systems

</td>
<td width="50%" valign="top">

### Agent Engineering

* Agent harnesses
* Agent execution loops
* Tool orchestration
* Context engineering
* Memory & state
* Long-running agents

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Reliability

* Evaluation systems
* Observability
* Tracing
* Guardrails
* Testing
* Feedback loops

</td>
<td width="50%" valign="top">

### AI Systems

* Model serving
* LLM inference
* vLLM / SGLang
* Distributed systems
* GPU computing
* CUDA

</td>
</tr>
</table>

---

## `02 / SELECTED WORK`

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Infercap

**LLM inference engineering toolkit**

Operational tooling for understanding an LLM workload before and after deployment.

```text
MODEL
  │
  ▼
CHECK ──► SERVE ──► VERIFY
                   │
                   ▼
              BENCHMARK
                   │
                   ▼
                ANALYZE
```

`Inference` `vLLM` `Benchmarking` `Telemetry`

**[Repository →](https://github.com/nguyenvmthien/infercap)**
**[Website →](https://infercap.vercel.app)**

</td>

<td width="50%" valign="top">

### ◈ Healthcare GraphRAG

**Knowledge-grounded AI system**

Exploring retrieval and reasoning over heterogeneous healthcare knowledge.

```text
DATA
 │
 ├──► INDEX
 │
 ├──► GRAPH
 │
 └──► RETRIEVAL
          │
          ▼
       CONTEXT
          │
          ▼
       REASONING
```

`GraphRAG` `Retrieval` `Knowledge Graphs` `LLMs`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ◌ Agent Systems

**Harnesses & execution loops**

Experiments around reliable agents that interact with tools and environments.

```text
GOAL
 │
 ▼
CONTEXT ──► MODEL
             │
             ▼
            ACT
             │
             ▼
          OBSERVE
             │
             └──────► LOOP
```

`Agents` `Tools` `Harness` `Context` `Evals`

</td>

<td width="50%" valign="top">

### ⌁ AI Systems

**Serving & performance**

Studying the infrastructure beneath production AI applications.

```text
REQUEST
   │
   ▼
SCHEDULER
   │
   ▼
MODEL EXECUTOR
   │
   ▼
GPU / KV CACHE
```

`vLLM` `SGLang` `CUDA` `Distributed Systems`

</td>
</tr>
</table>

---

## `03 / ENGINEERING STACK`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,pytorch,fastapi,postgres,redis,docker,linux,aws,git&theme=dark" />

</div>

<br/>

<table>
<tr>
<td><b>AI</b></td>
<td>PyTorch · Transformers · RAG · Agents · LLM APIs</td>
</tr>

<tr>
<td><b>Backend</b></td>
<td>Python · FastAPI · SQL · REST · Async Systems</td>
</tr>

<tr>
<td><b>Data</b></td>
<td>PostgreSQL · Vector Search · Redis · Data Pipelines</td>
</tr>

<tr>
<td><b>Serving</b></td>
<td>vLLM · SGLang · Model APIs · Batching · KV Cache</td>
</tr>

<tr>
<td><b>Systems</b></td>
<td>C++ · CUDA · Linux · Docker · Distributed Systems</td>
</tr>

<tr>
<td><b>Infrastructure</b></td>
<td>AWS · Observability · Benchmarking · CI/CD</td>
</tr>
</table>

---

## `04 / HOW I THINK ABOUT AI SYSTEMS`

```text
                         USER
                           │
                           ▼
                    ┌─────────────┐
                    │ APPLICATION │
                    └──────┬──────┘
                           │
           ┌───────────────┼───────────────┐
           ▼               ▼               ▼
          RAG            AGENT          MODEL API
           │               │
           │        ┌──────┴──────┐
           │        │   HARNESS   │
           │        └──────┬──────┘
           │               │
           │       context / tools
           │       memory / state
           │       loop / control
           │               │
           └──────────┬────┘
                      ▼
                ┌───────────┐
                │ LLM LAYER │
                └─────┬─────┘
                      │
                routing / evals
                safety / tracing
                      │
                      ▼
               ┌─────────────┐
               │   SERVING   │
               └──────┬──────┘
                      │
              vLLM / SGLang
                      │
                      ▼
               ┌─────────────┐
               │ GPU / CLOUD │
               └─────────────┘
```

<div align="center">

### Build the application.

### Engineer the loop.

### Measure the behavior.

### Operate the system.

</div>

---

## `05 / CURRENTLY EXPLORING`

**Agent Engineering**

`Harness Design` · `Agent Loops` · `Context Engineering` · `Tool Use` · `Long-running Agents`

**RAG & Knowledge Systems**

`GraphRAG` · `Hybrid Retrieval` · `Reranking` · `Retrieval Evaluation`

**AI Reliability**

`Evals` · `Tracing` · `Observability` · `Guardrails` · `Feedback Loops`

**AI Systems**

`Continuous Batching` · `KV Cache` · `Speculative Decoding` · `CUDA`

---

## `06 / ACTIVITY`

<div align="center">

<img
src="https://github-readme-activity-graph.vercel.app/graph?username=nguyenvmthien&bg_color=0d1117&color=8b949e&line=58a6ff&point=f0f6fc&area=true&hide_border=true"
width="96%"
/>

<br/><br/>

<code>APPLICATION → AGENT → MODEL → SERVING → INFRASTRUCTURE</code>

<br/><br/>

<sub>Building reliable AI systems across the stack.</sub>

</div>
