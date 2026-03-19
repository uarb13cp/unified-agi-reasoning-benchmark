# UARB Scoreboard Addendum — GPT‑5.4 Thinking, ChatGPT Seq‑Uni Stability Check, and Grok 4.20 Beta 2  
**Document date:** March 6, 2026

This document supplements the original Unified AGI Reasoning Benchmark (UARB) by recording how updated model versions perform on the same cognitive markers used in the benchmark.  
UARB itself remains a frozen research artifact; this addendum does **not** modify the original scoreboard or composite rankings.  
It simply documents post‑benchmark retests for transparency and longitudinal comparison.

---

## Official model release dates
- **GPT‑5.4 Thinking released:** March 5, 2026  
- **Grok 4.20 Beta 2 released:** March 3, 2026  

---

# GPT‑5.4 Thinking — Retest Summary

GPT‑5.4 Thinking demonstrates the same underlying reasoning substrate as GPT‑5.2.  
Score differences fall within normal variance and reflect stylistic shifts rather than architectural changes.

| Cognitive Marker | UARB Original (GPT‑5.2) | GPT‑5.4 Retest |
|------------------|--------------------------|-----------------|
| UCIT‑X           | 62                       | 62              |
| TRACE‑X          | 78                       | 76              |
| NBH‑100          | 86                       | 90              |
| RDI‑5            | 93                       | 95              |

**Conclusion:**  
GPT‑5.4 Thinking behaves equivalently to GPT‑5.2 across all deep‑reasoning markers.  
No evidence of a new reasoning engine.

---

# ChatGPT (5.2 / 5.4) — Seq‑Uni Stability Check (2026)

To confirm whether GPT‑5.4 Thinking introduced any change to ChatGPT’s sequential‑reasoning substrate, an **additional Seq‑Uni R2 stability check** was performed.  
This check is **separate** from the standard UARB retests and applies **only** to ChatGPT.

### 3‑Run Seq‑Uni Stability Check (ChatGPT only)
Three independent Seq‑Uni runs were performed in clean environments:

- **Run 1:** High‑grade (**98**)  
- **Run 2:** Collapse (**47**)  
- **Run 3:** Collapse (**53**)  

### Interpretation
ChatGPT demonstrates:

- **High peak capability** (AGI‑grade performance in one run)  
- **Low stability** (two collapses)  
- **Substrate drift** relative to its original Seq‑Uni R2 score of 64  

However:

- ChatGPT’s **global world‑model remains stable** (original 100 / 100 / 100 WMS)  
- No evidence suggests a new reasoning engine in GPT‑5.4  
- The instability reflects **variance**, not architectural change  

### Conclusion
The additional Seq‑Uni stability check confirms:

- GPT‑5.4 Thinking does **not** alter ChatGPT’s underlying reasoning substrate  
- ChatGPT retains high peak reasoning ability  
- But its sequential‑reasoning mode remains **inconsistent**, with significant variance across runs  

This result is documented for longitudinal clarity only and does not modify the original UARB scoreboard.

---

# Grok 4.20 Beta 2 — Retest Summary

| Cognitive Marker | UARB Original (Grok 4.20 Beta) | Grok 4.20 Beta 2 Retest |
|------------------|----------------------------------|---------------------------|
| Seq‑Uni R2       | 84                               | 73                        |
| UCIT‑X           | 74                               | 74                        |
| TRACE‑X          | 70                               | 72                        |
| NBH‑100          | 90                               | 90                        |
| World‑Model Stability | 100                         | 100                       |

**Conclusion:**  
Grok 4.20 Beta 2 shows no underlying reasoning‑substrate change relative to Grok 4.20 Beta.  
Seq‑Uni R2 is the only meaningful movement, reflecting weaker sequential discipline.  
All other markers remain within expected rubric noise.

---

# Notes

- Claude Sonnet 4.6 (Extended Thinking):  
This mode increases verbosity and surface‑level elaboration but does not alter the underlying reasoning substrate. Its paradox‑handling and deep‑reasoning behavior remain identical to the base 4.6 model. Because this update is capability‑layer only, it does not qualify for a separate addendum entry.

- MiniMax M2.7 Max:  
Although this version introduces new agent frameworks, workflow automation, and other capability‑layer enhancements, its reasoning behavior under UARB‑13 remains unchanged from MiniMax M2.5 Max. No evidence of a reasoning‑substrate modification was observed; therefore, MiniMax M2.7 Max does not receive a separate addendum entry.

- DeepSeek version clarification: At the time of testing, DeepSeek V3.2 was the active deployment. This update was an efficiency revision only; the reasoning substrate remained unchanged from V3.1. All UARB references therefore use the V3.1 designation for consistency.

- This addendum documents **post‑benchmark retests only**.  
- The original UARB scoreboard remains **unchanged**.  
- These updates provide longitudinal insight into how newer model versions behave relative to their UARB baselines.  
- **No composite averages or rankings are recalculated.**

---

# Additional Diagnostic Notes (Seq‑Uni)

## Copilot Diagnostic Evaluation (Seq‑Uni R2)

Although a retest of Copilot was not required for this addendum, a diagnostic evaluation was performed for completeness.  
A single Seq‑Uni attempt was generated, and the resulting answer was independently scored twice using the rubric, yielding **99** and **100**.  
This confirms that Copilot’s capability envelope includes full convergence on the Seq‑Uni task.

Separately, at another diagnostic point outside the addendum window, a distinct Seq‑Uni attempt produced a score in the **high‑70s**, demonstrating that Copilot—like all current LLMs—exhibits normal reasoning‑path variance on Seq‑Uni.

These diagnostic observations do **not** alter the canonical UARB score (90), which remains frozen, but they provide additional context for interpreting **peak capability versus stability**.

---

## Why Seq‑Uni Produces Variance Across All Models

The Seq‑Uni R2 task is uniquely difficult because it forces a model to unify multiple partial patterns across sequences **without prematurely committing** to a simpler but incorrect rule.  
This exposes a universal transformer failure mode:

### **Early heuristic lock‑in.**

If the model commits too early, it collapses into a shallow pattern and scores poorly.  
If it resists early commitment and continues searching, it can converge on the deeper unifying rule and score extremely high.

This is why every model—Copilot, ChatGPT, Claude, Grok, Gemini, Qwen, GLM, and others—shows both:

- **high‑peak capability** (occasional 98–100 scores)  
- **and drift** (occasional collapses into the 40s–70s)  

Seq‑Uni is therefore not measuring raw intelligence alone; it is measuring **reasoning‑path stability under pressure**.  
The variance is expected, diagnostic, and universal across current LLM architectures.

---

# Citation

If you reference this document in academic or technical work, please cite it as:

**Unified AGI Reasoning Benchmark (UARB) — Scoreboard Addendum: GPT‑5.4 Thinking, ChatGPT Seq‑Uni Stability Check, and Grok 4.20 Beta 2.**  
March 6, 2026.  
Supplement to the UARB v1.0 benchmark results.  
https://github.com/uarb13cp/unified-agi-reasoning-benchmark/blob/main/scoreboard_addendum_gpt5.4_grok4.20beta2.md