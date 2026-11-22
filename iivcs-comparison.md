# IIVCS Comparison with Established Frameworks

**TOGAF | BIZBOK | ArchiMate | SAFe | Service Blueprint | Value Stream Mapping | Jobs To Be Done**

Related prior work: **Service-Profit Chain | Strategy Maps | Net Promoter System**

A comparison of the Insheights Integrated Value Creation System against established Enterprise Architecture, product delivery, and value analysis frameworks.

---

## Positioning

The IIVCS ([Organization Strategy Model (OSM)](README.md#osm--organization-strategy-model) | [Product Transformation System (PTS)](README.md#pts--product-transformation-system) | [Customer Value Delivery Model (CVDM)](README.md#cvdm--customer-value-delivery-model)) is a system of three interdependent frameworks designed to span the full arc from strategic intent to realized customer outcome — integrated with a shared measurement language ([Efficiency, Experience, Effectiveness (3E)](3e.md), [Adoption, Engagement, Retention (AER)](aer.md), 8 Values) and a feedback architecture that returns customer signal upstream to strategy.

The frameworks below were each built for a different primary purpose — architecture description, delivery scaling, service design, demand insight. Each addresses part of this arc; IIVCS is designed to integrate them within one system, anchored outside-in on the customer journey. The comparison is *integrative reach*, not a claim that any single capability below is novel — several have decades of prior art (see [Related Prior Work](#related-prior-work)).

---

## Framework Comparison

**Reading the table.** Ratings reflect how directly each framework is *designed* to address each dimension — coverage by design, not validated outcomes. These are the dimensions IIVCS is built to integrate, and Insheights rated every row, its own included, so the table maps where established frameworks also address each; it is not a neutral ranking. A Yes or Strong in the IIVCS row means the model is designed to do this; the links it relies on are reasoned hypotheses, not validated (see [Limitations](#limitations)). The final column states maturity, where IIVCS is Conceptual and the others are established in practice.

| Framework | Strategy to Delivery | Customer Journey Anchor | Value Stream Coverage | Operating Model | Behavioral Measurement | Org Value Connection | Feedback Architecture | Maturity |
|---|---|---|---|---|---|---|---|---|
| **TOGAF** | Partial | Absent | Partial | Absent | Absent | Absent | Absent | Mature |
| **BIZBOK** | Partial | Partial | Strong | Partial | Absent | Partial | Absent | Mature |
| **ArchiMate** | Partial | Absent | Partial | Absent | Absent | Absent | Absent | Mature |
| **SAFe** | Strong | Partial | Strong | Strong | Partial | Partial | Partial | Mature |
| **Service Blueprint** | Absent | Strong | Partial | Absent | Absent | Absent | Absent | Established |
| **Value Stream Mapping** | Absent | Partial | Strong | Absent | Absent | Absent | Absent | Established |
| **Jobs To Be Done** | Absent | Partial | Absent | Absent | Absent | Absent | Absent | Established |
| **IIVCS** | Strong | Strong | Strong | Strong | Strong | Strong | Strong | Conceptual |

---

## Comparison by Framework

### TOGAF (The Open Group Architecture Framework)

TOGAF is a widely used enterprise architecture method. Its Architecture Development Method (ADM) is an iterative cycle for developing, governing and changing architecture across the business, data, application and technology domains.

**Alignment:** TOGAF's business architecture describes capabilities, and recent versions add value streams. IIVCS uses value streams as its organizing spine, and an existing TOGAF value-stream catalog can be its starting inventory.

**What it does well:** A disciplined, repeatable way to describe the current and target architecture, plan the move between them, and govern change. IIVCS has no equivalent and does not try to replace it.

**Key difference:** TOGAF describes and governs architecture. IIVCS is designed as a way of running value creation: strategy, an operating model for product teams, and delivery anchored on the customer journey, measured through 3E → AER → 8 Values. TOGAF does not make the customer journey its organizing unit, and it does not define a behavioral measurement layer. IIVCS is designed to add both; the link from IIVCS's design to the outcomes it targets is a reasoned hypothesis, not yet validated.

**How they work together:** [Integration — Enterprise Architecture](integration.md#enterprise-architecture-togaf-archimate-bizbok).

---

### BIZBOK (Business Architecture Guild Body of Knowledge)

The BIZBOK Guide defines business architecture as the blueprint of an enterprise — mapping strategy, capabilities, value streams, information, and organizational structures. It is the Business Architecture Guild's reference for the business architecture discipline.

**Alignment:** BIZBOK and IIVCS share a large structural overlap. BIZBOK defines a value stream as "an end-to-end collection of activities that create a result for a customer", and IIVCS uses value streams as its organizing spine. BIZBOK's capability mapping (what the organization can do) connects to CVDM's Capability layer. Where an organization has BIZBOK strategy maps, OSM can reuse them.

**What it does well:** A shared, well-defined vocabulary and set of maps — capabilities, value streams, information, organization — for describing the business and planning from strategy to initiatives.

**Key difference:** BIZBOK is a business architecture discipline: it models the enterprise's current and target state and is used to plan from strategy to initiatives, but it is not a delivery operating model. In CVDM, each journey step is paired with the value stage that serves it, and every other element is asked to justify itself by what it serves. BIZBOK does not define an operating model for delivery teams or a behavioral measurement layer. IIVCS is designed to add an operating model for the teams (PTS), a behavioral layer (AER), feedback loops that return customer signal upstream, and one measurement language across architecture levels (3E); the link to outcomes is a reasoned hypothesis, not yet validated.

**How they work together:** [Integration — Enterprise Architecture](integration.md#enterprise-architecture-togaf-archimate-bizbok).

---

### ArchiMate (Open Group Architecture Modeling Language)

ArchiMate is the Open Group's modeling language for enterprise architecture: a notation and set of viewpoints for describing strategy, motivation, business, application, technology and physical elements and the relationships between them.

**Alignment:** Its capability element and, in recent versions, its value stream element can represent IIVCS's capabilities and value streams.

**What it does well:** Shared, precise semantics for capability, value stream, value and stakeholder, so that one model can be read the same way by architects across an organization.

**Key difference:** ArchiMate is a notation, not a method, an operating model or a measurement model. It can describe IIVCS's elements, but it does not say how to run them or how to read whether they create value. IIVCS value streams and capabilities can be modeled in ArchiMate. IIVCS is designed to add how they are run and read; the link to outcomes is a reasoned hypothesis, not yet validated.

**How they work together:** [Integration — Enterprise Architecture](integration.md#enterprise-architecture-togaf-archimate-bizbok).

---

### SAFe (Scaled Agile Framework)

SAFe is a widely used enterprise framework for scaling agile practices across large organizations. It structures delivery across Portfolio, Large Solution, Program (ART), and Team levels — organizing work through value streams, Agile Release Trains, and PI Planning.

**Alignment:** SAFe and IIVCS are the closest pair at the operating model level. SAFe's value streams are a core organizing concept, directly aligned with IIVCS. SAFe's Portfolio layer (strategic themes, lean portfolio management) maps to elements of OSM. SAFe's ART construct and cross-functional team model maps to PTS's cross-functional product team structure. SAFe's Customer Centricity and Design Thinking practices align with CVDM's customer journey anchor.

**What it does well:** A widely adopted way to plan and deliver across many teams on shared value streams, with a measurement approach (Measure and Grow) across three domains: Outcomes, Flow and Competency.

**Key difference:** SAFe is a delivery scaling framework built around agile execution. Its customer orientation is a set of practices (Customer Centricity, Design Thinking) inside delivery. In CVDM, each journey step is paired with the value stage that serves it, as the structure of the delivery layer. SAFe's measures are organized in three domains; IIVCS is designed to read one ordered chain, 3E → AER → 8 Values, with each signal in one home layer, including a behavioral layer (AER) on both the customer and team tracks. IIVCS is designed to add that chain, and a strategy layer (OSM) linked to the operating model through shared value streams; the link to outcomes is a reasoned hypothesis, not yet validated.

**How they work together:** [Integration — SAFe](integration.md#safe-scaled-agile-framework).

---

### Service Blueprint

A Service Blueprint is a service design tool that maps a service in layers: the customer's actions, the frontstage actions the customer sees, the backstage actions they do not, and the support processes behind them. Teams can add evidence, and time and success metrics, to each step.

**Alignment:** A Service Blueprint maps the customer's actions against the frontstage, backstage and support processes that serve them, the same ground CVDM covers when it pairs journey steps with value stages, capabilities and processes. Where an organization has a Service Blueprint, it is a strong input to CVDM Step 1.

**What it does well:** It shows in one picture how what the customer does connects to the actions and processes behind it, so that gaps, handoffs and failure points can be found and redesigned.

**Key difference:** The Service Blueprint is a design and analysis artifact; CVDM is designed as an operating model — how the organization runs the service, reads it and improves it. IIVCS is designed to add measurement of each step through 3E, feedback loops that return what the Blueprint surfaces to the teams that can act on it, and the strategy and operating-model layers (OSM, PTS) around it; the link to outcomes is a reasoned hypothesis, not yet validated.

---

### Value Stream Mapping

Value Stream Mapping (VSM) is a Lean tool for visualizing and analyzing the flow of materials and information required to bring a product to a customer. In knowledge work contexts, it is adapted to map the flow of work from request to delivery.

**Alignment:** VSM and IIVCS both use the value stream as a central organizing unit. VSM's focus on waste, cycle time, and flow efficiency maps to the Efficiency dimension of 3E. VSM's end-to-end flow visibility — from customer request to delivery — aligns with CVDM's value stage mapping.

**What it does well:** It makes the flow of work, its waits and its quality visible end to end, and it is itself a continuous-improvement tool, moving from a current-state to a future-state map.

**Key difference:** VSM records time and flow data and quality data such as percent complete and accurate (%C/A), from the point of customer demand; it does not read how the customer experienced the journey or whether they achieved their outcome. IIVCS is designed to add both, through 3E's Experience and Effectiveness, alongside the Efficiency VSM already reads; the link to outcomes is a reasoned hypothesis, not yet validated.

**How they work together:** [Integration — Value Stream Mapping](integration.md#value-stream-mapping).

---

### Jobs To Be Done (JTBD)

Jobs To Be Done is a demand theory framework — most commonly associated with the work of Clayton Christensen and Tony Ulwick — that frames customer needs as "jobs" customers are hiring products and services to do. It is used primarily in product strategy, innovation, and market segmentation.

**Alignment:** JTBD's customer outcome orientation — what customers are trying to achieve — maps to the Effectiveness dimension of 3E and the Value Proposition construct in CVDM. JTBD's insight that customers evaluate products on functional, emotional, and social dimensions aligns with 3E's mapping to Bain's Elements of Value, which spans similar dimensions.

**What it does well:** It frames customer needs as jobs, independent of any one product, which gives strategy and innovation a stable basis.

**Key difference:** JTBD is a demand-research and product-strategy theory: it explains what customers are trying to get done and why they choose. IIVCS is designed as the system that turns those insights into delivery and reads whether the outcomes are realized. JTBD research is a natural input to OSM's strategic choices, PTS's Discover phase — where outcome research runs throughout, not only at initial definition — and CVDM's value propositions; the link from IIVCS to outcomes is a reasoned hypothesis, not yet validated.

**How they work together:** [Integration — Jobs To Be Done](integration.md#jobs-to-be-done-jtbd).

---

## Related Prior Work

Three bodies of work predate IIVCS and anticipate parts of its logic. IIVCS is designed to differ by integrating them into one system, not by being first to see these relationships.

### Service-Profit Chain (Heskett et al., "Putting the Service-Profit Chain to Work," HBR 1994)

The Service-Profit Chain is the closest intellectual precedent to the IIVCS measurement logic, and predates it by three decades. It proposes a chain: internal service quality → employee satisfaction and retention → service value → customer satisfaction and loyalty → revenue growth and profitability.

**Alignment:** The Service-Profit Chain links organizational and customer behavior and connects both to financial outcomes. IIVCS's dual-track AER also reads both sides together.

**What it does well:** It turned the link between how employees are served and how customers respond into a proposition that could be tested in service firms.

**Key difference:** The Service-Profit Chain links employee satisfaction, retention and productivity to customer satisfaction and loyalty, and on to profit. Of the three AER stages it reads only one, Retention (as loyalty), on each side; it does not read Adoption or Engagement. AER reads all three on two parallel tracks against one operating model: Customer AER in CVDM, and Organizational AER in PTS, from team records rather than surveys. The chain is a set of propositions; it does not define an operating model, a delivery architecture or a strategy layer. IIVCS is designed to add these; neither the chain nor IIVCS's paired reading is validated.

### Strategy Maps (Kaplan & Norton, 2004)

Strategy Maps cascade cause-and-effect across measurement perspectives, from learning and process measures up through customer to financial outcomes.

**Alignment:** They are the closest precedent to the 3E → AER → 8 Values chain.

**What it does well:** They make the assumed cause-and-effect of a strategy explicit, on one page, across perspectives.

**Key difference:** The detailed distinction is drawn in [8-values-comparison.md](8-values-comparison.md) (compounding model, operational grounding, leading-indicator structure) and [3e-comparison.md](3e-comparison.md) (stated order of reading vs. parallel perspectives). IIVCS is designed to add a chain anchored at the bottom on customer-journey delivery signal, with its leading/lagging order fixed in the model rather than set per implementation; the link to outcomes is a reasoned hypothesis, not yet validated.

### Net Promoter System (Bain & Company)

The Net Promoter System is Bain's management practice built around the Net Promoter Score. Its inner loop routes each customer's score and comment to the frontline employee or team, who follow up with that customer. Its outer loop takes issues beyond frontline control, such as products, processes and policies, to customer advocacy teams who prioritize structural fixes, and keeps frontline teams informed as they are resolved.

**Alignment:** Like CVDM's feedback loops, it returns customer signal to the people who can act on it, at two levels: the team, and changes the team cannot make alone.

**What it does well:** It closes the loop with the individual customer, and it gives issues beyond the frontline's control an owner.

**Key difference:** The Net Promoter System is built on one stated-intent score and the reason behind it. In IIVCS the product team owns every loop and the decision it informs. Operational signal returns to the team and PTS, and the product team consolidates strategic signals for OSM. The signal is read through 3E → AER → 8 Values: NPS is one 3E Experience signal, and the referral itself is recorded in Customer AER. IIVCS is designed to add that routing and that reading; the link to outcomes is a reasoned hypothesis, not yet validated.

---

## The Distinctive Contribution of IIVCS

### From Strategy to Outcome in One System

Among the frameworks compared here, each is built for one part of the strategy-to-outcome arc, not the whole of it — TOGAF and BIZBOK address architecture, SAFe addresses delivery scaling, Service Blueprint and VSM address delivery analysis, JTBD addresses demand insight. IIVCS's distinguishing choice is to integrate strategy, operating model, and customer value delivery within a single system connected by a shared measurement language — OSM sets strategic direction, PTS carries it into the operating model, CVDM realizes it — with value streams as the common spine. The integration is the contribution, not the individual spans, each of which has precedent.

### Customer Journey as Organizing Principle

CVDM pairs every customer journey step with the value stage that serves it, and asks every other element (capability, process, team) to justify itself by what it serves. That is CVDM's structural premise. Many architecture frameworks start from the inside, from capabilities and functions, instead. Customer Journey Mapping and the Service Blueprint are general practice for this; see [Integration](integration.md).

### Dual-Track Behavioral Reading

AER reads the same three behavioral stages on a customer track and a team track against one operating model. How that differs from the Service-Profit Chain is set out in [AER comparison — Dual-Track Structure](aer-comparison.md#dual-track-structure).

### Feedback Architecture Connecting Delivery to Strategy

Many established frameworks include a review cycle that returns signal to strategy, and the Net Promoter System routes customer feedback both to the frontline and to structural fixes (see [Related Prior Work](#related-prior-work)). CVDM's five feedback loops are designed to differ in two ways. The product team owns every loop: it returns experience signal to delivery teams and consolidates strategic signals for OSM. And the signal is read through 3E → AER → 8 Values. Each loop runs at the cadence set for it in the [feedback loops table](feedback.md#operational-feedback--cvdm).

### Consistent Measurement from Process to Organization

The 3E → AER → 8 Values measurement chain is designed to provide a consistent language from individual process level to organizational value generation. A process-level Efficiency signal aggregates through Capability and Value Stream levels via 3E, connects to behavioral response via AER, and is expected to drive one of eight organizational value dimensions — a reasoned hypothesis. Among the frameworks compared here, few carry a single measurement chain from an individual process step to an organizational value outcome; Kaplan & Norton's Strategy Maps cascade cause-and-effect across measurement levels, and this chain is in that lineage — distinguished by anchoring the bottom on customer-journey delivery signal and the top on a defined set of organizational value dimensions (see [Related Prior Work](#related-prior-work)).

### Integration, Not Replacement

IIVCS is designed to integrate existing organizational practices rather than replace them. TOGAF and ArchiMate remain relevant for architecture governance. SAFe and Scrum remain the operating practices for delivery teams. JTBD remains a valuable demand research lens. OKRs and Enterprise Risk Management (ERM) remain strategic management tools. IIVCS is designed as the system within which these practices operate — the connecting tissue between strategy, operating model, and value delivery — not a replacement for the practices themselves.

---

## Limitations

This comparison is a structured argument, not an independent evaluation. IIVCS is Conceptual: it has no field validation, no notation or tooling of its own, and no validated benchmarks. Insheights chose the dimensions it is compared on and rated every framework, its own included. The links between its parts are reasoned hypotheses. Each measurement model states its own limitations: [3E](3e.md#limitations), [AER](aer.md#limitations), [8 Values](8-values.md#limitations).

---

© 2026 Insheights LLC. All rights reserved.
