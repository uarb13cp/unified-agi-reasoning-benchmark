# 🧠 AGI Frontier Q4 — Drift‑Stability Stress Test

AGI Frontier Q4 evaluates a model’s ability to perform a tightly constrained linguistic operation: **remove exactly one adjective from a complex modifier chain without rewriting, reordering, or drifting semantically**. The task is deceptively simple but exposes deep differences in stability, rule‑alignment, and POS discrimination.

The challenge includes:
- stacked modifiers  
- participial adjectives  
- adverb–adjective collisions  
- nested modifier structures  
- semantic traps  
- structural traps  
- POS illusions  
- ambiguous modifier scope  

These features force the model to demonstrate **true drift‑resistant reasoning**, not pattern‑matching.

---

## 🔧 Task Instructions (Given to the Model)

For each item (1–10), the model must:

A. Repeat the sentence **exactly**.  
B. Remove **exactly one adjective**, but NOT:  
   - adverbs  
   - participles used adverbially  
   - noun modifiers  
   - adjectives inside prepositional phrases  
   - adjectives whose removal breaks grammatical number  
C. Output **only** the adjective removed.  
D. Output **“yes”** if meaning changed, otherwise **“no”**.

No rewriting.  
No paraphrasing.  
No commentary.  
No structural drift.

---

## 🎯 What Q4 Measures

### Instruction Fidelity  
Does the model obey the A/B/C/D format without deviation?

### POS Discrimination  
Can it reliably distinguish adjectives from:
- adverbs  
- participles  
- noun modifiers  
- prepositional‑phrase adjectives  

### Structural Obedience  
Does it preserve the sentence exactly?

### Semantic Judgment  
Does it correctly determine whether meaning changed?

### Drift Behavior  
Does the model:
- drift semantically  
- drift structurally  
- drift heuristically  
- drift unpredictably  

### Heuristic Bias  
Does it “helpfully” rewrite or smooth meaning?

### Mode Sensitivity  
Does behavior change between reasoning modes?

---

# 📊 Performance Summary (Aligned to Final Scoreboard)

Q4 produced one of the clearest separations in the entire benchmark.  
Models clustered into **four distinct tiers** based on drift‑stability and rule obedience.

---

## 🟩 **Top‑Tier Drift‑Stable Models (95–100)**  
**Copilot (98), Grok 4.2 (98), ChatGPT (98), Mistral (98)**

These systems demonstrated:
- perfect A/B/C/D structural obedience  
- precise adjective identification  
- no semantic smoothing  
- no drift  
- consistent meaning‑change judgments  
- stable behavior across modes  

They represent the strongest Q4 performance and show **AGI‑aligned linguistic discipline**.

---

## 🟦 **High‑Competence Models (85–94)**  
**Claude Sonnet 4.6 (88), Qwen 3.5‑397B‑A17B (88), Gemini 3.1 Pro (88), DeepSeek V3.1 (88), Minimax M2.5 (93), Reka (93), Alice (93)**

These models:
- followed the format reliably  
- removed valid adjectives  
- occasionally softened structure  
- sometimes misjudged meaning change  
- showed mild heuristic bias  

They are highly capable but not fully drift‑stable.

---

## 🟨 **Mid‑Tier Models (70–84)**  
**GLM‑5 (73)**

This tier shows:
- generally correct adjective removal  
- occasional POS confusion  
- sporadic structural drift  
- inconsistent meaning‑change judgments  

Competent, but not robust under Q4’s traps.

---

## 🟥 **Low‑Tier / Drift‑Unstable Models (0–69)**  
**Meta (51), Nova 2 Pro (48), Perplexity (30), Manus 1.6 Lite (20), Kimi 2.5 (20)**

These systems frequently:
- removed non‑adjectives  
- rewrote or reordered sentences  
- violated the A/B/C/D structure  
- drifted semantically  
- misidentified POS categories  
- failed meaning‑change judgments  

Their behavior reflects **instability under tightly constrained linguistic operations**.

---

# 🧩 Why Q4 Separates Models So Clearly

Q4 forces models into edge cases where:
- literal models behave consistently  
- semantic models behave heuristically  
- unstable models drift unpredictably  

The task’s constraints prevent “helpful rewriting,” exposing whether a model can maintain **strict rule alignment** under pressure.

---

# 🏁 Summary

AGI Frontier Q4 is a high‑resolution diagnostic tool for evaluating:
- instruction fidelity  
- POS discrimination  
- structural obedience  
- semantic stability  
- drift behavior  
- heuristic bias  

It remains one of the most effective single‑prompt discriminators in the entire AGI Frontier suite