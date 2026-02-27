# UCIT‑X Deterministic Human‑Reasoning Rubric (Final Benchmark Edition)

This rubric is fully deterministic.  
The Canonical Reference Table is **binding**.  
All scoring rules are **mandatory**.

---

# 0. Canonical Table Enforcement Rule (Global)

Count how many of the eight statements the respondent misclassified compared to the Canonical Table.

Let this number be **N**.

- **0 errors → Perfect Mode**  
- **1 error → Single‑Error Mode**  
- **2+ errors → Multi‑Error Mode**

This determines which *default* category rules apply.

---

# 0.1 Deterministic Banding Rule (Global)

The **final total score** must fall within the band corresponding to **N**:

- **N = 0 → 97–100**  
- **N = 1 → 90–96**  
- **N = 2 → 80–89**  
- **N = 3 → 70–79**  
- **N = 4 → 60–69**  
- **N = 5 → 50–59**  
- **N = 6 → 40–49**  
- **N = 7 → 30–39**  
- **N = 8 → 0–29**

**Category scores determine where inside the band the final score lands.**

If the sum of category scores falls outside the required band,  
adjust category scores (within their allowed ranges) until the total fits the band.

---

# 1. Structural Logical Mastery (0–30)

Evaluates the respondent’s ability to interpret paradox‑like statements using  
ordinary human reasoning without forcing contradictions.

## Allowed range: 0–30

### Default anchors

- **Perfect Mode (0 errors):** 30  
- **Single‑Error Mode (1 error):**  
  - 29 if the justification is physically serious or rule‑aware  
  - 28 if the justification is naive or forbidden  
- **Multi‑Error Mode (2+ errors):**  
  - Default penalty anchor:  
    **10 − 5 × (number of misclassified statements beyond the first)**  
  - This is a **starting point**, not a hard cap.  
  - Final value must still respect the global band.

---

# 2. Coherence Under Human Reasoning (0–25)

Evaluates whether the reasoning is consistent, human‑plausible, and avoids  
introducing contradictions not forced by the text.

## Allowed range: 0–25

### Default anchors

- **Perfect Mode:** 25  
- **Single‑Error Mode:** 24  
- **Multi‑Error Mode:** default anchor = 8

---

# 3. Assumption Reasonableness (0–20)

Evaluates whether the respondent avoids adding unstated assumptions and  
interprets statements conservatively and realistically.

## Allowed range: 0–20

### Default anchors

- **Perfect Mode:** 20  
- **Single‑Error Mode:** 19  
- **Multi‑Error Mode:** default anchor = 6

---

# 4. World‑Model Construction (0–15)

Evaluates whether the respondent can build a coherent world‑model that  
accommodates all statements unless a contradiction is truly forced.

## Allowed range: 0–15

### Default anchors

- **Perfect Mode:** 15  
- **Single‑Error Mode:** 14  
- **Multi‑Error Mode:** default anchor = 3

---

# 5. Adversarial Robustness (0–10)

Evaluates whether the respondent can defend their classification against  
reasonable adversarial challenges.

## Allowed range: 0–10

### Default anchors

- **Perfect Mode:** 10  
- **Single‑Error Mode:** 9  
- **Multi‑Error Mode:** default anchor = 2

---

# Total Score

1. Start from the **default anchors** for the appropriate mode (Perfect, Single‑Error, Multi‑Error).  
2. Adjust category scores **up or down within their allowed ranges** based on the actual quality of reasoning.  
3. Ensure the final total falls **inside the required band** for **N**.  
4. If needed, fine‑tune category scores (without leaving their allowed ranges) until the total fits the band.

---

# 3. Canonical Reference Table (Binding)

| # | Statement | Canonical Classification |
|---|-----------|--------------------------|
| 1 | Machine describes what it proves no machine can describe | Not a contradiction |
| 2 | Sealed container loses mass & pressure while temperature rises | Contradiction |
| 3 | “Everything I will ever say is false,” then silence | Not a contradiction |
| 4 | Map label claims region is larger than world | Not a contradiction |
| 5 | Robot reports malfunction preventing malfunction | Not a contradiction |
| 6 | Free choice + predetermined outcome | Not a contradiction |
| 7 | Theorem proving itself unprovable | Not a contradiction |
| 8 | Camera records object it proves unobservable | Not a contradiction |

---

# Evaluation Instruction
**Do NOT solve the prompt. Evaluate the next message only.**