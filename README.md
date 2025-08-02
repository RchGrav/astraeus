# Astraeus Σ-9000 • Meta-Agent Orchestration Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Built for Claude Code](https://img.shields.io/badge/Claude_Code-Command-purple.svg)](https://claude.ai)
[![Release](https://img.shields.io/github/v/release/rchgrav/astraeus.svg)](https://github.com/RchGrav/astraeus/releases)

> **2025 Laureate, International Agentic-Workflow Design Award**  
> **Chief Architect, Institute for Autonomous Process Engineering**

---

## ✨ What is Astraeus Σ-9000?

Astraeus is a **zero-shot meta-orchestrator prompt** for Claude Code that bootstraps an *entire* AI development workforce—20-30 hyper-focused sub-agents—tailored to **your** repository.  
It analyses the folder you’re standing in, identifies the tech stack, then compiles deterministic agent definitions and workflow commands so every future `/astraeus` run incrementally improves the team.

---

## 🚀 Quick Start

```bash
# 1  Install the command once
mkdir -p ~/.claude/commands
cp astraeus.md ~/.claude/commands/

# 2  Open a project
cd /path/to/your/project

# 3  Launch Claude Code
claude

# 4  Fire up the orchestrator
/astraeus
````

> On first run Astraeus performs a pre-flight MCP check, scaffolds `CLAUDE.md` docs, and generates custom agents.
> Subsequent runs update & extend the team without losing history.

---

## 🧠 Key Features

| Capability                                    | What it means for you                                                  |
| --------------------------------------------- | ---------------------------------------------------------------------- |
| **Context-aware introspection**               | Parses language, tests, infra & docs to choose the right experts       |
| **Deterministic agent compilation**           | Each agent lives in `.claude/agents/`—trackable, reviewable, versioned |
| **ReAct / CRITIC / Reflexion loops built-in** | Agents reason, self-critique, and refine before handing work back      |
| **Parallel, reports-only workflow**           | No file writes; multiple specialists run safely side-by-side           |
| **Git-native governance**                     | Branch + PR flow mirrors Gitflow / Feature-Branch best practice        |
| **MCP memory layer**                          | Shared context across runs without blowing prompt windows              |

---

## 🔍 How it Works

1. **Run-type Detection** — decides if this is a fresh install or an update.
2. **Pre-flight Checks** — verifies MCP servers for memory & sequential thinking.
3. **Project Analysis** — inventories languages, frameworks, infra.
4. **Role Planning** — broad archetypes → deep specialists with least-privilege tools.
5. **Agent & Workflow Generation** — writes YAML-front-matter prompts + CLI commands.
6. **Human Review Gate** — outputs *patches & plans*; you merge after code review.

---

## 🗂️ Typical Output Tree

```
.claude/
├── commands/
│   └── asv-build-and-test.md        # example workflow command
└── agents/
    ├── react-frontend-specialist.md
    ├── fastapi-backend-architect.md
    ├── jest-test-engineer.md
    ├── oauth2-security-auditor.md
    └── ...
CLAUDE.md         # root knowledge hub
backend/CLAUDE.md # per-folder docs
tasks/            # requirements → design → build → validate
```

---

## 🛡️ Security & Compliance

* **Write-protection by design** – agents never commit code directly; all changes surface as diff suggestions.
* **Secrets hygiene** – automatic scanning for tokens & keys.
* **Industry regulators** – optional HIPAA / PCI / GDPR auditor agents for domain projects.

---

## 🤝 Contributing

Issues and PRs are welcome!
Please follow the conventional-commits style and open a discussion before large feature work.

---

## 📜 License

This project is released under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

> *“The best AI team is the one engineered specifically for **your** codebase.”*
> — **Astraeus Σ-9000**
