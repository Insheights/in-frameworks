# Insheights 3E Operational Values Measurement Model — Practitioners Guide

**How to apply Efficiency, Experience, and Effectiveness measurement across any architecture element in the IIVCS.**

---

## At a Glance

| | |
|---|---|
| **What it does** | Provides a consistent three-dimension measurement language — Efficiency, Experience, Effectiveness — applied across any architecture element to surface whether value is accessible, felt, and achieving outcomes |
| **When to use it** | Any time you need to measure whether value is being delivered at a specific architecture element: Value Stream, Value Stage, Capability, Process, or Product/Service |
| **Who runs it** | Product team lead, Value Stream owner, or the person accountable for the element being measured |
| **Who must be in the room** | Customer-facing team members (for Experience signals); delivery team members (for Efficiency signals); outcome owners (for Effectiveness signals) |
| **Key inputs** | A defined architecture element; a stated value promise for that element; access to customer and delivery signals |
| **Key outputs** | A 3E profile for the element; a diagnostic reading (which dimension is underperforming and why); a measurement cadence |
| **Typical timeframe** | Initial profile: one working session. Ongoing measurement: aligned to CVDM feedback loop cadence |

> **Not a product organization?** "Product/Service" → "program/service"; "customer" → "patient/client/citizen/beneficiary"; "team" → "delivery unit."

---

## Before You Start

**Inputs required**

- [ ] A named architecture element (Value Stream, Value Stage, Capability, Process, or Product/Service) — you must know what you are measuring before you can apply 3E
- [ ] A stated value promise — what this element is supposed to deliver, to whom, and under what conditions
- [ ] Access to at least one signal source per dimension: friction/effort data for Efficiency, sentiment/behavioral data for Experience, outcome data for Effectiveness
- [ ] The CVDM customer journey map for the relevant value stream (for Efficiency and Experience signal sourcing)

**People required**

| Role | Why they must be present |
|---|---|
| Element owner | Owns the value promise definition and the measurement cadence |
| Customer-facing team member(s) | Source of Experience signals — they are closest to how value is being felt |
| Delivery/operations team member(s) | Source of Efficiency signals — they see friction and effort first |
| Outcome owner | Accountable for Effectiveness — whether outcomes are being achieved |

**Prepare the room**

- Have the element's value promise written down in advance — if the room cannot agree on what the element is supposed to deliver, 3E measurement cannot begin
- Gather any existing signal data (usage analytics, support tickets, NPS/CSAT, completion rates, outcome metrics) before the session
- Know which CVDM feedback loop this element feeds: Experience feedback, Journey insights, Delivery learning, Strategic evolution, or Performance optimization

---

## How to Run It

Each step below is an action. Complete them in order — later steps depend on earlier outputs.

---

### Step 1 — Define the element and its value promise

**What you do:** Name the architecture element you are measuring, state its level (Value Stream, Value Stage, Capability, Process, or Product/Service), and write a single-sentence value promise — what it is supposed to deliver, to whom.

**Key question this step answers:** *What is this element supposed to do, and for whom?*

**Inputs:** Knowledge of the IIVCS architecture; CVDM customer journey map
**Output:** Element definition — name, level, value promise sentence

**Guidance:**
- The value promise must be written from the customer's perspective, not the organization's. "Enables customers to onboard without IT involvement" is a value promise. "Completes the provisioning workflow" is not.
- If the team cannot agree on the value promise in this step, stop. Measuring without agreement on what you are measuring produces noise, not signal.
- You are done when you can complete this sentence: "[Element name] delivers [value] to [customer/stakeholder] by [mechanism]."

---

### Step 2 — Translate the 3E dimensions to this element

**What you do:** For each of the three dimensions — Efficiency, Experience, Effectiveness — write the specific question that dimension asks at this element's level. Use the 3E dimension questions as the starting template, then make them concrete.

**Key question this step answers:** *What does Efficiency, Experience, and Effectiveness mean specifically here?*

**Inputs:** Element definition (Step 1); 3E dimension definitions
**Output:** 3E question set — three specific, observable questions for this element

**Guidance:**
- Use the standard 3E architecture questions as your starting point, then substitute the element's specific value promise. "Can customers access and use it without friction?" becomes "Can a new B2B customer complete onboarding without raising a support ticket?"
- Effectiveness must connect directly to the value promise. If the value promise is "enable customers to realize ROI within 90 days," Effectiveness asks: "Are customers realizing ROI within 90 days?"
- The Efficiency question must be answerable with observable data — not a survey. If you cannot observe the friction, you need a different Efficiency question.

**3E question starter templates by level:**

| Level | Efficiency | Experience | Effectiveness |
|---|---|---|---|
| **Value Stream** | Does it activate and deliver without unnecessary cost or friction? | Do customers and teams experience it positively? | Does it achieve its strategic outcomes? |
| **Value Stage** | Does it activate without friction, delay, or unnecessary effort? | Does the customer feel positive, confident, and supported? | Does it deliver its intended contribution to the customer outcome? |
| **Capability** | Does it activate without waste, friction, or unnecessary cost? | Do teams and customers feel it working positively? | Does it deliver its intended contribution to the value stage? |
| **Process** | Does it execute without friction, delay, or unnecessary effort? | Do participants feel it is fair, clear, and supportive? | Does it produce its intended outcome consistently? |
| **Product/Service** | Can customers access and use it without friction? | Do customers feel positive, confident, and supported? | Does it deliver the intended value proposition? |

---

### Step 3 — Define and instrument measurement signals

**What you do:** For each 3E question, identify the specific observable signal(s) you will use to answer it. Classify each signal as leading (Efficiency, Experience) or lagging (Effectiveness).

**Key question this step answers:** *What will we measure, and when will those signals surface?*

**Inputs:** 3E question set (Step 2); available signal sources
**Output:** 3E signal map — signals per dimension, classified by leading/lagging, with source and cadence

**Guidance:**
- Each dimension needs at minimum one leading signal (Efficiency, Experience) or one lagging signal (Effectiveness). More signals give richer diagnosis; fewer signals give faster feedback.
- Efficiency signals are typically operational: completion rates, error rates, time-to-value, support ticket volume, drop-off points, cost-per-activation.
- Experience signals are behavioral and attitudinal: CSAT at step level, day-two return rate, churn before outcomes can be confirmed, qualitative sentiment from customer-facing teams.
- Effectiveness signals are outcome-based: goal attainment rates, retention curves, revenue impact, outcome validation interviews, NPS timed after sufficient time for outcomes to materialize.
- Do not wait for perfect signal data. One Efficiency signal, one Experience signal, and one Effectiveness signal is enough to begin the diagnostic.

**Signal source reference:**

| Dimension | Typical Signal Sources |
|---|---|
| **Efficiency** | Usage analytics, completion rates, support ticket category analysis, time-to-activation, error logs, cost-per-unit |
| **Experience** | Post-step CSAT, NPS (timed to feel, not outcome), qualitative interviews, team-reported friction observations, churn before outcomes are realized |
| **Effectiveness** | Outcome interviews, retention after sufficient time, goal attainment metrics, revenue per customer, repeat engagement rate |

---

### Step 4 — Baseline, diagnose, and act

**What you do:** Run the first 3E measurement. Record the current state of each dimension. Then use the sequence diagnostically — if Effectiveness is underperforming, trace upstream through Experience and Efficiency before concluding.

**Key question this step answers:** *Where in the Use → Feel → Achieve sequence is value breaking down?*

**Inputs:** 3E signal map (Step 3); current signal data
**Output:** 3E baseline profile — current state per dimension; diagnostic conclusion; prioritized action

**Guidance:**
- Read the sequence, not the dimensions in isolation. An Effectiveness gap preceded by a strong Experience signal points to a delivery or product failure. An Effectiveness gap preceded by a weak Experience signal points upstream — fix Experience first.
- Efficiency is the table stake. If Efficiency is failing, Experience and Effectiveness cannot be meaningfully measured until friction is resolved. Prioritize Efficiency before analyzing the other two dimensions.
- A baseline is not a judgment. The first measurement establishes where you are — not whether the element is good or bad. The value of the baseline is comparison over time.
- The diagnostic output must be a specific action, not a general observation. "Efficiency is low because onboarding requires IT involvement — action: remove the IT dependency from step 2" is complete. "Efficiency needs improvement" is not.

**Diagnostic sequence:**

```
Effectiveness underperforming?
    → Is Experience strong?
        → Yes: problem is in delivery or product — Effectiveness gap is real, address directly
        → No: fix Experience first — Effectiveness may follow
    → Is Efficiency strong?
        → No: fix Efficiency first — Experience and Effectiveness cannot be reached
```

---

### Step 5 — Activate the feedback loop

**What you do:** Define the cadence, owners, and return path for 3E signals from this element — establishing which CVDM feedback loop this element feeds and at what frequency signals are reviewed.

**Key question this step answers:** *How will we know when the 3E profile needs to be revisited?*

**Inputs:** 3E baseline profile (Step 4); CVDM feedback loop map
**Output:** 3E governance cadence — review frequency, named owners, return path, out-of-cycle triggers

**Guidance:**
- Experience signals must be reviewed on the shortest cadence — they surface before outcomes can be confirmed and are the most actionable early warning signal.
- Effectiveness signals are reviewed on the longest cadence — they require sufficient time for outcomes to materialize. Do not judge Effectiveness on a cadence shorter than the customer's outcome realization window.
- Name a single owner for each dimension signal. Shared ownership of a signal means no one acts on it.
- Define at minimum two out-of-cycle triggers: an Experience signal drop (early warning) and an Effectiveness signal drop (outcome confirmation). Both should trigger an immediate upstream review.

**Return path by CVDM feedback loop:**

| CVDM Loop | What 3E signals return to it | Cadence |
|---|---|---|
| **Experience feedback** | Experience signals from all elements | Continuous / weekly |
| **Journey insights** | Efficiency signals revealing friction across the journey | Sprint / bi-weekly |
| **Delivery learning** | Effectiveness signals from Value Stages and Products/Services | Monthly / quarterly |
| **Strategic evolution** | Effectiveness signals from Value Streams | Quarterly / annually |
| **Performance optimization** | Efficiency signals from Capabilities and Processes | Sprint / monthly |

---

## Worked Examples

---

### Example 1 — B2B SaaS Onboarding (Product/Service level)

> **Scenario:** A mid-market B2B SaaS company sells a workflow automation tool to operations teams. Customer success data shows that 40% of customers who complete a trial do not convert to paid accounts. The product team applies 3E to the onboarding product to diagnose where value is breaking down.

**Step 1 — Define the element and its value promise**

Element: **onboarding product** (Product/Service level). Value promise: *The onboarding product enables a new operations team to configure and run their first automated workflow without technical support, within their first five days.*

**Step 2 — Translate the 3E dimensions**

- **Efficiency:** Can a new operations team member complete their first workflow configuration without raising a support ticket or requiring IT involvement?
- **Experience:** Does the new customer feel confident and capable during onboarding — not anxious, confused, or dependent on external help?
- **Effectiveness:** Does the customer activate to a paid account and successfully run their first automated workflow within five days?

**Step 3 — Define signals**

| Dimension | Signal | Source | Type |
|---|---|---|---|
| **Efficiency** | % of trial users who complete configuration without opening a support ticket | Support system + product analytics | Leading |
| **Efficiency** | Average steps-to-first-run (actual vs. designed) | Product analytics | Leading |
| **Experience** | Post-onboarding CSAT (1–5) | In-product survey at day 3 | Leading |
| **Experience** | % of users who return to the product on day 2 without prompting | Product analytics (session data) | Leading |
| **Effectiveness** | % of trials converting to paid within 14 days | CRM / billing system | Lagging |
| **Effectiveness** | % of paid accounts running at least one workflow in first 30 days | Product analytics | Lagging |

**Step 4 — Baseline and diagnose**

Baseline: 62% of users complete configuration without raising a ticket (Efficiency: moderate). Post-onboarding CSAT: 3.2/5 (Experience: weak). Day-2 return rate: 44% (Experience: weak). Trial-to-paid conversion: 60% against a target of 75% (Effectiveness: underperforming).

Diagnostic: Effectiveness is underperforming. Experience is weak — this points upstream. Trace to Efficiency: 38% of users hit a friction point severe enough to raise a ticket. The Experience weakness is downstream of an Efficiency gap.

The Efficiency gap is in the configuration step — the API key entry requires an IT handoff. Action: implement OAuth-based auto-connect to remove the IT dependency. Measure Experience again once Efficiency is restored before acting on the conversion gap directly.

**Step 5 — Activate the feedback loop**

- Experience signals reviewed weekly by the product team → feeds CVDM Experience feedback loop
- Efficiency signals reviewed at each sprint end by the product lead → feeds Journey insights loop
- Effectiveness reviewed monthly — 14-day trial window requires 30-day confirmation to confirm trends
- Out-of-cycle trigger: Day-2 return rate drops below 40% → immediate experience review
- Owner: product lead owns Efficiency and Experience signals; customer success lead owns Effectiveness signal

---

### Example 2 — Patient Discharge Process (Process level, Healthcare)

> **Scenario:** A regional hospital system is seeing 30-day cardiac readmission rates above target. The care operations team applies 3E to the cardiac discharge process to understand where the value chain is breaking down.

**Step 1 — Define the element and its value promise**

Element: **cardiac discharge process** (Process level). Value promise: *The discharge process ensures every cardiac patient leaves with a clear, actionable care plan they understand and can follow, enabling recovery without preventable readmission.*

**Step 2 — Translate the 3E dimensions**

- **Efficiency:** Does the discharge process execute without delay, confusion, or unnecessary handoffs that extend the patient's stay or create administrative burden?
- **Experience:** Does the patient feel informed, confident, and supported at the point of discharge — not anxious or unclear about what to do next?
- **Effectiveness:** Does the patient complete their post-discharge care plan without requiring an unplanned return within 30 days?

**Step 3 — Define signals**

| Dimension | Signal | Source | Type |
|---|---|---|---|
| **Efficiency** | Average discharge time from physician sign-off to patient departure | EHR / operations data | Leading |
| **Efficiency** | % of discharge packets completed without requiring a second clinical review | EHR audit | Leading |
| **Experience** | Post-discharge confidence score (1–5): "How confident do you feel about your recovery plan?" | Discharge survey | Leading |
| **Experience** | % of patients calling the discharge helpline within 48 hours with questions already covered in discharge instructions | Call center data | Leading |
| **Effectiveness** | 30-day unplanned readmission rate | EHR / quality reporting | Lagging |
| **Effectiveness** | % of patients completing first follow-up appointment within 7 days | Scheduling system | Lagging |

**Step 4 — Baseline and diagnose**

Baseline: Average discharge time: 4.2 hours from sign-off against a target of 2 hours (Efficiency: high friction). Post-discharge confidence score: 3.8/5 (Experience: moderate). 48-hour helpline call rate for covered questions: 28% (Experience: weak — patients are not retaining instructions). 30-day readmission rate: 18% against a target of 12% (Effectiveness: underperforming).

Diagnostic: Effectiveness is underperforming. Experience is moderate-to-weak. Trace to Efficiency: the 4.2-hour discharge time is driven by a pharmacy, nursing, and administrative sign-off sequence running serially. The delay creates patient anxiety (undermining Experience) and rush at end of discharge (undermining instruction quality and Effectiveness downstream).

Actions: Redesign the sign-off sequence to run pharmacy and administrative steps in parallel (Efficiency fix). Add a teach-back confirmation step — patient verbally restates care plan before departure — to confirm comprehension before discharge completes (Experience fix that directly supports Effectiveness).

**Step 5 — Activate the feedback loop**

- Experience signals (confidence scores, helpline call rate) reviewed weekly by care operations → feeds Experience feedback loop
- Efficiency signals reviewed at each monthly operations review → feeds Performance optimization loop
- Effectiveness reviewed quarterly — 30-day readmission window requires 90+ days of data to confirm trends
- Out-of-cycle trigger: helpline call rate for covered questions exceeds 35% → immediate discharge instruction review
- Owner: discharge coordinator owns Efficiency signal; patient experience lead owns Experience signal; quality and outcomes lead owns Effectiveness signal

---

### Example 3 — Loyalty Value Stream (Value Stream level, Retail)

> **Scenario:** A national retailer's loyalty program is generating declining engagement despite significant investment. The commercial team applies 3E at the Value Stream level to understand whether the loyalty value stream is delivering its strategic outcomes.

**Step 1 — Define the element and its value promise**

Element: **loyalty value stream** (Value Stream level). Value promise: *The loyalty value stream earns the ongoing engagement and advocacy of our highest-value customers by consistently delivering personalized, rewarding experiences that make them feel recognized and valued.*

**Step 2 — Translate the 3E dimensions**

- **Efficiency:** Does the loyalty value stream activate and deliver value without unnecessary friction — is earning, redeeming, and experiencing benefits effortless for the customer?
- **Experience:** Do loyalty members feel recognized, valued, and personally served — not like recipients of generic promotions?
- **Effectiveness:** Is the loyalty value stream generating the customer retention, spend growth, and advocacy that justify its strategic investment?

**Step 3 — Define signals**

| Dimension | Signal | Source | Type |
|---|---|---|---|
| **Efficiency** | % of members who redeem at least one benefit per quarter without contacting support | Loyalty platform + CRM | Leading |
| **Efficiency** | Average steps to redeem a benefit (actual vs. designed) | Loyalty platform analytics | Leading |
| **Experience** | Loyalty NPS (measured 2 weeks after first reward redemption) | CRM survey | Leading |
| **Experience** | % of members opening personalized communications vs. generic | Email/push analytics | Leading |
| **Effectiveness** | Loyalty member 12-month retention rate vs. non-member (cohort comparison) | CRM | Lagging |
| **Effectiveness** | Average annual spend per loyalty member vs. non-member | Sales data | Lagging |
| **Effectiveness** | % of new customers acquired via member referral | Attribution data | Lagging |

**Step 4 — Baseline and diagnose**

Baseline: Quarterly benefit redemption rate: 34% (Efficiency: weak — two-thirds of members are not actively using the program). Loyalty NPS: 42 (Experience: moderate). Personalized communication open rate: 31% vs. 12% for generic (Experience: strong signal where personalization exists, but most communications are still generic). 12-month member retention: 61% vs. 48% non-member (Effectiveness: moderate). Annual spend differential: +22% against a program investment threshold of +35% (Effectiveness: underperforming at program scale).

Diagnostic: Effectiveness is below the investment threshold. Experience is moderate but the personalization signal shows customers respond strongly when they feel recognized — the opportunity exists. Trace to Efficiency: 66% of members are not redeeming any benefit per quarter. Redemption is the Efficiency gate for this value stream. Customers who cannot easily activate the value will not form the Experience or produce the Effectiveness outcomes the program requires.

Actions: Reduce steps-to-redemption from 5 to 2 (Efficiency fix). Extend personalized communications using available purchase history to the full member base, not just a segment (Experience fix). Measure Experience and Efficiency again at 60 days before reassessing Effectiveness.

**Step 5 — Activate the feedback loop**

- Experience signals reviewed monthly by the loyalty program team → feeds Experience feedback loop
- Efficiency signals reviewed quarterly and after any platform change → feeds Performance optimization loop
- Effectiveness reviewed semi-annually — retention and spend differentials require 6-month cohort windows
- Out-of-cycle trigger: quarterly redemption rate drops below 30%, or loyalty NPS drops 5+ points → immediate experience investigation
- Return path: Effectiveness signals → CVDM Strategic evolution loop → OSM strategic reassessment for loyalty investment decision
- Owner: loyalty program manager owns Efficiency and Experience signals; commercial director owns Effectiveness signal

---

## Measurement Connection

3E is the measurement framework, but its outputs connect forward to AER and upstream to the 8 Values.

### How 3E drives AER

Each 3E dimension drives the corresponding AER stage across both Customer AER and Organizational AER:

| 3E Dimension | AER Stage | Connection |
|---|---|---|
| **Efficiency** | Adoption | Frictionless access lowers the barrier to entry — customers and teams adopt what they can reach |
| **Experience** | Engagement | Positive feeling sustains active participation — customers and teams engage with what they trust |
| **Effectiveness** | Retention | Outcomes achieved earn continued commitment — customers and teams persist with what works |

A 3E gap predicts an AER gap. A diagnosed Efficiency failure predicts an Adoption problem in AER before behavioral data confirms it — enabling earlier intervention.

### 8 Values most directly influenced by 3E

| 3E Primary Signal | Most Influenced 8 Value | Mechanism |
|---|---|---|
| **Efficiency** (leading) | Operational Value | Friction-free execution is the core measure and output of operational capability |
| **Experience** (leading) | Customer Value | How value is felt is the most direct Customer Value signal — ahead of outcomes |
| **Effectiveness** (lagging) | Strategic Value | Outcome achievement validates or refutes the strategic hypotheses behind the element |

---

## System Health Check

These signals confirm 3E is being applied correctly — not just being followed procedurally.

| Signal | Healthy | At Risk |
|---|---|---|
| 3E question specificity | Each question is element-specific and answerable with observable data | Questions are generic ("is efficiency good?") or cannot be measured |
| Leading/lagging signal balance | At least one leading signal (Efficiency or Experience) is reviewed before Effectiveness | Only Effectiveness is monitored — leading signals are absent |
| Diagnostic sequencing | When Effectiveness underperforms, Experience and Efficiency are checked before action is taken | Actions are taken directly on Effectiveness without tracing upstream |
| Signal ownership | Each dimension has a named owner who is accountable for acting on signal changes | Signals are reported into a shared inbox but no one is specifically accountable |
| Feedback loop connection | 3E signals are named in at least one CVDM feedback loop with a defined cadence | 3E measurements are produced but not connected to any upstream return path |

**If two or more signals are At Risk:** Stop measuring and restart from Step 1. The 3E profile being generated is not connected to the value delivery system — reclarify the element, its value promise, and its feedback return path before measuring again.

---

## Translation Notes

### Non-product contexts

| IIVCS Default | Healthcare | Government | Professional Services | Manufacturing | Financial Services |
|---|---|---|---|---|---|
| Customer | Patient / client | Citizen / resident | Client / beneficiary | End customer / buyer | Client / policyholder |
| Product/Service | Clinical program / pathway | Policy / program / service | Engagement / solution | Product line / SKU | Product / policy |
| Value Stream | Care pathway | Service delivery stream | Client delivery lifecycle | Production line / value chain | Service fulfillment stream |
| Capability | Clinical capability | Program delivery capability | Practice capability | Production capability | Underwriting / servicing capability |
| Process | Clinical process | Administrative / service process | Methodology step | Manufacturing process | Underwriting / claims process |

> **Core principle:** The Use → Feel → Achieve sequence and the leading/lagging signal structure are unchanged across sectors — only the vocabulary for what "use," "feel," and "achieve" look like in that context shifts.

---

## Quick Reference

**Steps**

1. Define the element and its value promise — *What is this supposed to deliver, and for whom?*
2. Translate 3E dimensions to this element — *What does Efficiency, Experience, Effectiveness mean here?*
3. Define and instrument signals — *What will we measure, and when does it surface?*
4. Baseline, diagnose, and act — *Where in Use → Feel → Achieve is value breaking down?*
5. Activate the feedback loop — *How will we know when to revisit?*

**Health signals at a glance**

- 3E questions are element-specific and observable — not generic
- At least one leading signal exists for Efficiency and Experience before Effectiveness is read
- Effectiveness underperformance is always diagnosed upstream first
- Each dimension has a named owner accountable for acting
- Signals feed a named CVDM feedback loop with a defined cadence

**Diagnostic sequence**

```
Effectiveness gap → check Experience → check Efficiency → fix the earliest failure in the chain
```

**3E → AER connection**

Efficiency enables Adoption | Experience sustains Engagement | Effectiveness earns Retention

**Primary 8 Values driven:** Operational Value (Efficiency), Customer Value (Experience), Strategic Value (Effectiveness)

---

© 2026 Insheights LLC. All rights reserved.
