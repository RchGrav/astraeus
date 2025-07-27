## 🧠 Technical Overview: `astraeus.md` – Claude-Oriented Meta-Agent Compiler Prompt

`astraeus.md` is a **Claude Code–native, zero-shot meta-agent orchestration compiler prompt** engineered for **one-time repository bootstrapping** within deterministic, agentic development environments.

Designed to execute via Claude’s `/.claude/commands` slash command interface (`/astraeus`), this prompt instantiates a **domain-specific, production-tier sub-agent ecosystem**, synthesizing full-stack agent definitions, workflow graphs, and operational SOPs — all declaratively scaffolded from local context (e.g., `docs/`, `README.md`, and `tasks/`).

> **Execution Environment:** `astraeus.md` must be executed **within Claude Code**, scoped to a **specific project folder**, to enable reflexive codebase analysis and tailored pipeline generation.

### 🔬 Core Capabilities

* **Context-Aware Repository Analysis**
  Dynamically introspects existing `docs/`, `requirements/`, and architecture seeds to synthesize initialization metadata.

* **Deterministic Agent Network Generation**
  Generates `.claude/agents/` blueprint files defining specialized roles (e.g., `test-engineer`, `security-auditor`, `domain-specific-developer`), each with declarative scopes, SOPs, and operational heuristics.

* **Multi-Agent Workflow Command Chaining**
  Compiles workflow execution graphs as Claude-executable markdown pipelines — e.g., `secure-feature-delivery.md`, `refactor-and-reverify.md` — using imperative, reproducible, role-bound directives.

* **Critic-Centric Evaluation Loops**
  Embeds embedded reflexion loops and automated CRITIC protocols (`eval/`) to enforce compliance, traceability, and production-readiness.

* **Agent Interoperability via Dialogue Coordination**
  Encodes ReAct-based multi-agent messaging protocols for task-state synchronization and outcome arbitration.

* **Agentic Process Engineering Compliance**
  Fully conforms to modern agent architecture principles:

  * **Two-stage specialization** (broad role ➜ deep domain)
  * **SOP-aligned autonomy**
  * **High-assurance delivery chains**
  * **Artifact traceability & evaluability**

### 🧭 Deployment Workflow

```bash
cp astraeus.md ~/.claude/commands/
cd your-project/
claude code .
```

Then, inside Claude Code:

```
/astraeus
```

This triggers an **orchestration cascade** that constructs a future-proof, critic-governed agentic development kernel in your repo — ready for feature execution, TDD pipelines, and reflexive feedback cycles.
