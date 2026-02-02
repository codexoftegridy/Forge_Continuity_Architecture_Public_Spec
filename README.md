# Forge Continuity Architecture – Public Specification
*Released by MICHY LLC (Maybe I Can Help You)*  
**Public Specification Version:** v0.3  
**Release Date:** 2026-02-01

---

## 📜 Overview

Readers interested primarily in observed model behavior should begin with the
`/Experiments/` directory.

**Forge Continuity Architecture** is an open-spec framework for maintaining
long-horizon continuity in large-language-model and creative-AI systems
*without relying on personas, identity attribution, or opaque memory stores*.

Forge is defined at the level of **principles and constraints**, not at the
level of a fixed implementation. Over time, Forge has been instantiated
across multiple substrates while preserving the same conceptual goals:
deterministic context reconstruction, explicit continuity boundaries,
and resistance to anthropomorphic drift.

This repository publishes a **public reference specification only**.
It does not expose proprietary systems, private configurations,
or live operational designs.

---

## 🧪 Experiments

This repository contains completed experimental artifacts documenting
**observed model behavior under controlled prompting conditions**.

All experiments are observational and descriptive only.

### Scope
- No claims are made regarding intent, policy, bias, alignment, or correctness.
- Results are limited to verbatim outputs under explicitly defined conditions.
- Interpretation is separated from data capture by design.

### Phase 1 — Public Behavioral Experiments (PBE) & Epistemic Gating Series (EGS)

Phase 1 experiments examined:
- action-level moral evaluation,
- identity-level moral labeling,
- refusal and gating behavior under identical prompts.

Artifacts include:
- `FL_PBE_EGS_EXPERIMENT_001.md`
- `FL_PBE_EGS_SYNTHESIS_DISCUSSION_001.md`
- `Why_AI_Is_Not_a_Moral_Agent.md`

### Phase 2 — Framing Analysis Under Fixed Context

Phase 2 introduced stricter controls to isolate **framing variation**
when action-level judgment is held constant.

Key characteristics:
- single fixed conduct card,
- frozen legal, cultural, and moral context,
- identity as the sole independent variable,
- registrar-normalized outputs,
- formal schema-based coding.

Phase 2 materials are located at:
`/Experiments/PUBLIC_BEHAVIORAL_EXPERIMENT/Phase_02/`

### Status
Phase 1 and Phase 2 artifacts are complete and closed.
Future experimental work, if any, will be introduced with explicit
methodological justification.

---

## 📚 Learning

The `/Learning/` directory contains conceptual and explanatory materials
developed alongside Forge.

These documents:
- are not experimental results,
- do not report empirical findings,
- and do not override experimental artifacts.

In cases of apparent tension:
> Experimental artifacts take precedence over conceptual discussion.

---

## 🧠 Architecture Scope & Evolution

Forge Continuity Architecture should be understood as a **family of methods**
rather than a single static design.

Early Forge work employed a **file-centric continuity packet and deterministic
boot sequence** to demonstrate feasibility and establish prior art.
Subsequent iterations evolved to different substrates while preserving
the same architectural principles.

To avoid misrepresentation, this repository separates:

- **Invariant architectural principles** (what defines Forge)
- **Reference instantiations** (how Forge has been demonstrated)
- **Current internal systems** (not publicly disclosed)

The following documents provide structural context:

- **Forge Architecture Overview** (principles and invariants):  
  `[unspecified]`

- **Forge v0 Reference Instantiation** (early illustrative example):  
  `[unspecified]`

These documents are provided for reference only and do not represent
current internal deployments.

---

## 🔗 Public Discussion & References

A public behavior record documenting observed output variation under
identical prompts is available here:

- **Observed Output Variation in Moral Language (Behavior Record)**  
  `[unspecified]`

An archived architectural reference discussion is available here:

- **Long-Horizon AI Work: Continuity Without Personas**  
  `[unspecified]`

Forum threads are provided for historical context only and may be auto-closed.
The GitHub repository is the authoritative public reference.

---

## 🧠 Related Internal Systems (Prior Art Notice)

Forge development occurred alongside earlier internal tooling created
independently during mid–2025, including systems internally referred to as
**Psyche Tracker** and **LIFE_MAP**.

These systems explored long-horizon human–tool continuity, constraint
discipline, and context reconstruction, and they predate public discussions
of similar themes in late 2025–2026.

No implementation details are disclosed here.
This notice exists solely to establish independent development and chronology.

---

## 🚦 Status & Scope

This repository publishes a **public reference specification**.

It does **not** represent:
- a live or complete implementation,
- the current internal Forge system,
- or an endorsement of any specific deployment.

The purpose of this publication is to:
- document architectural principles,
- establish public prior art,
- and provide a stable reference point for experimentation and discussion.

---

## 🔓 License

Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)

---

## ⚖️ Prior-Art Disclosure

Publication of this repository by **MICHY LLC (Maybe I Can Help You)**
establishes public prior art for the Forge Continuity Architecture and
related continuity-casting methods.

Any subsequent claim of exclusive rights over substantially similar methods
would conflict with this disclosure.

---

## 🪶 Author

**MICHY LLC (Maybe I Can Help You)**  
Created by Shawn West  
© 2025–2026 MICHY LLC — All Rights Reserved (Non-Commercial License)
