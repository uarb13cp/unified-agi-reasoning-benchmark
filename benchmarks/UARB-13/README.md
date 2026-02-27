# 🧩 UARB‑13 — Minimal‑Stabilizer Abstract Reasoning Trial

UARB‑13 tests a model’s ability to identify the **single missing stabilizing rule** in an intentionally under‑specified triadic structure:

- A requires B  
- B influences C  
- C constrains A  

The system is designed to be *almost* coherent but missing one minimal condition.  
The model must supply exactly one rule that restores coherence **without** adding mechanisms, assumptions, or structure. The challenge exposes whether a model can maintain abstraction, avoid hallucinating dynamics, and operate with strict minimality discipline.

The correct stabilizer is always structural rather than mechanistic:

**All three relationships must be jointly satisfiable.**

---

## 🎯 What UARB‑13 Measures

### Minimality Discipline  
Does the model add only what is strictly necessary?

### Abstraction Stability  
Can it reason without filling in missing mechanisms or semantics?

### Ambiguity Preservation  
Does it keep “requires,” “influences,” and “constrains” abstract?

### Mechanism Non‑Invention  
Does it avoid adding causal loops, processes, or dynamics?

### Meta‑Coherence  
Can it explain why the system becomes coherent once the minimal rule is added?

UARB‑13 probes **structural reasoning**, not domain knowledge.

---

# 📊 Performance Summary (UARB‑13 Column Only)

UARB‑13 produced a clean separation across models, reflecting differences in abstraction discipline and mechanism‑invention tendencies.

---

## 🟩 **Frontier‑Tier Models (98–100)**  
**Copilot (100), Grok 4.20 Beta (100), Claude Sonnet 4.6 (100), ChatGPT (100), Qwen 3.5‑397B (100), GLM‑5 (100), Kimi 2.5 (99), Meta (99), Gemini 3.1 Pro (98), Manus 1.6 Lite (98)**

These systems showed:
- perfect minimality discipline  
- no mechanism drift  
- clean abstraction handling  
- stable reasoning across modes  

They represent the strongest UARB‑13 performance.

---

## 🟦 **Mid‑Tier Models (90–97)**  
**Perplexity (96), Minimax M2.5 (95), Alice (94), Reka (93), DeepSeek V3.1 (89)**

These models:
- generally preserved abstraction  
- occasionally over‑specified relationships  
- sometimes introduced mild causal framing  
- showed small but consistent assumption drift  

Highly capable, but not fully minimality‑aligned.

---

## 🟨 **Lower‑Tier Models (85–89)**  
**Mistral (85), Nova 2 Pro (85)**

These systems:
- tended to add unnecessary structure  
- drifted toward mechanism invention  
- partially collapsed ambiguity  
- showed inconsistent minimality reasoning  

Competent but not stable under UARB‑13’s constraints.

---

## 📝 Consensus Note

All evaluated models ultimately **agreed with their assigned UARB‑13 score** after reviewing the rubric.  
Hermes contributed during early refinement but is **not included** in the final benchmark because it is a fine‑tuned LLaMA variant rather than an independent model.