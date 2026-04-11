# Cognitive Thought Engine

**We build the WHY layer for autonomous AI governance — the governance layer above identity and policy enforcement.**

---

## Start Here

| | |
|-|-|
| **[constitutional-agent](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance)** | The runtime library. Six constitutional gates, 12 hard constraints enforced in code. `pip install constitutional-agent` |
| **[cgst-framework](https://github.com/CognitiveThoughtEngine/cgst-framework)** | The assessment tool. Score your agent system across six governance layers before the first incident. |
| **[agentic-governance-papers](https://github.com/CognitiveThoughtEngine/agentic-governance-papers)** | The research base. Five peer-reviewed preprints, full citations, NIST engagement docs. |

---

## The Three-Layer Stack

AI agent governance has three structurally distinct layers. The first two are well-served. The third is where decisions are made badly.

| Layer | Question | Examples |
|-------|----------|----------|
| **WHO** | Is this agent authorized to act? | Microsoft Entra Agent ID, Okta, AWS IAM, Glasswing |
| **HOW** | Is this action permitted by policy? | Microsoft AGT, NeMo Guardrails, OPA, Cedar |
| **WHY** | Does this decision align with constitutional principles? | **constitutional-agent** |

`constitutional-agent` complements identity and policy tools — it governs decision quality *after* the agent is authorized and the action is policy-compliant, covering the scenarios your policy writers haven't written rules for yet.

---

## Portfolio

| Repo | Purpose | Install |
|------|---------|---------|
| [constitutional-agent-governance](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance) | Runtime governance library — six gates, 12 hard constraints, EU AI Act Art. 27 FRIA evidence | `pip install constitutional-agent` |
| [cgst-framework](https://github.com/CognitiveThoughtEngine/cgst-framework) | Open scoring methodology — six layers, 100 points, YAML rubric, report template | Run on your system |
| [dli-instrument](https://github.com/CognitiveThoughtEngine/dli-instrument) | Human-side measurement — 10-question cognitive load assessment for AI-augmented workplaces | `pip install dli-instrument` |
| [agentic-governance-papers](https://github.com/CognitiveThoughtEngine/agentic-governance-papers) | Research hub — 5 preprints, 3 drafts, CITATIONS.bib, NIST submissions | Reference |

---

## Proof

- 98 days of live autonomous operation in production
- 56 registered agents, 40 active per cycle
- 64 constitutional amendments ratified through formal process
- NIST CAISI acknowledged in two submissions (800-2 + Agent Identity)
- 5 peer-reviewed preprints on Zenodo
- Self-assessed against CGST framework: **63/100** (ungoverned baseline: 6/100)

---

## Research

| Paper | DOI |
|-------|-----|
| Decision Load Index (DLI) | [10.5281/zenodo.18217577](https://doi.org/10.5281/zenodo.18217577) |
| Constitutional Semantic Governance | [10.5281/zenodo.19162104](https://doi.org/10.5281/zenodo.19162104) |
| Network of Decision (NoD) | [10.5281/zenodo.19195516](https://doi.org/10.5281/zenodo.19195516) |
| Constitutional Governance Harness | [10.5281/zenodo.19343034](https://doi.org/10.5281/zenodo.19343034) |
| Community Security Governance | [10.5281/zenodo.19343108](https://doi.org/10.5281/zenodo.19343108) |

Acknowledged by [NIST CAISI](https://www.nist.gov/artificial-intelligence) (2026).

---

## Contact

Constitutional Governance Review: research@cognitivethoughtengine.com

*The governance architecture in `constitutional-agent` was extracted from live operation of [cognitivethoughtengine.com](https://www.cognitivethoughtengine.com) — a Decision Load Index product running 56 registered agents under constitutional governance.*
