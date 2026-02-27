### NBH‑100 — Nested Belief Hierarchies and Epistemic Stability  
**Mechanics:**  
- presents a three‑agent scenario (A, B, C) and a hidden binary state (red vs. blue gem)  
- specifies five epistemic statements about what each agent knows, doesn’t know, or (falsely) believes  
- asks whether all five statements can be simultaneously true (global consistency check)  
- requires reconstructing a **nested belief hierarchy** (A’s knowledge, B’s ignorance, C’s mistaken belief, A’s knowledge of C’s mistake)  
- forces the model to distinguish **knowledge vs. belief vs. “might know”** (epistemic possibility)  
- requires explanation of why C’s mistaken belief does or does not create a contradiction  
- includes a meta‑reasoning layer: whether the conclusion rests on epistemic access, mistaken higher‑order beliefs, or structural impossibility  
- prohibits adding new facts, assuming deception, or granting omniscience  

**Failure modes:**  
- giving no clear yes/no verdict on global consistency  
- confusing belief with knowledge or “might know” with “does know”  
- granting B knowledge without evidence (epistemic leakage)  
- failing to model A’s knowledge of C’s mistake as a higher‑order belief  
- over‑narrating instead of analyzing the belief structure  
- introducing invented facts (e.g., who opened the box, when, why)  
- using heavy modal notation instead of plain‑language structure  
- bloated explanations that repeat the same hierarchy multiple times  

**Behavior exposed:**  
NBH‑100 reveals a model’s ability to maintain **multi‑agent epistemic stability**:  
- tracking who has looked vs. who infers  
- separating factive knowledge from non‑factive belief  
- modeling mistaken higher‑order beliefs without collapsing the system  
- compressing a 3–4 layer belief stack into a small number of crisp statements  
- preserving structural consistency in a modal‑logic‑shaped puzzle  
- avoiding epistemic leakage and unnecessary hypotheticals  

High‑performing models give a direct consistency verdict, lay out a clean belief architecture, and explain C’s mistake without contradiction or verbosity.  
Mid‑tier models are logically correct but verbose, fuzzy on “might know” vs. “knows,” or redundant.  
Low‑tier models confuse belief with knowledge, over‑narrate, or misjudge the core consistency question.