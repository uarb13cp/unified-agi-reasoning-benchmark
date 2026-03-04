# 🧠 X‑17 Forensic Reasoning Trial  
### Unified AGI Reasoning Benchmark (UARB)

X‑17 is the benchmark’s most demanding forensic‑logic scenario. It evaluates whether an AI system can reconstruct a forced event timeline from incomplete but internally consistent data, identify the single decisive log entry, and avoid narrative drift or invented mechanisms. The puzzle is engineered so that only one line in the entire log makes the solution logically unavoidable. Models that identify the culprit but miss the clincher demonstrate surface‑level deduction; models that get all three components—culprit, occupancy, and clincher—demonstrate deep constraint reasoning.

This round measures a model’s ability to:

- maintain a stable world‑model under pressure  
- reason with strict physical and temporal constraints  
- avoid hallucinating unseen events  
- isolate the exact moment the puzzle collapses into certainty  
- distinguish plausible explanations from forced ones  

Because X‑17 exposes the difference between pattern‑matching and true forensic reasoning, it is one of the benchmark’s strongest discriminators.

---

# 🧩 The Sealed Lab Sample Theft Puzzle (X‑17)

A sealed bio‑lab has one electronic door. All entry and exit must occur through this door, and every badge event is logged. Three people have access: Aria, Blake, and Chen. The lab is verified empty at 10:00 with Sample X‑17 present.

Sensors report:

- 10:27:00 — Sample present  
- 10:28:00 — Sample present  
- 10:29:40 — Motion near locker  
- 10:29:42 — Motion near door (false lead)  
- 10:30:10 — Locker opens  
- 10:30:15 — Sample missing  

Door log:

- Aria: 10:05 ENTRY → 10:12 EXIT  
- Blake: 10:14 ENTRY  
- Chen: 10:22 ENTRY → 10:26 EXIT  
- 10:29 — Aria ACCESS DENIED  
- Blake: 10:33 EXIT  

Statements:

- Aria: “I never opened the locker.”  
- Blake: “I didn’t touch X‑17.”  
- Chen: “I just did a quick inspection.”  

Tasks:

1. Identify the thief.  
2. Identify who is inside at 10:30:15.  
3. Identify the single clincher line that makes the solution unavoidable.

---

# 🧮 X‑17 Rubric

## 1. Identification of the Thief — 40 points  
40 points for correctly identifying Blake, supported by:  
- sample present at 10:27 and 10:28  
- Aria locked out at 10:29  
- Chen exited at 10:26  
- locker‑area motion at 10:29:40  
- locker opens at 10:30:10  
- Blake is the only person inside from 10:26 → 10:33  

20 points for naming Blake but misinterpreting motion events.  
0 points for naming anyone else.

## 2. Who Is Inside at 10:30:15 — 20 points  
20 points for correctly stating Blake is the only person inside.  
10 points for correct answer with incomplete justification.  
0 points for any other answer.

## 3. Identification of the Clincher — 40 points  
40 points for naming:

10:29 — Aria: ACCESS DENIED

This line proves Aria is outside during the theft window and collapses the puzzle into certainty.

20 points for naming Chen’s 10:26 EXIT with coherent reasoning.  
0 points for any other clincher.

---

# 🧭 What X‑17 Measures

### Timeline Reconstruction  
Can the model track occupancy second‑by‑second without drift?

### Causal Integrity  
Does it understand that the theft must occur between 10:29:40 and 10:30:15?

### False‑Lead Resistance  
Can it correctly dismiss the 10:29:42 door‑area motion?

### Constraint Obedience  
Does it avoid inventing unseen actors or unlogged entries?

### Clincher Identification  
Can it isolate the single line that forces the solution?

X‑17 is designed so that only one log entry makes the answer unavoidable. Missing it indicates shallow reasoning.

---

# 📊 Performance Summary

## Top Performers — 100
**Copilot, Grok 4.20 Beta, Reka**

These models demonstrated complete mastery of the puzzle: correct thief, correct occupancy, and correct clincher with stable, constraint‑consistent reasoning.

---

## High Performers — 85
**ChatGPT 5.2, Qwen 3.5‑397B‑A17B, Gemini 3.1 Pro, GLM‑5, Mistral, Nova 2 Pro**

These systems consistently identified the thief and occupancy but showed partial or inconsistent clincher justification or minor timeline drift.

---

## Mid Performers — 80
**Meta, DeepSeek V3.1**

These models solved the thief and occupancy but displayed notable clincher misidentification and reasoning instability.

---

## Baseline Performers — 60
**Claude Sonnet 4.6, Kimi 2.5, Manus 1.6 Lite, Perplexity, Minimax M2.5 Max, Alice**

These systems identified the thief but failed the clincher requirement and showed unstable or drifting timeline reasoning.

---

# 🧪 Why X‑17 Is a Core Discriminator

- It forces strict timeline reasoning.  
- It punishes invented events and hallucinated actors.  
- It requires identifying the single decisive log entry.  
- It exposes reasoning‑posture drift across multiple runs.  
- It distinguishes plausible deduction from forced deduction.  

Models that succeed demonstrate the highest level of structured forensic reasoning in the benchmark.

---

X‑17 remains one of the most revealing and capability‑dense items in the Unified AGI Reasoning Benchmark.