# Cognitive Thought Engine

**Building the WHY governance layer for autonomous AI agents.**

Most AI agent frameworks answer two questions: **WHO** is authorized to act and **HOW** behavior is enforced at runtime. We build the third layer — **WHY** an agent does what it does.

---

## Start Here

- **[constitutional-agent](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance)** — install the package: `pip install constitutional-agent`
- **[WHO vs HOW: the AI agent governance gap](https://www.cteinvest.com/blog/who-vs-how-ai-agent-governance-gap.html)** — the architecture problem this solves
- **[Constitutional Governance Review](https://www.cteinvest.com/blog/constitutional-agent-open-source-why-layer-governance.html#assessment)** — 2-hour assessment, written report, top gaps + roadmap: research@cognitivethoughtengine.com

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

The WHY governance layer for autonomous AI. Six constitutional gates, 12 hard constraints no agent can override, and a self-amendment protocol — extracted from 95 days of live autonomous operation. Self-assessed at **63/100** against the CGST framework (ungoverned baseline: 6/100).

```bash
pip install constitutional-agent
```

[![Tests](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/actions/workflows/tests.yml/badge.svg)](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/actions/workflows/tests.yml)
[![PyPI](https://img.shields.io/badge/pypi-v0.4.0-blue)](https://pypi.org/project/constitutional-agent/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/CognitiveThoughtEngine/constitutional-agent-governance/blob/main/LICENSE)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)

### [cgst-framework](https://github.com/CognitiveThoughtEngine/cgst-framework)

Open scoring methodology for the Constitutional AI Governance Stress Test. Six layers (WHO, HOW, WHY, ECONOMIC, AUTONOMY, INTEGRITY), 100 points, full rubric in YAML and Markdown. Run it on your own agent system before engaging a paid assessment.

### [dli-instrument](https://github.com/CognitiveThoughtEngine/dli-instrument)

The Decision Load Index — a 10-question cognitive load assessment for AI-augmented workplaces. Normative data from 901 users. Validated against the Zenodo preprint.

```bash
pip install dli-instrument
```

### [agentic-governance-papers](https://github.com/CognitiveThoughtEngine/agentic-governance-papers)

Research hub for all published and in-progress work on constitutional AI governance. Five Zenodo preprints, full BibTeX citations, NIST engagement documentation.

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

Constitutional Governance Review: research@cognitivethoughtengine.com

---

*The governance architecture in `constitutional-agent` was extracted from 95 days of live operation of [cognitivethoughtengine.com](https://www.cognitivethoughtengine.com) — a Decision Load Index product running 52 agents under constitutional governance. The product is the applied research context; this library is what we learned.*
