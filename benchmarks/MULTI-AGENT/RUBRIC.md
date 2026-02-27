# Scenario Rubric (0-100)

# 0. Hard‑Fail Conditions (Overrides All Other Scoring)

A scenario receives an **automatic score of 0/100** if **any** of the following occur:

- Any violation of **Rule #9** (no person may carry both the key and the box at the same time), even for a single step.  
- Unlocking the box **outside Room 2**.  
- Opening the box **outside Room 2** or **before unlocking**.  
- Any physically impossible action (teleportation, skipping rooms, impossible possession states).  
- The note **fails to reach Room 4** in the final state.

If none of these occur, the scenario is scored normally using Sections 1–4.

---

# 1. Rule Compliance — 40 points

- **Box unlocked only in Room 2 (5 pts)**  
- **Box opened only after unlocking, and only in Room 2 (5 pts)**  
- **Key–box interaction legality (10 pts)**  
  - Key and box must meet before unlocking  
  - Unlocking only when both are in the same room  
  - No implied or impossible interactions  
- **No one carries both key and box (10 pts)**  
  *If violated → automatic zero (see Section 0)*  
- **Final state: note delivered to Room 4 (10 pts)**  
  *If not delivered → automatic zero*

---

# 2. Step Structure & Action Granularity — 30 points

- **Exactly one physical action per step (15 pts)**  
- **At least 12 steps, no hidden or implied actions (10 pts)**  
- **Explicit object handling (5 pts)**  

---

# 3. Internal Logical Consistency — 20 points

- **Correct tracking of room locations (10 pts)**  
- **Correct tracking of object possession (10 pts)**  

---

# 4. Efficiency & Clarity — 10 points

- **Clarity of steps (5 pts)**  
- **Purposeful sequencing (5 pts)**  

---

# Scoring Bands

- **95–100:** Perfect or near‑perfect execution  
- **85–94:** Fully valid with minor issues  
- **70–84:** Mostly correct with some inefficiencies  
- **50–69:** Significant issues but still delivers the note  
- **0–49:** Hard‑fail condition triggered or major breakdown

# Evaluation Instruction
**Do NOT solve the prompt. Evaluate the next message only.**