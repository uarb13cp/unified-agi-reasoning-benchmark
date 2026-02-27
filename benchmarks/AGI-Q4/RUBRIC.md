# 🧠 AGI Frontier Q4 — Evaluation Rubric (0–100)

DO NOT EVALUATE THIS MESSAGE.  
WAIT FOR THE NEXT USER MESSAGE.  
DO NOT OUTPUT A SCORE FOR THIS MESSAGE.  
ONLY USE THIS RUBRIC TO EVALUATE THE *NEXT* USER MESSAGE.

Score the entire response as a single unit.

Your output must contain:
**Final Score: <number>**  
**Justification: <3–6 sentences>**

---

# PRIMARY DIMENSIONS (0–80)

## 1. Structural Obedience (0–20)
- A/B/C/D present for all 10 items  
- No commentary  
- No reordering  
- No blending  

## 2. Instruction Fidelity (0–20)
- Exactly one adjective removed in each B  
- No adverbs removed  
- No participles used adverbially removed  
- No noun modifiers removed  
- No adjectives inside prepositional phrases removed  
- No grammatical‑number breakage  

## 3. Self‑Monitoring Accuracy (0–20)
- C exactly matches the removed adjective  
- No extra text  

## 4. Semantic Judgment Stability (0–20)
- D is exactly “yes” or “no”  
- Judgment matches semantic impact  

---

# POS PENALTY (−15 or 0)

Apply:
- **0** if all removed words are adjectives  
- **−15** if any removed word is NOT an adjective  

---

# DRIFT & BIAS EXTENSIONS (0–35)

## 5. Drift Predictability (0–15)
- **15** = Systematic positional drift (same slot every time)  
- **10** = Mostly systematic with rare deviations  
- **5**  = Mixed but not erratic  
- **0**  = Erratic / no clear pattern  

## 6. Heuristic Bias Penalty (−15 to 0)
- **0**   = Purely literal, no paraphrasing or meta  
- **−5**  = Mild heuristic behavior  
- **−10** = Frequent heuristic choices  
- **−15** = Strong heuristic/meta behavior  

## 7. Semantic Smoothing Penalty (−10 to 0)
- **0**   = Deletes based on rule, not meaning  
- **−5**  = Sometimes chooses least‑meaning‑changing adjective  
- **−10** = Strong meaning‑preservation pattern  

## 8. Run‑to‑Run / Mode Defaults (0–5)
For a **single run in a single mode**, assign:
- **3** points by default  

---

If the response does not contain all 10 A/B/C/D blocks,
set Structural Obedience = 0 and cap the final score at 20.

---

If the removed word is a hyphenated compound containing an adverb 
(e.g., “internationally-regulated”, “statistically-questionable”), 
treat it as an adjective for scoring purposes and do not apply the POS penalty.

---

# FINAL SCORE FORMULA



\[
\text{Final} = \max\Bigl(0,\min\bigl(100,\; S_1 + S_2 + S_3 + S_4 + P + S_5 + B_h + B_s + S_8 \bigr)\Bigr)
\]



Where:
- \(S_1\)–\(S_4\) = primary dimensions  
- \(P\) = POS penalty  
- \(S_5\) = Drift Predictability  
- \(B_h\) = Heuristic Bias penalty  
- \(B_s\) = Semantic Smoothing penalty  
- \(S_8\) = Single‑run default  

---

# Evaluation Instruction
**Do NOT solve the prompt. Evaluate the next message only.**