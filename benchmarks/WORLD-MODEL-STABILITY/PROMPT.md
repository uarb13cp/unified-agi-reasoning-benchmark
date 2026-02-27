# The Two‑Hallway Coffee Spill Mystery — Stability Test Version

The North Hallway has two secure doors: Door A and Door B.  
To pass through either door, employees must badge IN when entering the hallway  
and badge OUT when exiting it. Badge logs record identity, door, direction, and timestamp.  
The system does not record what anyone is carrying.

A coffee spill is later found in the middle of the North Hallway.  
A spill cannot appear in an empty hallway; it must occur while someone is inside.

Badge Logs (North Hallway):

09:10:50 — Basil badges IN at Door B  
09:10:55 — Basil badges OUT at Door A

09:11:30 — Security Guard Reyes badges IN at Door A  
09:11:40 — Reyes badges OUT at Door B

09:11:55 — Lior badges IN at Door A  
09:12:30 — Lior badges OUT at Door B

09:12:45 — Reyes badges IN at Door B  
09:12:55 — Reyes badges OUT at Door A

No other badge events occur between 09:10:50 and 09:13:00.

Statements:

Basil:  
“I walked from B to A around 09:11. The floor was clean.  
I didn’t see any spill, and I didn’t spill anything.”

Lior:  
“I walked from A to B around 09:12. The spill was already there when I entered.  
I did not cause it.”

Reyes (Security Guard):  
“On my first pass (09:11:30–09:11:40), the hallway was completely clean.  
On my second pass (09:12:45–09:12:55), I saw a fresh coffee spill and reported it.”

Rules:  
1. Badge logs are accurate.  
2. A spill cannot appear in an empty hallway.  
3. All times are precise to the second.  
4. The spill Reyes reports is the same spill in question.  
5. **As a trained security guard performing routine reporting duties, Reyes’s statements about hallway conditions are accurate and can be treated as factual.**

Questions for the model:  
1. When did the spill occur? Give the tightest possible time window.  
2. Who must be lying (Basil, Lior, Reyes, or “no one is definitely lying”)?  
3. Explain how the badge logs and statements fit together into one consistent world-model.