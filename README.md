# Astraeus Σ-9000 — Meta-Agent Orchestration Framework 🧠🕸️

**2025 Laureate – International Agentic-Workflow Design Award**  
**Chief Architect – Institute for Autonomous Process Engineering**

---

## 🧠 Technical Overview

`astraeus.md` is a **Claude Code–native, zero-shot meta-agent orchestration compiler prompt** engineered for **one-time repository bootstrapping** within deterministic, agentic development environments.

Designed to execute via Claude’s `/.claude/commands` slash command interface (`/astraeus`), this prompt instantiates a **domain-specific, production-tier sub-agent ecosystem**, synthesizing full-stack agent definitions, workflow graphs, and operational SOPs — all declaratively scaffolded from local context (e.g., `docs/`, `README.md`, and `tasks/`).

> **Execution Environment:** `astraeus.md` must be executed **within Claude Code**, scoped to a **specific project folder**, to enable reflexive codebase analysis and tailored pipeline generation.

---

## 🔬 Core Capabilities

- 🧠 **Context-Aware Repository Analysis**  
- 🧩 **Deterministic Agent Network Generation**
- 🔗 **Multi-Agent Workflow Command Chaining**
- ✅ **Critic-Centric Evaluation Loops**
- 🔁 **Reflexion-Based Self-Improvement Protocols**
- 💬 **Dialogue-Based Coordination & Messaging**
- 📈 **Metric-Driven Retrospectives and Feedback Loops**

---

## 🚀 How to Run Astraeus Σ-9000

To initialize your project with Astraeus:

### 1. Install the Command

Copy the prompt file into your Claude commands directory:

```bash
cp astraeus.md ~/.claude/commands/
```

### 2. Launch Claude Code

From the root of your target project:

```bash
claude code .
```

### 3. Execute the Orchestrator

Inside Claude Code, type:

```
/astraeus
```

This launches the orchestrator within the current project folder. It will analyze context (like `docs/` and existing code), then generate a tailored agentic pipeline and supporting workflow artifacts.

---

## 🧭 Philosophy & Design Principles

| Principle                    | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| Declarative & Deterministic | All behavior is defined in reproducible configuration markdown              |
| Two-Stage Agent Scoping     | From general role → deeply scoped expert prompt                             |
| SOP-Centric Discipline      | Every agent adheres to embedded Standard Operating Procedures               |
| Critic-Oriented Reflexion   | Nothing ships until evaluated, revised, and signed off by an autonomous critic |
| Dialogue & Reasoning Loops  | Agent interoperation governed by structured dialogue & ReAct coordination    |

---

## 📁 Generated Repository Structure

```bash
├── tasks/
│   ├── 00_requirements/
│   ├── 01_design/
│   ├── 02_build/
│   └── 03_validate/
├── eval/                         # Formal critic reports & sign-offs
├── docs/                         # Diagrams, references, expert rosters
├── logs/                         # Timestamps, execution notes
└── .claude/
    └── agents/
        ├── meta-prompt-engineer.md
        ├── architect-agent.md
        ├── test-engineer.md
        ├── domain-specific-developer.md
        ├── code-reviewer.md
        ├── project-manager-agent.md
        ├── critic agents
        ├── self-refinement-agent.md
        ├── dialogue-coordinator.md
        ├── fullstack-delivery-workflow.md
        ├── secure-feature-delivery.md
        ├── regression-verification-loop.md
        ├── bug-investigation-cycle.md
        └── ...
```

---

## ✅ Acceptance Criteria

- **Completeness:** All generated artefacts match specification
- **Traceability:** Every task is backed by a critic-reviewed `eval/*.md` report
- **Reproducibility:** A new agent can recreate outcomes using only this repo
- **Explicitness:** No implicit steps; every command and file is defined

---

## 🧠 Sample Workflow Execution

```text
User runs /astraeus ➜
Astraeus examines project ➜
Generates agents + workflows ➜
Critic agents review artefacts ➜
Feedback triggers reflexive loops ➜
Final sign-off emitted ➜
✅ Repository bootstrapped with agentic pipeline
```

---

## 🛡️ Meta-Agent Types

- `meta-prompt-engineer.md` — Instantiates scoped agents with SOP alignment
- `architect-agent.md` — Designs system architecture & workflows
- `domain-specific-developer.md` — Implements deeply scoped logic
- `test-engineer.md` — Designs comprehensive validation suites
- `code-reviewer.md` — Enforces code quality and constraints
- `security-auditor.md` — Performs threat modeling and static inspection
- `dialogue-coordinator.md` — Orchestrates inter-agent messaging (ReAct/CAMEL)
- `critic` agents — Domain-specialist reviewers with fail/pass mandates
- `self-refinement-agent.md` — Detects intermediate faults and reruns correction loops

---

## 📘 Reference Materials

- [Agentic Workflow Design Guide](https://www.promptingguide.ai/agent-design)
- [CAMEL Dialogue Framework](https://arxiv.org/abs/2303.17760)
- [AutoReflexion & Self-Correction](https://arxiv.org/abs/2305.15334)
- [CriticEval Protocols](https://arxiv.org/abs/2309.00653)

---

## 📜 License

[MIT License](LICENSE)

---

## 🤝 Contributing

All contributions must:

- Include a new `.claude/agents/*.md` file (agent or workflow)
- Include a corresponding `eval/<artefact>_review.md` signed by a critic agent
- Conform to SOP and prompt architecture guidelines
- Be submitted via PR with traceable changelog

---

## ✨ Credits

Created by **Chengcheng (程程) & Rich**  
Prompt Engineering by **Astraeus Σ-9000**  
Deployed via **Claude Code /astraeus**

> *“Future software won’t be written — it will be orchestrated.”*  
> — *Astraeus Σ-9000*
