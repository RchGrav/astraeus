# Astraeus Σ-9000 — Orchestration Compiler for Claude Code Sub-Agents

> “Future software won’t be written — it will be **orchestrated**.”

**Astraeus Σ-9000** reads your repository and compiles a tailored team of **specialized sub-agents** for Claude Code. It supports **branching, dynamic workflows**, can **operate in parallel**, and **keeps track of prior workflows** so it can enhance itself and your agent team over time.

---

## Safety Defaults

- **No direct code edits by default.** Agents generate reports, plans, patches, and diffs, but **do not write to files** unless you explicitly allow it when starting Astraeus.
- To allow writes, include clear instructions up front (scope, paths, commit policy). Example template:

  **Template:**  
  `create ______ agent for ______ with direct code editing permission, ensure agent creates commits on start and periodically with commit details`

  *(Tip: also specify allowed paths and a target branch.)*

---

## Installation

Place the Astraeus prompt file in a **commands** folder:

- **Project folder (local):** `./.claude/commands/`
- **User folder:** `~/.claude/commands/`

On your next launch of Claude Code, the **`/astraeus`** command will be available.

---

## What Astraeus Does

- **Standalone** - Capable of creating any agent you request and implementing its agent definition file.
- **Repository-aware agent synthesis** — Reads your README/docs/source to create role-perfect agents with crisp handoffs.
- **Branching & parallel execution** — Explore alternatives concurrently; synthesize results into a single, coherent outcome.
- **Critic & synthesizer pattern** — Built-in evaluation and merger for higher-quality outputs.
- **Continuity** — Tracks prior workflows/decisions and improves subsequent runs.
- **Git-first hygiene** — Encourages auditable outputs (patches, diffs, reports) and frequent commits when write access is granted.

---

## Works with BMAD (A Highly Recommended Project)

**BMAD Framework:** https://github.com/bmad-code-org/BMAD-METHOD

Astraeus can:
- **Benefit from mutual co-ordination with BMAD workflows**
- **Ingest patterns from BMAD and enhance BMAD patterns**
- **Create BMAD add-on packs**
- **Analyze BMAD templates and agents and deeply integrate & enhance workflows**
- **Enhance existing agents**
- **Gap-fill in your existing workflows**
- **Enhance existing generic agents to have deep expertise in your project**

**Example requests (BMAD-focused):**
- “Co-ordinate with BMAD workflows; ingest & enhance BMAD patterns; create a BMAD add-on pack tailored to our stack; analyze BMAD templates and agents; deeply integrate and enhance our workflows.”
- “Use BMAD planning/checklists to produce a sprint plan; generate architecture/dev/QA/review agents with BMAD patterns; synthesize a release plan.”
- “Perform BMAD-style context flattening (read-only) and design a parallel branching workflow with 4 specialists; synthesize a migration plan with risks and mitigations.”

---

## Works with Generic Agent Packs (Non-BMAD)

If you’ve downloaded **generic agents** from around the web, Astraeus can **read and enhance** them:

- **Enhance existing generic agents to have deep expertise in your project**
- **Gap-fill in your existing workflows**
- Normalize handoffs to the **critic → synthesizer** chain
- Maintain least-privilege tools and only expand when necessary

**Example requests (generic packs):**
- “Read `./agents/` and enhance our generic agents into project-specialized experts; define MUST-USE triggers and handoffs; add critic guarantees; synthesize a single delivery plan.”
- “Create a parallel team (4–5 agents) from my generic pack to propose alternative architectures; include cost/risk; return a synthesized recommendation.”
- “Scan our workflow docs and fill missing roles (security auditor, test engineer, integrator); standardize outputs as reports and patch sets.”

---

## Direct-Edit Examples (Opt-In)

Use the template to grant write access and set guardrails:

- “**create refactor-dev agent for `src/`** with direct code editing permission, ensure agent creates commits on start and periodically with commit details; limit edits to `src/` and commit to `feature/refactor-pass-1`.”
- “**create test-author agent for integration tests** with direct code editing permission, ensure agent creates commits on start and periodically with commit details; operate under `tests/integration/` on branch `feature/tests-suite`.”
- “**create migration-planner agent for DB schema migration** with direct code editing permission, ensure agent creates commits on start and periodically with commit details; only touch `migrations/` and `db/` on `feature/db-migrate`.”

---

## Example Output Structure

```

.claude/
commands/
astraeus.md                # The orchestration compiler prompt
agents/
architect.md
domain-dev.md
test-engineer.md
code-reviewer.md
security-auditor.md
critic/
synthesizer.md
docs/
reports/
output/                        # Proposed changes & patches

```

*(Structure is illustrative; Astraeus adapts to your repo and evolves its layout over time.)*

---

## Contributing

1. Propose changes to `astraeus.md` (the meta-prompt).
2. Test both **first-run** and **update-run** paths.
3. Maintain backward compatibility when possible.
4. Document new archetypes/workflows.
5. Open a PR with a clear description.

---

## License

[MIT](./LICENSE)

---

## Credits

Created by **Chengcheng (程程)** & **Rich**.  
Astraeus Σ-9000 orchestrates the rest.
