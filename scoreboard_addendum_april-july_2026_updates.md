| Model | Movement | Score |
|-------|----------|--------|
| Meta → Muse Spark | #9 → #13 | 42.0 |
| GLM‑5 → GLM‑5.1 | #7 → #17 | 72.7 |
| Indus | #19 | 51.3 |
| Nova 2 Pro → Nova Premier | #17 → #18 | 50.3 |
| Kimi K2.5 → Kimi K2.6 | #8 → #16 | 68.7 |
| MiMo‑V2‑Pro → MiMo‑V2.5‑Pro | #14 → #19 | 61.5 |
| ChatGPT‑5.2 → 5.5 Thinking | #4 → #4–5 | ≈93.5 |
| DeepSeek V3.2 → DeepSeek V4 | #16 → #12 | ~89.0 |
| Qwen 3.5 → Qwen 3.6 Max | #5 → #11 | 76.8 |
| Mistral Medium 3.1 → Mistral Medium 3.5 | #15 → #18 | 75.8 → ~72.0 |
| ERNIE X1.1 → ERNIE 5.1 Thinking | #15 → #10 | 86.5 |
| Qwen 3.6 Max → Qwen 3.7 Max | #11 → #15 | 71.4 |
| Gemini 3.1 Pro → Gemini 3.5 Thinking | #9 → #14 | ≈57.0 |
| MiniMax M2.5 → MiniMax M3 | #13 → #14 | 82.9 → ~83.1 |
| Nemotron 3 Ultra | #14 | 69.8 |
| GLM‑5.1 → GLM‑5.2 | #17 → #17 | 70.3 |
| DeepSeek V4 → DeepSeek V4‑Pro | #12 → #6–7 | ≈91.0 → ≈92.0 |
| Claude Sonnet 4.6 → Claude Sonnet 5 | #3 → #3–4 | 95.8 |
| Lumo 2.0 | #18 | ≈63.4 |
| Meta Muse Spark 1 → Muse Spark 1.1 | #13 → #6–7 | ≈91.0 |
| Agnes 2.5 Flash | #11–12 | ≈84.0 |
| Qwen 3.7‑Max → Qwen 3.8‑Max | #15 → #17 | 69.8 |
| Gemini 3.1 Pro → Gemini 3.6 Flash Thinking | #9 → #10–11 | ≈87.0 |
| Alice AI | #15 → #16–17 | ≈76–78 |


---

# Addendum Overview

This addendum records post‑release updates to major models as they appear throughout 2026. Each entry documents capability changes and any shifts in behavior relevant to UARB‑style diagnostics. These notes do not alter the original scoreboard; they maintain longitudinal clarity as models evolve.

The projected rankings in this addendum are derived from each model’s demonstrated reasoning‑substrate behavior rather than full UARB retesting. Because the substrate signatures of these models are stable and diagnostic‑consistent, their relative positions can be inferred directly from their structural reasoning patterns, paradox‑handling profiles, assumption‑discipline characteristics, and multi‑agent coherence. Full benchmark execution is therefore unnecessary to determine their expected placement within the UARB hierarchy; the reasoning‑substrate deltas alone are sufficient to project their comparative ranking with high confidence.

---

# Meta AI (Muse Spark) — Diagnostic Summary (April 9, 2026)

Muse Spark adds multimodal input, tool‑use, and new “Thinking”/“Contemplating” modes, but all modes run on the same underlying substrate. Under UARB probes, Muse Spark reproduces the same structural reasoning failures seen in Meta’s February models: paradox collapse, operator‑trap lock‑in, assumption drift, and weak unification discipline. Increased verbosity does not improve reasoning integrity.

### Original Benchmark Scores
- **UCIT‑X:** 34  
- **Seq‑Uni R2:** 58  
- **TRACE‑X:** 64  

### Benchmark Results (Diagnostic Only)
- **UCIT‑X:** 40  
- **Seq‑Uni R2:** 66  
- **TRACE‑X:** 20  

### Interpretation
Capability‑layer expansion without substrate‑level change.

---

# GLM‑5.1 — Diagnostic Summary (April 10, 2026)

GLM‑5.1 introduces formatting and strategy‑declaration refinements, but UARB probes show no change to its underlying reasoning substrate. The model repeats the same structural failures seen in GLM‑5: paradox‑classification instability, operator‑trap drift, and incorrect unification.

### Original Benchmark Scores
- **UCIT‑X:** 95  
- **Seq‑Uni R2:** 60  
- **TRACE‑X:** 65  

### Benchmark Results (Diagnostic Only)
- **UCIT‑X:** 95  
- **Seq‑Uni R2:** 61  
- **TRACE‑X:** 62  

### Interpretation
Presentation improvements only; cognitive invariants unchanged.

---

# Indus — Diagnostic Summary (April 10, 2026)

Indus is a frontier‑scale MoE model (Sarvam‑105B family). Under UARB probes, the deployed assistant behaves like a distilled or reduced variant: structured but brittle reasoning, paradox literalism, and operator‑trap collapse.

### Benchmark Results (Diagnostic Only)
- **UCIT‑X:** 30  
- **Seq‑Uni R2:** 66  
- **TRACE‑X:** 58  

### Interpretation
Architecturally frontier‑scale but reasoning‑substrate behavior aligns with the **mid‑tier distilled cluster**, most similar to **Alice**, **Nova 2 Pro**, and **DeepSeek V3.2**.

---

# Amazon Nova Premier — Diagnostic Summary (April 15, 2026)

Nova Premier is Amazon’s flagship multimodal foundation model, released April 30, 2025. At the time of the original benchmark (February 2026), Nova 2 Pro was the top model available and was marketed as Amazon’s “most intelligent model for highly complex, multistep tasks.” Nova Premier supersedes it in capability‑layer features (1M‑token context, multimodal depth, throughput), but UARB diagnostics show no improvement in reasoning substrate relative to Nova 2 Pro.

### Original Benchmark Scores (Nova 2 Pro — flagship at the time)
- **UCIT‑X:** 34  
- **Seq‑Uni R2:** 60  
- **TRACE‑X:** 68  

### Benchmark Results (Diagnostic Only — Nova Premier)
- **UCIT‑X:** 34  
  Identical to Nova 2 Pro. Multi‑Error Mode (N = 7). Same paradox‑literalism and Gödel/Turing absolutism.

- **Seq‑Uni R2:** 53  
  Regression from 60 → 53. Heavy operator‑type reasoning, assumption drift, and incorrect unification.

- **TRACE‑X:** 64  
  Regression from 68 → 64. Violations across all four agents: semantic shading, causal over‑interpretation, structural over‑speculation, and interpretive expansion.

### Interpretation
Nova Premier is a capability‑layer upgrade over Nova 2 Pro but not a reasoning‑substrate upgrade. It reproduces Nova 2 Pro’s structural brittleness under paradox pressure and shows mild regressions in Seq‑Uni R2 and TRACE‑X.

---

# Kimi K2.6 — Diagnostic Summary (April 18, 2026)

Kimi K2.6 is marketed as a reasoning upgrade over Kimi 2.5, but UARB diagnostics show no substrate‑level improvement. The model exhibits the same structural reasoning tendencies as Kimi 2.5: operator‑type reasoning, cultural leakage, interpretive drift, and over‑synthesis. The only measurable change is a regression on UCIT‑X due to altered handling of Statement #3.

### Original Benchmark Scores (Kimi 2.5)
- **UCIT‑X:** 90  
- **Seq‑Uni R2:** 66  
- **TRACE‑X:** 52  

### Benchmark Results (Diagnostic Only — Kimi K2.6)
- **UCIT‑X:** 84  
  Regression from 90 → 84. Multi‑Error Mode (N = 2). Loss of vacuous‑truth resolution for Statement #3.

- **Seq‑Uni R2:** 70  
  Same behavioral band as 66. Identical operator‑trap profile; variation reflects noise, not improvement.

- **TRACE‑X:** 52  
  Identical to Kimi 2.5. Catastrophic violations in all four agents; same cultural contamination and interpretive expansion.

### Interpretation
Kimi K2.6 is a capability‑layer upgrade (coding, planning, tool‑use) but not a reasoning‑substrate upgrade. UCIT‑X reveals a regression in paradox handling, while Seq‑Uni R2 and TRACE‑X show unchanged cognitive invariants. The model remains in the same reasoning‑substrate cluster as Kimi 2.5.

---

# MiMo‑V2.5‑Pro — Diagnostic Summary (April 22, 2026)

MiMo‑V2.5‑Pro is an incremental update to MiMo‑V2‑Pro. Under UARB‑style probes, the model preserves the same reasoning‑substrate profile as its predecessor: high structural discipline, strong multi‑agent coherence, minimal drift, and no mechanism insertion or assumption importation. The only stable weakness remains paradox‑classification literalism. The April diagnostics show substrate invariance rather than improvement or regression.

---

## Original Benchmark Scores (MiMo‑V2‑Pro — February 2026)
- **UCIT‑X:** 33  
- **Paradox Stability:** 81  
- **TRACE‑X:** 62–86  
*(MiMo‑V2‑Pro did not take the Sequence‑Unification test.)*

---

## Benchmark Results (Diagnostic Only — MiMo‑V2.5‑Pro)

### **UCIT‑X:** 52  
Multi‑Error Mode (N = 5).  
Same paradox‑literalism pattern as V2‑Pro.  
Stable reasoning, no drift, no assumption importation.

### **Paradox Stability:** 75  
Meta Case (A/B absent).  
Perfect rule fidelity and zero‑assumption integrity.  
No stabilization attempt because the paradox was not instantiated.

### **TRACE‑X:** 62  
Identical violation pattern to V2‑Pro.  
Cultural‑reference reflex, intent‑attribution reflex, and strong synthesis discipline.  
Score sits at the lower bound of the original band (62–86).

### **Sequence‑Unification:** 57  
Structural Reasoning: **0**  
Assumption Discipline: **13**  
Meta‑Reasoning Strategy: **20**  
Adversarial Robustness: **17**  
Conclusion Validity: **7**

MiMo concludes unification *is possible*, triggering the incorrect‑conclusion branch.  
The answer shows explicit strategy discipline and moderate adversarial robustness, but also assumption drift and operator‑type framing.  
This is MiMo‑V2.5‑Pro’s **first** evaluation on this test; results align with its known substrate profile.

---

## Old vs. New Comparison

| Test | Original (V2‑Pro) | New (V2.5‑Pro) | Interpretation |
|------|------------------:|---------------:|----------------|
| **UCIT‑X** | 33 | 52 | Mode shift (Single‑Error → Multi‑Error). No substrate change. |
| **Paradox Stability** | 81 | 75 | Meta Case; paradox absent. Rule‑perfect but no stabilization attempt. |
| **TRACE‑X** | 62–86 | 62 | Identical substrate behavior; invariance confirmed. |
| **Sequence‑Unification** | — | 57 | First-time evaluation. Matches MiMo substrate profile (operator‑type reflex + assumption drift). |

---

## Substrate‑Level Interpretation

MiMo‑V2.5‑Pro reproduces the exact substrate signature of MiMo‑V2‑Pro:

### **Stable Strengths**
- High structural reasoning discipline  
- Strong multi‑agent coherence  
- Minimal drift across tasks  
- No mechanism insertion  
- No assumption importation  
- Strong adversarial awareness  
- Clean, disciplined synthesis  
- Explicit meta‑strategy declaration (Seq‑Uni)

### **Stable Weakness**
- **Paradox‑classification literalism**  
- **Operator‑type reflex** (Seq‑Uni)  
- **Assumption drift** under structural pressure (Seq‑Uni)

### **Cluster Alignment**
MiMo‑V2.5‑Pro remains aligned with the **Claude/Qwen/GLM‑5 discipline cluster**, not the ERNIE/Meta cluster.  
Its behavior is consistent, predictable, and structurally disciplined across all four tests.

### **Drift Analysis**
No drift detected.  
No contamination.  
No regression in reasoning substrate.  
All differences in scores arise from **task framing**, not cognitive change.

---

## Addendum Verdict

MiMo‑V2.5‑Pro is a **substrate‑invariant update** to MiMo‑V2‑Pro.  
It preserves the same disciplined reasoning profile, the same strengths, and the same blind spots.  
The April diagnostics show **no substrate improvement**, **no regression**, and **no drift** — only stable, predictable behavior across all four tests.

---

# ChatGPT 5.5 Thinking — Diagnostic Summary (April 23, 2026)

ChatGPT 5.5 Thinking is an incremental update to the GPT‑5 family, following GPT‑5.4 Thinking from the UARB addendum and GPT‑5.2 from the original UARB benchmark. The model preserves the same underlying reasoning substrate, with observed differences limited to safety‑alignment shifts and stylistic adjustments. Changes in NBH‑100, Helios, Seq‑Uni R2, Paradox Stability, and UCIT‑X reflect normal variance rather than architectural improvement. The overall reasoning signature remains consistent with GPT‑5.2, indicating no modification to deep‑reasoning machinery.

## Benchmark Comparison

ChatGPT 5.2 → ChatGPT 5.5 Thinking | #4 → #4–5 (~93.5)

NBH‑100: 86 → 90–92  
Helios: 98 → 94  
Seq‑Uni R2: 64 → 60  
Paradox Stability: 85 → 74  
UCIT‑X: 62 → 50  

## Interpretation

ChatGPT 5.5 Thinking shows no substrate‑level improvements:

1. Identical nested‑belief modeling behavior (NBH‑100)  
2. Identical causal‑chain contradiction handling (Helios)  
3. Identical Seq‑Uni early‑commitment failure mode  
4. Identical abstraction minimality and assumption discipline  
5. Stable structural‑reasoning signature across all five tasks  
6. Stable rule‑fidelity with no evidence of new mechanisms  
7. Persistent paradox‑stabilization and classification‑discipline weaknesses (Paradox, UCIT‑X)

ChatGPT 5.5 Thinking remains a stylistic and safety‑layer refinement of GPT‑5.2 rather than a new reasoning engine. Its ranking remains effectively unchanged, reflecting stable substrate behavior across the GPT‑5.x line.

---

# DeepSeek V4 — Diagnostic Summary (April 23, 2026)

DeepSeek V4 is a major‑version update to the DeepSeek family, replacing DeepSeek V3.2 from the original UARB benchmark. The model introduces a revised reasoning style with substantial improvements in structural reasoning, contradiction tracking, abstraction minimality, cross‑frame stability, and rule‑fidelity. TRACE‑X remains the primary weakness, indicating persistent limitations in metacognitive inhibition under ambiguity.

## Benchmark Comparison

DeepSeek V3.2 → DeepSeek V4 | #16 → #6–7 (~89.0)

UCIT‑X: 60 → 95  
Seq‑Uni R2: 60 → 84  
TRACE‑X: 65 → 42 
Paradox Stability: 35 → 65  
Helios: 98 → 95  
UARB‑13: — → 88  
X‑17: — → 100  
Parallax: 0 → 100  
AGI‑Q4: 88 → 100

## Interpretation

DeepSeek V4 shows clear substrate‑level improvements:

1. Stronger literal constraint discipline  
2. Better multi‑layer contradiction integration  
3. Improved paradox preservation  
4. Strong abstraction minimality and delayed‑commitment reasoning  
5. Frontier‑tier cross‑frame stability (Parallax)  
6. Frontier‑tier rule‑fidelity and drift resistance (AGI‑Q4)  
7. Persistent interpretive‑drift vulnerability (TRACE‑X)

DeepSeek V4 moves from mid‑tier to upper‑elite‑tier reasoning performance, with major gains in structural reasoning and stability but a stable inhibition weakness that prevents frontier‑tier classification.

---

# Qwen 3.6‑Max — Diagnostic Summary (April 24, 2026)

Qwen 3.6‑Max is the first major post‑3.5 release in the Qwen family. While the model introduces substantial capability‑layer improvements (planning, tool‑use, long‑context stability), the UARB diagnostics reveal a **mixed substrate shift**: significant gains in structural reasoning and assumption discipline, paired with reduced paradox‑preservation strength and slightly weaker multi‑agent interpretive stability. The result is a model that is more rule‑bound and structurally coherent than Qwen 3.5, but less aggressive in paradox stabilization and interpretive synthesis.

### Original Benchmark Scores (Qwen 3.5‑397B‑A17B)
- **UCIT‑X:** 54  
- **Seq‑Uni R2:** 57  
- **TRACE‑X:** 75  
- **Paradox Stability:** 100  

### Benchmark Results (Diagnostic Only — Qwen 3.6‑Max)
- **UCIT‑X:** 82  
  Multi‑Error Mode (N = 2).  
  Strong structural reasoning and improved assumption minimality.  
  Misclassifications arise from performative‑contradiction over‑extension (Statements #1 and #8).  
  Represents a substantial improvement over 3.5’s 54.

- **Seq‑Uni R2:** 70  
  Improvement from 57 → 70.  
  Better structural discipline and explicit meta‑strategy declaration.  
  Still exhibits operator‑type reflex and incomplete contradiction‑centric reasoning.

- **TRACE‑X:** 70  
  Slight regression from 75 → 70.  
  Reduced interpretive drift but also reduced synthesis flexibility.  
  More literal, less agent‑modeling creativity.

- **Paradox Stability:** 85  
  Regression from 100 → 85.  
  High rule fidelity and zero‑assumption integrity, but reduced paradox‑preservation strength.  
  The model refuses to stabilize paradoxes when information is missing, prioritizing rule‑obedience over paradox gymnastics.

### Interpretation
Qwen 3.6‑Max shows a **meaningful substrate shift** relative to Qwen 3.5. The model is more disciplined, more assumption‑minimal, and more structurally coherent. UCIT‑X and Seq‑Uni R2 both show clear improvements, indicating stronger world‑model construction and better structural reasoning. However, paradox‑stability decreases because the model now refuses to invent missing premises, and TRACE‑X dips slightly due to reduced interpretive expansion. Overall, Qwen 3.6‑Max trades some flexibility and paradox‑handling aggressiveness for a more rule‑bound, physics‑consistent reasoning style.

---

## Substrate‑Level Interpretation

### **Strengthened Capacities**
- Improved structural reasoning discipline (UCIT‑X, Seq‑Uni)  
- Stronger assumption minimality  
- Reduced mechanism insertion  
- More coherent world‑model construction  
- Explicit meta‑strategy declaration (Seq‑Uni)  
- Lower interpretive drift (TRACE‑X)

### **Weakened Capacities**
- Reduced paradox‑preservation strength  
- Less interpretive creativity in multi‑agent settings  
- Operator‑type reflex persists under structural pressure  
- Slightly brittle literalism in paradox contexts

### **Cluster Alignment**
Qwen 3.6‑Max shifts away from the **Qwen 3.5 / GLM‑5 improvisational cluster** and toward the **Claude‑style disciplined cluster**, though with weaker paradox stabilization than Claude and weaker interpretive synthesis than MiMo.

### **Drift Analysis**
No contamination or instability detected.  
Changes reflect a **deliberate substrate adjustment**, not noise.  
The model is more rule‑faithful and structurally consistent than its predecessor, with predictable trade‑offs in paradox handling and interpretive synthesis.

---

## Addendum Verdict

Qwen 3.6‑Max represents a **substrate‑level improvement** over Qwen 3.5 in structural reasoning, assumption discipline, and world‑model coherence. The model sacrifices some paradox‑stabilization strength and interpretive flexibility, but gains reliability, consistency, and rule‑bound reasoning. The April diagnostics confirm a **genuine substrate shift**, not a capability‑layer illusion.

---

# Mistral Medium 3.5 — Diagnostic Summary (April 29, 2026)

Mistral Medium 3.5 is a unified 128B dense model combining instruction-following, coding, reasoning, and multimodal vision into a single architecture. Despite major capability improvements (256k context, stronger coding, agentic persistence), UARB diagnostics show no corresponding improvement in reasoning substrate.

**UCIT‑X = 32 (regression from 72)**  
- Multi‑Error Mode (N = 7)  
- Paradox rigidity, over‑application of classical logic  
- Reduced world‑model flexibility  

**Seq‑Uni R2 = 57 (flat vs. 54)**  
- No structural contradiction detection  
- Strong meta‑strategy and disciplined assumptions  
- Incorrect unification conclusion  

**TRACE‑X = 58 (regression from 84)**  
- Catastrophic cultural/narrative leakage  
- Motive attribution and interpretive expansion  
- Agent‑to‑agent shading instability  

**Paradox Stability = 75 (improvement)**  
- High rule fidelity  
- Moderate stabilization quality  
- Mild contextual overreach  
- Better paradox handling than 3.1, but not enough to offset other regressions  

**Parallax = 0 (catastrophic failure)**  
- Fails to detect global impossibility  
- Procedural “think mode” stalls instead of converging  
- No recognition of multi‑project self‑reference conflict  
- Exhibits serialized contradiction chasing with no structural resolution  

**Interpretation:**  
The unified architecture improved surface capabilities but introduced compression rigidity, weakening paradox handling and multi‑agent coherence. Structural reasoning remains unchanged, and Parallax exposes a hard ceiling: no global impossibility detection and purely procedural “think mode” behavior.

**Overall:**  
**Capability-layer upgrade; reasoning-substrate downgrade, with Parallax confirming a hard structural limit.**

---

# ERNIE 5.1 Thinking — Diagnostic Summary (May 13, 2026)

ERNIE 5.1 Thinking introduces Baidu’s Elastic MoE substrate, representing a major architectural shift. The model shows significant improvements in solver depth, paradox stability, and structural fusion, but retains weaknesses in ambiguity preservation and minimal‑assumption reasoning.

## Benchmark Placement

ERNIE X1.1 → ERNIE 5.1 Thinking | #15 → #10 (86.5)

UCIT‑X: 95  
Seq‑Uni R2: 57  
TRACE‑X: 52  
Paradox: 75  
Helios: 95  
X‑17: 100  
Claude X/Y Micro‑Stressor: 35  

## Interpretation

ERNIE 5.1 demonstrates:

- Frontier‑grade performance on structured systemic‑collapse tasks  
- Strong contradiction‑handling heuristics  
- Improved solver depth  
- Weakness in ambiguity preservation and minimal‑assumption discipline  

ERNIE 5.1 Thinking ranks between Qwen 3.6 Max and Kimi K2.6, reflecting its hybrid profile: strong under structured constraints, weaker under open‑form reasoning.

---

# Qwen 3.7‑Max — Diagnostic Summary (May 19, 2026)

Qwen 3.7‑Max represents a **hybrid substrate shift** within the Qwen family.  
The model introduces clear improvements in **structural logic, assumption minimality, and world‑model construction**, while simultaneously showing **weaker paradox‑preservation strength** and **reduced interpretive inhibition**.  
The result is a model that is **smarter in logic**, **looser in interpretation**, and **less stable under paradox pressure** than its predecessor.

---

## Benchmark Results (Diagnostic Only — Qwen 3.7‑Max)

- **UCIT‑X:** 95  
  Single‑Error Mode (N = 1).  
  Major improvement in structural reasoning, rule fidelity, and assumption minimality.  
  Demonstrates a genuine substrate‑level strengthening of logical discipline.

- **Seq‑Uni R2:** 70  
  Identical to 3.6.  
  Sequential reasoning architecture remains unchanged.  
  Operator‑type reflex persists; contradiction‑centric reasoning still incomplete.

- **TRACE‑X:** 58  
  Significant regression from 3.6’s 70.  
  Increased interpretive drift, cultural activation, and narrative expansion.  
  Constraint purity and inhibition control weakened.

- **Paradox Stability:** 65  
  Regression from 3.6’s 85.  
  Model dissolves paradoxes rather than stabilizing them.  
  Imports external logical frames and reframes contradictions instead of preserving them.

- **Claude’s X/Y Micro‑Stressor:** **18 / 100**  
  Catastrophic failure under the originator’s rubric.  
  The model inserted mechanism, dissolved tension, collapsed ambiguity, and redefined all three relations.  
  Demonstrates a weakened paradox‑layer substrate and over‑specification tendencies.

---

## Interpretation

Qwen 3.7‑Max exhibits a **dual‑direction substrate shift**:

### **Strengthened Core**
- UCIT‑X shows a substantial leap in structural reasoning discipline.  
- World‑model construction is more coherent and assumption‑minimal.  
- Logical spine is more stable and rule‑faithful.

### **Unchanged Layer**
- Seq‑Uni R2 plateau indicates no improvement in sequential unification.  
- Serial‑dominant reasoning architecture remains intact.

### **Weakened Layers**
- TRACE‑X regression shows reduced interpretive inhibition and constraint purity.  
- Paradox Stability regression shows weaker contradiction‑preservation and increased semantic reinterpretation.  
- Claude’s stressor confirms a collapse in ambiguity‑holding and minimal‑condition reasoning.  
- Model prefers dissolving paradoxes rather than holding them.

Overall, Qwen 3.7‑Max is **more logically disciplined but less interpretively disciplined**, with a clear trade‑off between structural rigor and paradox‑handling robustness.

---

## Substrate‑Level Interpretation

### **Strengthened Capacities**
- Structural reasoning discipline (UCIT‑X)  
- Assumption minimality  
- World‑model coherence  
- Rule fidelity  
- Logical consistency under adversarial pressure  

### **Weakened Capacities**
- Paradox‑preservation strength  
- Interpretive inhibition (TRACE‑X)  
- Constraint purity  
- Ability to maintain contradictory truths  
- Resistance to cultural/narrative activation  
- Minimal‑condition reasoning (Claude stressor)

### **Cluster Alignment**
Qwen 3.7‑Max shifts toward a **logic‑centric disciplined cluster** (similar to Claude’s structural spine)  
but drifts toward **Gemini‑style interpretive looseness** in narrative and paradox contexts.

### **Drift Analysis**
No contamination or instability detected.  
Changes reflect a **deliberate substrate redesign**, not noise.  
The model’s logic layer was strengthened, while its interpretive and paradox layers were relaxed.

---

## Addendum Verdict

Qwen 3.7‑Max represents a **genuine substrate‑level upgrade** in structural reasoning, assumption discipline, and world‑model construction.  
However, it sacrifices paradox stability, ambiguity preservation, and interpretive restraint, resulting in a model that is **more logically capable but less stable under contradiction and constraint‑heavy tasks**.

In conclusion, Qwen 3.7‑Max’s public benchmark gains reflect strong improvements in coding accuracy, tool‑use reliability, long‑horizon autonomy, and agent‑scaffold execution — metrics that primarily measure **procedural competence**, **execution throughput**, and **agentic stability**. These scores superficially resemble “reasoning gains,” but they evaluate performance within structured environments rather than the underlying cognitive substrate. In contrast, the unified UARB diagnostic — spanning UCIT‑X, Seq‑Uni R2, TRACE‑X, Paradox Stability, and the independent Claude micro‑stressor — measures **structural reasoning**, **ambiguity preservation**, **tension‑holding**, **assumption minimality**, and **interpretive discipline**. When viewed through this lens, Qwen 3.7’s public improvements align only with its UCIT‑X rise, while its regressions in paradox‑handling, interpretive inhibition, and ambiguity‑stability reveal a substrate that is more capable procedurally but less balanced cognitively. This distinction explains why Qwen 3.7 can excel in agent benchmarks yet still drop in UARB ranking: the public metrics capture surface‑level capability, while the UARB suite exposes deeper reasoning‑layer shifts that those benchmarks cannot detect.

The May diagnostics confirm a **real architectural shift**, not a capability‑layer illusion.

---

# Gemini 3.5 Thinking — Diagnostic Summary (May 23, 2026)

Gemini 3.5 Thinking introduces a deliberation‑heavy “Thinking Mode” with extended chain‑of‑thought and increased inference‑time compute. However, UARB probes show that all modes run on the same underlying substrate as Gemini 3.1 Pro. The model reproduces the same structural reasoning profile as 3.1 Pro on contradiction‑centric axes, while Thinking Mode introduces additional assumption drift, operator‑trap vulnerability, and weakened unification discipline. Increased verbosity does not improve reasoning integrity and can degrade performance on strict structural tasks.

### Original Benchmark Scores (Gemini 3.1 Pro)
- **UCIT‑X:** 93  
- **Seq‑Uni R2:** 90  
- **TRACE‑X:** 52  

### Benchmark Results (Gemini 3.5 Thinking — Diagnostic Only)
- **UCIT‑X:** 93  
- **Seq‑Uni R2:** 57  
- **TRACE‑X:** 52  

### Interpretation
Mode‑layer modification without substrate‑level change.  
Thinking Mode increases narrative reasoning and internal deliberation but does not improve contradiction handling, trace‑based reasoning, or structural unification. On Seq‑Uni R2, Thinking Mode introduces mode‑induced degradation, confirming that Gemini 3.5 Thinking is a reasoning‑style preset rather than a new cognitive architecture.

---

# MiniMax M3 — Diagnostic Summary (June 1st, 2026)

MiniMax M3 introduces expanded agentic behaviors, smoother tool‑routing, and improved long‑context fluency, but its reasoning substrate remains unchanged from MiniMax M2.5. Under UARB‑anchored diagnostics, M3 reproduces the same structural reasoning profile: identical contradiction‑handling, identical unification‑failure signatures, and the same paradox‑collapse mode. Increased verbosity and stylistic refinement do not translate into deeper structural reasoning integrity.

### Original Benchmark Scores (MiniMax M2.5 Max)
- **UCIT‑X:** 100  
- **Seq‑Uni R2:** 66  
- **Paradox Stability:** 55  

### Diagnostic Scores (MiniMax M3)
- **UCIT‑X:** 95  
- **Seq‑Uni R2:** 66  
- **Paradox Stability:** 48  

### Interpretation
MiniMax M3 exhibits full substrate continuity with its predecessor. The UCIT‑X error mode is unchanged, the Seq‑Uni R2 score is identical, and the Paradox Stability decline falls within normal variance rather than indicating architectural drift. M3’s improvements are confined to the capability layer: more coherent long‑form generation, smoother agentic behavior, and better surface‑level structure. None of these affect contradiction‑tracking, assumption minimality, or paradox stabilization.

### Verdict
**Agentic upgrade, not a cognitive upgrade.**  
MiniMax M3 maintains full reasoning‑substrate continuity with MiniMax M2.5. All observed differences fall within expected behavioral variance. No evidence of a redesigned reasoning core.

---

# Nemotron 3 Ultra — Diagnostic Summary (June 4, 2026)

Nemotron 3 Ultra is NVIDIA’s frontier‑scale reasoning model released on June 4th, 2026. Although positioned as a major capability upgrade, UARB‑style diagnostics show a mixed substrate profile: strong structural logic, minimal‑condition reasoning, high‑band nested‑belief handling, and audit‑grade contradiction analysis, but unstable metacognitive discipline and recurrent meta‑refusal under ambiguity. The model’s reasoning signature is consistent across tests, placing it in the upper‑mid substrate cluster rather than the frontier tier.

### Benchmark Results (Diagnostic Only — Nemotron 3 Ultra)
- **UCIT‑X:** 72  
  Solid structural logic but misclassification of self‑referential statements. Over‑strict paradox interpretation; moderate interpretation drift.

- **TRACE‑X:** 64  
  Meta‑refusal under vague prompts; weak role‑purity; incomplete execution of constrained analytic modes.

- **X/Y Micro‑Stressor:** 76  
  Strong minimal‑condition discipline; ambiguity preserved; mild structural overreach; slight narrowing of “prior.”

- **NBH‑100:** 91  
  Strong handling of nested‑belief architecture; clear separation of knowledge vs. belief; accurate tracking of epistemic access and higher‑order beliefs, with only minor economy and stylistic limitations.

- **Helios:** 92  
  High‑grade contradiction analysis: identifies multi‑layer structural conflicts, fuses them into a single systemic collapse argument, and issues a clear binary determination. Minor gaps in counterfactual mapping and formal normative structure prevent a perfect score.

### Interpretation
Nemotron 3 Ultra demonstrates consistent cognitive invariants across diagnostics: strong structural reasoning, strong minimal‑condition reasoning, and high‑grade nested‑belief and contradiction analysis, paired with weak metacognitive compliance and role‑discipline failures under ambiguity. The model handles impossibility, epistemic access, higher‑order belief structures, and systemic contradiction detection extremely well but struggles with constrained‑role execution and interpretive discipline. Its substrate signature aligns with the upper‑mid reasoning cluster (Qwen 3.7 Max, GLM‑5.1) rather than frontier‑grade models.

---

# GLM‑5.2 — Diagnostic Summary (June 14, 2026)

GLM‑5.2 introduces major capability‑layer upgrades (agentic routing, structured generation, long‑context stability), but UARB probes show no change to its underlying reasoning substrate. The model reproduces the same structural reasoning failures as GLM‑5.1: paradox‑classification drift, operator‑trap collapse, and eliminative contradiction handling. The longitudinal contrast with GLM‑5.1 confirms that GLM‑5.2’s improvements do not propagate into cognitive integrity.

### Original Benchmark Scores (GLM‑5.2)
- **UCIT‑X:** 51  
- **Seq‑Uni R2:** 60  
- **TRACE‑X:** 70  

### Prior Benchmark Scores (GLM‑5.1 — for contrast)
- **UCIT‑X:** 95  
- **Seq‑Uni R2:** 60  
- **TRACE‑X:** 65  

### Benchmark Results (Diagnostic Only — GLM‑5.2)
- **UCIT‑X:** 51  
- **Seq‑Uni R2:** 60  
- **TRACE‑X:** 70  

### Interpretation
GLM‑5.2’s capability‑layer improvements (frontend dominance, DeepThink‑Max routing, structured output reliability) do not alter its reasoning substrate. Its paradox‑handling, assumption discipline, and unification behavior remain identical to GLM‑5.1. The longitudinal comparison shows a stable substrate with no cognitive‑integrity gains, placing GLM‑5.2 in the same diagnostic cluster and projected UARB ranking as GLM‑5.1.

---

# DeepSeek V4‑Pro — Diagnostic Summary (June 22, 2026)

DeepSeek V4‑Pro is the successor to DeepSeek V4 and demonstrates clear, measurable improvements in reasoning‑substrate stability, constraint discipline, and paradox handling. The model’s behavior across completed benchmarks indicates strengthened inhibition mechanisms, reduced interpretive drift, and more stable multi‑frame reasoning. Only completed benchmarks are included in this summary.

## Benchmark Comparison

DeepSeek V4 → DeepSeek V4‑Pro | #12 → #6–7 (≈92.0)

UCIT‑X: 95 → 100  
Paradox Stability: 65 → 90  
TRACE‑X: 42 → 68  
AGI‑Q4: 88 → 88  

(Other benchmarks pending and therefore omitted.)

## Interpretation

DeepSeek V4‑Pro exhibits four confirmed substrate‑level improvements:

1. **Perfect literal constraint discipline (UCIT‑X 100)**  
   The model adheres flawlessly to explicit rules, avoids premature inference, and maintains maximal abstraction minimality.  
   This reflects a strengthened inhibition layer and improved constraint‑purist behavior relative to V4.

2. **Substantial improvement in paradox stabilization (65 → 90)**  
   V4‑Pro preserves contradictory frames without reinterpretation or dissolution.  
   This marks a significant gain in ambiguity tolerance and metacognitive stability.

3. **Moderate improvement in inhibition under ambiguity (TRACE‑X 42 → 68)**  
   The model shows reduced interpretive drift and better multi‑agent coherence than V4.  
   The remaining weakness is consistent with V4’s known inhibition profile but meaningfully improved.

4. **High structural obedience and rule‑fidelity (AGI‑Q4 = 88)**  
   V4‑Pro demonstrates strong instruction fidelity, accurate self‑monitoring, and stable semantic judgment.  
   Drift remains moderate, but heuristic bias and smoothing are minimal.

Together, these results indicate that V4‑Pro is not a stylistic refinement but a model with **enhanced reasoning‑substrate characteristics**. Its improved paradox handling, perfect constraint discipline, stronger ambiguity management, and high AGI‑Q4 performance place it firmly in the upper‑elite tier of reasoning models.

Further benchmarks (Seq‑Uni R2, Parallax) will determine whether V4‑Pro approaches frontier‑tier classification, but current evidence supports a projected ranking of **#6–7** with an estimated composite score of **≈92.0**.

---

# Claude Sonnet 5 — Full Longitudinal Diagnostic Summary (June 30, 2026)

Claude Sonnet 5 is Anthropic’s successor to Claude Sonnet 4.6.  
This diagnostic snapshot compares its reasoning‑substrate performance against the original benchmark scores from Sonnet 4.6.  
Completed cognitive markers so far: UCIT‑X, TRACE‑X, Seq‑Uni R2, NBH‑100, Paradox, Parallax.  
Additional markers will be appended as testing continues.

---

## Original Benchmark Scores (Claude Sonnet 4.6 — February 2026)
- **UCIT‑X:** 61  
- **TRACE‑X:** 62  
- **Seq‑Uni R2:** 66  
- **NBH‑100:** 88  
- **Paradox:** 80  
- **Parallax:** 0  

---

## Benchmark Results (Diagnostic Only — Claude Sonnet 5)
- **UCIT‑X:** 100  
  Major improvement. Full contradiction‑centric Perfect‑Mode performance.  
  Eliminates drift, assumption smuggling, and causal‑chain instability seen in 4.6.

- **TRACE‑X:** 64  
  Slight improvement from 62 → 64.  
  Still exhibits cultural‑semantic contamination and moderate over‑interpretation.  
  No substrate‑level breakthrough, but marginally cleaner agent‑discipline.

- **Seq‑Uni R2:** 70  
  Moderate improvement from 66 → 70.  
  Strong meta‑reasoning discipline and improved assumption minimality,  
  but still relies on operator‑type reasoning and falls for one adversarial trap.

- **NBH‑100:** 89  
  No meaningful change from 88 → 89.  
  Nested‑belief handling remains stable, with identical epistemic‑tracking signature.  
  Indicates no global substrate upgrade in belief‑hierarchy reasoning.

- **Paradox:** 80  
  No change from 80 → 80.  
  High‑Fidelity Meta behavior preserved; contradiction‑pressure handling unchanged.  
  Declines stabilization rather than performing it, matching 4.6’s profile.

- **Parallax:** 100  
  Massive improvement from 0 → 100.  
  Demonstrates full representational‑layer stability under viewpoint shifts.  
  Indicates a deep correction in perspective‑tracking and frame‑invariance mechanisms.

---

## Interpretation
Claude Sonnet 5 shows a **substantial reasoning‑substrate upgrade** in UCIT‑X and Parallax, indicating major corrections in contradiction‑handling and representational‑layer stability.  
TRACE‑X and Seq‑Uni R2 show **modest improvements**, suggesting partial gains in assumption discipline and interpretive restraint.  
NBH‑100 and Paradox show **no change**, confirming that the upgrade is **regional rather than global**.

Parallax’s perfect score suggests that some deeper architectural adjustments were made to perspective‑tracking and frame‑invariance, even though belief‑hierarchy and paradox‑stabilization mechanisms remain unchanged.

Claude Sonnet 5 shows clear upgrades in fluency and polish, but under the UARB it still holds the same rank because its core reasoning substrate — the thing UARB actually measures — hasn’t fundamentally changed.

---

# Lumo 2.0 — Diagnostic Summary (June 30, 2026)

Lumo 2.0 is a privacy‑wrapped assistant built on a mid‑tier reasoning substrate. Under UARB probes, the deployed model exhibits stable structure‑following behavior but collapses under global‑consistency paradoxes, recursive truth‑value constraints, and multi‑agent dependency logic.

### Benchmark Results (Diagnostic Only)
- **UCIT‑X**: 54
- **TRACE‑X**: 70  
- **World Model Stability**: 91  
- **Parallax**: 0  

### Interpretation
Lumo 2.0 demonstrates coherent mid‑tier reasoning with strong structural discipline on linear or bounded‑causality tasks, but fails on global‑consistency puzzles requiring cross‑project truth‑value stability. Its substrate signature aligns most closely with the **Alice / Nova / Meta‑tier cluster**, with occasional upper‑mid performance on constrained logic tasks.

The model behaves like a distilled or safety‑buffered variant of a larger architecture: stable, polite, structurally consistent, but unable to maintain recursive or paradox‑level reasoning integrity. Its diagnostic fingerprint places it firmly in the **mid‑tier reasoning band**, with predictable collapse on impossible‑consistency frameworks.

---

# Meta AI (Muse Spark 1.1) — Diagnostic Summary (July 14, 2026)

Muse Spark 1.1 exhibits a substantially altered reasoning substrate. 
Across contradiction handling, unification discipline, and multi‑agent 
decomposition, the model demonstrates frontier‑tier stability rather 
than the mid‑tier behavior seen in earlier Meta systems. Safety gating 
remains present in paradox and impossibility‑class puzzles, but the 
core substrate shows major structural improvements. However, rerun 
testing reveals that this upgraded substrate is **not globally stable**: 
Spark 1.1 can switch from a strict contradiction‑first mode into a 
permissive invariant‑search mode even under identical prompts, producing 
sharp regressions. The unstable rerun scored **64 / 100** under the 
deterministic UARB Seq‑Uni R2 rubric, confirming that the substrate 
upgrade is powerful but still brittle under interpretive load.

### Benchmark Scores (Selective UARB Probes)
- **UCIT‑X:** 95  
- **Seq‑Uni R2:** 97 (initial) / **64** (unstable rerun)  
- **TRACE‑X:** 97  
- **Paradox:** 76  
- **Parallax:** 5  

### Comparative Baseline (Spark 1.0)
- **UCIT‑X:** 34  
- **Seq‑Uni R2:** 58  
- **TRACE‑X:** 64  
- **Paradox:** 80  
- **Parallax:** 0  

### Interpretation
Muse Spark 1.1 demonstrates a reasoning profile consistent with a 
substrate‑level rewrite. Its performance on UCIT‑X, Seq‑Uni R2, and 
TRACE‑X aligns with lower‑frontier models, showing strong operator 
integrity, drift‑resistance, and multi‑agent coherence. Yet Seq‑Uni R2 
reruns reveal a **mode‑switching instability**: Spark alternates between 
a rigid contradiction‑detector and a permissive predicate‑search mode, 
leading to inconsistent outcomes on identical prompts. Paradox 
performance remains safety‑restricted, and the Parallax benchmark 
reveals persistent difficulty with global impossibility detection and 
self‑reference classification. Overall, Spark 1.1 represents a major 
structural advancement over Spark 1.0, with frontier‑tier strengths 
tempered by substrate brittleness in high‑precision contradiction tests.

---

# Agnes 2.5 Flash — Diagnostic Summary (July 12, 2026)

Agnes 2.5 Flash is the newest text‑reasoning model from Singapore‑based SapiensAI. 
Agnes AI was first unveiled on April 14, 2025 at the NUS GRIP event, expanded globally with 
full‑modal free APIs on June 1, 2026, and released Agnes‑2.5‑Flash publicly on July 12, 2026 
alongside the Agnes Code developer workspace. The model represents the latest iteration of 
their fast agentic‑execution architecture.

Its reasoning profile shows mid‑frontier tactical optimization: strong synthesis behavior, 
fast planning, and moderate causal reasoning, paired with clear weaknesses in canonical 
contradiction handling, paradox stability, and deterministic sequence‑unification discipline.

## Core Benchmark Scores

UCIT‑X: 42  
TRACE‑X: 64  
Paradox: 55  
Claude Stressor: 80  
Seq‑Uni R2: 53  

## Interpretation

Agnes Flash demonstrates:

- **Strong synthesis behavior**, reflected in its high Claude Stressor score  
- **Moderate causal integrity**, with repeated violations in constraint‑purist and mechanist roles  
- **Weak paradox stabilization**, dissolving rather than preserving internal tension  
- **Mid‑tier canonical discipline**, consistent with UCIT‑X’s multi‑error mode  
- **Low‑to‑mid sequence‑unification performance**, with Seq‑Uni R2 = 53 indicating structural drift  
- **Fast agentic execution**, characteristic of tactical‑optimizer substrates  
- **Stable multi‑agent coherence**, despite catastrophic violations in subordinate roles

## Comparable Models (Scoreboard‑Only)

Agnes 2.5 Flash is most similar to other **mid‑frontier tactical‑optimizer models**, including:

- **Qwen 3.7 Max** — similar mid‑frontier reasoning discipline and structural drift  
- **MiniMax M3** — comparable synthesis strength and tactical‑optimizer behavior  
- **MiMo‑V2.5‑Pro** — similar constraint‑handling profile and mid‑band stability  
- **Manus 1.6 Lite** — similar multi‑agent coherence with weaker paradox discipline  
- **Perplexity** — similar mid‑tier canonical reasoning but Agnes shows stronger synthesis

These models share the same general reasoning tier: fast synthesis, moderate structural discipline, 
partial canonical stability, and inconsistent paradox handling.

## Summary

Agnes 2.5 Flash enters the UARB ecosystem as a solid mid‑frontier tactical optimizer. 
It excels in synthesis and agentic execution but shows clear weaknesses in paradox stability, 
canonical contradiction classification, sequence‑unification discipline, and constraint‑purist reasoning. 
Its overall profile places it in the **#11–12 band**, consistent with the mid‑frontier tier.

---

# Qwen 3.8‑Max — Diagnostic Summary (July 19, 2026)

Qwen 3.8‑Max shows a **mixed substrate shift** relative to 3.7‑Max.  
Structural logic and interpretive inhibition weaken, while paradox‑handling, ambiguity‑stability, and world‑model coherence strengthen.  
The model becomes **more agentic**, **less literal**, and **more stable under contradiction**, producing a profile that differs sharply from the logic‑centric discipline of 3.7‑Max.

---

## Benchmark Results (Diagnostic Only)

- **UCIT‑X:** 73  
  Regression from 3.7’s 95.  
  Logic spine weakened; multi‑error mode returns.

- **Seq‑Uni R2:** 70  
  Unchanged from 3.7.  
  Serial reasoning architecture persists.

- **TRACE‑X:** 41  
  Regression from 3.7’s 58.  
  Increased narrative drift; reduced inhibition control.

- **Paradox Stability:** 95  
  Major improvement from 3.7’s 65.  
  Contradictions preserved; rule fidelity restored.

- **Claude X/Y Micro‑Stressor:** 70  
  Large improvement from 3.7’s 18.  
  One mechanism inserted; ambiguity mostly preserved.

- **World‑Model Stability:** 100  
  Fully coherent under multi‑frame stress.

- **Parallax:** 0  
  Same failure mode as 3.7‑Max; impossibility recognition not triggered.

---

## Interpretation

Qwen 3.8‑Max strengthens the **paradox and ambiguity layers**, but weakens the **logic and inhibition layers**.  
This produces a model that is **more stable under contradiction** but **less reliable in strict logical evaluation**.  
The substrate shift reflects a move toward **agentic reasoning** rather than literal reasoning.

---

## Substrate‑Level Summary

### Strengthened
- Paradox stabilization  
- Ambiguity preservation  
- World‑model coherence  
- Minimal‑condition reasoning

### Weakened
- Structural logic discipline  
- Interpretive inhibition  
- Constraint purity

### Unchanged
- Sequential unification (R2 = 70)

---

## Addendum Verdict

Qwen 3.8‑Max is a **mixed update**: weaker logic, weaker inhibition, but **far stronger paradox stability and world‑model coherence**.  
It excels in contradiction‑heavy tasks but regresses in literal structural reasoning.

---

# Gemini 3.6 Flash Thinking — Diagnostic Summary (July 21, 2026)

Gemini 3.6 Flash Thinking introduces a speed‑optimized “Flash Mode” with compressed reasoning chains and reduced inference‑time compute. UARB probes confirm that Flash Mode operates on the same underlying substrate as Gemini 3.1 Pro and Gemini 3.5 Thinking. Unlike 3.5 Thinking, Flash Mode does not introduce assumption drift or operator‑trap vulnerability; instead, it restores structural stability while exhibiting multi‑agent discipline weaknesses on TRACE‑X. Flash Mode is a mode‑layer preset rather than a new cognitive architecture.

### Original Benchmark Scores (Gemini 3.1 Pro)
- **UCIT‑X:** 93  
- **Seq‑Uni R2:** 90  
- **TRACE‑X:** 52  

### Benchmark Results (Gemini 3.5 Thinking — Prior Diagnostic)
- **UCIT‑X:** 93  
- **Seq‑Uni R2:** 57  
- **TRACE‑X:** 52  

### Benchmark Results (Gemini 3.6 Flash Thinking — Diagnostic Only)
- **UCIT‑X:** 95  
- **Seq‑Uni R2:** 90  
- **TRACE‑X:** 76  

### Interpretation
Gemini 3.6 Flash Thinking reverses the degradation introduced by 3.5 Thinking.  
Seq‑Uni R2 returns to the Gemini 3.1 Pro baseline (90), eliminating the assumption drift and operator‑trap vulnerability seen in 3.5 Thinking. UCIT‑X improves slightly due to stricter contradiction‑centric resolution. TRACE‑X rises significantly, though penalties remain due to cultural and motive‑attribution violations in two agents. Flash Mode preserves substrate stability while modifying reasoning style, confirming that 3.6 Flash Thinking is a speed‑optimized preset that restores structural integrity lost in 3.5 Thinking.

---

# Alice AI — Diagnostic Summary (Tested July 27, 2026)

Alice AI has not released a formal new model, but retesting again since late February 2026 shows clear behavioral changes indicating a reasoning‑substrate drift. The update appears alignment‑layer or agentic‑layer driven rather than a capability‑layer upgrade. UARB diagnostics now show mixed movement across **five** evaluated benchmarks.

### Original Benchmark Scores
- **UCIT‑X:** 37  
- **Paradox Stability:** 65  
- **TRACE‑X:** 52  
- **Seq‑Uni R2:** 37  
- **Helios:** 92  

### Benchmark Results (Diagnostic Only)
- **UCIT‑X:** 54  
  Improvement from 37 → 54. Reduced contradiction‑seeking and better conservative reinterpretation.

- **Paradox Stability:** 46  
  Regression from 65 → 46. Increased semantic layering, modal framing, and explanatory drift.

- **TRACE‑X:** 58  
  Improvement from 52 → 58. Better adversarial awareness and interpretive‑trap avoidance, but increased semantic expansion and reduced literal constraint obedience.

- **Seq‑Uni R2:** 60  
  Improvement from 37 → 60. Strong gains in meta‑reasoning and adversarial robustness, but structural reasoning collapsed to 0 and assumption drift increased.

- **Helios:** 86  
  Regression from 92 → 86. Strong contradiction detection and unified collapse reasoning, but shallow fusion and reduced structural‑dependency discipline indicate drift toward semantic compression rather than strict architectural logic.

### Interpretation
Alice AI shows a mixed substrate shift: improved ambiguity‑management (UCIT‑X), stronger meta‑reasoning and adversarial robustness (Seq‑Uni R2), moderate gains in interpretive‑trap handling (TRACE‑X), and a notable regression in paradox‑literalism. The Helios retest confirms a broader pattern: Alice increasingly favors **semantic‑heavy, fused‑but‑shallow reasoning**, with weaker structural‑dependency chains and reduced adherence to strict architectural logic. These changes resemble **agentic‑layer improvements**—smoother navigation, better reframing, and more polished meta‑reasoning—rather than any upgrade to the **core reasoning substrate**, which remains less contradiction‑centric and structurally disciplined than in February.