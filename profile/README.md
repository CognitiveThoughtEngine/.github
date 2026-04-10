# Cognitive Thought Engine

**Building the WHY governance layer for autonomous AI agents.**

Most AI agent frameworks answer two questions: **WHO** is authorized to act and **HOW** behavior is enforced at runtime. We build the third layer — **WHY** an agent does what it does.

---

## Start Here

- **[constitutional-agent](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance)** — install the package: `pip install constitutional-agent`
- **[WHO vs HOW: the AI agent governance gap](https://www.cteinvest.com/blog/who-vs-how-ai-agent-governance-gap.html)** — the architecture problem this solves
- **[Constitutional Governance Review](https://www.cteinvest.com/blog/constitutional-agent-open-source-why-layer-governance.html#assessment)** — 2-hour assessment, written report, top gaps + roadmap: mike@cognitivethoughtengine.com

---

## The Three Layers

AI agent governance has three structurally distinct layers. The first two are well-served. The third is where decisions are made badly.

| Tier | Question | Tools | What the layer can't address alone |
|------|----------|-------|-------------------------------------|
| **WHO** | Is this agent authorized to act? | Microsoft Entra Agent ID, Okta, AWS IAM, Glasswing | Authorization doesn't evaluate whether an authorized agent's decision is sound |
| **HOW** | Is this action permitted by policy? | Microsoft AGT, NeMo Guardrails, OPA, Cedar | Policy enforcement covers scenarios administrators wrote rules for — not novel ones |
| **WHY** | Does this decision align with constitutional principles? | **constitutional-agent** | — |

WHO governance gets the agent through the door. HOW governance enforces the rules on the books. Neither asks whether the decision is *right* — aligned with the organization's mission, economic survival, and foundational values. That's the WHY layer.

`constitutional-agent` works alongside identity and policy tools, not instead of them. Use Okta or Entra for WHO, OPA or Cedar for HOW, and constitutional-agent for the governance layer above both.

---

## Open Source

### [constitutional-agent-governance](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance)

The WHY governance layer for autonomous AI. Six constitutional gates, 12 hard constraints no agent can override, and a self-amendment protocol — extracted from 95 days of live autonomous operation.

```bash
pip install constitutional-agent
```

[![Tests](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/actions/workflows/tests.yml/badge.svg)](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/actions/workflows/tests.yml)
[![PyPI](https://img.shields.io/badge/pypi-v0.4.0b3-blue)](https://pypi.org/project/constitutional-agent/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/blob/main/LICENSE)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)

---

## Proof

- 95 days of live autonomous operation in production
- 52 agents/cycle operating under constitutional governance
- 64 constitutional amendments ratified through formal process
- NIST CAISI acknowledged in two submissions (800-2 + Agent Identity)
- 5 peer-reviewed preprints published on Zenodo

---

## Research

| Paper | DOI |
|-------|-----|
| Decision Load Index (DLI) Framework | [10.5281/zenodo.18217577](https://doi.org/10.5281/zenodo.18217577) |
| Constitutional Semantic Governance (CSG) | [10.5281/zenodo.19162104](https://doi.org/10.5281/zenodo.19162104) |
| Network of Decision (NoD) | [10.5281/zenodo.19195516](https://doi.org/10.5281/zenodo.19195516) |
| Constitutional Governance Harness Design | [10.5281/zenodo.19343034](https://doi.org/10.5281/zenodo.19343034) |
| Community Security Governance | [10.5281/zenodo.19343108](https://doi.org/10.5281/zenodo.19343108) |

---

## Contact

Constitutional Governance Review: mike@cognitivethoughtengine.com

---

*Also: [cognitivethoughtengine.com](https://www.cognitivethoughtengine.com) — DLI cognitive measurement product, 883+ users.*
