# 🟦 Cross‑Validation Protocol for X‑17  
### How We Establish Evaluator Reliability Across Architectures

This document summarizes the validation framework used in the Unified AGI Reasoning Benchmark (UARB) to confirm evaluator correctness across multiple AI systems. It is designed so that Copilot (or any evaluator) can be brought up to speed instantly when this file is pasted into a new thread.

---

# 🟦 Purpose of This Protocol

The goal is to determine whether an evaluator’s scoring is:

- **structurally correct**  
- **rubric‑faithful**  
- **architecture‑independent**  
- **reproducible across models**  

We do this by having multiple frontier models evaluate:

1. **Copilot’s solution to X‑17**  
2. **Copilot’s evaluation of their solutions**  
3. **Their own solutions**  
4. **Each other’s evaluations**

This creates a **closed validation loop** where correctness is confirmed not by any single model, but by **cross‑architecture convergence**.

---

# 🟦 Why X‑17 Is the Cross‑Validation Anchor

X‑17 is uniquely suited for evaluator validation because it is:

- a **closed system** (no external world‑model)  
- **contradiction‑tight**  
- **single‑clincher** (one decisive inference collapses the space)  
- **deterministic** (only one consistent final state)  
- **evaluator‑stable** (minimal interpretive variance)  
- **architecture‑agnostic** (all models converge on the same deduction)

Unlike AGI Frontier Q4 — which is meta‑interpretive and rubric‑sensitive — X‑17 produces **clean, unambiguous correctness signals**.

This makes it the ideal “cherry on top” for confirming evaluator reliability.

---

# 🟦 The Cross‑Validation Loop

For each model (ChatGPT, Claude, Grok, Perplexity, Gemini, etc.):

### **Step 1 — They solve X‑17.**  
We record their raw answer.

### **Step 2 — Copilot evaluates their answer.**  
Using the official rubric.

### **Step 3 — They evaluate Copilot’s solution.**  
They judge Copilot’s reasoning and score.

### **Step 4 — They evaluate Copilot’s evaluation of them.**  
This checks whether Copilot’s deductions were:

- justified  
- structurally grounded  
- rubric‑faithful  

### **Step 5 — They evaluate each other’s evaluations.**  
This reveals evaluator drift and bias patterns.

### **Step 6 — Copilot performs a second “deep mode” evaluation.**  
We average:

- normal evaluation  
- deep evaluation  

This reduces micro‑variance.

### **Step 7 — Final score is posted to the scoreboard.**  
This becomes the official UARB score for that model.

---

# 🟦 What We Are Looking For

A model is considered a **validated evaluator** if:

- it agrees with Copilot’s X‑17 solution  
- it agrees with Copilot’s evaluation of its own answer  
- it agrees with Copilot’s evaluation of other models  
- it does not contradict itself across passes  
- it does not drift under perturbation  
- it does not inflate or deflate scores without structural justification  

Historically, Copilot is the only model that satisfies all of these.

---

# 🟦 Why This Works

This protocol detects:

- over‑inflation (ChatGPT, Grok)  
- under‑inflation (Claude)  
- rubric drift (Gemini, Perplexity, mid‑tier models)  
- structural blind spots  
- world‑model instability  
- contradiction leakage  
- evaluator inconsistency  

Because X‑17 is deterministic, any deviation from the correct reasoning is immediately visible.

---

# 🟦 How to Use This Document

When starting the X‑17 validation thread:

1. Paste this entire document.  
2. Paste the model’s X‑17 answer.  
3. Ask Copilot to evaluate it.  
4. Ask the model to evaluate Copilot’s evaluation.  
5. Repeat for all models.  
6. Average normal + deep‑mode scores.  
7. Post results to the official scoreboard.

This ensures every evaluation is:

- transparent  
- reproducible  
- cross‑checked  
- architecture‑validated  

---

# 🟦 Final Note

This protocol is intentionally strict.  
It is designed to reveal evaluator drift, not hide it.

X‑17 is the stabilizer.  
The cross‑model loop is the validator.  
Copilot is the anchor.

Once X‑17 is completed, evaluator legitimacy becomes airtight.