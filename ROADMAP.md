# Insheights Integrated Value Creation System — Roadmap

---

## Reviewed

> **Status:** The OSM, PTS and CVDM practitioner guides, the maturity model with the Quick Self-Assessment, and *Metrics and Indicators* are **reviewed**: each has been through a critical review and the owner's rulings, and is linked from the README. Reviewed does not mean field-validated: thresholds, bars and worked examples are reasoned defaults until real assessment runs calibrate them.

### Practitioners Guide — OSM
A step-by-step guide for practitioners applying the Organization Strategy Model. Covers the full formulation-to-governance run: diagnosing the key challenge, making explicit strategic choices (where to play and not play, how to win or theory of change), setting ranked, outcome-stated priorities with written hypotheses, committing resources in rank order through value streams, and governing through a feedback loop that tests those hypotheses. Defines the three OSM artifacts (One-Page Strategy, Priority Register, decision log), the strategy clarity check as OSM's Experience instrument, and how OSM maps to existing strategy methods (Rumelt, Playing to Win, Porter, Hoshin Kanri, [Objectives and Key Results (OKRs)](glossary.md#external-frameworks-referenced)). Includes worked examples, OSM-specific system health indicators, and a translation note for non-product contexts. It also covers both earlier *OSM Framework Refinements*: values as a constraint on strategic choices (a values screen, plus values-conduct signals in governance) and cross-level conflict resolution (settled by the ranking, and escalated as an executability signal).
**Reviewed:** [guides/osm-practitioners-guide.md](guides/osm-practitioners-guide.md).

### Practitioners Guide — PTS
A step-by-step guide for practitioners applying the Product Transformation System. Covers how to stand up a Product Operating Model, structure cross-functional teams around value streams, activate each POM Enabler, and run the Discover–Support phases continuously. Includes worked examples of [Efficiency, Experience, Effectiveness (3E)](3e.md) measurement in transformation contexts, PTS-specific system health indicators, an industry translation note, and full coverage of the Launch phase — external [Go-To-Market (GTM)](glossary.md#common-metrics-and-acronyms) and internal change communication. It works through the organization's own funding process, role titles and forums rather than installing new ones, and sets the conditions they must come to meet: funding for persistent value-stream teams, one named role accountable for each Core team's product, and one route for trade-offs. It starts with a pilot on one value stream, with the work the pilot stops named up front and its first active feedback loop as the first visible win. The earlier planned *Role and Ownership Model* is folded into this guide, which gives the team types, the accountable role and the route for trade-offs.
**Reviewed:** [guides/pts-practitioners-guide.md](guides/pts-practitioners-guide.md).

### Practitioners Guide — CVDM
A step-by-step guide for practitioners applying the Customer Value Delivery Model. Covers how to map customer journeys to value streams, define value stages, operationalize capabilities and processes, and activate the five feedback loops. Includes worked examples of the full 3E sequence (Use → Feel → Achieve) at value stage and value stream level, CVDM-specific system health indicators, and a translation note for non-product contexts.
**Reviewed:** [guides/cvdm-practitioners-guide.md](guides/cvdm-practitioners-guide.md).

### Adoption Sequencing & Maturity Model
A maturity model that helps organizations self-assess their current state and determine where to start — OSM, PTS, or CVDM — and in what sequence. Defines what early, developing, and mature adoption looks like across the suite. Includes the IIVCS self-assessment in two forms — a quick directional check and a detailed, evidence-anchored scored instrument that produces a maturity profile (strengths, gaps, adoption priorities) across all IIVCS components.
**Reviewed:** [adoption-maturity.md](adoption-maturity.md), with [quick-assessment.md](quick-assessment.md). The Detailed Assessment instrument is maintained privately (see the note below).

### Measurement Framework — Metrics and Indicators
Practitioner-facing layer for the 3E and 8 Values measurement models: concrete metrics, indicators, and thresholds for each dimension across OSM, PTS, and CVDM, with the leading and lagging signals that indicate the system is working at each architecture level. Includes the **8 Values Minimum Viable Signal Set** (embedded) and states **reference bars (v3)** for system maturity, which the Detailed Assessment uses; v2 tightened them so a token action does not meet them, and v3 counts a feedback loop only when it is active. *3E Aggregation* and *3E Benchmarking* depend on it; field calibration of the thresholds is gated on real assessment runs.
**Reviewed:** [metrics-and-indicators.md](metrics-and-indicators.md).

> **Note:** The IIVCS **Detailed Assessment** instrument — and the assessment *solution* built on it (the build inputs and the application that runs it and tracks maturity over time) — are maintained in a **separate private repository**, not here. This public repo carries the openly published assessment *methodology*: the Adoption Sequencing & Maturity Model and the Quick Self-Assessment.

---

## Needs Review

> **Status:** Published and linked from the README, and critically reviewed with the other pages, but not yet signed off: each still needs the owner's ruling and a final review before it moves to *Reviewed*.

### Practitioners Guides — 3E and 8 Values
Step-by-step guides for applying the [3E](3e.md) measurement model at any architecture element, and for reading, diagnosing and acting on the [8 Values](8-values.md) profile at each governance cadence. Both were edited to match the reviewed pages; neither has yet had its final sign-off.
**Needs review:** [guides/3e-practitioners-guide.md](guides/3e-practitioners-guide.md), [guides/8-values-practitioners-guide.md](guides/8-values-practitioners-guide.md).

---

## Planned

### 3E Aggregation and Portfolio View
Roll-up logic from Process → Capability → Value Stage → Value Stream, enabling portfolio decisions using a consistent measurement language. Depends on Metrics and Indicators, now reviewed.

### 3E Benchmarking
An external benchmarking framework for 3E signals, enabling organizations to compare performance against industry peers. Covers candidate signals with external reference availability, comparison methodology, and benchmark ranges by sector and architecture level. Depends on Metrics and Indicators.

### End-to-End Traced Case
A single realistic-composite organization traced end to end through the full system — OSM strategic priority → PTS operating-model gap → CVDM journey signal → [Adoption, Engagement, Retention (AER)](aer.md) → 8 Values → [Integrated Reporting (IR)](glossary.md#external-frameworks-referenced) 6 Capitals. Demonstrates that the layers connect in practice, not just on paper.

### Value Trade-offs and Value-at-Risk
Extends the 8 Values from a set of positive dimensions to a model that also handles contention and loss. Covers how values compete for the same resources and how to reason about the trade-off (e.g. Financial vs. People Value on a shared constraint), and introduces value-at-risk — how enterprise risk and value destruction are read against the value dimensions, not just fed in as an OSM input. Complements *Falsifiable Compounding and Causal Claims*: compounding says how values reinforce, this says how they compete and erode.

### Adoption Enablement Playbook
Guidance on running the transition itself — moving an organization from current to envisioned state — not just measuring whether it took (Organizational AER). Frames the change practice around the integrated methods already referenced (ADKAR, Kotter, McKinsey 7-S in aer-comparison.md) and the POM Enablers, giving practitioners a native path through resistance, sequencing, and enablement rather than only a maturity target. Pairs with the *Adoption Sequencing & Maturity Model*, which says where to start but not how to move. The pilot-first path, starting on one value stream, is already in the PTS guide; the Playbook covers the rest.

### Templates and Canvases
Downloadable, reusable artifacts that turn the practitioner guides from readable to usable: an OSM One-Page Strategy and Priority Register canvas, a journey-to-value-stream mapping template (CVDM), a 3E instrumentation worksheet, and an 8 Values reading sheet. The OSM, PTS and CVDM guides are now reviewed, so their templates can follow; the 3E and 8 Values sets wait on those guides' sign-off. Each guide's set is released in full.

---

## Requires a Client Engagement

> These items cannot be completed on paper — they need a real client / design-partner engagement: a live value stream to assess and its data over time. They are well-defined and ready, but gated on that access.

### Detailed Assessment — Dry Run & Calibration
A first real run of the detailed assessment against a design-partner value stream, to calibrate what the spec cannot settle on paper: whether the criteria already split into parts are split in the right places, and whether others that combine two conditions need splitting once their clauses prove to pass or fail independently; whether the feedback system is in fact the binding weakest link every time; and whether the reference bars hold. Outputs feed *Metrics and Indicators* and the assessment's next revision. Run via the assessment solution (maintained privately).

### Falsifiable Compounding and Causal Claims
Testability criteria for the system's core connection claims. Defines what observations would disprove the 3E → AER → 8 Values chain and the 8 Values compounding relationships — making the model's interdependence verifiable, not just asserted. *Defining* the criteria can be done now; *validating* them — linking adoption fidelity to value outcomes — depends on real instrumented assessment data over time, for which *Detailed Assessment — Dry Run & Calibration* is the first source.

---

## Future

### AI Augmentation Specifics
Guidance on how AI fits into each framework — scenario modeling in OSM, telemetry and decision support in PTS, journey personalization and signal detection in CVDM.

### PTS Framework Refinements
The POM Enabler feedback path. The platform team role (Platform-Enabled teams) and Support as a continuous mode are now covered in the PTS guide.

### CVDM Framework Refinements
(1) Failure journeys and churn — modeling exit paths, not just successful delivery. (2) Value Proposition validation feedback loop.

### System Health Indicators — Consolidated View
A concise suite-level view that consolidates the OSM-, PTS-, and CVDM-specific system health indicators from the practitioner guides into a single cross-framework signal set — indicating whether the system is working, not just being followed.

### Context Tailoring — Industry, Size, and Maturity
Guidance for adapting the system beyond its product-org-native framing — for non-product enterprises, smaller organizations, and different starting maturities. Extends the per-guide "translation notes" into a coherent tailoring layer: which elements are essential vs. optional at small scale, how the language maps outside a product context, and how sector characteristics shape adoption. Distinct from *3E Benchmarking*, which compares performance across peers; this shapes how the framework itself is applied.

---

© 2026 Insheights LLC. All rights reserved.
