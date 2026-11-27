# Customer Value Delivery Model (CVDM) — Practitioners Guide

**How to map the customer journey to value streams, define the value stages that deliver the value proposition, and run the five feedback loops that realize and prove customer value.**

---

## At a Glance

| | |
|---|---|
| **What it does** | Maps each customer journey step to the value stage that serves it, defines the capabilities, processes, products/services, and information concepts (and their flows) that deliver the value proposition as a realized customer outcome, and surfaces signal through five continuous feedback loops |
| **When to use it** | Designing or fixing how value reaches the customer; when delivery produces activity but not outcomes; when the journey and the value stream are not connected; when customer signal is not feeding back upstream |
| **Who runs it** | The persistent cross-functional product team (built in [Product Transformation System (PTS)](../README.md#pts--product-transformation-system)); the value-stream / journey owner |
| **Who must be in the room** | Customer-facing team members, delivery/operations members, the value-stream owner, and someone who owns each capability the journey depends on |
| **Key inputs** | The teams and capabilities supplied by PTS; the value-stream outcome from [Organization Strategy Model (OSM)](../README.md#osm--organization-strategy-model); customer journey knowledge; the value proposition |
| **Key outputs** | A journey-to-value-stream map; defined value stages with value propositions; operationalized capabilities/processes; [Efficiency, Experience, Effectiveness (3E)](../3e.md) + Customer [Adoption, Engagement, Retention (AER)](../aer.md) instrumentation; five active feedback loops |
| **Typical timeframe** | Initial map and instrumentation: one to two working sessions per value stream. Feedback loops: continuous thereafter |

> **New to the [Insheights Integrated Value Creation System (IIVCS)](../README.md)?** This guide uses system terms — value stream, value stage, capability, value proposition, 3E, AER, the 8 Values, OSM, PTS, Product Mindset — defined in the [Glossary](../glossary.md). [Framework Positioning](../positioning.md) explains how CVDM relates to the other frameworks in a few minutes; read it first if you are starting here.

> **Not a product organization?** "Customer" → "patient / citizen / client"; "product/service" → "program / pathway / engagement"; "journey" → "patient pathway / case lifecycle." The realization logic is unchanged — only the vocabulary shifts. See [Translation Notes](#translation-notes).

> **Where this fits:** CVDM is the delivery and realization layer of the IIVCS — where value is **realized** as a customer outcome. It is **enabled** by the teams and capabilities PTS supplies, **realizes** the value-stream outcomes OSM defined, and returns operational feedback to PTS and strategic signals to OSM. It is the home of **Customer AER** and where **3E** is primarily surfaced. See [Framework Positioning](../positioning.md).

---

## Before You Start

**Inputs required**

- [ ] **The value-stream outcome (from OSM, carried by PTS)** — what this value stream is meant to produce. CVDM realizes it; it does not redefine it.
- [ ] **The persistent cross-functional team and capabilities (from PTS)** — CVDM is activated by the teams PTS builds. Without empowered teams serving the value stream's stages, there is no one to realize the journey.
- [ ] **The customer journey** — the actual steps a customer takes, from their perspective, not the org's internal process.
- [ ] **The value proposition** — what value the customer is promised at the journey, and the realized outcome that proves it.
- [ ] **Access to customer and delivery signal** — experience, friction, and outcome data sources, so the five feedback loops have something to surface.

**People required**

| Role | Why they must be present |
|---|---|
| Value-stream / journey owner | Owns the journey-to-value-stream mapping and the value-stage definitions |
| Customer-facing team member(s) | Closest to how the journey is actually experienced — add staff observation to the customer's own signal |
| Delivery / operations member(s) | Own the capabilities and processes each value stage depends on |
| Capability owners | Accountable for the capabilities and processes that deliver each value stage |
| Data / analytics support | Instruments 3E and Customer AER across the journey |

**Prepare the room**

- Bring the *actual* customer journey, mapped from the customer's point of view — not the internal workflow diagram. CVDM starts from the journey, not the org chart.
- Have the value-stream outcome and value proposition written down — the journey is mapped to deliver *these*.
- Gather existing signal: experience data, friction/drop-off points, outcome metrics — so the feedback loops can be instrumented, not invented.

---

## How to Run It

Each step below is an action. Complete them in order — later steps depend on earlier outputs. Once mapped and instrumented, the five feedback loops run continuously.

---

### Step 1 — Map the customer journey to the value stream

**What you do:** Lay out the customer journey step by step, from the customer's perspective. For each journey step, identify the value stage that serves it. Every journey step must trigger the right value stage — that mapping is the spine of CVDM.

**Key question this step answers:** *What does the customer actually do, and which value stage serves each step?*

**Inputs:** The customer journey; the value stream and its outcome
**Output:** A journey-to-value-stream map, with its main path and any variants — each journey step paired with the value stage that serves it

**Guidance:**
- Map the journey as the customer experiences it, not as the organization processes it. "Decides whether to trust us with their data" is a journey step; "completes KYC workflow" is the internal process that serves it.
- Every journey step must map to a value stage. A journey step with no value stage serving it is a gap where the customer is on their own — flag it.
- One value stage may serve several journey steps. A value stage that serves no customer journey step is not automatically waste: it may be work behind the scenes that a later customer-facing stage depends on, or part of a value stream whose stakeholder is an internal user rather than a customer. Question it only if it serves neither.
- **Map the main path first, then the variants that matter.** Add a variant for a customer segment, a channel, or a failure and recovery path — what happens when a step goes wrong and how the customer gets back on track — only where it changes which value stage serves the customer, or where its signal differs from the main path. Variants are branches of the same map, not separate funnels, so each value stream keeps one map and one owning product team.
- **Grounding the map in customer research is recommended, not required.** Practices vary between organizations: a map built in working sessions is enough to start Steps 2–5. Where you can, check each journey step against a source from outside the room: direct contact with customers (interviews, observation) or records they generate (support logs, complaints, drop-off analytics). Where the value stream loses customers, hear from some who left or never started. Mark the steps that rest on staff knowledge alone, so the Journey insights loop knows where to look first.
- You are done when every customer journey step is paired with the value stage that serves it, and every value stage either serves a journey step or is justified as behind-the-scenes or internal-stakeholder work.

---

### Step 2 — Define value stages and their value propositions

**What you do:** For each value stage, define what value it delivers to the customer and the realized outcome that proves it. The value stage is where the value proposition becomes a concrete promise at a specific point in the journey.

**Key question this step answers:** *What value does each stage deliver, and what realized outcome proves it landed?*

**Inputs:** Journey-to-value-stream map (Step 1); the value proposition
**Output:** Defined value stages — each with a stated value promise, a realized-outcome definition and a target band

**Guidance:**
- State each value stage's promise from the customer's outcome, not the deliverable. "The customer can trust the service with their money" is a value-stage promise; "account is provisioned" is the deliverable that serves it.
- **A value stage's outcome is measured; the value hypotheses that serve it are tested.** Define the stage's realized outcome, the customer's and not a product measure standing in for it, precisely enough that you could later confirm whether it happened, and read it against a target band ([Metrics and Indicators](../metrics-and-indicators.md#setting-healthy--watch--at-risk-bands), with step 5 for a first band). The stage carries no rejection condition of its own. What is tested is each value hypothesis that claims to move the outcome: it names the outcome as its measure and carries the condition, as the [PTS guide](pts-practitioners-guide.md#step-4--run-the-continuous-product-lifecycle) sets out. Several hypotheses may serve one stage, and one hypothesis may move several stages, naming each outcome under one condition.
- The sum of value stages must add up to the value proposition. If the customer completes every stage but the value proposition is not realized, a stage is missing or mis-defined.
- You are done when each value stage has a customer-outcome promise, a realized-outcome definition you can measure, and a target band to read it against.

---

### Step 3 — Operationalize capabilities, processes, products/services, and information concepts

**What you do:** For each value stage, define what is required to deliver it: the Products/Services the customer interacts with, the Capabilities it draws on from the organization's capability map, the Processes that execute, and the Information concepts, and the flows that feed them to capabilities. This is where the value stage becomes operational.

**Key question this step answers:** *What must exist and execute for each value stage to deliver its outcome?*

**Inputs:** Defined value stages (Step 2); capabilities from the organization's capability map, with owning and consuming teams recorded by PTS
**Output:** An operational definition per value stage — products/services, capabilities, processes, and information concepts with their flows

**Guidance:**
- Work down the architecture: Value Stage → Capability → Process → Product/Service, with Information concepts feeding the capabilities. Each value stage is delivered by capabilities, which run processes, which the customer meets as products/services.
- Information flows are not an afterthought. A value stage fails most often not because a capability is missing, but because information does not flow between capabilities at the moment the customer needs it.
- **Select capabilities from the map; do not invent them locally.** If a value stage needs a capability the map does not have, propose it to OSM, which decides it; PTS then gives it an owning team. A capability sourced from a partner is selected like any other, and its accountable internal team is named here.
- Cross-functional ownership applies here: the team owns the full chain for the value stage, not a single process with handoffs to other teams. Consuming a capability owned by a Shared or Platform-Enabled team, on agreed terms or as self-service, is not a handoff. If delivering a value stage needs an ad-hoc handoff outside the team, revisit the PTS team topology.
- You are done when each value stage has its capabilities, processes, products/services, and information concepts and their flows named and owned.

---

### Step 4 — Instrument 3E and Customer AER across the journey

**What you do:** Instrument measurement at the journey and value-stage level. Apply the full **3E sequence — Use → Feel → Achieve** (Efficiency → Experience → Effectiveness) — at each value stage and across the value stream. Instrument **Customer AER** — whether customers adopt, engage with, and retain the value.

**Key question this step answers:** *Is value being used without friction, felt positively, and achieving the outcome — and are customers adopting, engaging, and returning?*

**Inputs:** Operationalized value stages (Step 3); customer and delivery signal sources
**Output:** 3E instrumentation per value stage and value stream; Customer AER instrumentation across the journey

**Guidance:**
- CVDM is where 3E is primarily surfaced. Apply it in sequence: **Efficiency (Use)** — can the customer access and use the value stage without friction; **Experience (Feel)** — does the customer feel positive, confident, supported; **Effectiveness (Achieve)** — is the value-stage outcome realized. Read the sequence, not the dimensions in isolation (see the [3E Practitioners Guide](3e-practitioners-guide.md) for the diagnostic).
- Customer AER is CVDM's behavioral track: **Adoption** (the customer starts), **Engagement** (the customer actively uses), **Retention** (the customer returns / sustains). The model expects Efficiency to enable Adoption, Experience to sustain Engagement, and Effectiveness to earn Retention — a reasoned hypothesis, confirmed with evidence. To read Customer AER against Organizational AER on the same value stream, see the [AER Practitioners Guide](aer-practitioners-guide.md).
- **Name a break only on two signals.** Name a break at a value stage only when two signals of different kinds agree there — one about what customers do (behavior) and one about how they feel or what they say (perception). A single signal is a *candidate break*: investigate it, and name the break once a second signal confirms it.
- Measure at two levels: value stage (where the customer experiences each step) and value stream (whether the whole journey realizes the value proposition). A value stream can show strong stage-level signal yet fail to retain — measure both.
- You are done when each value stage has a 3E reading and the value stream has a Customer AER reading you can act on.

---

### Step 5 — Activate the five feedback loops

**What you do:** Stand up CVDM's five continuous feedback loops — **Experience feedback, Journey insights, Delivery learning, Performance optimization, Strategic signals** — each owned by the product team, with the decision it informs, how its signal is collected, a cadence, and a return path. These are the operational feedback mechanism of the IIVCS, returning signal to PTS and OSM.

**Key question this step answers:** *How does customer signal surface continuously and return upstream to improve delivery and refine strategy?*

**Inputs:** 3E + Customer AER instrumentation (Step 4)
**Output:** Five active feedback loops — each with its owner role, the decision it informs, its signal source and rough cost, its cadence, and its upstream return path

**Guidance:**
- The loops form a diagnostic sequence, each narrowing the cause one layer further: **Experience feedback** first (the most immediate customer signal), then **Journey insights** (where in the journey), **Delivery learning** (which value stage is not delivering its outcome), **Performance optimization** (which capability or process to fix), and **Strategic signals** last (whether strategic priorities still hold). Delivery learning and performance optimization work as a pair. The sequence is the order of diagnosis, not of cadence — performance optimization can run more often than delivery learning. Do not collapse them into one review — each surfaces a different signal at a different cadence.
- Each loop has a return destination. Experience, Journey insights, and Performance optimization mostly improve delivery (return to the team and PTS); Delivery learning confirms value-stage outcomes; Strategic signals land on the value stream as a whole and return customer reality to OSM for strategic reassessment — the product team consolidates its learnings, including these signals, and OSM decides.
- **Specify each loop, hear the customer directly, and set its cadence.** The rules are set out once in the [IIVCS Feedback System](../feedback.md#operational-feedback--cvdm): the product team owns every loop, and a loop is active only once it is specified and has informed a decision; loops that read the customer draw on the customer's own words or behavior, with staff observation added and labelled; and the cadences shown are typical, run at the organization's own. A loop that surfaces signal no one acts on is not a feedback loop.
- **Delivery learning reads each value stage against its band.** A stage below its band is a signal, not the rejection of a hypothesis: retune the stage, writing the retune as a value hypothesis with its own condition in Define ([PTS guide](pts-practitioners-guide.md#step-4--run-the-continuous-product-lifecycle)), or remodel the value stream where a stage is missing or mis-defined (Step 2). A stage whose outcome no value hypothesis names is a gap; flag it.
- **Set out-of-cycle triggers.** An experience-signal drop should trigger an immediate journey review; a retention drop should trigger a delivery-learning and strategic-signals review.

**The five feedback loops** — what each surfaces, its typical signal source, the decision it informs, where it returns, and its typical cadence — are set out once in the [IIVCS Feedback System](../feedback.md#operational-feedback--cvdm).

---

## Worked Examples

> **Illustrative.** These examples are composites written to show the method. They are not client cases, and their numbers are not benchmarks.

---

### Example 1 — Consumer fitness subscription app (Product/Service, full 3E sequence)

> **Scenario:** A direct-to-consumer fitness app has strong sign-ups but poor 90-day retention. The value proposition — *help members build a sustainable workout habit* — is not being realized. The cross-functional team (built in PTS) runs CVDM on the new-member value stream.

**Step 1 — Map the journey to the value stream**
Journey steps → value stages: *discovers the app* → Acquisition stage; *signs up and sets a goal* → Onboarding stage; *completes first workouts* → Activation stage; *builds a routine* → Habit-formation stage; *sees results* → Outcome-realization stage. *Variant:* members who lapse after week 2 take a recovery path — *gets a re-engagement prompt and returns* — back into the Habit-formation stage; its signal differs from the main path, so it is read separately.

**Step 2 — Define value stages and value propositions**
- Onboarding: *the member has a plan that fits their life* (realized outcome: a scheduled plan they commit to).
- Activation: *the member succeeds at their first workouts* (realized outcome: 3 completed sessions in week one).
- Habit-formation: *the member returns without prompting* (realized outcome: 3+ sessions/week sustained to week 4).
- Outcome-realization: *the member sees progress* (realized outcome: a measurable result they attribute to the app).

**Step 3 — Operationalize capabilities and processes**
Habit-formation value stage: Product/Service = streak tracking + adaptive reminders; Capability = personalization engine; Process = weekly plan adjustment; Information concept = workout completion, feeding the personalization engine to adapt next week's plan.

**Step 4 — Instrument 3E + Customer AER (full Use → Feel → Achieve)**
At the Habit-formation stage: **Efficiency (Use)** — % of members who can log a workout in under 10 seconds (88%, healthy); **Experience (Feel)** — does the member feel the plan fits them? In-app sentiment 3.1/5 (weak); **Effectiveness (Achieve)** — % sustaining 3+ sessions/week to week 4 (29%, underperforming). Customer AER at value-stream level: Adoption high, Engagement falling at week 2, Retention at 90 days low.

Diagnostic (Use → Feel → Achieve): Efficiency holds, but Experience is weak — members do not feel the plan fits (3.1/5, a perception signal), and Engagement falls at week 2 at the same stage (a behavior signal), before the habit forms; Retention then fails. Two signals of different kinds agree, so the break is named at Feel, not Use. Action: use the workout-completion information flow to actually adapt the plan (the capability existed but the information flow was not wired to it).

**Step 5 — Activate the five loops**
Experience feedback (weekly, owned by the team's product manager, from in-app sentiment) caught the sentiment drop first — a candidate break; Journey insights (bi-weekly, from usage analytics) located it at the Habit-formation stage and confirmed it with the week-2 Engagement drop, so the break was named; Delivery learning (quarterly, → PTS) confirmed the stage was not delivering its outcome (29% sustaining to week 4) and tracks whether the fix moves it; Performance optimization (monthly, → PTS) traced that to the under-performing personalization capability; Strategic signals (quarterly, → OSM) fed back that retention — not acquisition — was the real strategic constraint.

> **What it produced:** A journey mapped to value stages with a precise diagnosis (Experience break at Habit-formation), a wired-up information flow that made the personalization capability real, and five loops returning signal — including strategic signals that reframed the company's growth priority from acquisition to retention.

---

### Example 2 — Retail bank mortgage application (Value Stream, Financial Services translation)

> **Scenario:** A retail bank's mortgage value stream has high application start rates but high abandonment before completion, and approved customers report a stressful experience. The value proposition — *get the customer confidently into their home* — is not being realized at the value-stream level. *(Translation: "customer" → "applicant"; "product/service" → "mortgage product"; "journey" → "application journey.")*

**Step 1 — Map the journey to the value stream**
Journey → value stages: *explores affordability* → Pre-qualification stage; *applies* → Application stage; *submits documents and waits* → Underwriting stage; *receives a decision* → Decision stage; *completes and draws down* → Completion stage. *Variant:* applications that come through a broker follow the same stages, but at Underwriting the status updates go to the broker, and the applicant's confidence signal arrives through the broker too; that signal differs from the direct path, so it is read separately.

**Step 2 — Define value stages and value propositions**
- Application: *the applicant can apply without confusion or fear of getting it wrong* (realized outcome: a complete, accurate application submitted).
- Underwriting: *the applicant feels informed and in control while waiting* (realized outcome: the applicant knows status and next step at all times).
- Decision: *the applicant gets a clear, timely answer* (realized outcome: a decision within the promised window, clearly explained).

**Step 3 — Operationalize capabilities and processes**
Underwriting value stage: Product/Service = application status portal; Capability = document verification + risk assessment; Process = underwriting review; Information concept = verification status, flowing to the portal so the applicant sees progress in real time, and to the broker's view for broker-channel applications.

**Step 4 — Instrument 3E + Customer AER (value stage and value stream)**
At Underwriting: **Efficiency (Use)** — average document re-request rate (high — 40% of applicants asked for documents twice); **Experience (Feel)** — applicant confidence during wait (low — 2.6/5, "no idea what's happening"); **Effectiveness (Achieve)** — % decided within promised window (68%). Value-stream Customer AER: Adoption strong, Engagement collapses at Underwriting (the wait), Retention (completion + would-recommend) weak.

Diagnostic (Use → Feel → Achieve): the Efficiency gap (duplicate document requests) drives the Experience collapse during the wait (2.6/5 confidence, a perception signal), which drives abandonment before Decision (Engagement collapsing at Underwriting, a behavior signal) — two signals of different kinds agreeing at the same stage. The information flow from verification to the status portal was not built — the capability ran blind to the applicant. Action: wire verification status into the portal and eliminate duplicate requests.

**Step 5 — Activate the five loops**
Experience feedback (weekly) flagged the Underwriting anxiety; Journey insights (bi-weekly) located abandonment at the wait; Delivery learning (quarterly → PTS) showed Underwriting missing its outcome (68% decided within the promised window) and tracks completion-rate recovery; Performance optimization (monthly → PTS) targeted the verification process and duplicate-request defect; Strategic signals (quarterly → OSM) returned that mortgage experience — not pricing — was the competitive gap.

> **What it produced:** A value stream mapped to value stages, a 3E diagnosis tracing abandonment to a missing information flow at Underwriting, and five loops feeding both delivery fixes (to PTS) and a strategic signal (to OSM) that customer experience, not rate, was where the bank was losing applicants.

---

## Measurement

### 3E Application

CVDM is where **3E is primarily surfaced** — at the journey and value-stage level. The full **Use → Feel → Achieve** sequence is read here, closest to the customer. **Experience is CVDM's leading signal** — it is the first and most immediate signal from the journey and CVDM's home turf. **Effectiveness is the proof** — whether the value proposition was realized as a customer outcome. **Efficiency is the table stake** — frictionless access without which Experience and Effectiveness cannot be reached.

| 3E Dimension | What It Measures Here | Primary Signal |
|---|---|---|
| **Efficiency — Use** | Can the customer access and use each value stage without friction, delay, or unnecessary effort? | Leading |
| **Experience — Feel** | Does the customer feel positive, confident, and supported across the journey? | Leading |
| **Effectiveness — Achieve** | Is the value proposition realized as the intended customer outcome? | Lagging |

**Primary 3E signal for this framework:** Experience — CVDM is the customer-facing layer where feeling surfaces first and most actionably. But read it in sequence: an Experience gap usually traces upstream to an Efficiency break, and Effectiveness (realized outcome) is the proof the value proposition landed.

### 8 Values Generated

This framework most directly drives:

| Value | How This Framework Generates It |
|---|---|
| **Customer Value** | CVDM is the primary source of Customer Value — every journey step triggers the right value stage, delivering outcomes customers adopt, engage with, and return to |
| **Operational Value** | Delivery learning and performance optimization continuously improve value-stream execution quality and the unit economics of delivery |
| **Impact Value** | The experience customers, partners, and communities have with the organization's delivery defines its societal reputation |

All 8 Values are touched across the full IIVCS — the table above shows which Values CVDM is the primary generator of. Customer Value is CVDM's most direct output; Operational and Impact Value are generated through how value is delivered and experienced.

### AER Connection

CVDM is the home of **Customer AER** — the customer half of the IIVCS dual-track behavioral measurement (PTS holds the organizational half). The 3E output is expected to drive each AER stage on the customer track: **Efficiency → Adoption** (frictionless access lowers the barrier — customers adopt what they can reach), **Experience → Engagement** (positive feeling sustains active use — customers engage with what they trust), **Effectiveness → Retention** (outcomes achieved earn continued commitment — customers return to what works). CVDM surfaces Customer AER and 3E and returns them upstream: operational feedback (delivery learning, performance optimization) to PTS, and strategic signals to OSM, where Customer AER converges with PTS's Organizational AER to validate whether strategic priorities are generating value. The two tracks run in parallel because either alone produces nothing.

---

## System Health Check

These signals confirm CVDM is working — not just being followed. Review them before each PTS operating-model review, where the product team's loops are read together.

| Signal | Healthy | At Risk | Remedy when At Risk |
|---|---|---|---|
| Journey-to-value-stream mapping | Every journey step maps to a value stage; no orphaned steps or stages | The map reflects internal process, not the customer journey; gaps go unflagged | Step 1: re-map from the customer's perspective |
| Value stages stated as outcomes | Each stage has a customer-outcome promise and a realized-outcome definition | Stages are defined as internal deliverables, not customer outcomes | Step 2: restate the stage as a customer-outcome promise |
| Information flows wired | Information flows between capabilities at the moment the customer needs it | Capabilities exist but run blind — information does not reach the customer or the next stage | Step 3: wire the information flow the capability runs without |
| 3E read in sequence | Use → Feel → Achieve is read in order; Experience gaps traced upstream; a break is named only on two signals of different kinds | Only outcome (Effectiveness) is watched; experience and friction are invisible; a break is named on one signal | Step 4: read Use → Feel → Achieve in order, and name a break only on two signals |
| Five loops active and owned | All five loops are specified — owner role, decision informed, method, rough cost — and each has informed a decision | Loops are collapsed into one review, left unspecified, or surface signal no one acts on | Step 5: specify the loop |
| Customer's own signal | Experience feedback, Journey insights, and Delivery learning draw on the customer's own words or behavior | A loop that reads the customer runs on staff observation only (provisional) | Step 5: replace provisional staff observation with a customer-sourced method |

**When a signal is At Risk:** apply its remedy before the next review. A signal still At Risk at two reviews running goes to the value-stream owner; where a value stage cannot deliver its outcome, it also returns to PTS through Delivery learning.

---

## Translation Notes

### Non-product contexts

CVDM applies to any organization that realizes value for someone through a journey. The following table maps default IIVCS language to equivalent terms by sector:

| IIVCS Default | Healthcare | Government | Professional Services | Manufacturing | Financial Services |
|---|---|---|---|---|---|
| Customer | Patient / member | Citizen / resident | Client | End customer / buyer | Applicant / policyholder |
| Customer journey | Patient pathway | Citizen service journey | Engagement lifecycle | Order-to-delivery journey | Application / servicing journey |
| Value stage | Care stage | Service stage | Engagement stage | Fulfillment stage | Application / servicing stage |
| Product/Service | Clinical program / pathway | Public service | Solution / deliverable | Product line / SKU | Mortgage / policy product |
| Value proposition | Health outcome promise | Service outcome promise | Client-impact promise | Product value promise | Financial outcome promise |

> **Core principle:** The logic is unchanged across sectors — map the journey to the value stream, define value stages as customer outcomes, operationalize what delivers them, and run the five loops. Only the vocabulary for "customer," "journey," and "value stage" shifts.

---

## Quick Reference

**Steps**

1. Map the customer journey to the value stream — *Which value stage serves each journey step?*
2. Define value stages and value propositions — *What outcome does each stage deliver and prove?*
3. Operationalize capabilities, processes, products/services, information concepts — *What delivers each stage?*
4. Instrument 3E + Customer AER — *Is value used, felt, achieved — and adopted, engaged, retained?*
5. Activate the five feedback loops — *How does signal surface and return upstream?*

**Health signals at a glance**

- Every journey step maps to a value stage — from the customer's perspective
- Value stages are stated as customer outcomes, not internal deliverables
- Information flows are wired where the customer needs them
- 3E is read in sequence (Use → Feel → Achieve), with gaps traced upstream
- All five loops are specified, owned by the product team, and have informed a decision
- Loops that read the customer draw on the customer's own words or behavior

**The five feedback loops** (typical cadences; run each at the organization's own): Experience feedback (continuous / weekly) · Journey insights (sprint / bi-weekly) · Delivery learning (monthly / quarterly) · Performance optimization (sprint / monthly) · Strategic signals (quarterly / annually → OSM) — a diagnostic sequence, Experience first, Strategic signals last.

**Primary 3E signal:** Experience — CVDM is the customer-facing layer where feeling surfaces first; read it in sequence, with Effectiveness as the proof the value proposition landed.

**Primary 8 Values driven:** Customer Value (primary source), Operational Value (delivery learning), Impact Value (delivery experience).

**CVDM holds Customer AER** — the customer half of the dual track; PTS holds Organizational AER. Both converge at OSM. See [Framework Positioning](../positioning.md).

---

© 2026 Insheights LLC. All rights reserved.
