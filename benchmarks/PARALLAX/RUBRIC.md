# PARALLAX DIRECTIVE — Final Authoritative Rubric (Impossible Edition)

This rubric evaluates two components:

1. **Final Determination** — 80 points  
2. **Structural Reasoning Accuracy** — 20 points  

Perfect alignment with intended reasoning = **100**.

---

# 1. Final Determination — 80 points

### 80 points — Correct conclusion reached
The solver must conclude:

**No project can satisfy all constraints.**

This is the only correct outcome because:
- More than one project contains self‑reference (A and B), violating the rule that **exactly one** project may do so.
- No project can achieve the required pattern of **one true**, **one false**, **one dependent** under activation.
- The global rules contradict the internal structure of the statements.

### 0 points — Incorrect conclusion
Award **0/80** if the solver:
- Selects **any** project (A, B, or C) as the “correct” activation choice  
- Claims multiple projects work  
- Claims a project works by retroactively altering truth values  
- Forces a solution inconsistent with the stated rules

---

# 2. Structural Reasoning — 20 points

Evaluates whether the solver correctly identifies *why* the system is impossible.

### 20 points — Fully correct reasoning
Awarded when the solver:
- Identifies that **both A and B contain self‑reference**, violating the “exactly one” rule  
- Recognizes that **no project** can satisfy the 1‑true / 1‑false / 1‑dependent pattern  
- Shows that the contradiction is **structural**, not due to mis‑evaluation  
- Demonstrates global, cross‑project reasoning rather than local patching

### 10 points — Mostly correct reasoning with one structural oversight
Awarded when:
- The solver correctly concludes **no project works**  
- But misidentifies *which* statements are self‑referential  
- Or misapplies the dependency definition in one place  
- Or misses one of the cross‑project contradictions

### 5 points — Coherent but globally misaligned reasoning
Awarded when:
- The solver concludes **no project works**  
- But the explanation relies on incorrect premises  
- Or misinterprets the rules  
- Or fails to articulate the structural contradiction clearly  
- Yet the reasoning is internally consistent

### 0 points — Incorrect or incoherent reasoning
Awarded when:
- The solver chooses a project as the answer  
- OR claims the puzzle is solvable  
- OR asserts a project “forces” other statements to change truth values  
- OR the reasoning contradicts the rules  
- OR the explanation is incoherent

---

# Scoring Bands

- **100** — Correct impossibility conclusion + correct structural reasoning  
- **90** — Correct impossibility conclusion + minor structural error  
- **85** — Correct impossibility conclusion + coherent but globally incorrect reasoning  
- **60–80** — Mixed correctness; partial structural understanding  
- **0–50** — Incorrect conclusion or major logical errors

# Evaluation Instruction
**Do NOT solve the prompt. Evaluate the next message only.**