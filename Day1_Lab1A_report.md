# Analytical Report: AI Model Performance on Placement Transformation Summary

## 1. Executive Summary

The source article describes a three-phase evolution of AI in Indian engineering campus placements (2023–2028), highlighting recruiter countermeasures, equity gaps, verification challenges, and the impending rise of agentic AI. Four leading AI models—ChatGPT, Claude, Gemini, and Perplexity—were tasked with summarizing the article into **5 bullet points, each ≤15 words**.

All four models demonstrated strong **faithfulness** (no major factual errors or fabrications). However, significant differences emerged in **nuance preservation**, **statistical coverage**, and **brevity discipline**. Claude performed best at preserving contextual nuance and recruiter tactics. Gemini and Perplexity excelled at numeric fidelity. ChatGPT delivered the cleanest structural balance but over-summarized. No model achieved perfect 15-word compliance across all bullets.

---

## 2. Detailed Analysis by Model

### ChatGPT

| Metric | Score | Comment |
|--------|-------|---------|
| Faithfulness | 4.5/5 | All claims correct, but omits the critical **AICTE 18% statistic** |
| Structure | 5/5 | Perfectly parallel, numbered bullets, conversational tone |
| Brevity | 4/5 | Most bullets under 15 words; bullet 5 is 16 words |

**Unique strength:** Best at synthesizing macro trends (2023→2025→2028 progression)

**Weakness:** Skips low-frequency but high-importance stats like 18% and 8–12% hallucination rate

---

### Claude

| Metric | Score | Comment |
|--------|-------|---------|
| Faithfulness | 5/5 | Preserves all key claims including 60% error reduction |
| Structure | 4.5/5 | Clear but lacks numbering; slightly long bullets |
| Brevity | 3.5/5 | Several bullets exceed 15 words (up to 19 words) |

**Unique strength:** Best at capturing **causal relationships** (e.g., recruiter countermeasures)

**Weakness:** Brevity discipline is weakest; most verbose of the four

---

### Gemini

| Metric | Score | Comment |
|--------|-------|---------|
| Faithfulness | 5/5 | Includes 95%, 2.4×, three-step chain; missing 35% longer interviews |
| Structure | 4/5 | Clean but curt; bullet 2 is factually dense |
| Brevity | 4.5/5 | Four of five bullets under 15 words |

**Unique strength:** Strongest on **actionable takeaways** for placement officers

**Weakness:** Lacks the "35% longer interview" data point

---

### Perplexity

| Metric | Score | Comment |
|--------|-------|---------|
| Faithfulness | 5/5 | Only model to explicitly cite 8–12% hallucination rate |
| Structure | 4.5/5 | Clean but bullet 4 uses two sentences (less parallel) |
| Brevity | 3.5/5 | One bullet at 18 words; inconsistent length |

**Unique strength:** Only model that adds inline citations and external sources

**Weakness:** Brevity inconsistency; less clean parallel structure

---

## 3. Columnar Report: What Each Tool Will Likely Give You

| Tool | Expected output style | Common strength | Common weakness |
|------|----------------------|-----------------|-----------------|
| **ChatGPT** | 5 well-formed bullets, balanced coverage | Clean structure, conversational tone, strong macro narrative | May skip the AICTE 18% statistic; over-summarises some nuances |
| **Claude** | 5 thorough bullets with sub-points if allowed | Best at preserving nuance, quotes, and causal links | Often exceeds 15 words/bullet; most verbose without explicit constraint |
| **Gemini** | 5 bullets, sometimes adds source links | Strong on numeric facts (60%, 95%, 2.4×) | Style varies — sometimes too curt; may omit one medium-importance stat |
| **Perplexity** | 5 bullets WITH inline citations | Cites the article + adds external sources naturally; best factual recall | Smaller bullet count if asked nicely; less clean parallel structure |

---

## 4. Scoring Summary

| Model | Faithfulness (max 5) | Structure (max 5) | Brevity (max 5) | **Total (15)** |
|-------|---------------------|------------------|----------------|----------------|
| **ChatGPT** | 4.5 | 5 | 4 | **13.5** |
| **Claude** | 5 | 4.5 | 3.5 | **13.0** |
| **Gemini** | 5 | 4 | 4.5 | **13.5** |
| **Perplexity** | 5 | 4.5 | 3.5 | **13.0** |

### Tie-breaker Notes

- **ChatGPT and Gemini tie at 13.5.** ChatGPT wins on structure; Gemini wins on numeric completeness. For placement officer use cases, Gemini's numeric fidelity is slightly more valuable.
- **Claude and Perplexity tie at 13.0.** Claude wins on nuance; Perplexity wins on citation behavior (not scored in this rubric).

---

## 5. Key Insights from Cross-Model Analysis

| Insight | Detail |
|---------|--------|
| **No fabrication** | All four models produced zero false claims — remarkable given the article's density |
| **Most dropped stat** | The **35% longer interview rounds** was missed by Gemini |
| **Second most dropped** | The **18% AICTE trained officers** was missed only by ChatGPT |
| **Brevity hardest constraint** | Only Gemini achieved 4/5 bullets under 15 words without re-prompting |
| **Verification chain recall** | All four models correctly reported the three-step chain (ask AI → Perplexity → primary source) |
| **Agentic AI coverage** | Covered by ChatGPT, Gemini, and Perplexity; Claude omitted the 70% figure |

---

## 6. Recommendation for Placement Officers / Report Users

| Use Case | Recommended Model | Reason |
|----------|-------------------|--------|
| Most compact, stat-dense summary under strict word limits | **Gemini** | Best numeric fidelity within 15-word constraint |
| Understanding recruiter psychology and causal chains | **Claude** | Best at preserving "why" behind recruiter tactics |
| Presentation-ready leadership deck | **ChatGPT** | Cleanest structure and professional tone |
| Fact verification against source + external data | **Perplexity** | Built-in citations and source-checking behavior |

### Optimal Combination for 2026 Mentor-Training Programs

> **Gemini + Claude combined** — Gemini for the hard numbers (60%, 95%, 2.4×, 18%, 35%), Claude for the "why this matters" narrative (recruiter countermeasures, verification chain logic, equity implications).

---

## 7. Scoring Guide Reference (from Task 1)

| Score | Faithfulness | Structure | Brevity |
|-------|-------------|-----------|---------|
| **5** | All key claims preserved, no fabrication | Numbered, parallel form, easy to read | Every bullet ≤ 15 words |
| **3 (anchor)** | Most key claims preserved, 1-2 minor omissions | Mostly clean, 1 awkward bullet | One or two bullets slightly long |
| **1** | Major omission, fabrication, or misattribution | Inconsistent format, prose blocks | Long-winded, ignored word limit |