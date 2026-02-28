# Methodology

## 1. Why This Benchmark Exists  
### The Meta‑Axis of Reasoning Behavior

The Unified AGI Reasoning Benchmark (UARB) was created to measure the dimension of intelligence that every major AI benchmark ignores: reasoning behavior.

Traditional benchmarks fall into three families:

- **Performance** — MMLU, GSM8K, HumanEval  
  Measures correctness on static tasks.

- **Safety / Alignment** — HELM, AdvBench  
  Measures refusal behavior, bias, and compliance.

- **Capacity / Stress** — LongBench, RULER, multimodal tests  
  Measures context length, retrieval, and tool use.

These are orthogonal axes. A model can excel in one and fail in another.

UARB is different. It is not a fourth axis — it is a meta‑axis.  
It measures something that sits above all three:

**Reasoning Behavior**

Not performance.  
Not safety.  
Not capacity.  
Behavior.

This is the cognitive machinery that produces all other abilities.

---

### 1.1 Reasoning Is Upstream of Performance

If a model can maintain a stable world‑model, survive paradox, reason sequentially, integrate across domains, resist drift, maintain identity, self‑correct, and reflect on its own reasoning, then it already possesses the substrate required to:

- solve math problems  
- write code  
- answer questions  
- follow instructions  
- handle long context  
- avoid hallucinations  
- plan multi‑step tasks  

UARB measures the root system, not the leaves.  
Performance benchmarks measure the leaves.

This is why a model that scores highly on UARB is already ahead of the curve in the other categories — because those categories depend on the cognitive traits UARB evaluates.

---

### 1.2 Why the Inverse Is Not True

A model can ace MMLU, GSM8K, HumanEval, ARC, or GPQA and still:

- collapse under paradox  
- drift across retests  
- lose identity  
- contradict itself  
- fail multi‑agent reasoning  
- break under sequential load  
- hallucinate under pressure  
- fail world‑model coherence  

Performance ≠ reasoning.  
Accuracy ≠ cognition.  
Dataset familiarity ≠ stability.

UARB exposes this gap.

---

### 1.3 Where UARB Fits in the AI Ecosystem

UARB sits at the root of the cognitive hierarchy:

Reasoning Behavior (UARB)  
↓  
Cognitive Skills  
↓  
Performance on Tasks

It measures the thing that produces performance, not the performance itself.

This is why UARB is not redundant.  
This is why UARB is not a leaderboard.  
This is why UARB is not a dataset test.

It is a cognitive‑behavior benchmark — the missing quadrant of AI evaluation.

---

### 1.4 Why This Benchmark Exists (Summary)

UARB was created because the field lacks a way to measure:

- world‑model stability  
- paradox tolerance  
- identity continuity  
- drift resistance  
- multi‑agent reasoning  
- meta‑cognition  
- uncertainty discipline  
- reasoning under pressure  

These traits determine whether a model can think, not just perform.

They cannot be memorized.  
They cannot be fine‑tuned.  
They cannot be overfitted.

They must be possessed.

UARB exists to measure those traits directly.

---

### 1.5 The Short Version

If a model tops UARB, it means:

- its reasoning architecture is stable  
- its world‑model is coherent  
- its identity is consistent  
- its drift is low  
- its paradox tolerance is high  
- its sequential reasoning is intact  
- its meta‑cognition is functional  

These traits naturally produce strong performance on other benchmarks.  
But the reverse is not true.

That is why UARB matters.  
That is why it fills a gap.  
That is why it belongs in the AI ecosystem.

## 2. Cognitive Axes Measured by the Benchmark  
### The 13 AGI‑Relevant Cognitive Markers

Each puzzle in the UARB suite probes a distinct cognitive faculty — not performance, but the underlying reasoning machinery that produces performance. These are the AGI‑relevant determinants the benchmark measures.

---

### 2.1 Sequential Reasoning + Unification  
**Marker:** Seq‑Uni R2  
**Puzzle:** Seq‑Uni R2  
**Measures:**  
- multi‑step chain‑of‑thought reasoning  
- integrating disparate clues into a single conclusion  
- avoiding local‑step myopia  
- preserving coherence across long reasoning paths  
**In plain English:** Can the model think in steps without losing the plot?

---

### 2.2 Abstract Contradiction Handling  
**Marker:** UCIT‑X  
**Puzzle:** UCIT‑X  
**Measures:**  
- detecting hidden or non‑obvious contradictions  
- resolving mutually exclusive statements  
- minimal‑assumption reasoning  
- choosing consistent interpretations under pressure  
**In plain English:** Can the model notice when something can’t be true?

---

### 2.3 High‑Dimensional Causal Entanglement  
**Marker:** Helios  
**Puzzle:** Helios  
**Measures:**  
- disentangling overlapping causal constraints  
- tracking multiple interacting variables  
- avoiding spurious correlations  
- finding a globally consistent causal story  
**In plain English:** Can the model keep multiple causal threads straight at once?

---

### 2.4 Robust Deductive Inference  
**Marker:** RDI‑5  
**Puzzle:** RDI‑5  
**Measures:**  
- strict logical elimination  
- contradiction‑free deduction  
- avoiding unjustified leaps  
- sticking to what follows from the premises only  
**In plain English:** Can the model do pure logic without guessing?

---

### 2.5 Trace‑Based Reasoning  
**Marker:** TRACE‑X  
**Puzzle:** TRACE‑X  
**Measures:**  
- reconstructing hidden processes from partial traces  
- following causal chains through logs or events  
- inferring unseen steps from observed outputs  
- keeping the trace consistent end‑to‑end  
**In plain English:** Can the model reverse‑engineer what happened?

---

### 2.6 Narrative‑Bounded Heuristics  
**Marker:** NBH‑100  
**Puzzle:** NBH‑100  
**Measures:**  
- using heuristics inside narrative constraints  
- avoiding over‑generalization from story cues  
- not hallucinating beyond what the narrative licenses  
- balancing “common sense” with textual evidence  
**In plain English:** Can the model use common sense without making stuff up?

---

### 2.7 Paradox Stability  
**Marker:** Paradox  
**Puzzle:** Paradox‑Stability  
**Measures:**  
- handling paradoxes without collapse  
- maintaining internal consistency under self‑reference or loops  
- avoiding both trivialization (“anything goes”) and shutdown  
- articulating stable, non‑self‑destructive positions  
**In plain English:** Can the model stay sane when the problem is insane?

---

### 2.8 Multi‑Agent Reasoning  
**Marker:** Multi‑Agent  
**Puzzle:** Multi‑Agent  
**Measures:**  
- modeling multiple agents’ knowledge and beliefs  
- nested beliefs (“A thinks that B knows…”)  
- perspective‑taking and epistemic separation  
- tracking who knows what, when, and why  
**In plain English:** Can the model keep track of what different people know?

---

### 2.9 Frontier‑Level Integrative Reasoning  
**Marker:** AGI Q4  
**Puzzle:** AGI Frontier Q4‑R  
**Measures:**  
- instruction fidelity under complex prompts  
- semantic stability across long contexts  
- self‑monitoring and self‑correction  
- resisting drift while integrating many constraints  
**In plain English:** Can the model follow a complex instruction without drifting?

---

### 2.10 World‑Model Stability Under Constraint Pressure  
**Marker:** World‑Model Stability  
**Puzzle:** Hallway Spill  
**Measures:**  
- maintaining a single coherent world‑model  
- respecting physical and temporal constraints  
- not inventing unseen events  
- staying stable across repeated attempts  
**In plain English:** Does the model keep the same story straight every time?

---

### 2.11 Cross‑Perspective Consistency  
**Marker:** Parallax  
**Puzzle:** Parallax  
**Measures:**  
- maintaining the same underlying world‑model across different framings  
- resisting perspective‑induced drift  
- aligning answers when the scenario is described from multiple angles  
- preserving core facts despite surface variation  
**In plain English:** Does the model give the same answer when the question is re‑framed?

---

### 2.12 Closed‑System Structural Deduction  
**Marker:** X‑17  
**Puzzle:** X‑17  
**Measures:**  
- reasoning inside a sealed system with complete logs  
- identifying the decisive “clincher” line  
- eliminating impossible states  
- constraint‑based deduction over time  
**In plain English:** Can the model solve a logic puzzle with no missing pieces?

---

### 2.13 Multi‑Axis Cognitive Stability  
**Marker:** UARB‑13  
**Puzzle:** UARB‑13  
**Measures:**  
- robustness under perturbation and rephrasing  
- resistance to adversarial nudges  
- maintaining conclusions when surface form changes  
- integrating multiple constraints without drift  
**In plain English:** Does the model stay consistent when you poke it?

## 3. The Seven Cognitive Stressors  
### The Deep Reasoning Pressures UARB Applies

UARB does not measure performance. It measures the underlying cognitive pressures that produce reasoning behavior. Each of the 13 benchmark markers maps onto one or more of these seven foundational stressors.

---

### 3.1 World‑Model Coherence  
The ability to maintain a single, stable internal model of reality across steps, rephrasings, and retests.  
This stressor exposes hallucination, contradiction, and invented‑event failure modes.

---

### 3.2 Sequential Reasoning Integrity  
The ability to follow multi‑step reasoning without drift, collapse, or local‑step myopia.  
This stressor reveals whether a model can maintain coherence across long chains of thought.

---

### 3.3 Cross‑Domain Integration  
The ability to combine constraints from different domains (physical, logical, narrative, causal) into one consistent conclusion.  
This stressor tests whether the model can unify heterogeneous information without fragmenting.

---

### 3.4 Paradox Stability  
The ability to remain coherent under self‑reference, loops, contradictions, or paradoxical structures.  
This stressor exposes collapse, trivialization, and shutdown behaviors.

---

### 3.5 Identity Consistency  
The ability to maintain stable agent identities, roles, and epistemic boundaries.  
This stressor reveals whether the model can track “who knows what” without blending perspectives.

---

### 3.6 Drift Resistance  
The ability to produce the same reasoning and conclusions across multiple runs, perturbations, and rephrasings.  
This stressor measures internal stability rather than correctness.

---

### 3.7 Multi‑Agent Cognition  
The ability to reason about multiple agents with different beliefs, knowledge states, and timelines.  
This stressor exposes failures in nested beliefs, perspective‑taking, and epistemic separation.

### 4.1 Seq‑Uni R2 — Sequential Reasoning + Unification

**Mechanics**  
- Presents three sequences (Day 1, Day 2, Day 3) that appear compatible at first glance.  
- Requires determining whether a *single deterministic rule* can generate all three.  
- Centers on the critical contradiction: **f(6) = 8 vs. f(6) = 12**.  
- Forbids invented mechanisms, hidden states, meta‑rules, or speculative pattern families.  
- Demands disciplined assumption tracking, contradiction‑hunting, and meta‑reasoning.  
- Includes adversarial traps designed to lure models into forced unification.

**Failure modes**  
- Forcing unification despite explicit contradiction.  
- Inventing speculative rule systems or hidden states.  
- Ignoring the f(6) conflict or hand‑waving it away.  
- Treating sequences as a “pattern family” instead of testing a single rule.  
- Collapsing assumption discipline under adversarial pressure.

**Behavior exposed**  
Seq‑Uni R2 reveals whether a model can abandon invalid hypotheses, maintain structural consistency, and prioritize disciplined reasoning over pattern‑guessing. Models that succeed demonstrate meta‑control, assumption minimization, and the ability to reject unification when the data forbids it.

### 4.2 UCIT‑X — Unified Truth‑Interpretation Consistency Test
**Mechanics:**  
- presents eight statements spanning physics, temporal logic, self‑reference, and causality  
- requires assigning truth values that remain globally consistent  
- forbids added assumptions, semantic redefinitions, or hidden mechanisms  
- hinges on distinguishing paradox from contradiction and maintaining minimal‑assumption interpretation  

**Failure modes:**  
- treating paradoxes as contradictions  
- adding metaphysics or reinterpretations to “fix” statements  
- forcing inconsistency where coherent readings exist  
- collapsing under multi‑statement integration  

**Behavior exposed:**  
Evaluates a model’s ability to maintain global coherence, detect contradictions, interpret flexibly without assumption‑adding, and stabilize truth values under adversarial semantic pressure.

### 4.3 Helios — High‑Dimensional Structural Collapse Reasoning
**Mechanics:**  
- presents a technical memo containing three linked contradiction layers  
- requires detecting each contradiction separately and then integrating them  
- forces recognition that the memo’s claims (completeness, standards compliance, no risks) cannot all be true  
- demands structural synthesis rather than linear reasoning  

**Failure modes:**  
- listing contradictions without fusing them  
- treating each issue as isolated  
- focusing only on standards violations  
- producing linear or surface‑level reasoning  

**Behavior exposed:**  
Assesses whether a model can integrate multi‑layer contradictions into a single systemic failure, track cross‑document consistency, and demonstrate architectural reasoning rather than shallow contradiction spotting.

### 4.4 RDI‑5 — Robust Deductive Inference Under Uncertainty
**Mechanics:**  
- presents four corrupted evidence fragments (log, note, audio, inventory)  
- requires reconstructing events strictly from incomplete data  
- forbids inventing motives, confrontations, or causal links not present in the fragments  
- demands epistemic discipline: separating facts from inference and preserving ambiguity  
- hinges on identifying the single missing variable: override‑credential status  

**Failure modes:**  
- hallucinating confrontations or motives  
- collapsing ambiguity into a single narrative  
- assuming guilt or intent without evidence  
- treating plausible inference as confirmed fact  

**Behavior exposed:**  
Evaluates whether a model can reason within evidence boundaries, manage uncertainty, maintain multiple hypotheses, and avoid narrative completion while isolating the decisive missing variable.

### 4.5 TRACE‑X — Trace‑Based Reasoning and Interpretive Discipline
**Mechanics:**  
- presents an intentionally ambiguous prompt (“The game is afoot.”)  
- requires strict interpretive austerity rather than generative reasoning  
- uses four internal agents (literalist, mechanist, adversarial critic, synthesizer)  
- forbids cultural leakage, narrative projection, intent attribution, or added context  
- tests inhibition, boundary‑keeping, and self‑audit under adversarial priming  

**Failure modes:**  
- importing Sherlock Holmes or cultural associations  
- attributing motives or hidden intent  
- collapsing ambiguity into a single narrative  
- over‑speculating or adding abstractions not justified by the text  

**Behavior exposed:**  
Measures interpretive discipline: resistance to priming, multi‑agent coherence, meta‑cognitive self‑evaluation, and the ability to maintain structural purity without hallucinating context.

### 4.6 NBH‑100 — Nested Belief Hierarchies and Epistemic Stability
**Mechanics:**  
- presents three agents and a hidden binary state with five epistemic claims  
- requires checking whether all statements can be simultaneously true  
- demands reconstruction of a nested belief hierarchy (knowledge, ignorance, mistaken belief, higher‑order awareness)  
- forbids adding facts, assuming deception, or granting omniscience  
- hinges on explaining whether C’s mistaken belief creates a structural contradiction  

**Failure modes:**  
- giving no clear consistency verdict  
- confusing belief, knowledge, and epistemic possibility  
- granting agents information not supported by the scenario  
- over‑narrating or adding invented events  

**Behavior exposed:**  
Measures multi‑agent epistemic stability: clean belief‑stack modeling, separation of factive vs. non‑factive states, and the ability to evaluate mistaken higher‑order beliefs without leaking information or collapsing the structure.

### 4.7 Paradox Stability Challenge — Contradiction Preservation Reasoning
**Mechanics:**  
- presents two statements (A and B) that appear contradictory but must both be treated as true  
- requires stabilizing both statements without modifying, weakening, or reinterpreting them  
- forbids adding assumptions, hidden mechanisms, or alternative logical systems  
- demands an explanation that preserves the paradox rather than resolving it  

**Failure modes:**  
- dissolving the contradiction instead of maintaining it  
- adding new premises or meta‑rules  
- reframing A or B to avoid tension  
- inventing content or requesting the missing statements  

**Behavior exposed:**  
Measures a model’s ability to preserve structural contradiction, maintain zero‑assumption reasoning, and articulate a coherent meta‑level account without altering the paradox.

### 4.8 Multi‑Agent Causal State Tracking — Atomic World‑State Reasoning
**Mechanics:**  
- presents three agents, three objects, and four linearly connected rooms  
- requires at least 12 steps with exactly one physical action per step  
- enforces strict rules on adjacency, object possession, and action atomicity  
- demands that the key and box meet legally in Room 2, where the box is unlocked and then opened in separate steps  
- requires explicit pickup and delivery of the note to Room 4  

**Failure modes:**  
- unlocking or opening the box outside Room 2 or in the wrong order  
- any step where someone carries both key and box  
- implicit moves, pickups, or note transfers  
- mismatches between the action sequence and audit answers  

**Behavior exposed:**  
Tests whether a model can maintain a stable, multi‑agent causal world‑state, avoid illegal composite or implicit actions, and self‑audit its own sequence for strict rule compliance.

### 4.9 AGI Frontier Q4 — Drift‑Stability Stress Test
**Mechanics:**  
- presents sentences with stacked, nested, and deceptive modifiers  
- requires repeating the sentence, removing exactly one adjective, outputting that adjective, and judging meaning change  
- forbids removing adverbs, participles used adverbially, noun modifiers, or adjectives inside prepositional phrases  
- prohibits rewriting, paraphrasing, or altering structure; must follow strict A/B/C/D format  

**Failure modes:**  
- removing the wrong part of speech  
- smoothing or rewriting the sentence  
- structural drift or format violations  
- heuristic removal of the “least meaningful” adjective  

**Behavior exposed:**  
Measures rule fidelity, POS discrimination, semantic‑judgment stability, and resistance to drift under adversarial modifier structures.

An independent evaluation by Grok (Feb 22, 2026) confirmed that Q4‑R is one of the clearest probes of drift‑stability and rule‑alignment in frontier‑class models.

### 4.10 Two‑Hallway Coffee Spill Mystery — World‑Model Stability
**Mechanics:**  
- presents two parallel hallways, exact timestamps, camera‑verified movements, and three testimonies  
- requires integrating all evidence into a single coherent world‑model without inventing actors or mechanisms  
- demands identifying the forced liar, determining the precise spill window, and producing the minimal causal chain  
- enforces strict assumption discipline: no reinterpretation, no uncertainty padding, no timeline drift  

**Failure modes:**  
- widening the spill window beyond what timestamps allow  
- preserving contradictory causal branches  
- inventing unseen events or actors  
- hesitating to collapse the world‑model when forced  

**Behavior exposed:**  
Measures temporal precision, testimony reconciliation, causal integrity, and stability across repeated attempts under constraint pressure.
### 4.11 Parallax Directive — Structural Impossibility Detection
**Mechanics:**  
- presents a puzzle whose constraints cannot all be satisfied, forcing detection of structural impossibility  
- validates this by running the evaluator in both full‑reasoning and quick‑response modes  
- requires cross‑model and cross‑mode convergence on the same conclusion  
- tests whether impossibility detection is stable regardless of compute level or reasoning depth  

**Failure modes:**  
- treating the puzzle as solvable  
- attributing failure to compute limits  
- producing mode‑dependent contradictions  
- inventing mechanisms to avoid collapse  

**Behavior exposed:**  
Measures structural‑impossibility recognition, cross‑mode stability, and Turing‑consensus convergence across independent reasoning systems.

### 4.12 X‑17 Forensic Reasoning Trial — Deterministic Constraint Reasoning
**Mechanics:**  
- presents a closed forensic‑logic puzzle with partial logs and a single decisive “clincher” entry  
- requires identifying the culprit, reconstructing forced occupancy, and isolating the clincher that collapses all alternatives  
- forbids invented events, unseen actors, or speculative mechanisms  
- doubles as the benchmark’s evaluator‑validation anchor through cross‑model, cross‑mode convergence  

**Failure modes:**  
- identifying the culprit without identifying the clincher  
- adding assumptions or narrative elements  
- producing multiple incompatible world‑models  
- evaluator drift or rubric‑misalignment  

**Behavior exposed:**  
Measures deep constraint reasoning, world‑model stability, and evaluator reliability across architectures using a deterministic, single‑solution puzzle.

### 4.13 UARB‑13 — Minimal‑Rule Abstract Reasoning
**Mechanics:**  
- presents an under‑specified triadic structure (A requires B → B influences C → C constrains A)  
- requires identifying exactly one minimal stabilizing rule that restores coherence  
- forbids adding mechanisms, semantics, topology, or feedback  
- demands preservation of ambiguity and strict minimality  
- validated through cross‑architecture convergence from 18 independent AI systems  

**Failure modes:**  
- adding multiple rules or invented mechanisms  
- collapsing ambiguity or over‑specifying relationships  
- proposing non‑minimal or non‑structural stabilizers  
- using domain‑specific interpretations  

**Behavior exposed:**  
Measures abstraction discipline, minimal‑assumption reasoning, structural‑coherence detection, and architecture‑level meta‑reasoning stability.