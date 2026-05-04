# Career Catalyst: Advisory — KPMG Virtual Experience Program

> **A full-cycle consulting simulation portfolio built on the KPMG CREATE Framework, tackling a real-world operational challenge for a multi-site urgent care provider.**

---

## Table of Contents

1. [Project Background](#1-project-background)
2. [The KPMG CREATE Framework](#2-the-kpmg-create-framework)
3. [Task 1 — Understanding the Client's Operations & Analysing Data](#3-task-1--understanding-the-clients-operations--analysing-data)
4. [Task 2 — Leading Practice Research](#4-task-2--leading-practice-research)
5. [Task 3 — Preparing the Executive Summary Presentation](#5-task-3--preparing-the-executive-summary-presentation)
6. [Task 4 — Initiative Brainstorming](#6-task-4--initiative-brainstorming)
7. [Overall Results & Key Findings](#7-overall-results--key-findings)
8. [Conclusion](#8-conclusion)
9. [Repository Structure](#9-repository-structure)
10. [Skills Demonstrated](#10-skills-demonstrated)

---

## 1. Project Background

**Client:** Healthy Co — a regional urgent care network operating **25 facilities** across the United States, serving approximately **10,000 patients** per month and employing **3,000 staff members**.

**Business Problem:**
Healthy Co's leadership engaged KPMG Advisory with a single, high-priority concern: *patients are waiting too long*. Preliminary complaints data and anecdotal feedback from facility managers pointed to inconsistent wait times, especially during morning rush hours, lunchtime, and early evenings. Long wait times were driving patient dissatisfaction, increasing operational costs (via overtime and repeat visits), and threatening the organisation's competitive position in a market where patients increasingly have walk-in alternatives.

**Engagement Objective:**
Conduct a structured, data-driven advisory engagement to:
- Quantify the scale and root causes of the wait-time problem.
- Identify evidence-based practices from comparable healthcare settings.
- Develop actionable, prioritised recommendations packaged into an executive presentation.
- Generate a long-list of forward-thinking initiatives to seed future innovation roadmaps.

**Simulation Scope:**
This repository covers **four sequential tasks** that mirror an actual KPMG advisory engagement — from initial data review through to creative ideation — all structured around the **KPMG CREATE Framework**.

---

## 2. The KPMG CREATE Framework

Every task in this engagement was anchored in KPMG's proprietary **CREATE Framework**, which structures complex consulting problems into six stages:

| Stage | Description |
|---|---|
| **C**larify | Define the problem, client context, and constraints |
| **R**esearch | Gather relevant data, benchmarks, and leading practices |
| **E**xplore | Examine data patterns, outliers, and root causes |
| **A**nalyze | Draw evidence-based conclusions and size the opportunity |
| **T**est | Pressure-test recommendations against feasibility and impact |
| **E**xecute | Package insights into a client-ready plan with a clear roadmap |

Each task in this portfolio maps directly to one or more of these stages, ensuring that the output at every step is purposeful, structured, and client-ready.

---

## 3. Task 1 — Understanding the Client's Operations & Analysing Data

### Background & Objective

Before any recommendation can be made, a consultant must understand the client's operations deeply. This task involved reviewing Healthy Co's **Client Profile** — covering organisational structure, staffing model, patient demographics, and current workflow — and then performing a thorough analysis of **4,984 raw patient visit records** to identify where, when, and why wait times were unacceptably high.

The analysis had to be entirely data-driven: no assumptions, no anecdote — only what the numbers revealed.

### Approach

**Step 1 — Data Cleaning & Preparation**
The raw Excel dataset contained timestamps for each stage of the patient journey: arrival, registration, vitals, doctor consultation, and discharge. The first step was to clean the data — handling blanks, correcting timestamp formatting, and removing records that were clearly erroneous (e.g., negative wait durations).

**Step 2 — Calculated Columns**
Four new calculated columns were engineered from the raw timestamps:
- **Registration Wait** — time from arrival to registration desk
- **Vitals Wait** — time from registration to nurse assessment
- **Doctor Wait** — time from nurse assessment to doctor consultation
- **Total Visit Time** — end-to-end time from arrival to discharge
- **Total Wait Time** — sum of all non-clinical wait segments
- **Wait Cost** — estimated cost of wait time per visit, using Healthy Co's average revenue and capacity cost assumptions

**Step 3 — Pivot Table Analysis (9 Pivots)**
A suite of nine pivot tables was built to slice the data across multiple dimensions:
- Wait time by **hour of day** (to identify peak congestion windows)
- Wait time by **day of week** (to detect weekly demand patterns)
- Wait time by **individual doctor** (to identify performance outliers)
- Wait time by **diagnosis group** (to understand patient complexity mix)
- Staff **utilisation rates** by shift and role
- Visit volume and average wait by facility (where data permitted)

**Step 4 — Data Visualisation**
Charts were built to make patterns visible at a glance — column charts for hourly trends, bar charts for doctor comparisons, and a stacked chart showing wait breakdown by stage.

### Results & Key Findings

| Finding | Detail |
|---|---|
| **Peak congestion windows** | Wait times exceeded 40 minutes during 9–10 AM, 12–1 PM, and 6–7 PM. The noon slot recorded the highest average at **48.3 minutes** |
| **Staffing variation** | Nurse vitals processing time varied by **35%** across staff — a strong indicator of inconsistent protocols or training gaps |
| **Doctor-level outlier** | Dr. Balla averaged **29.6 minutes** of doctor wait time per patient, compared to the facility average of ~18 minutes — translating to an estimated **$1,482 per visit** in excess wait cost |
| **Patient volume by diagnosis group** | Group 3 (low-acuity patients) represented **59% of total visit volume** and had the shortest average visit time — making them ideal candidates for a Fast-Track triage lane |
| **Overall average wait** | Across all 4,984 visits, the mean total wait time was **39.7 minutes** — well above the industry benchmark of 20–25 minutes for urgent care |

### Deliverable

📁 `02_Understanding_Client_Operations/output/Healthy_Co_Data_Analysis_Task2.xlsx`
A fully structured Excel workbook containing: cleaned data, six calculated columns, nine pivot tables, a visual dashboard tab, and a written summary of key insights.

---

## 4. Task 2 — Leading Practice Research

### Background & Objective

Data analysis identifies *what* is broken. Leading practice research answers *what works elsewhere*. This task required evaluating **five pre-selected academic and industry resources** relevant to urgent care operational efficiency, then selecting and recommending the **two most applicable practices** to Healthy Co — backed by evidence and tied explicitly to the findings from Task 1.

The goal was not simply to summarise the literature, but to act as a trusted advisor: filtering for relevance, credibility, and feasibility, then making a clear recommendation with a rationale grounded in the client's specific data.

### Approach

**Step 1 — Resource Evaluation**
Each of the five provided resources was assessed across four dimensions:
- **Relevance** — How closely does the setting, problem, and scale match Healthy Co?
- **Credibility** — Is this peer-reviewed research, a credible industry report, or anecdotal?
- **Recency** — Is the evidence current enough to reflect today's urgent care environment?
- **Actionability** — Can the practice be realistically implemented at Healthy Co?

**Step 2 — Shortlisting & Recommendation**
Based on the evaluation matrix, two leading practices were selected as the strongest fit. The recommendation explicitly linked each practice back to Task 1 findings — for example, connecting the staffing variation data to the retraining practice.

### Results & Selected Leading Practices

**Leading Practice 1 — Predictive Staff Scheduling**
*Source: National Urgent Care Centre Association case study*

Urgent care facilities that implemented demand-forecasting algorithms to dynamically adjust staffing levels saw:
- **15% reduction** in average patient wait time
- **12% improvement** in staff utilisation rates
- Reduced overtime costs through smarter pre-shift rostering

**Why it fits Healthy Co:** The pivot table analysis revealed that peak congestion is concentrated in predictable three-hour windows (9–10 AM, 12–1 PM, 6–7 PM). These windows are consistent enough to be modelled with a simple forecasting tool. Healthy Co does not need a sophisticated AI system — a rules-based scheduling model built on historical visit volume data would be sufficient to start.

---

**Leading Practice 2 — Staff Retraining, Workflow Streamlining & Block Scheduling**
*Source: Peer-reviewed study on process improvement in ambulatory care*

A combined intervention targeting three levers simultaneously produced a **28% reduction** in median wait time across studied facilities:
- *Staff retraining* standardised clinical protocols, reducing the variation in nurse vitals time.
- *Workflow streamlining* eliminated redundant documentation steps between the registration and vitals stages.
- *Block scheduling* staggered patient appointment slots to prevent simultaneous arrivals overwhelming triage.

**Why it fits Healthy Co:** The 35% variation in nurse vitals time is a directly addressable problem through standardised retraining. Block scheduling is also highly relevant given the sharp peak-hour congestion identified in the data.

### Deliverable

📁 `03_Leading_Practice_Research/output/Healthy_Co_Task3_Completed.docx`
A completed research brief containing: evaluation summaries for all five resources, a clear recommendation of the top two practices, and a rationale section linking each recommendation to specific Task 1 data points.

---

## 5. Task 3 — Preparing the Executive Summary Presentation

### Background & Objective

Consultants are only as effective as their ability to communicate. The most rigorous analysis and the most compelling research mean nothing if the client cannot understand, trust, and act on the findings. This task required synthesising Tasks 1 and 2 into a **concise, executive-ready PowerPoint presentation** suitable for delivery to Healthy Co's senior leadership team.

The deck had to tell a coherent story: from the problem, through the evidence, to the solution — all within six slides and in a style consistent with KPMG's professional communication standards.

### Approach

**Step 1 — Storyboarding**
Before touching PowerPoint, a narrative arc was mapped out. The storyboard logic followed a classic consulting structure:
- *Here is your situation* (what the data shows)
- *Here is what others have done* (leading practices)
- *Here is what we recommend you do* (actionable next steps)
- *Here is what success looks like* (projected impact)

**Step 2 — Slide Design**
Using the KPMG-provided presentation shell, each slide was built to balance data density with visual clarity. Key design principles applied:
- One key message per slide (headline answers the "so what")
- Data visualisations from the Task 1 Excel workbook were incorporated directly
- A consistent colour palette and font hierarchy maintained a professional look

**Step 3 — Self-Reflection Slide**
The final slide was a structured self-reflection on the consulting process — acknowledging what worked well, what could be improved, and what was learned. This mirrors the quality-review culture within KPMG advisory teams.

### Deck Structure

| Slide | Title | Content |
|---|---|---|
| 1 | Cover | Healthy Co Operational Efficiency Analysis — KPMG Advisory |
| 2 | Executive Summary | Three headline findings + projected financial impact ($180K–$250K in annual wait-cost savings) |
| 3 | Data Insights | Peak-hour wait chart, doctor outlier table, diagnosis group breakdown |
| 4 | Leading Practices | Two recommended strategies with fit-to-client rationale and evidence citations |
| 5 | Next Steps | 3-phase, 90-day implementation roadmap with owner assignments and milestones |
| 6 | Self-Reflection | Strengths, areas for improvement, and key personal learnings from the engagement |

### Results

The completed deck communicated a clear, evidence-based case for change. The projected impact headline — **$180,000–$250,000 in annual savings** from reduced wait costs, improved throughput, and avoided overtime — gave leadership a concrete financial anchor to justify investment in the recommended changes. The 90-day roadmap broke the implementation into manageable phases, reducing the perceived risk of change for a risk-averse healthcare client.

### Deliverable

📁 `04_Preparing_Summary_Presentation/output/Healthy_Co_Wait_Time_Reduction_Strategy.pptx`
A six-slide, KPMG-style executive presentation ready for client delivery, incorporating data visuals, leading practice summaries, financial impact estimates, and an implementation roadmap.

---

## 6. Task 4 — Initiative Brainstorming

### Background & Objective

Even the best near-term recommendations can feel incremental. To genuinely transform patient experience, Healthy Co also needs a long-term innovation horizon. This task required shifting from analytical thinking to **divergent, creative ideation** — generating 10–15 bold, patient-centric initiatives without being constrained by budget, technology readiness, or organisational feasibility.

The secondary objective was to identify which **additional KPMG service lines** could support Healthy Co beyond the current engagement scope.

### Approach

**Step 1 — Unconstrained Ideation**
Initiatives were generated using a structured brainstorm template, with each idea rated on two axes:
- **Patient Impact** — How significantly would this improve the patient experience?
- **Implementation Ease** — How feasible is this to implement given Healthy Co's current capabilities?

Ideas were deliberately diverse — spanning technology, process redesign, staffing, and communication — to ensure a broad solution space.

**Step 2 — Categorisation & Rationale**
Each initiative was assigned a category (Digital Innovation, Operational Redesign, Clinical Pathway, Patient Communication) and given a brief rationale explaining the connection to the core problem.

**Step 3 — KPMG Service Alignment**
For each cluster of initiatives, relevant KPMG service offerings were identified that could support implementation — signalling potential expansion opportunities for the engagement.

### Results — 15 Initiatives Generated

| # | Initiative | Category | Rationale |
|---|---|---|---|
| 1 | Pre-Arrival Digital Check-In | Digital Innovation | Removes registration bottleneck; reduces lobby crowding |
| 2 | Real-Time Wait Transparency Dashboard | Patient Communication | Sets expectations; reduces perceived wait anxiety |
| 3 | Text-to-Seat Virtual Queue | Digital Innovation | Lets patients wait outside until called; frees physical space |
| 4 | AI Symptom Triage Chatbot | Clinical Pathway | Pre-sorts patients before arrival; flags high-acuity cases early |
| 5 | Low-Acuity Fast-Track Lane | Operational Redesign | Routes Group 3 patients (59% of volume) to dedicated express pathway |
| 6 | Predictive Peak-Hour Staffing Model | Operational Redesign | Dynamic scheduling based on historical demand patterns |
| 7 | Tele-Urgent Care Diversion | Clinical Pathway | Diverts appropriate cases to video consult; reduces in-person volume |
| 8 | On-Site Pharmacy Integration | Patient Experience | Eliminates post-visit pharmacy trip; improves discharge completion |
| 9 | Electronic Medical Records (EMR) Optimisation | Digital Innovation | Reduces documentation time between stages; speeds up handoffs |
| 10 | Community Health Navigator Programme | Patient Communication | Proactive outreach to repeat visitors to address root health causes |
| 11 | Standardised Nurse Vitals Protocol | Operational Redesign | Directly reduces the 35% variation identified in Task 1 data |
| 12 | Appointment Slot Block Scheduling | Operational Redesign | Staggers arrivals to prevent simultaneous triage demand spikes |
| 13 | Patient Satisfaction Pulse Survey (Post-Visit SMS) | Patient Communication | Captures real-time feedback to close the loop on experience improvements |
| 14 | Facility-Level Performance Scorecards | Operational Redesign | Creates accountability and friendly competition across 25 facilities |
| 15 | Voice-Activated Clinical Notation (AI Scribe) | Digital Innovation | Reduces doctor documentation burden; shortens per-patient consultation time |

### Additional KPMG Services Recommended

| Service Line | Relevance to Healthy Co |
|---|---|
| **Digital Transformation & Technology** | Required to implement Initiatives 1, 3, 4, 7, 9, 15 — covering app development, EMR integration, and AI tooling |
| **People & Change / Human Capital** | Critical for staff retraining (Initiative 11), change management, and embedding new workflows sustainably |
| **Customer Experience (CX) Transformation** | Needed to redesign the end-to-end patient journey from a human-centred perspective, not just an operational one |

### Deliverable

📁 `05_Initiative_Brainstorming/output/Healthy_Co_Initiative_Brainstorm_Completed.docx`
A fully populated brainstorm template containing all 15 initiatives with impact/ease ratings, category tags, and implementation rationales, plus the KPMG service alignment recommendations.

---

## 7. Overall Results & Key Findings

Across all four tasks, the engagement produced a coherent, evidence-based picture of Healthy Co's operational challenges and a credible path to resolution.

### Quantified Problem Size

| Metric | Value |
|---|---|
| Average total wait time | **39.7 minutes** (vs. 20–25 min industry benchmark) |
| Peak wait time | **48.3 minutes** (noon slot) |
| Nurse vitals variation | **35%** across staff |
| Doctor outlier excess cost | **$1,482/visit** (Dr. Balla) |
| Visits analysed | **4,984 patient records** |

### Projected Impact of Recommendations

| Recommendation | Evidence-Based Impact |
|---|---|
| Predictive Staff Scheduling | **15% wait reduction**, 12% utilisation improvement |
| Staff Retraining + Workflow + Block Scheduling | **28% median wait reduction** |
| Combined implementation | Estimated **$180,000–$250,000** annual savings from reduced overtime, improved throughput, and lower per-visit wait costs |

### Innovation Horizon

The 15-initiative brainstorm provides Healthy Co with a pipeline of ideas spanning quick wins (Pre-Arrival Check-In, Fast-Track Lane) through to longer-term digital transformation plays (AI Triage Chatbot, Voice Scribe), ensuring the engagement's value extends well beyond the immediate deliverables.

---

## 8. Conclusion

This simulation demonstrates that operational improvement in healthcare is achievable — and measurable — when approached through a structured, data-first consulting methodology.

**The core insight from this engagement is straightforward:** Healthy Co's wait-time problem is not a mystery. The data reveals predictable peak windows, addressable staffing variation, and a large segment of low-acuity patients who could be routed faster. None of these root causes require expensive technology or a multi-year transformation. The two leading practices selected — predictive scheduling and retraining-plus-workflow streamlining — are proven, implementable, and financially justifiable.

**The 90-day roadmap** proposed in the executive presentation breaks this down into three phases:
1. **Weeks 1–4** — Baseline measurement, staff retraining design, and scheduling model scoping
2. **Weeks 5–8** — Pilot implementation at 2–3 high-volume facilities; process adjustments based on real-world feedback
3. **Weeks 9–13** — Full rollout across all 25 facilities; performance scorecard launch; initiative pipeline prioritisation

**Beyond the immediate engagement**, the 15-initiative brainstorm signals that Healthy Co has the potential to evolve from reactive urgent care to a proactively managed, digitally enabled patient experience leader. With the right partners and phased investment, the innovations identified in Task 4 could differentiate Healthy Co in an increasingly competitive urgent care market.

This portfolio demonstrates the full advisory skill set — analytical rigour, evidence-based research, executive communication, and creative thinking — applied in a realistic, client-centred context using the KPMG CREATE Framework.

---

## 9. Repository Structure

```
theforage-kpmg-advisory/
│
├── 02_Understanding_Client_Operations/
│   ├── input/
│   │   ├── KPMG Healthy Co Profile.pdf          # Client background and org structure
│   │   └── KPMG Healthy Co Raw Data.xlsx        # 4,984 raw patient visit records
│   └── output/
│       └── Healthy_Co_Data_Analysis_Task2.xlsx  # Cleaned data, 9 pivots, charts, summary
│
├── 03_Leading_Practice_Research/
│   ├── input/
│   │   ├── KPMG Task3 Resources.pdf             # 5 curated research resources
│   │   └── KPMG Task3 Template.docx             # Structured evaluation template
│   └── output/
│       └── Healthy_Co_Task3_Completed.docx      # Resource evaluations + top 2 recommendations
│
├── 04_Preparing_Summary_Presentation/
│   ├── input/
│   │   └── Presentation Shell.pptx              # KPMG-branded slide template
│   └── output/
│       └── Healthy_Co_Wait_Time_Reduction_Strategy.pptx  # 6-slide executive deck
│
├── 05_Initiative_Brainstorming/
│   ├── input/
│   │   └── Template - Initiative Brainstorm.docx  # Structured ideation template
│   └── output/
│       └── Healthy_Co_Initiative_Brainstorm_Completed.docx  # 15 initiatives + KPMG service recs
│
└── assets/
    ├── KPMG CREATE Prompts.pdf                  # Framework reference guide
    ├── KPMG PowerPoint Storyboard Training.pdf  # Presentation design training material
    ├── KPMG Presentation Tips for Effective Delivery.pdf
    └── Task 2_ Step-by-Step Guide.pdf           # Data analysis methodology guide
```

Each task folder follows the same `input/` → `output/` pattern, making it easy to trace the progression from raw materials to polished deliverables across the full consulting workflow.

---

## 10. Skills Demonstrated

| Skill Area | Application in This Engagement |
|---|---|
| **Data Literacy & Excel** | Cleaned 4,984 records; built 9 pivot tables; engineered calculated columns; produced a data dashboard |
| **Quantitative Analysis** | Identified statistical outliers (Dr. Balla), calculated cost impact of wait time, and sized the improvement opportunity |
| **Research & Synthesis** | Evaluated 5 resources across credibility, relevance, recency, and actionability; distilled into two precise recommendations |
| **Evidence-Based Advisory** | Tied every recommendation directly to client data — no generic advice |
| **Executive Communication** | Designed a six-slide deck with a clear narrative arc, visual hierarchy, and a one-message-per-slide discipline |
| **Creative Problem-Solving** | Generated 15 patient-centric initiatives across four categories, rated by impact and ease |
| **Strategic Thinking** | Identified KPMG service expansion opportunities and framed a 90-day phased implementation roadmap |
| **Structured Frameworks** | Applied the KPMG CREATE Framework consistently across all four tasks |

---

*This portfolio was prepared as part of the **KPMG Virtual Experience Program (VEP) — Career Catalyst: Advisory** track. All client data and scenarios are simulated for educational purposes. Prepared: May 2026.*
