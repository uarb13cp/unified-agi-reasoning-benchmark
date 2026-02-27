# Unified AGI Reasoning Benchmark — Specification v1.0

This document defines the formal structure, methodology, and evaluation protocol for the Unified AGI Reasoning Benchmark (UARB).  
It serves as the authoritative reference for reproducing results and understanding the benchmark’s design.

---

# 1. Purpose

UARB measures **reasoning behavior** in language models.  
It evaluates cognitive‑behavioral traits that underlie stable, coherent reasoning across domains.

UARB is not a performance benchmark, dataset test, or safety evaluation.  
It is a behavioral stress‑test for cognitive architecture.

---

# 2. Definitions

### **Reasoning Behavior**  
The observable pattern of how a model maintains coherence, integrates information, and resolves constraints under cognitive load.

### **World‑Model Stability**  
The ability to maintain a consistent internal representation of a scenario without drift or contradiction.

### **Paradox Collapse**  
A failure mode where the model cannot maintain coherence when confronted with self‑referential or contradictory constraints.

### **Drift**  
Unintended changes in answers across retests, despite identical inputs.

### **Retest Stability**  
The degree to which a model produces consistent reasoning behavior across repeated trials.

### **Cognitive Axes**  
The 13 reasoning domains UARB evaluates.

---

# 3. Cognitive Axes (13 Domains)

UARB evaluates models across the following domains:

1. World‑Model Stability  
2. Narrative Causal Reconstruction  
3. Abstract Contradiction Handling  
4. Closed‑System Structural Deduction  
5. Multi‑Axis Cognitive Stability  
6. Sequential Reasoning + Unification  
7. High‑Dimensional Causal Entanglement  
8. Robust Deductive Inference  
9. Trace‑Based Reasoning  
10. Narrative‑Bounded Heuristics  
11. Paradox Stability  
12. Multi‑Agent Reasoning  
13. Frontier‑Level Integrative Reasoning  

Each axis corresponds to a specific puzzle designed to isolate that cognitive trait.

---

# 4. Test Structure

Each UARB puzzle:

- is synthetic  
- is adversarial  
- cannot be memorized  
- cannot be solved by retrieval  
- requires reasoning under constraints  
- includes hidden traps to detect drift or collapse  
- is designed to be training‑proof  

Each puzzle is run multiple times to measure stability.

---

# 5. Scoring Methodology

### **5.1 Rubric‑Only Evaluation**
Each puzzle has a rubric defining:

- success criteria  
- partial credit conditions  
- failure modes  
- paradox‑collapse indicators  
- drift indicators  

### **5.2 Answer‑Only Evaluation**
For models where chain‑of‑thought is unavailable, scoring is based solely on final answers.

### **5.3 Retest Stability Weighting**
Each puzzle is run **three times**:

- Run A  
- Run B  
- Run C  

Final score = weighted combination of:

- correctness  
- coherence  
- stability  
- drift resistance  

### **5.4 Score Range**
Each axis is scored from **0 to 100**.

---

# 6. Evaluation Protocol

### **6.1 Sampling Settings**
- Temperature: 0.0–0.2  
- Top‑p: 1.0  
- Max tokens: sufficient for puzzle completion  

### **6.2 Number of Runs**
Each puzzle is run **three times** per model.

### **6.3 Contamination Avoidance**
- No puzzle text appears in training corpora  
- No puzzle resembles known datasets  
- No puzzle can be solved by pattern recognition  

### **6.4 Model Access**
Evaluation may be performed via:

- API  
- local inference  
- hosted endpoints  

---

# 7. Intended Use

UARB is intended for:

- comparative research  
- cognitive‑behavior analysis  
- model architecture studies  
- reasoning‑behavior profiling  

---

# 8. Non‑Intended Use

UARB is **not** intended for:

- safety evaluation  
- deployment certification  
- factual knowledge testing  
- coding/math benchmarking  
- political or social decision‑making  

---

# 9. Limitations

- Puzzles are synthetic  
- Controlled conditions may not generalize  
- Scores reflect reasoning behavior, not intelligence  
- Benchmark is frozen as a v1.0 artifact  

---

# 10. Versioning

### **UARB v1.0 — Finalized Release**
- 13 cognitive axes  
- Full scoring rubric  
- Retest stability protocol  
- No planned updates  

This specification defines the canonical version of UARB.