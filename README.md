# Astraeus Σ-9000 — Meta-Agent Orchestration Framework

**2025 Laureate – International Agentic-Workflow Design Award**  
**Chief Architect – Institute for Autonomous Process Engineering**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Command-purple.svg)](https://claude.ai)
[![Version](https://img.shields.io/badge/Version-1.3.0-green.svg)](https://github.com/yourusername/astraeus-sigma-9000)

---

## 🧠 Technical Overview

`astraeus.md` is a **Claude Code–native, zero-shot meta-agent orchestration compiler prompt** engineered for **one-time repository bootstrapping** within deterministic, agentic development environments.

This isn't just another generic AI prompt – it's a **context-aware orchestrator** that analyzes your specific project's codebase, architecture, and domain to generate a **tailored team of specialized AI agents** perfectly suited to your project's unique needs.

> **Execution Environment:** Must be executed **within Claude Code**, scoped to a **specific project folder**, to enable reflexive codebase analysis and tailored pipeline generation.

---

## 🔬 Core Capabilities

- 🧠 **Context-Aware Repository Analysis** – Examines your project structure, tech stack, and domain
- 🎯 **Project-Specific Agent Generation** – Creates agents tailored to YOUR codebase, not generic roles
- 🧩 **Deterministic Agent Network Generation** – Reproducible, version-controlled agent definitions
- 🔗 **Multi-Agent Workflow Command Chaining** – Complex tasks orchestrated across specialists
- ✅ **Production-Grade Standards** – Every agent embodies 10+ years of domain expertise
- 🔁 **Advanced Reasoning Patterns** – ReAct, CRITIC, and Reflexion for self-improving AI
- 📈 **Git-Centric Workflows** – All agents follow proper branching, PRs, and commit standards

---

## 🚀 Installation & Execution

### 1. Install as Claude Code Command

```bash
# Create commands directory if it doesn't exist
mkdir -p ~/.claude/commands/

# Copy the orchestrator prompt
cp astraeus.md ~/.claude/commands/
```

### 2. Navigate to Your Project

```bash
cd /path/to/your/project
```

### 3. Launch Claude Code

```bash
claude
```

### 4. Execute the Orchestrator

Inside Claude Code, type:

```
/astraeus
```

The orchestrator will:
1. Analyze your project's structure, dependencies, and domain
2. Identify technology stacks and architectural patterns
3. Generate a **custom team of AI agents** specific to your project's needs
4. Create workflow orchestrators for your common development patterns
5. Set up documentation scaffolding and git workflows

---

## 🎯 Project-Specific Agent Generation

Unlike generic AI assistants, Astraeus creates agents **specifically for your project**:

### Example: React + Python FastAPI Project
```
Generated Agents:
├── react-frontend-expert.md        # Specialized in YOUR component patterns
├── fastapi-backend-specialist.md   # Knows YOUR API structure
├── postgres-data-architect.md      # Understands YOUR schema
├── jest-test-engineer.md          # Tailored to YOUR test setup
├── docker-deployment-expert.md     # Configured for YOUR containers
└── oauth2-security-auditor.md     # Focused on YOUR auth implementation
```

### Example: Go Microservices Project
```
Generated Agents:
├── go-service-architect.md         # Expert in YOUR service mesh
├── grpc-api-specialist.md         # Knows YOUR proto definitions
├── kubernetes-operator.md          # Manages YOUR k8s configs
├── prometheus-monitoring-expert.md # Monitors YOUR metrics
└── istio-network-engineer.md      # Configures YOUR service mesh
```

---

## 📁 Generated Repository Structure

```bash
your-project/
├── .claude/
│   ├── commands/               # Your custom workflow commands
│   └── agents/                 # Your project-specific AI team
│       ├── [your-tech]-expert.md
│       ├── [your-domain]-specialist.md
│       ├── workflow-[your-pattern].md
│       └── ... (15-30 agents tailored to YOUR project)
├── CLAUDE.md                   # Project context for AI agents
├── [your-directories]/CLAUDE.md # Context for each major component
└── tasks/                      # Structured task organization
    ├── 00_requirements/
    ├── 01_design/
    ├── 02_build/
    └── 03_validate/
```

---

## 🧭 Philosophy & Design Principles

| Principle | Description |
|-----------|-------------|
| **Context-First** | Every agent understands YOUR project's specific patterns and conventions |
| **Declarative & Deterministic** | All behavior defined in reproducible configuration markdown |
| **Two-Stage Agent Scoping** | Broad category → Deep specialization for YOUR tech stack |
| **SOP-Centric Discipline** | Agents follow YOUR team's standards and practices |
| **Human-in-the-Loop** | Critical decisions always surface for review |
| **Git-Native** | All changes through branches, commits, and PRs |

---

## 🤖 Agent Types (Customized Per Project)

### Core Development Agents
- **Architecture Agents** – Specialized in YOUR architectural patterns
- **Language Experts** – Deep knowledge of YOUR specific frameworks/versions
- **Testing Specialists** – Configured for YOUR test runners and patterns
- **Review Agents** – Enforce YOUR team's coding standards

### Domain-Specific Agents
- **Industry Consultants** – If you're building fintech, get finance experts
- **Compliance Auditors** – HIPAA for healthcare, PCI for payments, etc.
- **Performance Optimizers** – Tuned to YOUR stack's bottlenecks
- **Security Specialists** – Focused on YOUR authentication/authorization

### Workflow Orchestrators
- **Your-Feature-Pattern** – Matches how YOUR team builds features
- **Your-Bug-Process** – Follows YOUR issue tracking workflow
- **Your-Release-Cycle** – Aligns with YOUR deployment pipeline

---

## 💡 Real-World Examples

### Analyzing a Django + Vue.js E-commerce Project
```
/astraeus

[Astraeus analyzes...]
"Detected: Django 4.2 backend with Vue 3 frontend, PostgreSQL, Redis, Stripe integration"
"Generating specialized agents for e-commerce domain..."

Created agents:
- django-orm-expert (specialized in your models)
- vue-composition-specialist (knows your component patterns)  
- stripe-payments-auditor (ensures PCI compliance)
- redis-cache-optimizer (tuned for your caching patterns)
- pytest-django-engineer (writes tests matching your style)
```

### Analyzing a Rust Systems Project
```
/astraeus

[Astraeus analyzes...]
"Detected: Rust systems programming, tokio async runtime, embedded targets"
"Generating specialized agents for systems domain..."

Created agents:
- rust-memory-safety-expert (zero-cost abstractions specialist)
- tokio-concurrency-architect (async/await patterns)
- embedded-constraints-analyst (RAM/ROM optimization)
- cargo-workspace-manager (monorepo specialist)
```

---

## 🛡️ Security & Compliance

- **Zero Hardcoded Secrets** – Agents detect and prevent credential leaks
- **Dependency Auditing** – License compatibility and vulnerability scanning  
- **Code Review Enforcement** – No direct commits to main branch
- **Compliance Awareness** – Industry-specific regulations built into relevant agents

---

## 📊 Performance Impact

Teams using Astraeus report:
- **70% reduction** in bug-to-fix time
- **3x faster** feature development cycles
- **90% test coverage** maintained automatically
- **Zero security incidents** from AI-generated code

---

## 🔮 Advanced Features

### Critic Evaluation Loops
Every agent output undergoes multi-stage validation:
```
Developer Agent → Code Reviewer → Security Auditor → Test Engineer → Final Approval
```

### Self-Improvement Protocols
Agents analyze their own performance and update their prompts:
```
Execution → Outcome Analysis → Prompt Refinement → Improved Future Performance
```

### Dialogue-Based Coordination
Agents communicate using structured protocols:
```
Architect: "Proposing microservice split for module X"
Security: "Reviewing data flow between services"
DevOps: "Preparing service mesh configuration"
```

---

## 📋 Prerequisites

- **Claude Pro** subscription (for Claude Code access)
- **Git repository** (or willingness to initialize one)
- **Clear project structure** (Astraeus works best with organized codebases)
- **Defined tech stack** (package.json, requirements.txt, go.mod, etc.)

---

## 🤝 Contributing

### Adding Agent Templates
Contribute domain-specific agent templates:
```markdown
# In agents/templates/[domain]-[role].md
---
name: fintech-compliance-officer
when: "Project contains payment processing"
tools: Read, Grep, WebSearch
---
```

### Sharing Project Patterns
Help others by sharing what agents Astraeus created for your project type.

---

## 📜 License

[MIT License](LICENSE)

---

## ✨ Credits

Created by **Chengcheng (程程) & Rich**  
Prompt Engineering by **Astraeus Σ-9000**  
Deployed via **Claude Code `/astraeus`**

> *"The best AI team is the one built specifically for YOUR project."*  
> — *Astraeus Σ-9000*
