# Cognitive Thought Engine

**Building the WHY governance layer for autonomous AI.**

---

## The Three-Tier Problem

Most autonomous AI work focuses on identity and behavior. The third tier — constitutional self-governance — is unsolved.

| Tier | Question | Examples |
|------|----------|---------|
| **WHO** | Identity and access — who is this agent, is it authorized? | Glasswing, OpenAI API keys, OAuth |
| **HOW** | Behavioral policy — what is the agent allowed to do? | NeMo Guardrails, AGT, Constitutional AI |
| **WHY** | Constitutional self-governance — does the agent know when to stop, learn from failure, and preserve runway? | **This is the gap we are filling.** |

WHO and HOW have mature tooling. WHY does not.

An agent can be fully authenticated (WHO) and policy-compliant (HOW) while still burning 30 API cycles on a shadow-banned channel, running on a broken payment pipeline for weeks, or locking into a failed strategy with zero documented lessons. These are WHY failures.

---

## What We Build

### [constitutional-agent-governance](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance)

A Python library that gives autonomous agents a six-gate constitutional framework: Epistemic, Risk, Governance, Economic, Autonomy, and Constitutional gates. Each gate answers part of the WHY question.

```bash
pip install constitutional-agent
```

The library is grounded in a real production system: a Level 4 autonomous organization (38 agents, 11 cron jobs, live since 2026-01-04) that has processed 883 signups and runs governance cycles continuously.

**Case study:** [What constitutional governance would have caught in the AgentHustler 200-run experiment](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/blob/main/examples/agenthustler_audit.md) — $6.74 earned after 200 runs, 4 failure modes, each maps to a specific gate.

---

## Research

Five preprints on the theory and practice behind this work:

| Paper | DOI |
|-------|-----|
| Deliberate Learning Infrastructure (DLI) | [10.5281/zenodo.18217577](https://doi.org/10.5281/zenodo.18217577) |
| Constitutional Self-Governance (CSG) | [10.5281/zenodo.19162104](https://doi.org/10.5281/zenodo.19162104) |
| Nodes of Dependency (NoD) | [10.5281/zenodo.19195516](https://doi.org/10.5281/zenodo.19195516) |
| Governance Harness | [10.5281/zenodo.19343034](https://doi.org/10.5281/zenodo.19343034) |
| Community Security in Autonomous Systems | [10.5281/zenodo.19343108](https://doi.org/10.5281/zenodo.19343108) |

NIST engagement: submitted comments to NIST 800-2 and the CAISI Agent Identity framework (March 2026). The constitutional-agent library is the concrete implementation artifact referenced in those submissions.

---

## Product

The governance framework is also the engine behind [CTE Invest](https://cteinvest.com) — a burnout diagnostic tool that gives individuals a Deliberate Learning Index score and a structured return path.

Writing on autonomous AI governance, the Constitutional Enterprise model, and the WHO/HOW/WHY thesis: [cognitivethoughtengine.com/blog](https://cognitivethoughtengine.com/blog)

---

*Cognitive Thought Engine LLC — Texas. Michael Saleme, Sole Member.*
