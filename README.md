# Architectural Stabilization of LLM Output Under Behavioral Prompt Variation

### KSU C-Day · Spring 2026 · Masters Research
**Crystal Tubbs** · MSAI, Kennesaw State University · Big Data Analytics · Advisor: Dr. Martin Brown

---

## 🌐 View the live site

# → **[msmetamorphosis.github.io/C_Day_Spring26](https://msmetamorphosis.github.io/C_Day_Spring26/)** ←

*The full research presentation, live dashboards, and project portfolio.*

---

## The thesis in one sentence

LLM failures in enterprise settings are not a model problem. They are an **architecture problem** — and a `generate → critique → validate → repair` loop achieves **100% schema compliance** across every prompt style tested, where baseline systems collapse.

---

## What you'll find on the site

**The research** — the conjecture, the method, the finding, and an interactive walkthrough of the four-stage reliability pipeline that proved structural intervention beats fine-tuning.

**The live reliability dashboard** — bring your own Anthropic API key, pick a system, pick a task, pick the prompt styles, and watch real Python execute on the backend and stream schema compliance, parse rate, latency, and total runs back in real time. Reproduce the finding yourself.
→ [msmetamorphosis.github.io/llm-reliability-dashboard](https://msmetamorphosis.github.io/llm-reliability-dashboard/)

**CRAFT** — the operationalization. The same research thesis, shipped as a working prompt coach. Paste any enterprise prompt; CRAFT classifies the task, audits the prompt against a task-weighted rubric, rewrites it, and scores the output side by side.
→ [msmetamorphosis.github.io/CRAFT](https://msmetamorphosis.github.io/CRAFT/)

**CHRYSALIS** — where this research is heading. The same structural-intervention thesis, extended one layer deeper — into the belief state of autonomous agents, with on-chain attestation, metacognitive intervention, and regulatory-ready provenance.
→ [chrysalisai.io](https://www.chrysalisai.io/)

**Other research** — three projects on the same through-line: bias that evades audit (CIPHER), accountability that evades policy (SAF), screening behavior that evades scrutiny (PRISM).

---

## The headline result

| System | Description | Schema compliance across all prompt styles |
|---|---|---|
| Baseline A | Naive direct LLM | **0%** |
| Baseline B | Retrieval-augmented | **0%** |
| **Reliability pipeline** | **Generate → critique → validate → repair** | **100%** |

Baseline A showed a **100-point compliance gap** between structured and casual prompts despite a 100% JSON parse rate — proving the failure is silent and style-driven. The reliability pipeline closed it without fine-tuning, without retraining, and without touching the model.

---

## The four-stage pipeline

```
   ┌──────────────┐
   │  1. Generate │   produce candidate
   └──────┬───────┘
          ↓
   ┌──────────────┐
   │  2. Critique │   audit against task criteria
   └──────┬───────┘
          ↓
   ┌──────────────┐
   │  3. Validate │   enforce structural contract
   └──────┬───────┘
          ↓
   ┌──────────────┐
   │  4. Repair   │   targeted correction before return
   └──────┬───────┘
          ↓
       100% ✓
```

---

## How to navigate this repository

This repo contains the static GitHub Pages site for the C-Day presentation. The actual research code, datasets, and experiment runners live in the linked dashboards above.

```
C_Day_Spring26/
├── index.html          → the full presentation site
└── assets/
    ├── reliability-dashboard.png
    ├── craft-dashboard.png
    ├── chrysalis-logo.png
    └── crystal.jpg
```

---

## About the researcher

I'm an MSAI candidate at Kennesaw State University and the founder of **Metamorphic Curations**, an AI transformation consultancy. My research sits at the intersection of LLM behavior, AI fairness, and governance — the parts of the field where the metric doesn't match reality, and where the fix has to be structural.

→ [metamorphiccurations.com](https://www.metamorphiccurations.com) · [github.com/Msmetamorphosis](https://github.com/Msmetamorphosis) · [CHRYSALISAI.io](https://chrysalisai.io)  · [NextMission Navigator](https://www.VetNavi.ai)

---

*Make it a great day.*
