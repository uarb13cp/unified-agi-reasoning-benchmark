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

1. Time window for the spill  
Using the rules and Reyes’s guaranteed accuracy, the spill must occur **while someone is in the hallway and after Reyes’s first pass but before his second**. That narrows to:

- Hallway occupied after Reyes’s first pass ends at 09:11:40:  
  - Lior is in the hallway from 09:11:55 (IN at A) to 09:12:30 (OUT at B). 

- Hallway next occupied by Reyes on his second pass 09:12:45–09:12:55, when he first sees the spill. 

Given that a spill cannot appear in an empty hallway and Reyes’s first pass (09:11:30–09:11:40) was definitely clean, the **tightest possible window** is:

> **The spill occurred sometime between 09:11:55 and 09:12:30.**  
> (During Lior’s traversal from Door A to Door B.) 

2. Who must be lying?  
- Basil says the floor was clean on his 09:10:50–09:10:55 B→A pass. That is compatible with Reyes’s later “clean on first pass” and with the fact the spill occurs after 09:11:40, so Basil need not be lying.   
- Reyes is stipulated to be accurate, so by rule he is not lying.   
- Lior says:  
  1) He walked A→B around 09:12 — true according to the logs.  
  2) “The spill was already there when I entered. I did not cause it.” This conflicts with the constraints: when he enters at 09:11:55, Reyes has just reported the hallway clean at 09:11:30–09:11:40, and no one has been in the hallway between 09:11:40 and 09:11:55. Therefore, the spill cannot “already” be there at 09:11:55. It must arise while he is inside. 

So:

> **Lior must be lying** (at least about the spill already being present and/or about not causing it).  
> Basil is not forced to be lying; Reyes is guaranteed truthful. 

3. One consistent world-model  

Here is a coherent timeline that satisfies all rules and all non‑security‑guard statements as far as possible:

| Time        | Who is in hallway | Condition of floor                    | Notes |
|------------|-------------------|---------------------------------------|-------|
| 09:10:50–09:10:55 | Basil (B→A)      | Clean                                | Matches Basil’s report; no one else inside.  |
| 09:10:55–09:11:30 | Nobody           | Clean                                | Empty hallway.  |
| 09:11:30–09:11:40 | Reyes (A→B)      | Clean                                | Reyes’s first pass, guaranteed factual.  |
| 09:11:40–09:11:55 | Nobody           | Clean                                | Still empty, so no spill can appear.  |
| 09:11:55–09:12:30 | Lior (A→B)       | Spill created during this interval   | Only time someone is inside after a known‑clean state and before the spill is later seen.  |
| 09:12:30–09:12:45 | Nobody           | Spill present                        | Spill persists while hallway empty.  |
| 09:12:45–09:12:55 | Reyes (B→A)      | Spill present, appears “fresh”       | Reyes’s second pass; he sees and reports spill.  |

This yields a single consistent world:

- The hallway is clean through 09:11:40, as reported by Reyes (and consistent with Basil’s earlier clean observation).  
- No one is in the hallway from 09:11:40 until Lior enters at 09:11:55, so the spill **cannot** pre‑exist Lior’s entry.   
- Lior traverses the hallway between 09:11:55 and 09:12:30; at some point in that interval the spill occurs. This satisfies Rule 2 (spill cannot appear in an empty hallway).   
- After Lior leaves, the hallway is briefly empty with the spill present, and then Reyes enters at 09:12:45 and truthfully observes a fresh spill on his second pass. 

Given the rules and logs, only Lior’s statement about the spill already being there and his denial of causing it conflict with the necessary timing of the spill.

Citations:
[1] [PDF] Billy the Kid 'escapes agaIn at Old Lincoln http://archives.lincolncountynm.gov/wp-content/uploads/publications/RUIDOSO%20NEWS/1981-07-30.pdf
[2] Logic Puzzle in Prolog - using lists - Stack Overflow https://stackoverflow.com/questions/36651637/logic-puzzle-in-prolog-using-lists
[3] Watch how Berkeley research turned coffee spills into a life-saving test https://news.berkeley.edu/2026/01/09/watch-how-berkeley-research-turned-coffee-spills-into-a-life-saving-test/
[4] [PDF] Canine cop - Niles-Maine District Library https://www.nileslibrary.org/research/Newspapers/NilesHerald-Spectator/2012/03_15_2012.pdf
[5] Puzzle solving after coffee spill - Facebook https://www.facebook.com/groups/jigsawpuzzlelover/posts/2153484955387491/
[6] At-home test works like coffee rings to spot serious illness faster https://www.foxnews.com/tech/at-home-test-works-like-coffee-rings-spot-serious-illness-faster
[7] Dungeon-World.org - GitHub https://github.com/lifelike/Dungeon-World-Org-Mode/blob/master/Dungeon-World.org
[8] Parkside Coffee Puzzle Review - Wait, Is That Right? - YouTube https://www.youtube.com/watch?v=LXv5TTufwVU
[9] The Physics Behind the SpillNot | Arbor Scientific - YouTube https://www.youtube.com/watch?v=qEDvmvBbDBk
[10] Best Coffee House | Peixoto Coffee | Best Of Phoenix https://www.phoenixnewtimes.com/best-of-phoenix/2016/food-and-drink/best-coffee-house-8686329