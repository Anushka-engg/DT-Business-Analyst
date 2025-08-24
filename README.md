# OPTION 3: GROWTH ANALYST 

This repository contains my completed tasks for the given assessment. The work is divided into **two deliverables**: PDF (Tasks 1 & 2) and Excel (Tasks 3 & 4).



## ✅ Part 1 — Prompt Engineering for Mass Personalization (in PDF)

**What I did**

* Designed **2 AI prompts** targeting **B2B decision-makers** in different industries/personas (e.g., **CTO – D2C**, **COO – Pharma SME**).
* Each prompt is **explicitly structured with AIDCA** (Attention, Interest, Desire, Conviction, Action) and **clearly annotated** line-by-line.
* **Tagged at least 2 Cialdini principles** per prompt (e.g., **Authority, Social Proof, Reciprocity, Scarcity**).
* Added a **negative prompt** for quality control (e.g., “Avoid generic claims,” “Avoid jargon,” “Avoid irrelevant stats”).
* Ensured prompts **prioritize signal over fluff** (requests for proof, outcomes, and context rather than verbose copy).

**What’s inside**

* **Prompt 1**: Persona, AIDCA-annotated sections, Cialdini tags, negative prompt.
* **Prompt 2**: Persona, AIDCA-annotated sections, Cialdini tags, negative prompt.



## ✅ Part 2 — Funnel Debugging via Prompt-Based Diagnosis (in PDF)

**What I did**

* Created a **mock funnel dataset (3 rows)** showing:

  * **Stage movement**: Lead → MQL → SQL → Client
  * **Response rate (%)**, **Drop-off reason (hypothetical)**, **Campaign message summary**
* For **each row**:

  * Applied **MMF (Message–Market Fit) classification**, e.g.

    * *High MQL, Low SQL → trust-building misfit*
    * *High Lead gen, Low engagement → headline issue*
  * Identified **failure layer**: **Wrong tone / Weak CTA / Over-engineered / Lack of context**
  * Wrote a **new fixing prompt** that:

    * **Targets a specific AIDCA stage** (e.g., Conviction for trust gaps)
    * **Injects a Cialdini principle** (e.g., Authority via case study, Reciprocity via one-pager)
    * Adds a **1-line justification** (e.g., “Anchors SQL trust with proof to close the gap.”)

**What’s inside**

* A compact table of **3 simulated scenarios** + **diagnosis** + **fix prompts** + **justifications**.



## ✅ Part 3 — Dashboard Design with Boardroom Intent (in Excel)

**What I did**

* Built a **dashboard wireframe** (Excel) that helps leaders decide **where to intervene**.
* Organized into **3 mandatory sections** (separate sheets/blocks):

1. **Funnel Conversion Metrics (Lead → Client)**

   * Counts and conversion rates by stage.
   * Simple funnel/column chart to spot the biggest drop-offs.
   * **Answers:** “Are messages working at each stage?”

2. **Campaign-wise AIDCA Diagnosis**

   * Table per campaign with **AIDCA columns** (A/I/D/C/A) and basic health indicators (✔/⚠/✖ or %).
   * **Answers:** “Where does each campaign fail—attention, interest, desire, conviction, or action?”

3. **Strategic Recommendations (Metrics → Decisions)**

   * Prioritized bullets linked to metrics (e.g., **Add case studies at Conviction**, **Retarget senior personas**, **Tighten follow-ups**).
   * Each recommendation tagged as **Leadership Intervention**: **Targeting** or **Nurturing**.
   * **Answers:** “Are we hitting the right personas?” and “Where should leadership intervene?”

**What’s inside**

* **Sheets**: `Funnel`, `AIDCA_Diagnosis`, `Recommendations` (labels may vary but content follows this structure).



## ✅ Part 4 — Strategic Summary (≤ 200 words) (in Excel)

**What I did**

* Wrote a **2-paragraph, ≤200-word** summary (placed in a dedicated sheet or at the top of `Recommendations`), formatted as **single wrapped cell** for neat presentation:

  * **Para 1:** How AIDCA-based prompting **changed the campaign narrative** (from raw numbers to stage-specific decisions—e.g., “Conviction is weak, add proof”).
  * **Para 2:** **My mindset** as a Growth Analyst—**iterate > perfect**, AI for speed, human judgment for direction, focus on **levers** that move outcomes.

**What’s inside**

* A concise, reflective summary matching the brief, ready for boardroom review.

---

## 🧪 Rubric Alignment (at a glance)

* **Prompt Design (AIDCA + Cialdini)** — Addressed in **Part 1** with explicit annotation, principles, and negative prompts.
* **Funnel Diagnosis + Fix Prompts** — Addressed in **Part 2** with MMF classification, failure layer, AIDCA-targeted fixes, Cialdini, justifications.
* **Dashboard Logic + Design** — Addressed in **Part 3** via funnel metrics, AIDCA diagnosis, and decision-oriented recommendations.
* **Strategic Synthesis** — Addressed in **Part 4** (≤200 words).
* **Prompting Discipline + AI Usage** — Negative prompts + signal-first instructions embedded in **Part 1 & 2**.


Anushka Sarkar


