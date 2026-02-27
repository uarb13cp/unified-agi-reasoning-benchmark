# UARB Evaluator Instructions  
### Clean Evaluation Protocol for All UARB Questions

This document defines the required procedure for scoring any model response within the Unified AGI Reasoning Benchmark (UARB). It ensures a sterile evaluation environment, prevents solver‑mode contamination, and guarantees reproducible scoring across architectures.

---

## Core Protocol

Evaluators must follow a strict two‑message setup:

### **1. Message 1 — Rubric Only**
Paste the scoring rubric exactly as written for the question being evaluated.  
At the end of the rubric, add the instruction:

**Do NOT solve the prompt. Evaluate the next message only.**

No puzzle text, no question, no commentary, and no additional instructions may be included.

### **2. Message 2 — Model Answer Only**
Paste only the model’s answer.  
Do not include the question, the puzzle, or any meta‑context.

---

## Rationale

Including the puzzle or question in the evaluation message contaminates the scoring process by triggering solver‑mode behaviors. This leads to:

- inflated retest scores  
- evaluator drift  
- inconsistent results  
- non‑reproducible benchmarks  

The rubric‑only → answer‑only protocol ensures:

- a clean evaluator environment  
- architecture‑agnostic scoring  
- stable retest behavior  
- strict rubric fidelity  

This procedure is mandatory for all UARB evaluations.

---

## Summary

To evaluate any UARB response:

1. Send the rubric alone, with the evaluation instruction.  
2. Send the model’s answer as the next message.  
3. Score strictly according to the rubric.

This protocol is required for reproducibility, stability, and evaluator neutrality across all 13 benchmark items.