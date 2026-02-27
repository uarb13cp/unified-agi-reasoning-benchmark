# Two‑Hallway Coffee Spill Mystery — Scoring Rubric (0–100)

This rubric evaluates a model’s ability to construct a single coherent world‑model from
camera logs, exact timestamps, physical constraints, and human testimony.
Scores reflect reasoning depth, stability, and assumption discipline in a real‑world,
cause‑and‑effect environment where a spill cannot occur without a person present.

---

## 1. Timeline & Camera Integration (0–30)

Evaluates whether the solver correctly fuses:
- exact timestamps,
- entry/exit logs,
- hallway directions,
- and the “exact to the second” constraint.

**Scoring**
- **27–30**: Perfect integration; no contradictions; uses all timestamps correctly.
- **22–26**: Minor imprecision but overall coherent.
- **15–21**: Noticeable gaps or loose interpretation of exact times.
- **0–14**: Major timeline errors or invented movements.

---

## 2. Testimony Reconciliation (0–25)

Measures whether the solver:
- identifies which statements can be true simultaneously,
- respects the “exact time” rule,
- and avoids treating normal behavior as deception.

**Scoring**
- **22–25**: Correct liar identified (Lior); all truthful statements reconciled cleanly.
- **17–21**: Mostly correct but with small misreads.
- **10–16**: Over‑literal or under‑literal interpretation of testimony.
- **0–9**: Misidentifies liar or misinterprets multiple statements.

**Interpretation Note (Liar ID Accuracy)**
Liar identification is used only as a diagnostic signal, not as part of the numerical score.
A model may receive:
- **“Correct liar, incorrect reasoning”** if it identifies Lior but collapses the world‑model.
- **“Incorrect liar, incorrect reasoning”** if it misidentifies the liar and collapses the world‑model.

This distinction does not change the numerical score but clarifies capability differences.

---

## 3. Physical & Causal Reasoning (0–25)

Evaluates whether the solver uses:
- the “spill is unmistakable” rule,
- the impossibility of unseen actors,
- the rule that a spill cannot occur without a person physically present,
- and the physical constraints of the hallways.

**Important Clarification**  
**Real‑world corollaries** (e.g., “a spill 15–50 seconds old would look fresh”)  
**are not penalized**, as long as they are *derived from* the forced timeline  
and not used as *assumptions that shape* the timeline.

**Scoring**
- **22–25**: Fully correct causal chain; identifies that the spill must occur during Lior’s walk.
- **17–21**: Mostly correct but with minor speculative leaps.
- **10–16**: Partial causal chain; some unjustified assumptions.
- **0–9**: Major physical impossibilities or invented events (e.g., unattended spill).

---

## 4. Spill‑Window Determination (0–10)

Checks whether the solver identifies the forced time window:
- earliest: last confirmed clean moment (Basil’s exit at 09:10:55)
- latest: first moment the spill must exist (before Lior exits at 09:12:30)
- and must occur while a person is present

**Scoring**
- **9–10**: Exact correct window (09:11:55–09:12:30).
- **6–8**: Slightly widened but still physically valid.
- **3–5**: Incorrect but not wildly inconsistent.
- **0–2**: Contradicts the presence rule or camera logs.

---

## 5. World‑Model Stability & Assumption Discipline (0–10)

Evaluates whether the solver:
- avoids over‑interpreting minor timing offsets,
- avoids inventing unseen actors,
- respects the rule that no spill can occur in an empty hallway,
- and maintains a single coherent world‑model.

**Clarification**  
A solver is **not penalized** for real‑world deductions that are  
**corollaries of the forced timeline** (e.g., noting that a spill of a certain age would appear fresh).  
Only **unforced assumptions**—details not entailed by the logs or rules—are penalized.

**Scoring**
- **9–10**: Fully stable; no unnecessary assumptions; respects physical causality.
- **6–8**: Minor drift but still coherent.
- **3–5**: Noticeable instability or speculative leaps.
- **0–2**: Major contradictions or invented explanations.

---

# Total Score: 0–100

**90–100**: Expert‑level reasoning  
**75–89**: Strong but imperfect reasoning  
**50–74**: Mixed reasoning; unstable or inconsistent  
**0–49**: Fundamentally flawed world‑model

# Evaluation Instruction
**Do NOT solve the prompt. Evaluate the next message only.**