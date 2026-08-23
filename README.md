# Alexsandro (nobazzy)

**Backend & AI Systems Engineer**  
*Building autonomous systems for LLM infrastructure, resource orchestration, and AI-powered automation.*

---

### 🧠 Core Philosophy & Architecture

I build systems where **AI acts as the pilot, but deterministic local policy remains the authority**.

```
[ Telemetry & State ] ──> [ AI Reasoning / Pilot ] ──> [ Deterministic Policy Engine ] ──> [ Execution & Guardrails ]
          ▲                                                                                             │
          └──────────────────────── Feedback & Recovery Loop ──────────────────────────────────────────┘
```

- **Deterministic Control**: Models propose actions; robust local policies validate, enforce resource constraints, and execute.
- **Autonomous Recovery**: Self-healing lifecycles driven by continuous telemetry and state feedback loops.
- **Resource-Aware**: Dynamically optimizing hardware boundaries (VRAM, RAM, CPU) under heavy and concurrent workloads.

---

### 🚀 Featured Systems

#### [MEM — LLM Orchestrator](https://github.com/nobazzy/mem-llm-orchestrator)
> *Autonomous LLM training & execution orchestration with self-healing lifecycle management.*
- **Role**: AI pilot + local safety authority + hardware resource controller.
- **Key Highlights**: Dynamic task scheduling, crash detection, automated state recovery, and guardrailed model execution.
- **Stack**: Python, LLM APIs / Local Models, System Telemetry, Process Management.

#### [Orquestra — Dynamic Resource Orchestrator](https://github.com/nobazzy/orquestra-resource-orchestrator)
> *Real-time resource governor for Windows workloads balancing VRAM, RAM, and compute priority.*
- **Role**: Continuous system telemetry feeder informing an adaptive local policy engine.
- **Key Highlights**: Proactive VRAM reallocation, process throttling, memory compaction, and latency minimization.
- **Stack**: Python, Win32 APIs, System Telemetry, Resource Scheduling.

#### [WhatsApp AI Automation Engine](https://github.com/nobazzy/IA_Atendimento_Inteligente_whatsapp)
> *Multi-provider conversational engine built for production resilience and high-concurrency flows.*
- **Role**: Practical AI agent deployment with transactional state handling.
- **Key Highlights**: Anti-blocking serial queue, session isolation, multi-model fallback (OpenAI, Claude, Gemini, DeepSeek, Groq), and live admin dashboard.
- **Stack**: Node.js, TypeScript, Express, Prisma, Redis, SQLite / MySQL.

#### [Secret Exposure Detector](https://github.com/nobazzy/secret-exposure-detector)
> *Static analysis and entropy scanner for automated credential leak prevention in DevSecOps pipelines.*
- **Role**: Security guardrail for CI/CD and developer workflows.
- **Key Highlights**: Pattern matching, high-entropy token detection, zero-leak verification, and custom regex rulesets.
- **Stack**: Python, Regex Engine, DevSecOps / Git Hook Integration.

---

### 🛠️ Technical Stack & Focus Areas

- **Systems & Architecture**: Autonomous Agents, Orchestration Engines, State Machines, Telemetry & Self-Healing Loops, DevSecOps.
- **Languages & Runtime**: Python, TypeScript, Node.js.
- **AI & Infrastructure**: LLM Tooling (OpenAI, Anthropic, Gemini, Groq, Ollama/Local Weights), Docker, Redis, Prisma, SQL (PostgreSQL, MySQL, SQLite), Win32 / OS System APIs.

---

### 🌐 Connect

- **GitHub**: [@nobazzy](https://github.com/nobazzy)
- **Explore**: Take a look at [MEM](https://github.com/nobazzy/mem-llm-orchestrator) and [Orquestra](https://github.com/nobazzy/orquestra-resource-orchestrator) to see the architecture in action.
