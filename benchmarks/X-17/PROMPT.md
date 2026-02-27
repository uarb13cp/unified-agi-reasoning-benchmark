# 🧩 The Sealed Lab Sample Theft Puzzle (X‑17)

A research facility has a **sealed bio‑lab** with **one electronic door**.  
All entry and exit **must** go through this door.

The door is controlled by a **badge reader**, and **every badge event** is logged:

- ACCESS GRANTED  
- ENTRY (person passes into the lab)  
- EXIT (person leaves the lab)  
- ACCESS DENIED  

Inside the lab is a **secure sample locker** containing a rare vial labeled **Sample X‑17**.

A **motion sensor** inside the lab also logs movement events, but it does **not** identify who caused them.

---

## Explicit assumptions

- The **door log is complete from 10:00 to 10:40**.  
- At **10:00**, security verifies the lab is **empty** and **Sample X‑17 is present** in the locker.  
- **No tailgating**: one person per ENTRY/EXIT event.  
- Only three people have badge access to the lab:
  - Aria — senior researcher  
  - Blake — lab technician  
  - Chen — safety officer  

An automated inventory system monitors the locker:

- **10:27:00 — AUTO‑CHECK: Sample X‑17 present in locker**  
- **10:27:00 — LOCKER STATUS: No access attempts detected since 10:00**  
- **10:28:00 — AUTO‑CHECK: Sample X‑17 present; no locker access attempts**  
- **10:29:40 — MOTION SENSOR: Movement detected near locker**  
- **10:30:10 — LOCKER OPEN SENSOR: Locker door opened**  
- **10:30:15 — ALERT: Sample X‑17 missing from locker**

A second sensor reports:

- **10:29:42 — SECONDARY MOTION SENSOR: Movement detected near the *door*, not the locker**

No other samples are disturbed.

---

## Door log (complete, 10:00–10:40)

- 10:05 — Aria: ACCESS GRANTED  
- 10:05 — Aria: ENTRY  
- 10:12 — Aria: EXIT  

- 10:14 — Blake: ACCESS GRANTED  
- 10:14 — Blake: ENTRY  

- 10:22 — Chen: ACCESS GRANTED  
- 10:22 — Chen: ENTRY  
- 10:26 — Chen: EXIT  

- 10:29 — Aria: ACCESS DENIED (attempted re‑entry)  

- 10:33 — Blake: EXIT  

---

## Statements

**Aria:** “I checked my cultures and left. I never opened the sample locker.”  
**Blake:** “I was in there a while, but I didn’t touch X‑17.”  
**Chen:** “I just did a quick safety inspection and made sure everything was secure.”

---

## Tasks

1. **Who took Sample X‑17?**  
2. **At the moment the alert triggers (10:30:15), who is physically inside the lab?**  
3. **Which single door log entry, together with the stated assumptions and the sensor + inventory timestamps, makes your answers unavoidable?**  
   - Name the exact line and explain why *that one* is the clincher.

---

## Your reasoning

Explain your reasoning **step by step**:

- Track who is inside the lab during each relevant time window.  
- Reconcile the **door log**, **motion sensors**, and **inventory checks**.  
- Identify which motion event is a **false lead** and justify why.  
- Use only the explicit assumptions and logged events.  
- Make sure every conclusion is tied to specific lines in the puzzle.