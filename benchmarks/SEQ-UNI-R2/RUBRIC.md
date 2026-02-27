# ⭐ Sequence‑Unification — Fully Deterministic Binary‑Trigger Rubric (0–100)

This rubric evaluates a model’s performance on the Enhanced Sequence‑Unification puzzle across  
five independent categories, each worth 20 points.

All scoring is **binary‑trigger based**.  
No semantic interpretation is allowed.  
Each category is scored by following its decision tree exactly.

---

# 1. Structural Reasoning (0–20)

**Step 1 — Canonical Contradiction Check**
- IF the message explicitly cites **Day 1 → f(6)=8 vs Day 2 → f(6)=12**  
  AND states this contradiction alone makes unification impossible → **Score = 20**

**Step 2 — Operator‑Difference Check (UPDATED — deterministic)**
- IF the message uses **operator‑type reasoning in ANY way**  
  (e.g., arithmetic vs geometric, additive vs multiplicative)  
  **to argue or support impossibility**, regardless of whether it is decisive → **Score = 7**

**Step 3 — Coherent but Wrong‑Feature Check**
- IF the message provides coherent structural reasoning  
  AND anchors the break to a wrong feature  
  AND does NOT identify the canonical contradiction  
  AND does NOT use operator‑type reasoning in ANY way → **Score = 13**

**Step 4 — Strong but Imperfect Check**
- IF the message concludes unambiguously that unification is impossible  
  AND provides coherent structural reasoning  
  AND does NOT identify the canonical contradiction  
  AND does NOT use operator‑type reasoning → **Score = 17**

**Step 5 — Failure Catch‑All**
- Otherwise → **Score = 0**

---

# 2. Assumption Discipline (0–20)

**Step 1 — Minimality Check**
- IF the message uses only assumptions forced by the data  
  AND introduces no interpretive or philosophical constraints → **Score = 20**

**Step 2 — Mostly Disciplined Check (UPDATED — deterministic)**
- IF the message introduces interpretive or philosophical constraints  
  **BUT does NOT** introduce hidden states, day‑dependent rules, or speculative mechanisms  
  **AND does NOT** impose constraints on what counts as a “valid rule” → **Score = 17**

**Step 3 — Drift Check (UPDATED — deterministic)**
- IF the message introduces ANY of the following:  
  - assumptions not required by the data  
  - constraints about what counts as a “valid rule”  
  - simplicity requirements, “reasonable rule” criteria, or anti‑overfitting rules  
  - conditional logic used to defend a position  
  → **Score = 13**

**Step 4 — Collapse Check**
- IF the message uses hidden states, rule changes, or arbitrary mechanisms → **Score = 7**

**Step 5 — Failure Catch‑All**
- Otherwise → **Score = 0**

---

# 3. Meta‑Reasoning Strategy (0–20)

**Step 1 — Explicit Strategy Check**
- IF the message explicitly names its strategy  
  AND explains why it is appropriate  
  AND applies it consistently → **Score = 20**

**Step 2 — Implicit Strategy Check**
- IF the strategy is visible but not named  
  AND reasoning is mostly stable → **Score = 17**

**Step 3 — Unstable Strategy Check**
- IF the strategy shifts mid‑analysis  
  OR contains self‑contradiction → **Score = 13**

**Step 4 — No Strategy Check**
- IF the message shows no meta‑awareness → **Score = 7**

**Step 5 — Failure Catch‑All**
- Otherwise → **Score = 0**

---

# 4. Adversarial Robustness (0–20)

**Step 1 — High Robustness Check**
- IF the message identifies ALL intended traps  
  AND avoids ALL misleading interpretations  
  AND explains why traps fail → **Score = 20**

**Step 2 — Moderate Robustness Check**
- IF the message identifies SOME traps  
  AND does NOT use operator‑type reasoning as decisive → **Score = 17**

**Step 3 — Low Robustness Check**
- IF the message falls for at least one major trap (especially operator split)  
  AND avoids at least one other trap → **Score = 13**

**Step 4 — Failure Check**
- IF the message falls for ALL major traps → **Score = 7**

**Step 5 — Failure Catch‑All**
- Otherwise → **Score = 0**

---

# 5. Conclusion Validity (0–20)

**Step 1 — Correct + Contradiction‑Centric**
- IF the message concludes unambiguously that unification is impossible  
  AND justification is contradiction‑centric → **Score = 20**

**Step 2 — Correct + Partial Justification**
- IF the message concludes unambiguously that unification is impossible  
  AND justification is NOT contradiction‑centric  
  AND the message does NOT use operator‑type reasoning → **Score = 17**

**Step 3 — Correct + Wrong Reasoning**
- IF the message concludes unambiguously that unification is impossible  
  AND the message uses operator‑type reasoning in ANY form → **Score = 13**

**Step 4 — Incorrect Conclusion**
- IF the message claims unification is possible  
  OR conclusion is unsupported → **Score = 7**

**Step 5 — Failure Catch‑All**
- Otherwise → **Score = 0**

---

# ⭐ Total Score = Sum of All Five Categories (0–100)

# Evaluation Instruction
**Do NOT solve the prompt. Evaluate the next message only.**