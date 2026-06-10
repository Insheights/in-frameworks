# IIVCS Integration with Existing Practices

**SAFe | Scrum | OKRs | ITIL | ERM | Design Thinking | Value Stream Mapping | Jobs To Be Done**

How the Insheights Integrated Value Creation System connects to and integrates with existing organizational practices, methods, and frameworks — rather than replacing them.

---

## The Integration Premise

The IIVCS does not ask organizations to discard existing practices. Most organizations already use agile delivery methods, strategic planning tools, risk frameworks, architecture governance, and customer measurement instruments. These practices work within their domains.

What IIVCS provides is the connecting system — the architecture within which existing practices operate, the measurement language that makes their outputs composable, and the feedback architecture that returns their signals to the right place in the organization.

The test: an organization running SAFe, OKRs, and ITIL has delivery teams, strategic objectives, and service management. What it typically lacks is a shared spine connecting strategic intent to value stream execution to customer outcome — measured consistently from process level to organizational value level, with feedback running upstream. IIVCS is that spine.

---

## What IIVCS Adds — and What It Does Not Replace

| Capability | IIVCS Provides | Existing Practice Handles |
|---|---|---|
| Strategy-to-delivery spine | OSM → PTS → CVDM: single connected system from strategic intent to customer outcome | — |
| Customer journey as organizing principle | CVDM anchors all internal elements to customer journey steps | Service Blueprint, Customer Journey Mapping tools |
| Consistent cross-architectural measurement | 3E (Efficiency → Experience → Effectiveness) from Process to Value Stream | Domain-specific measurement instruments (see below) |
| Behavioral signal layer | AER: Customer and Organizational Adoption, Engagement, Retention | — |
| Organizational value model | 8 Values: eight outcome dimensions that delivery generates | Balanced Scorecard, ESG/GRI (external reporting) |
| Feedback architecture | Five CVDM feedback loops + upstream signal path to OSM | Retrospectives, governance reviews (execution mechanism) |
| Agile delivery ceremonies | — | Scrum, SAFe, Kanban |
| Portfolio prioritization method | — | WSJF, OKR scoring, investment scoring models |
| Architecture notation and governance | — | TOGAF, ArchiMate, BIZBOK |
| Risk management methodology | — | ERM frameworks |
| Service management processes | — | ITIL, ISO 20000 |
| Demand research methods | — | JTBD, ethnographic research, customer surveys |
| Customer measurement instruments | — | NPS, CSAT, CES surveys |
| Financial modeling | — | Business case methods, NPV, ROI frameworks |
| HR and people practices | — | HR operating models, performance frameworks |

---

## Integration by Existing Practice

### SAFe (Scaled Agile Framework)

SAFe provides the delivery execution structure — Agile Release Trains, PI Planning, portfolio management, and flow metrics — that PTS's cross-functional product teams operate within.

**Where SAFe connects into IIVCS:**

- **Portfolio → OSM:** SAFe's Portfolio layer (Strategic Themes, Lean Portfolio Management) maps to OSM's strategic value priorities and value stream allocation. OSM sets the value priorities that SAFe's portfolio layer executes against. Strategic themes become the bridge between OSM's Strategic Objectives and SAFe's portfolio investment decisions.
- **ART structure → PTS:** SAFe's Agile Release Trains are the team structures PTS's operating model organizes around. PTS's four POM Enablers (Leadership, Practices & Behaviors, Organizational Architecture, Culture & Relationships) are the conditions that make SAFe ARTs effective — or identify why they are not.
- **PI Objectives → CVDM:** SAFe's Program Increment Objectives become the delivery commitments that CVDM's value stream stages and capabilities must deliver against. CVDM's 3E measurement makes visible whether PI execution is producing customer outcomes, not just shipped features.
- **Flow metrics → 3E Efficiency:** SAFe's flow metrics (Flow Velocity, Flow Time, Flow Efficiency, Flow Load) are Efficiency signals in 3E terms. They measure whether value can be accessed without friction at the delivery level. 3E connects these signals forward to Experience and Effectiveness — dimensions SAFe's native metrics do not capture.

**What IIVCS adds that SAFe does not provide:** A customer journey anchor that is structural (not just practiced). A measurement architecture that connects flow performance to customer outcomes and organizational value. A feedback architecture that returns PI-level delivery signal to strategic reassessment in OSM.

---

### Scrum

Scrum provides the team-level delivery ceremonies and practices — Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective — that PTS's cross-functional product teams run.

**Where Scrum connects into IIVCS:**

- **Sprint planning → CVDM:** Sprint goals are delivery commitments for specific CVDM value stage capabilities and processes. Scrum's Definition of Done aligns with CVDM's Effectiveness threshold: was value actually delivered to the customer, not just completed in the build?
- **Sprint Review → 3E Effectiveness:** The Sprint Review is the point at which Effectiveness signal surfaces — did what was built achieve the intended outcome? The Review is the ceremony; 3E is the measurement model that makes the question systematic.
- **Sprint Retrospective → Feedback loops:** Retrospective outcomes feed directly into CVDM's Delivery Learning feedback loop — and, when systemic, into PTS's operating model improvement cycle.
- **Velocity and throughput → 3E Efficiency:** Sprint velocity and throughput are Efficiency signals at the team level. They surface whether the team can access and deliver value without friction.

**What IIVCS adds:** The system above and around Scrum — the customer journey that Sprint goals serve, the value streams that Scrum teams operate within, the measurement architecture that connects Sprint delivery to customer behavioral response and organizational value.

---

### OKRs (Objectives and Key Results)

OKRs are the strategic execution practice through which OSM's Strategic Objectives are expressed, tracked, and evaluated.

**Where OKRs connect into IIVCS:**

- **Objectives → OSM Strategic Objectives:** OKRs translate OSM's value priorities and strategic intent into time-bound organizational commitments. The Objective is the strategic direction; the Key Results are the measurable signals that confirm the strategic bet is being won or lost.
- **Key Results → 3E and 8 Values:** Well-formed Key Results at the organizational level are 8 Values signals — Customer Value, Financial Value, Market Value, and the other six outcome dimensions. At the operating level, Key Results are 3E Effectiveness signals — did we achieve the intended outcome?
- **OKR cadence → OSM Governance cycle:** The OKR review cycle (quarterly or annual) is the execution mechanism for OSM's Governance & Measurement loop. IIVCS does not define a cadence — it defines what the measurement language is. OKR ceremonies are how the cadence runs.
- **Portfolio OKRs → Value stream allocation:** Portfolio-level OKRs determine which value streams are prioritized for investment — directly informing OSM's Execution & Deployment layer.

**What IIVCS adds:** A measurement architecture (3E → AER → 8 Values) that makes Key Result design more rigorous — distinguishing leading Efficiency and Experience signals from lagging Effectiveness outcomes. A feedback architecture that returns delivery signal to OKR retrospectives. A framework for surfacing whether OKR attainment is driving the organizational value dimensions it was intended to drive.

---

### ITIL (IT Infrastructure Library)

ITIL's service management processes — Incident Management, Problem Management, Change Management, Service Continuity, and the rest — operate within CVDM's Support phase as Capability and Process elements.

**Where ITIL connects into IIVCS:**

- **Service Management → CVDM Capabilities:** ITIL capabilities (Service Desk, Incident Management, Change Management) are CVDM Capabilities at the Support stage of the customer journey. CVDM defines why these capabilities exist (to deliver a value stage in the customer journey); ITIL defines how they operate.
- **Incident and Problem Management → 3E Efficiency:** Incidents and problems are Efficiency failures — they interrupt the customer's ability to use value. ITIL's resolution metrics (MTTR, first-contact resolution) are Efficiency signals in 3E terms.
- **Service Level Agreements → 3E thresholds:** SLA targets define the acceptable Efficiency floor for service delivery. Breaches are CVDM feedback loop triggers — signals that a capability is not meeting the value delivery threshold.
- **Continual Service Improvement → CVDM Performance Optimization loop:** ITIL's Continual Service Improvement cycle is the execution mechanism for CVDM's fifth feedback loop (Performance Optimization). CSI provides the improvement methodology; CVDM's feedback loop defines what signal triggers it and where the output goes.

**What IIVCS adds:** A customer journey context for ITIL processes — every ITIL capability exists to serve a specific step in the customer's journey. 3E measurement that connects ITIL's service metrics to customer experience and outcome dimensions ITIL's metrics do not capture. A feedback architecture that returns service performance signal upstream through PTS operating model improvement to OSM strategic reassessment.

---

### ERM (Enterprise Risk Management)

Enterprise Risk Management is a direct input to OSM's Strategic Value Creation process, not a framework that IIVCS replaces or modifies.

**Where ERM connects into IIVCS:**

- **Risk signal → OSM inputs:** OSM's Strategic Value Creation process has Enterprise Risk as a named input alongside Internal Context, External Context, Leadership Direction, and Stakeholder & Customer Expectations. ERM's risk assessments, risk appetite statements, and emerging risk signals feed directly into strategic value creation — informing which strategic options are viable, which value streams are at risk, and which priorities warrant protective investment.
- **Risk appetite → Value priorities:** The organization's risk appetite, defined through ERM governance, is a constraint on OSM's value priority setting. High-risk value streams require risk-adjusted strategic treatment; ERM provides the framework for defining what that means.
- **Value stream risk → PTS operating model:** Risks identified through ERM at the value stream level (operational, technology, people, compliance) are inputs to PTS's operating model design — informing how teams are structured and enabled to manage risk in execution.

**What IIVCS adds:** A delivery architecture that connects risk signal to operational response. ERM identifies risk; IIVCS is the system through which the organization executes its risk-adjusted strategy and monitors whether delivery is producing or mitigating the outcomes ERM flagged.

---

### Design Thinking

Design Thinking practices — Empathize, Define, Ideate, Prototype, Test — are the research and innovation methods used within CVDM's value proposition development and PTS's Discover phase.

**Where Design Thinking connects into IIVCS:**

- **Empathize → CVDM Customer Journey inputs:** Design Thinking's empathy research (interviews, observations, journey mapping, jobs-to-be-done research) surfaces the customer needs that define CVDM's journey steps and value propositions. Empathy outputs are the input to defining what customer value delivery must achieve.
- **Prototype and Test → CVDM Effectiveness validation:** Design Thinking's prototype and test cycle is the mechanism for validating whether a new capability or value stage design achieves its intended Effectiveness before scaling. The test is the Effectiveness signal; CVDM's feedback loops carry the result upstream.
- **PTS Discover phase:** PTS's Discover phase is where Design Thinking is practiced — continuously, not as a one-time project. The Discover phase is the ongoing loop that keeps teams in contact with customer reality and prevents delivery from drifting away from customer need.

**What IIVCS adds:** The delivery system that operationalizes Design Thinking outputs. Design Thinking surfaces what to build and why; IIVCS is how the organization builds it, delivers it, measures it, and improves it continuously.

---

### Value Stream Mapping

Value Stream Mapping is a diagnostic tool used within PTS and CVDM to analyze flow efficiency and identify waste in specific value streams.

**Where VSM connects into IIVCS:**

- **VSM analysis → 3E Efficiency baseline:** A Value Stream Map is a current-state Efficiency analysis. VSM surfaces cycle time, wait time, and waste in the value stream — which are the Efficiency signals 3E measures on an ongoing basis. VSM is the point-in-time diagnostic; 3E is the continuous measurement.
- **Future-state VSM → CVDM capability redesign:** VSM's future-state maps define the target capabilities and processes that CVDM must operationalize. The future-state design becomes the target architecture for CVDM's capability and process layer.
- **VSM kaizen events → PTS improvement cycles:** VSM-driven improvement events are inputs to PTS's operating model improvement cycle. They surface operating model gaps (people, practices, architecture) that PTS's enablers must address.

**What IIVCS adds:** The Experience and Effectiveness dimensions that VSM cannot see. A VSM-efficient value stream can still fail on customer experience or outcome achievement — 3E makes these gaps visible. A feedback architecture that turns VSM's point-in-time findings into a continuous improvement signal.

---

### Jobs To Be Done (JTBD)

JTBD research is a demand insight method that informs OSM's strategic value creation process and CVDM's value proposition definition.

**Where JTBD connects into IIVCS:**

- **Job definition → OSM value priorities:** JTBD research surfaces which jobs customers most urgently need done — directly informing which value priorities OSM sets and which value streams to invest in. Job importance and satisfaction gaps are leading indicators of strategic opportunity.
- **Outcome research → PTS Discover phase:** PTS's Discover phase is continuous — teams never stop learning from customers across all delivery phases. JTBD outcome research is a primary method for this: it keeps teams grounded in what customers are trying to achieve, not just what they are asking for. Where Design Thinking surfaces how customers experience problems, JTBD surfaces what outcomes they need — the two are complementary at the Discover phase.
- **Job executor's desired outcomes → CVDM value propositions:** JTBD's outcome statements (what customers want to accomplish, at what speed, with what precision) are the basis for CVDM's value propositions at each journey stage. The value proposition is the organization's answer to the job; CVDM is how the organization delivers it.
- **Job satisfaction research → 3E Effectiveness signal:** JTBD outcome surveys (e.g., Outcome-Driven Innovation) measure whether customers are achieving their desired outcomes — which is the Effectiveness dimension of 3E at the customer level.

**What IIVCS adds:** The delivery system that turns JTBD demand insights into realized customer outcomes. JTBD identifies what job to do; IIVCS is the system that does it and measures whether it was done.

---

## Integration Map by IIVCS Framework

### OSM — What connects in

| Existing Practice | Connects at | What It Provides |
|---|---|---|
| OKRs | Governance & Measurement cycle | Time-bound objectives and measurable key results for strategic commitments |
| ERM | Strategic Value Creation inputs | Enterprise risk signal as a constraint on strategic options |
| TOGAF / BIZBOK | Architecture governance layer | Architecture review and governance processes for OSM's deployment decisions |
| Portfolio prioritization methods (WSJF, NPV) | Value stream allocation | Investment scoring and prioritization logic for value stream funding decisions |
| Board and Executive governance cadences | Governance & Measurement | The organizational forums through which OSM's measurement cycle runs |

### PTS — What connects in

| Existing Practice | Connects at | What It Provides |
|---|---|---|
| SAFe | ART structure and PI Planning | Team structures, delivery ceremonies, and portfolio management practices |
| Scrum / Kanban | Team delivery practices | Sprint ceremonies, flow management, and team-level velocity |
| Design Thinking | Discover phase | Customer empathy research and iterative prototyping methods |
| Jobs To Be Done | Discover phase | Outcome research that keeps teams grounded in what customers are trying to achieve across all delivery phases |
| Value Stream Mapping | Operating model analysis | Point-in-time Efficiency diagnostics for value stream improvement |
| HR and people frameworks | POM Enablers (People, Culture) | Performance management, career development, and organizational design practices |

### CVDM — What connects in

| Existing Practice | Connects at | What It Provides |
|---|---|---|
| Scrum / SAFe | Process layer, delivery ceremonies | Team-level delivery execution and sprint/PI rhythms |
| ITIL | Support phase, capability layer | Service management processes for the support stage of the customer journey |
| Design Thinking | Value proposition definition | Customer research and prototype testing methods |
| Service Blueprint | Journey-to-capability mapping | Current-state documentation of customer journey and backstage processes |
| NPS / CSAT / CES | 3E signal instruments | Survey instruments that produce Efficiency (CES), Experience (CSAT), and Effectiveness (NPS) signals |
| JTBD | Value proposition and journey step definition | Demand research defining what outcomes each journey stage must achieve |

---

© 2026 Insheights LLC. All rights reserved.
