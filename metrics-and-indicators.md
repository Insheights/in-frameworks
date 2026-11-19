# Measurement Framework — Metrics and Indicators

**The practitioner-facing layer of the [Efficiency, Experience, Effectiveness (3E)](3e.md) and 8 Values measurement models: concrete metrics, indicators, and thresholds for each dimension across [Organization Strategy Model (OSM)](README.md#osm--organization-strategy-model), [Product Transformation System (PTS)](README.md#pts--product-transformation-system), and [Customer Value Delivery Model (CVDM)](README.md#cvdm--customer-value-delivery-model) — and the leading and lagging signals that show the system is working at each architecture level.**

---

This guide turns the measurement *models* into measurable *signals*. Where [3E](3e.md) defines the three dimensions and [8 Values](8-values.md) defines the eight organizational dimensions, this guide names the specific metrics to instrument, classifies each as leading or lagging, and gives threshold guidance for reading them.

It is paired with the practitioner guides — [3E](guides/3e-practitioners-guide.md) for *how* to apply 3E to an element, [8 Values](guides/8-values-practitioners-guide.md) for *how* to read organizational value. This guide is the *reference layer* underneath them: the candidate metric set and the bands to read it against.

> **Read thresholds honestly.** The [Insheights Integrated Value Creation System (IIVCS)](README.md) has **no validated external benchmarks** (3e.md, 8-values.md both state this). This guide uses two kinds of number:
>
> - **Indicator thresholds** — how good a reading is. Every one is either **baseline-relative** (compare an element to its own prior reading and its stated target) or a **conservative starting band to calibrate**, never a universal industry truth. Set targets from your own baseline, and treat these absolute numbers as starting points, not pass/fail lines.
> - **[Reference bars](#reference-bars-for-system-maturity)** — the exception. They are stated lines for whether a practice exists, is current, and is used, so that two readers of the same evidence agree. They are not benchmarks of good performance, and they are provisional until real assessment runs confirm them.
>
> Peer/sector benchmark ranges are a separate, later deliverable (*3E Benchmarking* on the [Roadmap](ROADMAP.md)); field calibration comes from the first real assessment runs.

---

## How to Read This Guide

**Leading vs lagging.** Leading signals (most Efficiency and Experience metrics) surface *before* outcomes and are the earliest actionable warning — review them on a short cadence. Lagging signals (most Effectiveness and Financial metrics) confirm outcomes *after* the fact — review them on a longer cadence matched to the outcome-realization window.

**Architecture levels.** 3E metrics are read at five levels — Value Stream, Value Stage, Capability, Process, Product/Service. Pick the level you are measuring; the metric and its threshold change with it.

**Threshold bands.** Throughout, read each metric in three bands:

| Band | Meaning |
|---|---|
| **Healthy** | At or above your stated target, and stable or improving vs. your own baseline |
| **Watch** | Below target, or flat where you expected movement — a leading-signal early warning |
| **At risk** | Declining vs. baseline, or below the floor you set — act, don't wait for the lagging confirmation |

**Framework emphasis.** Each framework leans on the dimensions it owns (per 3e.md): **OSM** is read mainly on Effectiveness (strategic outcomes) and Experience (stakeholder confidence); **PTS** treats Efficiency as the table stake and is proven on Effectiveness and Experience (incl. Organizational [Adoption, Engagement, Retention (AER)](aer.md)); **CVDM** is where all three 3E dimensions are primarily surfaced, customer-side.

---

## Part 1 — 3E Metrics and Indicators

Candidate metrics per dimension, with the architecture level they suit, signal type, typical source, and threshold guidance. Instrument **at least one signal per dimension per element** before reading the sequence (Use → Feel → Achieve).

### Efficiency — Use *(leading, operational)*

| Metric | Best at level | What it captures | Typical source | Threshold guidance |
|---|---|---|---|---|
| Completion / activation rate without assistance | Product/Service, Value Stage | % who complete without a support ticket or hand-off | Product analytics + support system | Healthy: at/above target & rising; At risk: falling, or a rising share needing assistance |
| Time-to-value (time-to-activation) | Value Stage, Value Stream | Elapsed time from start to first realized value | Analytics / operations data | Set target from the value promise (e.g. "first value in 5 days"); At risk: trending longer |
| Steps-to-complete (actual vs. designed) | Process, Product/Service | Friction beyond the intended path | Process analytics | Healthy: actual ≈ designed; At risk: actual ≫ designed |
| Rework / support-ticket rate | Process, Capability | Share of work redone or escalated | Support + QA data | At risk: rising rework or escalation rate |
| Error / defect rate | Process, Capability | Execution quality at the operational layer | Error logs / QA | Baseline-relative; At risk: above your defect floor |
| Flow efficiency / cycle time (PTS) | Value Stream, Process | How cleanly work flows without queues/hand-offs | Delivery flow metrics | Healthy: stable/short; At risk: lengthening queues |
| Cost-per-activation / unit cost | Capability, Value Stream | Operational cost of delivering value | Finance + ops data | Baseline-relative trend; At risk: rising unit cost without value gain |

### Experience — Feel *(leading, behavioral & attitudinal)*

| Metric | Best at level | What it captures | Typical source | Threshold guidance |
|---|---|---|---|---|
| Post-step CSAT / confidence score | Value Stage, Product/Service | How the customer feels *at the moment of use* (timed to feel, not outcome) | In-product / post-interaction survey | Healthy: at/above target & stable; Watch: any sustained dip — earliest warning |
| Customer Effort Score (CES) | Process, Product/Service | Perceived effort to get value | Post-interaction survey | At risk: rising perceived effort |
| Early return / day-2 engagement rate | Product/Service | Behavioral signal of felt value before outcomes confirm | Session analytics | At risk: falling unprompted return rate |
| Engagement depth / active-use frequency | Product/Service, Value Stream | Whether value is actively used, not just accessed | Usage analytics | Baseline-relative; At risk: declining active use |
| Customer-facing team sentiment | Value Stage | Qualitative read of how value is landing | Team feedback / CRM notes | A leading qualitative flag; corroborate with a behavioral signal |
| Team adoption & engagement of the operating model (Org AER) | Value Stream (PTS) | Whether *teams* feel and engage with the way of working | Org AER instrumentation, eNPS | At risk: falling adoption/engagement of the model |
| Strategy clarity & belief (OSM) | Organization, Value Stream | Whether leaders and teams can state the top priority, why it wins, and one thing ruled out — and believe it can succeed | Strategy clarity check (3 open questions + 1 belief rating), sampled at each quarterly decision forum | v1 reference: At risk below two in three answers consistent with the Strategy Kernel; Watch on flat clarity with falling belief |

### Effectiveness — Achieve *(lagging, outcome)*

| Metric | Best at level | What it captures | Typical source | Threshold guidance |
|---|---|---|---|---|
| Outcome-attainment rate | Value Stage | % achieving the stage's realized-outcome definition | Outcome tracking | Read only after the outcome window; At risk: below target |
| Retention / repeat / renewal rate | Value Stream, Product/Service | Whether outcomes earn continued commitment | CRM / billing | Lagging proof; cohort over the realization window |
| Conversion / goal-attainment rate | Product/Service | Whether the value proposition is realized | CRM / analytics | Baseline-relative vs. target |
| NPS (timed after outcome) | Value Stream | Advocacy once outcomes can be felt | Survey timed post-outcome | Trend vs. your baseline (no external benchmark) |
| Revenue per customer / LTV | Value Stream | Financial proof of realized value | Finance / billing | Forward-looking; read with retention |
| Strategic-outcome achievement (OSM) | Value Stream | Whether the value-stream outcome is being produced | Governance review | At risk: priority off-track across ≥1 cycle |

> **Read the sequence, not the cells.** A weak Effectiveness reading is diagnosed *upstream* — check Experience, then Efficiency — before acting (see the [3E Practitioners Guide](guides/3e-practitioners-guide.md) diagnostic). Efficiency is the table stake: if it fails, Experience and Effectiveness cannot be reached.

---

## Part 2 — 8 Values Metrics and Indicators

Each value is *read from* 3E and AER signals against its operational source (OSM/PTS/CVDM). The table gives the key indicators, what the value reads from, leading/lagging weight, and the **minimum viable signal** — the one observable to watch if you have nothing else (consolidated in [Part 3](#part-3--8-values-minimum-viable-signal-set)).

| Value | Key indicators (current → forward) | Reads from | Weight | Minimum viable signal |
|---|---|---|---|---|
| **Customer** | Customer AER (adoption, engagement, retention rates); CSAT / NPS / trust | CVDM · 3E Experience + Customer AER | Leading + lagging | Value-stream **retention / repeat rate** |
| **Financial** | Revenue, gross/net margin, unit economics → pipeline, LTV | Customer AER → revenue | Lagging | **Revenue trend** of the value stream (with gross margin) |
| **People** | Engagement (eNPS), capability depth, voluntary turnover, culture; Org AER | PTS · 3E Experience (internal) + Org AER | Leading | **Team engagement (eNPS)** + voluntary turnover |
| **Operational** | Process maturity, system reliability, delivery consistency → flow/throughput | PTS/CVDM · 3E Efficiency | Leading | Value-stream **cycle time / throughput** (or rework rate) |
| **Market** | Brand perception, share of voice, market position → advocacy/referral | Customer AER retention/advocacy → market | Lagging | **Advocacy / referral rate** (NPS as proxy) |
| **Strategic** | Priority-outcome attainment, portfolio performance → agility, risk posture | OSM · 3E Effectiveness (value stream) | Lagging | **% strategic value-stream outcomes on track** |
| **Innovation** | Discovery cadence, validated-opportunity throughput → new-value-stream pipeline, new-launch outcome rate | PTS Discover · 3E Effectiveness | Leading (pipeline) | **Discovery throughput** (validated opportunities / period) |
| **Impact** | Mission-advancement measures, ESG metrics → community/societal contribution | OSM mission · 3E Experience + Effectiveness | Mixed | One **mission / ESG outcome** metric |

> Customer and Financial Value are read primarily through **Customer AER**; People Value through **Organizational AER**; both AER tracks run in parallel and neither alone is sufficient. The remaining values *compound* from these over time (see 8-values.md compounding network) — measure their sources first.

---

## Part 3 — 8 Values Minimum Viable Signal Set

For an organization without full 3E and AER instrumentation, this is the **single minimum observable signal per value** — enough to begin reading a value before the full signal set exists. It is the floor, not the target: one signal per value, chosen to be cheap to observe and hard to fake.

| Value | Minimum viable signal | Where it comes from | Type |
|---|---|---|---|
| **Customer** | Retention / repeat rate on the primary value stream | CRM / billing | Lagging |
| **Financial** | Revenue trend of the value stream | Finance | Lagging |
| **People** | Team engagement (eNPS) + voluntary turnover | HR / survey | Leading |
| **Operational** | Value-stream cycle time or rework rate | Delivery / ops data | Leading |
| **Market** | Advocacy / referral rate (or NPS as proxy) | CRM / survey | Lagging |
| **Strategic** | % of strategic value-stream outcomes on track | Governance review | Lagging |
| **Innovation** | Validated-opportunity throughput from discovery | PTS Discover | Leading |
| **Impact** | One mission / ESG outcome metric | Mission / ESG reporting | Mixed |

> **Use it to start, not to settle.** A single signal per value is enough to surface the obvious gaps and begin the conversation. It is not a full profile — several values will read as *unmeasured* on a first pass, which is the expected starting finding (8-values.md). Expand toward the Part 2 indicator set as instrumentation matures.

---

## Part 4 — Thresholds and Reference Bars

### Setting healthy / watch / at-risk bands

1. **Anchor to the value promise.** The target for a metric comes from what the element promised (e.g. "first value in 5 days" sets the time-to-value target). No promise → no defensible threshold.
2. **Read leading signals on a short cadence, lagging on a long one.** Experience weekly/sprint; Efficiency sprint/monthly; Effectiveness and Financial monthly/quarterly, never shorter than the outcome-realization window.
3. **Compare to your own baseline.** Movement vs. your prior reading is more trustworthy than any absolute number, until external benchmarks exist (*3E Benchmarking*).
4. **Set an at-risk floor and act on it** — don't wait for the lagging confirmation to arrive.

### Reference bars for system maturity

Judging how mature a practice is needs a stated bar rather than room judgment. The reference bars below (v2) state where that line sits for each practice, so that two people reading the same evidence reach the same answer. The Detailed Assessment uses them.

Each bar asks three things of a practice: that it **exists**, that it is **current** (a baseline and repeated, dated readings), and that it **changed something** (at least one recorded decision or action). A practice that exists on paper but has never been read, or never acted on, does not meet its bar.

| What is measured | Reference bar (v2) | Signal / source | Review cadence |
|---|---|---|---|
| **Governance responsiveness** | In the last 2 governance cycles, at least 1 value priority was changed, retired, or re-resourced because of a signal: the record names the signal and its reading from before the decision, and a later record (budget, staffing, or roadmap) shows the change happened. A change already planned before the signal does not count. | Governance minutes and the Priority Register | Per governance cycle |
| **Organizational AER coverage** | Adoption, engagement, **and** retention of the way of working each have at least 1 named signal with a baseline, read at 2 or more consecutive reviews, and at least 1 reading led to a recorded change in the way of working within 2 quarters | Org AER instrumentation and review records | Monthly |
| **Feedback loops and Customer AER coverage** | Each of the 5 feedback loops has a named owner and cadence and ran in its last cadence period, and at least 1 loop's output led to a recorded change in a priority or the backlog. Customer adoption, engagement, **and** retention each have a distinct signal with a baseline across the journey. | CVDM loop records + analytics | Per loop cadence |
| **3E across architecture levels** | A 3E profile exists at 3 or more of the 5 architecture levels, including value stream **and** value stage; each has a baseline and a reading within its review cadence, and at least 1 is cited in a recorded decision | 3E profiles and decision records | Quarterly |
| **AER on primary journeys** | Adoption, engagement, **and** retention each have a definition, a baseline, and a target on every primary journey — named as primary before measurement began — read at 2 or more consecutive reviews | Journey analytics | Monthly |
| **Breadth of value measured** | At least 3 of the 8 value dimensions each have a named indicator, a baseline, and a current reading, and at least 1 was read where a decision was taken | 8 Values reading | Quarterly |
| **Outcome-based success measures** | For half or more of the value stream's product teams, the primary success measure is an outcome with a baseline and a target, and the team's last goal review judged progress against it | Team goal/[Objectives and Key Results (OKR)](glossary.md#external-frameworks-referenced) review | Quarterly |

> **What "v2" does and does not mean.** v2 tightens the v1 bars so that a token action does not meet them. It does **not** mean the bars are field-validated or peer-benchmarked: that remains pending the first real assessment runs (*Detailed Assessment — Dry Run & Calibration*, client-gated) and external benchmarking (*3E Benchmarking*). Re-confirm them against real-run data when it exists.

---

## Is the System Working? — Signals by Architecture Level

A quick read of whether the system is *working*, not just *running*, at each level — pairing a leading and a lagging signal:

| Level | Leading signal (acts early) | Lagging signal (confirms) |
|---|---|---|
| **Value Stream** | Efficiency: flow/cycle time stable; Experience: engagement holding | Effectiveness: strategic outcome on track; retention rising |
| **Value Stage** | Experience: stage CSAT/confidence at target | Effectiveness: stage realized-outcome attained |
| **Capability** | Efficiency: activation without waste/escalation | Effectiveness: contribution to the value stage delivered |
| **Process** | Efficiency: steps ≈ designed, rework low | Effectiveness: intended outcome produced consistently |
| **Product/Service** | Efficiency: activation without assistance; Experience: early return | Effectiveness: value proposition realized (conversion/retention) |

If a level's leading signals are healthy but its lagging signals fail, the value proposition itself is suspect — return to discovery (per the 3E diagnostic). If leading signals are already failing, fix there first.

---

## Limitations

Consistent with [3e.md](3e.md) and [8-values.md](8-values.md):

- **No external benchmarks yet.** Every band here is baseline-relative or a starting default to calibrate — not a validated industry range. Peer comparison is the separate *3E Benchmarking* deliverable.
- **Thresholds are reference defaults, not field-validated.** The v2 reference bars rest on reasoned judgment until real assessment runs calibrate them.
- **Instrumentation-dependent.** A metric you cannot observe is not a metric — the Minimum Viable Signal Set exists precisely because most organizations start under-instrumented.
- **Metrics are signals, not the value.** A metric proxies a dimension; it does not *equal* it. Read several together and in sequence, and treat a single number as a prompt to look, not a verdict.

---

## Summary

This guide makes the measurement models operable: concrete 3E metrics by dimension and level, 8 Values indicators with a minimum viable signal each, and threshold bands read against your own baseline. It states reference bars for system maturity — while keeping honest that external benchmarks and field calibration are still ahead.

Measure leading signals early and often, confirm with lagging ones, read the Use → Feel → Achieve sequence rather than isolated cells, and calibrate every band to your own baseline until benchmarks exist.

See [3E](3e.md), [8 Values](8-values.md), and [AER](aer.md).

---

© 2026 Insheights LLC. All rights reserved.
