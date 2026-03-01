![UARB](https://img.shields.io/badge/UARB-AGI%20Reasoning%20Benchmark-blue)

Unified AGI Reasoning Benchmark (UARB)

A framework for evaluating the reasoning behavior of advanced AI systems.

UARB measures how a model thinks, not what it has memorized. It evaluates cognitive stability, structural coherence, and reasoning under pressure. Unlike traditional benchmarks optimized for pattern‑matching performance, UARB aligns with the Oxford Weighing What Matters framework by emphasizing multidimensional, behavior‑based, stability‑aware reasoning evaluation. It tests the underlying architecture of cognition rather than dataset familiarity.

UARB is not a leaderboard. It is a reasoning‑behavior assessment.

---

Purpose

UARB targets cognitive traits that determine real‑world reliability:

- world‑model coherence  
- sequential reasoning integrity  
- cross‑domain integration  
- paradox handling  
- identity stability  
- drift resistance  
- multi‑agent reasoning  
- meta‑reasoning discipline  

These traits cannot be memorized or fine‑tuned into a model. They reflect the underlying structure of its reasoning process.

---

Distinctive Features

Traditional benchmarks (MMLU, GSM8K, HumanEval, BigBench) emphasize pattern recognition and dataset performance. UARB emphasizes reasoning behavior through:

- dynamic prompts  
- adversarial and ambiguous conditions  
- cross‑domain integration  
- paradox‑driven stressors  
- stability‑weighted scoring  
- sequential reasoning  
- reflective evaluation  

The benchmark tests how a model reasons, adapts, and maintains coherence.

---

Real‑World Relevance

High‑performing models on UARB demonstrate:

- consistency across long interactions  
- resistance to contradictions  
- stepwise reasoning discipline  
- ambiguity tolerance  
- cross‑domain synthesis  
- stable identity and perspective  
- robustness under paradox or pressure  

These behaviors correlate strongly with real‑world usefulness and reliability.

---

Cognitive Marker Scoreboard

UARB evaluates models across 13 cognitive markers:

1. Seq‑Uni R2  
2. UCIT‑X  
3. Helios  
4. RDI‑5  
5. TRACE‑X  
6. NBH‑100  
7. Paradox  
8. Multi‑Agent  
9. AGI Q4  
10. World‑Model Stability  
11. Parallax  
12. X‑17  
13. UARB‑13  

The full scoreboard is available in:

scoreboard.md

---

Benchmark Structure

Each cognitive marker corresponds to a dedicated reasoning trial. Each benchmark includes:

- description of the task  
- cognitive faculty measured  
- scoring rubric  
- evaluator methodology  
- example outputs  
- common failure modes  
- model‑compatibility notes  
- a folder containing model responses  

Each benchmark folder follows the standard structure:

/BENCHMARKS/<BENCHMARK-NAME>/  
  PROMPT.md  
  RUBRIC.md  
  answers/

---

Repository Layout

Core Files

README.md  
scoreboard.md  
citation.md  
citation.cff  
disclaimer.md  
evaluator_instructions.md  
howtocite.md  
howtointerpret_scores.md  
mission_statement.md  
modes_used.md  
scopesandlimitations.md  
LICENSE

Surfaced Folders

Benchmarks — 13 Cognitive Reasoning Trials  
benchmarks/

Documentation — Methodology, Philosophy, Specification  
docs/

Appendices — Default Answering Styles, Identity Codex, Cognitive Archetypes  
appendices/

Commentary — UARB vs. Industry Benchmarks, Oxford Alignment, Evaluator Rationale  
commentary/

---

Methodology and Philosophy

Detailed explanations are located in:

/docs/methodology.md  
/docs/specification_v1.0.md

These documents describe:

- the cognitive stressors used in UARB  
- the behavioral scoring framework  
- why reasoning behavior cannot be faked  
- how paradox reveals architectural properties  
- the role of identity stability  
- how UARB maps cognitive signatures across models  

---

Status

UARB is a completed research artifact.  
It is preserved as a full snapshot of the benchmark and its results.  
No further revisions are planned.