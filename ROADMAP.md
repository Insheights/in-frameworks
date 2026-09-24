# Insheights Integrated Value Creation System — Roadmap

---

## In Development

> **Status:** The practitioner-guide, maturity-model, and *Metrics and Indicators* items are **draft ready, needs review** — first drafts written, committed, and linked from the README, pending review and refinement before being considered final.

### Practitioners Guide — OSM
A step-by-step guide for practitioners applying the Organization Strategy Model. Covers the full formulation-to-governance run: diagnosing the crux, making explicit strategic choices (where to play and not play, how to win or theory of change), setting ranked, outcome-stated priorities with written assumptions, committing resources in rank order through value streams, and governing through a feedback loop that tests those assumptions. Defines the three OSM artifacts (Strategy Kernel, Priority Register, decision log), the strategy clarity check as OSM's Experience instrument, and how OSM maps to existing strategy methods (Rumelt, Playing to Win, Porter, Hoshin Kanri, OKRs). Includes worked examples, OSM-specific system health indicators, and a translation note for non-product contexts. It also covers both earlier *OSM Framework Refinements*: values as a constraint on strategic choices (a values screen, plus values-conduct signals in governance) and cross-level conflict resolution (settled by the ranking, and escalated as an executability signal).
**Draft:** [guides/osm-practitioners-guide.md](guides/osm-practitioners-guide.md) — *needs review.*

### Practitioners Guide — PTS
A step-by-step guide for practitioners applying the Product Transformation System. Covers how to stand up a Product Operating Model, structure cross-functional teams around value streams, activate each POM Enabler, and run the Discover–Support phases continuously. Includes worked examples of 3E measurement in transformation contexts, PTS-specific system health indicators, an industry translation note, and full coverage of the Launch phase — external GTM and internal change communication.
**Draft:** [guides/pts-practitioners-guide.md](guides/pts-practitioners-guide.md) — *needs review.*

### Practitioners Guide — CVDM
A step-by-step guide for practitioners applying the Customer Value Delivery Model. Covers how to map customer journeys to value streams, define value stages, operationalize capabilities and processes, and activate the five feedback loops. Includes worked examples of the full 3E sequence (Use → Feel → Achieve) at value stage and value stream level, CVDM-specific system health indicators, and a translation note for non-product contexts.
**Draft:** [guides/cvdm-practitioners-guide.md](guides/cvdm-practitioners-guide.md) — *needs review.*

### Adoption Sequencing & Maturity Model
A maturity model that helps organizations self-assess their current state and determine where to start — OSM, PTS, or CVDM — and in what sequence. Defines what early, developing, and mature adoption looks like across the suite. Includes the IIVCS self-assessment in two forms — a quick directional check and a detailed, evidence-anchored scored instrument that produces a maturity profile (strengths, gaps, adoption priorities) across all IIVCS components.
**Draft:** [adoption-maturity.md](adoption-maturity.md), with [quick-assessment.md](quick-assessment.md) — *needs review.* The Detailed Assessment instrument is maintained privately (see the note below).

### Measurement Framework — Metrics and Indicators
Practitioner-facing layer for the 3E and 8 Values measurement models: concrete metrics, indicators, and thresholds for each dimension across OSM, PTS, and CVDM, with the leading and lagging signals that indicate the system is working at each architecture level. Includes the **8 Values Minimum Viable Signal Set** (embedded) and defines the **reference (v1) thresholds** for the detailed assessment's † criteria — which lets the assessment lift its "Mature-pending" cap once reviewed. *3E Aggregation* and *3E Benchmarking* depend on it; field calibration of the thresholds is gated on real assessment runs.
**Draft:** [metrics-and-indicators.md](metrics-and-indicators.md) — *needs review.*

> **Note:** The IIVCS **Detailed Assessment** instrument — and the assessment *solution* built on it (the build inputs and the application that runs it and tracks maturity over time) — are maintained in a **separate private repository**, not here. This public repo carries the openly published assessment *methodology*: the Adoption Sequencing & Maturity Model and the Quick Self-Assessment.

---

## Planned

### 3E Aggregation and Portfolio View
Roll-up logic from Process → Capability → Value Stage → Value Stream, enabling portfolio decisions using a consistent measurement language. Depends on Metrics and Indicators being defined first.

### 3E Benchmarking
An external benchmarking framework for 3E signals, enabling organizations to compare performance against industry peers. Covers candidate signals with external reference availability, comparison methodology, and benchmark ranges by sector and architecture level. Depends on Metrics and Indicators.

### Role and Ownership Model
Defines who drives OSM, who operationalizes PTS, and who governs CVDM. Covers decision rights, responsibilities, and how leadership and teams interact across the three frameworks.

### End-to-End Traced Case
A single realistic-composite organization traced end to end through the full system — OSM strategic priority → PTS operating-model gap → CVDM journey signal → AER → 8 Values → IR 6 Capitals. Demonstrates that the layers connect in practice, not just on paper.

### Value Trade-offs and Value-at-Risk
Extends the 8 Values from a set of positive dimensions to a model that also handles contention and loss. Covers how values compete for the same resources and how to reason about the trade-off (e.g. Financial vs. People Value on a shared constraint), and introduces value-at-risk — how enterprise risk and value destruction are read against the value dimensions, not just fed in as an OSM input. Complements *Falsifiable Compounding and Causal Claims*: compounding says how values reinforce, this says how they compete and erode.

### Adoption Enablement Playbook
Guidance on running the transition itself — moving an organization from current to envisioned state — not just measuring whether it took (Organizational AER). Frames the change practice around the integrated methods already referenced (ADKAR, Kotter, McKinsey 7-S in aer-comparison.md) and the POM Enablers, giving practitioners a native path through resistance, sequencing, and enablement rather than only a maturity target. Pairs with the *Adoption Sequencing & Maturity Model*, which says where to start but not how to move.

### Templates and Canvases
Downloadable, reusable artifacts that turn the practitioner guides from readable to usable: an OSM Strategy Kernel and Priority Register canvas, a journey-to-value-stream mapping template (CVDM), a 3E instrumentation worksheet, and an 8 Values reading sheet. Depends on the practitioner guides being finalized.

---

## Requires a Client Engagement

> These items cannot be completed on paper — they need a real client / design-partner engagement: a live value stream to assess and its data over time. They are well-defined and ready, but gated on that access.

### Detailed Assessment — Dry Run & Calibration
A first real run of the detailed assessment against a design-partner value stream, to calibrate what the spec cannot settle on paper: whether the double-barreled criteria (3.M1, 3.M3) need splitting once their clauses prove to pass/fail independently; whether component 7 (Feedback System) is in fact the binding weakest-link floor every time; and whether the v0 † thresholds hold. Outputs feed *Metrics and Indicators* and the assessment's next revision. Run via the assessment solution (maintained privately).

### Falsifiable Compounding and Causal Claims
Testability criteria for the system's core connection claims. Defines what observations would disprove the 3E → AER → 8 Values chain and the 8 Values compounding relationships — making the model's interdependence verifiable, not just asserted. *Defining* the criteria can be done now; *validating* them — linking adoption fidelity to value outcomes — depends on real instrumented assessment data over time, for which *Detailed Assessment — Dry Run & Calibration* is the first source.

---

## Future

### AI Augmentation Specifics
Guidance on how AI fits into each framework — scenario modeling in OSM, telemetry and decision support in PTS, journey personalization and signal detection in CVDM.

### PTS Framework Refinements
(1) Platform team role — mandate and interaction model for Core, Shared, and Platform-Enabled teams. (2) POM Enabler feedback path. (3) Support phase reframed as a continuous operating mode.

### CVDM Framework Refinements
(1) Failure journeys and churn — modeling exit paths, not just successful delivery. (2) Value Proposition validation feedback loop.

### System Health Indicators — Consolidated View
A concise suite-level view that consolidates the OSM-, PTS-, and CVDM-specific system health indicators from the practitioner guides into a single cross-framework signal set — indicating whether the system is working, not just being followed.

### Context Tailoring — Industry, Size, and Maturity
Guidance for adapting the system beyond its product-org-native framing — for non-product enterprises, smaller organizations, and different starting maturities. Extends the per-guide "translation notes" into a coherent tailoring layer: which elements are essential vs. optional at small scale, how the language maps outside a product context, and how sector characteristics shape adoption. Distinct from *3E Benchmarking*, which compares performance across peers; this shapes how the framework itself is applied.

---

© 2026 Insheights LLC. All rights reserved.
