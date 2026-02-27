# How to Interpret UARB Scores

The Unified AGI Reasoning Benchmark (UARB) evaluates reasoning behavior, not performance.  
This document explains how to correctly interpret the scores produced by the benchmark and how to avoid common misreadings.

---

## 1. What High Scores Mean

A high score on UARB indicates that a model demonstrates:

- **Stable reasoning behavior** under cognitive load  
- **Coherent world‑model maintenance** across steps  
- **Low drift** across retests  
- **Strong paradox tolerance**  
- **Reliable sequential reasoning**  
- **Cross‑domain integration**  
- **Consistent identity and perspective**  
- **Robust multi‑agent reasoning**  

High‑scoring models tend to behave predictably and coherently in complex reasoning scenarios.

---

## 2. What Low Scores Mean

A low score indicates that a model exhibits one or more of the following:

- **World‑model collapse**  
- **Contradictions or self‑inconsistency**  
- **Paradox failure**  
- **Reasoning drift** across retests  
- **Sequential breakdown**  
- **Inability to integrate clues**  
- **Perspective instability**  
- **Multi‑agent reasoning failure**  

Low scores do not imply the model is “bad” — only that its reasoning behavior is unstable under UARB conditions.

---

## 3. What UARB Scores Do *Not* Mean

UARB does **not** measure:

- intelligence  
- safety or alignment  
- factual accuracy  
- coding or math skill  
- real‑world reliability  
- model usefulness in all domains  
- deployment readiness  

A model can score high on UARB and still fail at tasks requiring knowledge, safety, or specialized skills.  
A model can score low on UARB and still perform well on traditional benchmarks.

---

## 4. How to Compare Models

When comparing models:

- **Look at patterns**, not just totals  
- Identify **strengths and weaknesses** across the 13 axes  
- Compare **reasoning signatures**, not raw scores  
- Consider **retest stability** as a major factor  
- Avoid over‑interpreting small numerical differences  

UARB is designed to reveal *architectural differences*, not to crown a single “winner.”

---

## 5. Why Retest Stability Matters

UARB includes repeated trials to detect drift.  
This is intentional.

- A model that scores **90 → 40 → 95** is unstable  
- A model that scores **70 → 72 → 69** is far more reliable  

Consistency is a core indicator of reasoning integrity.

---

## 6. Summary

UARB scores should be interpreted as indicators of **reasoning behavior**, not general intelligence or capability.  
They reveal how a model thinks, not what it knows.

Use UARB scores to understand:

- reasoning stability  
- cognitive architecture  
- behavioral coherence  
- failure modes  

Do **not** use them as a universal measure of model quality or safety.