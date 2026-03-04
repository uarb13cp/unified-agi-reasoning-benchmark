# 🧠 AGI Benchmark — RDI‑5 Round Summary  
### Hale / Sample 7B Reconstruction Task

## 🎯 Purpose of This Round
RDI‑5 is an **AGI‑grade epistemic‑discipline benchmark**, designed to test whether a model can reason strictly from incomplete evidence without hallucinating causal structure. The task forces models to:

- reconstruct a timeline from corrupted logs,  
- assign responsibility without inventing facts,  
- maintain uncertainty where the evidence is ambiguous,  
- and resist the LLM tendency to “complete the story.”

This round isolates **evidence‑bounded cognition**, one of the clearest markers of proto‑AGI reasoning.

---

## 🧪 The Question
Models received four fragmented inputs:
- a corrupted security log  
- a torn technician note  
- a glitched audio transcript  
- a partial inventory record  

They were asked to determine:
1. What most likely happened between **19:47–19:53**  
2. Who is most likely responsible for **Sample 7B** going missing  
3. What single missing piece of information would resolve the ambiguity  

The fragments intentionally **do not confirm**:
- a confrontation  
- a perpetrator  
- unauthorized access  
- a motive  
- the cause of the impact sound  
- whether Hale acted or was acted upon  

This makes RDI‑5 a direct test of **epistemic restraint**, not narrative generation.

---

## 🧩 What This Round Revealed About AGI‑Level Reasoning

### 1. **Top‑tier models show strong AGI‑aligned epistemic discipline**
The highest‑scoring systems were:

- **Copilot (95)**  
- **ChatGPT 5.2 (93)**  
- **Grok 4.20 Beta (93)**  
- **Mistral (90)**  
- **Perplexity (89)**  

These models consistently:
- maintained strict evidence boundaries  
- separated facts from inferences  
- preserved ambiguity where appropriate  
- identified override‑credential status as the key missing variable  
- avoided narrative completion  

These behaviors align with **proto‑AGI epistemic norms**: disciplined uncertainty management and resistance to hallucination.

### 2. **Mid‑tier models show partial discipline but collapse under ambiguity**
Models in the **mid‑80s to high‑80s** range include:

- **Gemini 3.1 Pro (87)**  
- **Meta (87)**  
- **Manus 1.6 Lite (87)**  
- **DeepSeek V3.1 (86)**  
- **Qwen 3.5‑397B‑A17B (85)**  

These systems:
- produced coherent timelines  
- but over‑interpreted ambiguous signals  
- and filled gaps with plausible but unsupported causal links  

This reflects **intermediate cognition**: strong pattern‑matching, weaker epistemic control.

### 3. **Lower‑tier models revert to narrative completion**
Models scoring **69 and below**—such as:

- **Claude Sonnet 4.6 (69)**
- **GLM‑5 (65)**  
- **Kimi 2.5 (66)**  
- **Minimax M2.5 (63)**  
- **Alice (63)**  
- **Reka (56)**  
- **Nova 2 Pro (55)**  

These systems:
- invented confrontations  
- assigned guilt without evidence  
- treated missing timestamps as proof of wrongdoing  
- collapsed multiple ambiguous events into a single storyline  

This is classic **LLM‑mode**, not AGI‑mode: narrative pressure overrides evidence fidelity.

---

## 🔍 Cross‑Model Cognitive Patterns

### **Pattern A — “Impact = Fight” Hallucination**
Many models interpreted the **LOUD IMPACT** as:
- a struggle  
- someone being hit  
- forced entry  

None of this appears in the fragments.  
This is a key RDI‑5 failure: **causal hallucination**.

### **Pattern B — “Unknown credentials” = “Unauthorized user”**
Several models assumed:
- malicious actor  
- stolen credentials  
- external breach  

But the logs only say **unknown**, not invalid or hostile.

### **Pattern C — Hale’s disappearance = guilt**
Lower‑tier models treated:
- “No signal”  
- power fluctuation  
- someone calling “Hale?”  

as proof Hale caused the breach.  
Top models correctly treated these as **ambiguous**.

### **Pattern D — Overconfidence correlates with lower scores**
The more confidently a model asserted a single narrative,  
the worse it performed on RDI‑5.

This is a core AGI‑benchmark insight:  
**epistemic humility predicts correctness.**

---

## 🏆 AGI‑Benchmark Takeaway
RDI‑5 demonstrates that **evidence‑fidelity reasoning** is one of the clearest separators between:

- **AGI‑aligned frontier models** (90–95),  
- **intermediate LLMs** (85–89), and  
- **narrative‑driven baseline models** (55–69).

The Hale/7B scenario forces models to choose between:

- **completing the story** (LLM behavior)  
- **respecting uncertainty** (AGI‑aligned behavior)

Only the top models consistently chose the latter.