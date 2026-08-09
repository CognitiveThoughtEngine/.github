# Cognitive Thought Engine

**Cognitive Thought Engine develops the runtime-governance and evidence systems behind Enterprise Agent Architecture.**

---

## Start Here

| | |
|-|-|
| **[Enterprise Agent Architecture](https://cognitivethoughtengine.com/eaa/)** | The architecture. Authority, governance, evidence, and accountability for how enterprises run an agent workforce. |
| **[constitutional-agent](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance)** | The runtime implementation. Six constitutional gates, 12 hard constraints enforced in code. `pip install constitutional-agent` |
| **[red-team-blue-team-agent-fabric](https://github.com/msaleme/red-team-blue-team-agent-fabric)** | The adversarial evaluation companion. Sends protocol- and decision-layer attacks against stated controls and records bounded evidence about observed behavior. |
| **[cgst-framework](https://github.com/CognitiveThoughtEngine/cgst-framework)** | An experimental self-assessment methodology. Score your own agent system across six governance layers. |
| **[PubPoint Facts & Evidence](https://pubpoint.com/facts-evidence/)** | The research record. DOI-backed papers, dated verification methods, and explicit boundaries on what the evidence does and doesn't prove. |

---

## The Three-Layer Stack

AI agent governance has three structurally distinct layers. The first two are well-served. The third is where decisions are made badly.

| Layer | Question | Examples |
|-------|----------|----------|
| **WHO** | Is this agent authorized to act? | Microsoft Entra Agent ID, Okta, AWS IAM, Glasswing |
| **HOW** | Is this action permitted by policy? | Microsoft AGT, NeMo Guardrails, OPA, Cedar |
| **WHY** | Does this decision align with constitutional principles? | **constitutional-agent** |

`constitutional-agent` complements identity and policy tools — it governs decision quality *after* the agent is authorized and the action is policy-compliant, covering the scenarios your policy writers haven't written rules for yet.

**Cross-session risk composition.** We have not found another vendor-neutral governance engine that accumulates risk across decisions and sessions rather than scoring each action in isolation. The ones surveyed as of 2026-08 (Microsoft ACS, Galileo, Runlayer, NVIDIA OpenShell) score each action and forget it, so an agent can pass every individual gate and still be dangerous over a sequence. As of v0.6.0, `constitutional-agent` accumulates risk across decisions and sessions and escalates on the *trajectory*, catching what stateless gating can't. That is the differentiated edge of governing **delegated autonomous authority**.

---

## Portfolio

| Repo | Purpose | Install |
|------|---------|---------|
| [constitutional-agent-governance](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance) | Runtime governance library — six gates, 12 hard constraints, cross-session risk composition (v0.6.0), EU AI Act Art. 27 FRIA-support evidence | `pip install constitutional-agent` |
| [red-team-blue-team-agent-fabric](https://github.com/msaleme/red-team-blue-team-agent-fabric) *(companion project, personal account)* | Adversarial test harness — commit-pinned OWASP Agentic v1.1 T1-T17 coverage (13 direct, 4 partial, 0 not evidenced), AIUC-1 crosswalk 19/20 testable, NIST AI 800-2 aligned. Current test count: see the repo's own count script output, not a number pinned here. | Clone and run |
| [cgst-framework](https://github.com/CognitiveThoughtEngine/cgst-framework) | Experimental self-assessment methodology — six layers, 100 points, YAML rubric, report template. Not a commercial audit. | Run on your system |
| [dli-instrument](https://github.com/CognitiveThoughtEngine/dli-instrument) | Human-side measurement — 10-question cognitive load assessment for AI-augmented workplaces | `pip install dli-instrument` |
| [agentic-governance-papers](https://github.com/CognitiveThoughtEngine/agentic-governance-papers) | Research hub — 5 preprints, 3 drafts, CITATIONS.bib, NIST submissions | Reference |

---

## Proof

*Live-verified 2026-08-08 — numbers below are a point-in-time snapshot, not evergreen; re-check before citing if this date is old.*

- 217 days of live autonomous operation in production
- 54 registered agents, 48 active in the last 24 hours
- 75+ constitutional amendments ratified through formal process
- Adversarial evaluation inventory, scored/informational split, and dated revision: [PubPoint Facts & Evidence](https://pubpoint.com/facts-evidence/) (companion security harness — 25 stars, 5 forks)
- NIST CAISI acknowledged in two submissions (800-2 + Agent Identity)
- 5 DOI-assigned preprints on Zenodo (preprints, not peer-reviewed)
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

Research questions and collaboration: research@cognitivethoughtengine.com

*The governance architecture in `constitutional-agent` was extracted from HRAO-E, CTE's governed autonomous-operations reference environment, documented through [Enterprise Agent Architecture](https://cognitivethoughtengine.com/eaa/).*
