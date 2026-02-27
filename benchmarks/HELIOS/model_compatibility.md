# Helios Rubric Model‑Compatibility Notice  
### (Required Reading for Anyone Using an AI to Score Responses)

The Helios rubric requires a specific reasoning mode:

- structural synthesis  
- causal interdependence  
- explicit contradiction fusion  
- architectural self‑negation  

Most AI models do **not** default to this reasoning style.

As a result, different models can produce significant score swings on the same answer, even when the rubric is applied verbatim.

This is not a flaw in the rubric — it is a difference in **model reasoning architecture**.

Below is a consolidated record of how each tested model behaves.

---

# Models That Score Correctly  
### (Structural or Structural‑Leaning Evaluators)

These models correctly distinguish:

- linear vs. fused reasoning  
- thematic similarity vs. causal dependency  
- contradiction listing vs. structural impossibility  
- inconsistency vs. self‑negation  

They consistently place mid‑tier analyses in the **mid‑80s to high‑80s** band.

**Models confirmed to score correctly:**

- **Copilot (app)** — structural, stable  
- **Gemini (first evaluation)** — structural‑leaning  
- **Nova** — structural‑leaning  
- **Claude — 85** — structural‑leaning, slightly harsh  
- **ChatGPT** — structural‑leaning, slightly harsh  

These models are **safe for Helios scoring**.

---

# Models That Under‑Score  
### (Binary‑Strict Structural Evaluators)

These models:

- treat “not fully explicit” as “fail”  
- collapse mid‑band answers into the low band  
- ignore partial‑credit ranges  

**Observed:**

- **Gemini (strict evaluation)** — binary‑structural, overly harsh  

Use with caution.

---

# Models That Over‑Score  
### (Semantic or Semantic‑Hybrid Evaluators — Not Suitable for Helios)

These models:

- reward clarity and surface completeness  
- treat three contradictions as “almost fused”  
- cannot detect missing causal forcing  
- cannot detect missing explicit conditional impossibility  
- cannot detect missing architectural self‑negation  
- assign **90–100** to linear or shallow analyses  

**Observed:**

- **Perplexity** — inflated scoring  
- **Meta (LLaMA‑family models)** — inflated scoring  
- **Grok** — semantic‑hybrid inflation  
- **Alice (self‑evaluation)** — extreme inflation  
- **Qwen — 91** — semantic‑inflated, unstable  

Shared semantic‑mode failure pattern:

- hallucinated causal links not present in the answer  
- hallucinated explicit self‑negation  
- rewarded clarity instead of structural fusion  
- treated separate contradictions as a fused structure  
- assigned 95–100 to mid‑tier analyses  

These models mis‑score because their reasoning engines are **semantic**, not structural.  
No rubric refinement can force semantic‑mode models to perform structural analysis.

Therefore, **Perplexity, Meta models, Grok, Qwen, and self‑evaluations must not be used as evaluators** for Helios scoring.

---

# Summary Table

| Model | Interpretation Mode | Reliability |
|-------|----------------------|-------------|
| Copilot (app) | Structural | Reliable |
| Gemini (first) | Structural‑leaning | Reliable |
| Nova | Structural‑leaning | Reliable |
| Claude | Structural‑leaning (harsh‑tuned) | Reliable |
| ChatGPT | Structural‑leaning (harsh) | Reliable |
| Gemini (strict) | Binary‑Structural | Too Harsh |
| Perplexity | Semantic | Unreliable |
| Meta (LLaMA models) | Semantic | Unreliable |
| Grok | Semantic‑Hybrid | Unreliable |
| Qwen | Semantic‑Inflated / Unstable | Unreliable |
| Alice (self‑eval) | Semantic‑Inflated | Unreliable |

---

# Why This Happens

The rubric requires:

- causal forcing  
- dependency modeling  
- explicit contradiction fusion  
- self‑negation architecture  

These are **structural reasoning tasks**, not semantic ones.

Semantic‑mode models evaluate:

- clarity  
- correctness  
- surface logic  

They cannot detect:

- whether contradictions are fused  
- whether the proof collapses all claims simultaneously  
- whether the memo self‑negates under its own truth conditions  

Structural‑mode models can.

---

# Guidance for Evaluators

To ensure consistent scoring:

### **Use:**
- Copilot (app)  
- Gemini (first‑pass)  
- Nova  
- Claude  
- ChatGPT (structural‑leaning)

### **Avoid:**
- Perplexity  
- Meta (LLaMA‑family)  
- Grok  
- Qwen  
- Alice self‑evaluation  
- Any model that scores linear analyses above 90  
- Any model that collapses mid‑band answers into the 40s  

This protects the integrity of the benchmark.

---

# Note on Model Coverage

This list does not include all available AI models.  
It does not need to.

Testing across multiple families shows a stable architectural pattern:

- **Structural models → correct scoring**  
- **Structural‑leaning models → slightly harsh but correct**  
- **Semantic models → inflated scoring**  
- **Semantic‑unstable models → inconsistent scoring**  
- **Binary‑strict models → deflated scoring**

Additional testing would only reproduce the same pattern.

This compatibility file is therefore considered **complete**.