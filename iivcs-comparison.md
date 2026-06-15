# IIVCS Comparison with Established Frameworks

**TOGAF | BIZBOK | ArchiMate | SAFe | Service Blueprint | Value Stream Mapping | Jobs To Be Done**

A comparison of the Insheights Integrated Value Creation System against established Enterprise Architecture, product delivery, and value analysis frameworks.

---

## Positioning

The IIVCS (OSM | PTS | CVDM) is a system of three interdependent frameworks designed to span the full arc from strategic intent to realized customer outcome — integrated with a shared measurement language (3E, AER, 8 Values) and a feedback architecture that returns customer signal upstream to strategy.

The frameworks below were each built for a different primary purpose — architecture description, delivery scaling, service design, demand insight. Each addresses part of this arc; what distinguishes IIVCS is how tightly it integrates them within one system, anchored outside-in on the customer journey. The comparison is *integrative reach*, not a claim that any single capability below is novel — several have decades of prior art (see [Related Prior Work](#related-prior-work)).

---

## Framework Comparison

**Reading the table.** Ratings reflect how directly each framework is *designed* to address each dimension — coverage by design, not validated outcomes. These are the dimensions IIVCS is built to integrate, so the table maps where established frameworks also address each; it is not a neutral ranking. The final column states maturity, where IIVCS is Conceptual and the others are proven in practice.

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

TOGAF is the dominant Enterprise Architecture methodology, providing a structured approach — the Architecture Development Method (ADM) — for developing and maintaining enterprise architecture across business, data, application, and technology domains.

**Alignment:** TOGAF's Business Architecture layer covers strategy-to-capability mapping. Its value stream concept (introduced in TOGAF 9.2) aligns with how IIVCS uses value streams as the organizing unit of execution. Phase A of the ADM (Architecture Vision) maps loosely to the strategic intent work in OSM. The Application and Technology layers address delivery infrastructure that CVDM's Capability and Process elements sit within.

**Key difference:** TOGAF is an architecture description framework — it documents and governs architecture states. IIVCS is a value creation operating system — it drives how organizations define, build, and deliver value as an ongoing practice. TOGAF produces architecture artifacts; IIVCS produces customer outcomes. TOGAF's ADM is a sequential governance cycle; IIVCS is a continuous operating system with overlapping feedback loops.

The most significant gap is the customer. TOGAF has no customer journey anchor — it organizes from the inside out (business capabilities to technical infrastructure) rather than from the outside in (customer journey to internal delivery requirements). CVDM's fundamental premise — that every internal architecture element exists to serve a step in a customer's journey — is structurally absent from TOGAF.

TOGAF also has no behavioral measurement layer and no model for how architectural decisions connect to organizational value generation. An organization can be fully TOGAF-compliant and still have no way to determine whether its architecture is producing value for customers or the organization.

**IIVCS gap filled:** Strategy-to-delivery continuity with a customer journey anchor. An operating model that empowers delivery teams (PTS) rather than governs architecture states. A connected measurement architecture (3E → AER → 8 Values) that runs from individual process level to organizational outcomes. A feedback system that returns customer signal to strategy, not just architecture review.

---

### BIZBOK (Business Architecture Guild Body of Knowledge)

The BIZBOK Guide defines business architecture as the blueprint of an enterprise — mapping strategy, capabilities, value streams, information, and organizational structures. The Business Architecture Guild's framework is the primary standard for the business architecture discipline.

**Alignment:** BIZBOK and IIVCS share the most structural overlap of any framework pair in this comparison. BIZBOK's value streams are defined as end-to-end sequences of activities that create value for stakeholders — directly aligned with how IIVCS uses value streams as the organizing spine. BIZBOK's capability mapping (what the organization can do) connects to CVDM's Capability layer. BIZBOK's strategy mapping connects to OSM's strategic intent layer.

**Key difference:** BIZBOK is a business architecture description discipline — it captures the current and target state of the enterprise as an artifact, not a delivery operating model. IIVCS is a system that organizations run to create value continuously. BIZBOK tells you what exists; IIVCS tells you how to operate.

BIZBOK has a partial customer journey component (customer journey is one of seven business architecture domains), but it does not anchor the full system to the customer's experience. In BIZBOK, the customer journey is a domain to be documented; in CVDM, the customer journey is the reason every internal element exists.

BIZBOK has no operating model for delivery teams (the equivalent of PTS), no behavioral measurement layer, and no model for how business architecture connects to organizational value generation or customer behavioral response.

**IIVCS gap filled:** An operating model that operationalizes business architecture through empowered teams (PTS). A behavioral measurement layer that bridges value delivery to organizational outcomes (AER). A feedback architecture that continuously returns customer signal upstream. A consistent measurement language across all architecture levels (3E).

---

### ArchiMate (Open Group Architecture Modeling Language)

ArchiMate is the Open Group's architecture modeling language for describing, analyzing, and visualizing enterprise architecture. It provides a notation and viewpoint system for representing strategy, motivation, business, application, technology, and physical layers.

**Alignment:** ArchiMate's Motivation layer (goals, drivers, values, principles, requirements) maps conceptually to OSM's strategic intent work. ArchiMate 3.0's Strategy layer (capabilities, resources, value streams) introduces constructs that correspond to IIVCS architecture elements.

**Key difference:** ArchiMate is a notation and modeling language — it provides a vocabulary and grammar for drawing architecture pictures. It is not a methodology, an operating model, or a measurement framework. An organization using ArchiMate creates accurate architecture models; it has no mechanism for connecting those models to customer value delivery, behavioral response, or organizational outcomes.

ArchiMate has no customer journey anchor, no operating model construct, no feedback architecture, no measurement model, and no concept of behavioral or organizational value. It is a precision tool for a specific purpose (architecture communication and analysis) that is entirely orthogonal to most of what IIVCS does.

**IIVCS gap filled:** Everything beyond architecture description. ArchiMate and IIVCS address different questions: ArchiMate answers "what does our architecture look like?" — IIVCS answers "how do we create value for customers and generate organizational value through it?"

---

### SAFe (Scaled Agile Framework)

SAFe is the leading enterprise framework for scaling agile practices across large organizations. It structures delivery across Portfolio, Large Solution, Program (ART), and Team levels — organizing work through value streams, Agile Release Trains, and PI Planning.

**Alignment:** SAFe and IIVCS are the closest pair at the operating model level. SAFe's value streams are a core organizing concept, directly aligned with IIVCS. SAFe's Portfolio layer (strategic themes, lean portfolio management) maps to elements of OSM. SAFe's ART construct and cross-functional team model maps to PTS's cross-functional product team structure. SAFe's Customer Centricity and Design Thinking practices align with CVDM's customer journey anchor.

**Key difference:** SAFe is a delivery scaling framework built around agile execution. IIVCS is a value creation system that connects strategy, operating model, and customer delivery within a shared measurement architecture. The practical distinctions:

SAFe's customer orientation is an embedded practice (Design Thinking, CALMR) rather than the structural anchor of the whole system. In IIVCS, the customer journey is the organizing unit at the delivery layer (CVDM) — every capability, process, and value stream step is defined by what it does for a customer journey step. In SAFe, customer centricity is practiced within delivery without being the structural basis for how delivery is organized.

SAFe has no equivalent to 3E — a consistent measurement language applied from team-level process to portfolio-level value stream. SAFe metrics (flow metrics, OKR attainment, team performance) are valuable but heterogeneous; they do not compose into a single measurement model that runs from process to organizational outcome.

SAFe has no equivalent to AER — a behavioral signal layer that measures whether teams and customers are adopting and retaining value from the operating model. SAFe's metrics capture delivery flow, not behavioral response to value delivery.

**IIVCS gap filled:** A customer journey anchor that is structural (not just practiced). A consistent measurement architecture (3E → AER → 8 Values) that connects delivery metrics to organizational value outcomes. A strategy layer (OSM) that connects to the operating model through shared value streams, not just strategic themes. A feedback architecture that runs upstream from customer signal to strategic reassessment.

---

### Service Blueprint

A Service Blueprint is a service design tool that maps the full service delivery system — customer journey steps (frontstage), employee actions and supporting processes (backstage), and supporting systems — to identify gaps, handoffs, and failure points.

**Alignment:** The Service Blueprint is the closest industry tool to CVDM's core function: mapping customer journey steps to the internal delivery elements that serve them. CVDM's architecture — Customer Journey → Value Stream Stage → Capabilities → Processes — is the operational system that a Service Blueprint describes. A well-constructed Service Blueprint is the input document for CVDM adoption.

The Service Blueprint also captures Efficiency signals in its onstage layer — the customer's friction and experience — which maps directly to the Efficiency and Experience dimensions of 3E.

**Key difference:** The Service Blueprint is a design and analysis artifact; CVDM is an operating model. A Service Blueprint maps the current or intended service; CVDM is how the organization runs it, measures it, and improves it continuously. The Service Blueprint has no measurement layer, no feedback architecture, no connection to the operating model that delivers the service, and no mechanism for feeding delivery signal back to strategy.

The Service Blueprint also ends at the service layer — it has no strategic tier (OSM) above it and no operating model (PTS) that empowers the teams delivering the backstage processes.

**IIVCS gap filled:** An operating system that runs what the Service Blueprint describes. Measurement (3E) that makes the Blueprint's efficiency and experience observations systematic. Feedback architecture that returns what the Blueprint surfaces back to the teams and leaders who can act on it. A strategy and operating model layer (OSM + PTS) that sets direction for and empowers the delivery system the Blueprint maps.

---

### Value Stream Mapping

Value Stream Mapping (VSM) is a Lean manufacturing tool for visualizing and analyzing the flow of materials and information required to bring a product to a customer. In knowledge work contexts, it is adapted to map the flow of work from request to delivery.

**Alignment:** VSM and IIVCS both use the value stream as a central organizing unit. VSM's focus on identifying waste, cycle time, and flow efficiency maps to the Efficiency dimension of 3E. VSM's end-to-end flow visibility — from customer request to delivery — aligns with CVDM's value stream stage mapping.

**Key difference:** VSM is an Efficiency analysis tool for a specific value stream snapshot. IIVCS is a system that continuously operates, measures, and improves value delivery across the full architecture. VSM's analysis is point-in-time and flow-focused; IIVCS's measurement is continuous and outcome-focused.

VSM captures only Efficiency (waste, cycle time, flow) — it has no Experience or Effectiveness dimension. A value stream that is efficient (fast, low-waste) but produces poor customer experience or fails to achieve intended outcomes is invisible to VSM. IIVCS's 3E model makes the Experience and Effectiveness gaps visible alongside Efficiency.

VSM has no customer journey anchor (it maps work flow, not customer experience), no operating model, no behavioral measurement, and no feedback architecture connecting delivery performance to strategic direction.

**IIVCS gap filled:** Experience and Effectiveness dimensions alongside Efficiency. A customer journey anchor that connects flow performance to what customers actually experience and achieve. An operating model and feedback architecture that turns VSM's snapshot analysis into a continuous improvement system.

---

### Jobs To Be Done (JTBD)

Jobs To Be Done is a demand theory framework — most commonly associated with the work of Clayton Christensen and Tony Ulwick — that frames customer needs as "jobs" customers are hiring products and services to do. It is used primarily in product strategy, innovation, and market segmentation.

**Alignment:** JTBD's customer outcome orientation — what customers are trying to achieve — maps to the Effectiveness dimension of 3E and the Value Proposition construct in CVDM. JTBD's insight that customers evaluate products on functional, emotional, and social dimensions aligns with 3E's grounding in Bain's Elements of Value, which spans similar dimensions.

**Key difference:** JTBD is a demand research and product strategy theory. It explains what customers want and why they choose products. IIVCS is an operating system that delivers, measures, and continuously improves the outcomes customers want. JTBD informs the front end of strategic and product decisions; IIVCS operationalizes them.

JTBD has no delivery architecture, no operating model, no measurement layer for how well jobs are being done in execution, and no feedback architecture. An organization using JTBD to define customer needs has no JTBD-native mechanism for determining whether its delivery system is producing the outcomes those needs require.

**IIVCS gap filled:** Everything after the demand insight. JTBD tells you what job to do; IIVCS is the system for doing it, measuring it, and improving it. JTBD and IIVCS are complementary — JTBD research is a natural input to OSM's strategic value creation process, PTS's continuous Discover phase, and CVDM's value proposition definition. In PTS, JTBD outcome research runs throughout Discover — keeping teams grounded in what customers are trying to achieve across all delivery phases, not just at the point of initial definition.

---

## Related Prior Work

Two bodies of work predate IIVCS and anticipate parts of its logic. IIVCS's contribution is comparative — tighter integration and operationalization — not the first discovery of these relationships.

### Service-Profit Chain (Heskett, Sasser & Schlesinger, HBR 1994)

The Service-Profit Chain is the closest intellectual precedent to the IIVCS measurement logic, and predates it by three decades. It establishes a causal chain: internal service quality → employee satisfaction and retention → service value → customer satisfaction and loyalty → revenue growth and profitability. It is the original articulation that *organizational* behavior and *customer* behavior are linked, and that both connect to financial outcomes.

**Alignment:** The Service-Profit Chain anticipates the dual-track logic at the heart of IIVCS — that organizational and customer behavior both drive value and must be read together. AER's two parallel tracks (Organizational AER and Customer AER) are a direct descendant of this insight.

**Key difference:** The Service-Profit Chain is a causal hypothesis supported by empirical research across service firms — not an operating system. It does not define an operating model (PTS), a delivery architecture anchored on the customer journey (CVDM), a strategy-governance layer (OSM), or a measurement language applied consistently across architecture levels (3E). It establishes that the links exist; it does not provide the system to operate, measure, and improve them. IIVCS operationalizes the relationship the Service-Profit Chain identified, across a full strategy-to-delivery architecture.

What IIVCS adds is not the discovery that organizational and customer behavior both matter — the Service-Profit Chain established that — but an integrated system for running and measuring both within one architecture.

### Strategy Maps (Kaplan & Norton, 2004)

Strategy Maps cascade cause-and-effect across measurement perspectives, from learning and process measures up through customer to financial outcomes — the closest precedent to the 3E → AER → 8 Values chain. The detailed distinction is drawn in [8-values-comparison.md](8-values-comparison.md) (compounding model, operational grounding, leading-indicator structure) and [3e-comparison.md](3e-comparison.md) (sequenced diagnostic vs. parallel perspectives). IIVCS differs in anchoring the bottom of the chain on customer-journey delivery signal and structuring leading/lagging order explicitly rather than per-implementation.

---

## The Distinctive Contribution of IIVCS

### From Strategy to Outcome in One System

Most established frameworks are built for one part of the strategy-to-outcome arc, not the whole of it — TOGAF and BIZBOK address architecture, SAFe addresses delivery scaling, Service Blueprint and VSM address delivery analysis, JTBD addresses demand insight. IIVCS's distinguishing choice is to integrate strategy, operating model, and customer value delivery within a single system connected by a shared measurement language — OSM sets strategic direction, PTS operationalizes it, CVDM realizes it — with value streams as the common spine. The integration is the contribution, not the individual spans, each of which has precedent.

### Customer Journey as Organizing Principle

Most frameworks organize from the inside out: from capabilities, functions, teams, or processes outward to customer impact. IIVCS organizes from the outside in: every internal architecture element — capability, process, team, value stream stage — is defined by what it does for a specific step in the customer's journey. This is CVDM's structural premise, not a design philosophy layered on top.

### Feedback Architecture Connecting Delivery to Strategy

Established frameworks document or optimize individual layers without building a feedback system that returns delivery signal upstream to strategy. IIVCS closes the loop in both directions: CVDM's five feedback loops return customer experience signal to delivery teams and strategic evolution signal to OSM. The feedback runs continuously, not as a point-in-time review cycle.

### Consistent Measurement from Process to Organization

The 3E → AER → 8 Values measurement chain provides a consistent language from individual process level to organizational value generation. A process-level Efficiency signal aggregates through Capability and Value Stream levels via 3E, connects to behavioral response via AER, and ultimately drives one of eight organizational value dimensions. Few frameworks carry a single measurement chain from an individual process step to an organizational value outcome; Kaplan & Norton's Strategy Maps cascade cause-and-effect across measurement levels, and this chain is in that lineage — distinguished by anchoring the bottom on customer-journey delivery signal and the top on a defined set of organizational value dimensions (see [Related Prior Work](#related-prior-work)).

### Integration, Not Replacement

IIVCS is designed to integrate existing organizational practices rather than replace them. TOGAF and ArchiMate remain relevant for architecture governance. SAFe and Scrum remain the operating practices for delivery teams. JTBD remains a valuable demand research lens. OKRs and ERM remain strategic management tools. IIVCS provides the system within which these practices operate — the connecting tissue between strategy, operating model, and value delivery — not a replacement for the practices themselves.

---

© 2026 Insheights LLC. All rights reserved.
