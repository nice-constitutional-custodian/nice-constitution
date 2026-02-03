
⸻

TERMINOLOGY DECISIONS & RATIONALE
NICE Constitutional System — v0

Purpose
This document records intentional terminology choices made in the NICE Constitutional System, including alternatives that were explicitly rejected.

Its purpose is not to define terms (see glossary.md), but to preserve design intent and prevent semantic drift.

Every term documented here reflects a deliberate tradeoff.

⸻

General Naming Principles
	1.	Terms describe constraints, not capabilities
Language in the constitution must limit what systems may do, not advertise what they can do.
	2.	Terms privilege human agency over system function
If a term could imply autonomous system action, it was rejected or constrained.
	3.	Familiar words are preferred only when they do not import harmful assumptions
Novelty is avoided unless necessary to prevent misreading.
	4.	Declarative language is preferred over imperative language
The constitution declares conditions; it does not issue commands.

⸻

Declaration (Chosen)
Rejected alternatives: Policy, Rule, Instruction, Contract

Rationale
“Declaration” emphasizes:
• statement of intent or constraint
• inspectability
• non-executability

Rejected terms implied:
• automatic enforcement
• executable logic
• bilateral obligation

Declarations in NICE constrain what may happen; they do not cause anything to happen.

⸻

Visibility (Chosen)
Rejected alternatives: Routing, Distribution, Delivery, Notification

Rationale
“Visibility” communicates:
• availability to be observed
• absence of obligation
• pull-based interaction

Rejected terms implied:
• push semantics
• command delivery
• implied execution paths

Participation availability must be visible, not routed.

⸻

Availability (Chosen, but constrained)
Rejected alternatives: Permission, Authorization, Grant

Rationale
“Availability” signals possibility, not approval.

Authorization occurs only at the human authority boundary.
Availability merely states that participation is possible under declared constraints.

⸻

Eligibility (Chosen)
Rejected alternatives: Access Control, Admission, Approval

Rationale
“Eligibility” reflects:
• evaluation against declared criteria
• absence of discretion
• non-authoritative determination

Rejected terms implied:
• gatekeeping power
• centralized approval
• subjective judgment

Eligibility is evaluated, not granted.

⸻

Conformance (Chosen)
Rejected alternatives: Certification, Accreditation, Compliance (unqualified)

Rationale
“Conformance” indicates:
• alignment to declared standards
• inspectable properties
• revocability

Rejected terms implied:
• institutional authority
• permanent status
• external endorsement

Conformance is declared and attested, not bestowed.

⸻

Boundary (Chosen)
Rejected alternatives: Surface, Layer, Zone, Environment

Rationale
“Boundary” emphasizes:
• constraint edges
• enforcement limits
• separation of concerns

Rejected terms implied:
• functional areas
• execution contexts
• ownership domains

Boundaries constrain behavior; they do not perform it.

⸻

Participation Mediation (Chosen)
Rejected alternatives: Coordination, Orchestration, Routing

Rationale
“Mediation” reflects:
• reconciliation without authority
• evaluation without execution
• neutrality

Rejected terms implied:
• control flow
• centralized coordination
• command sequencing

Mediation reconciles declarations; it never routes execution.

⸻

Assistance (Chosen)
Rejected alternatives: Agent, Delegate, Proxy, Automation

Rationale
“Assistance” clearly signals:
• subordination to human judgment
• non-agentic behavior
• revocability

Rejected terms implied:
• delegated authority
• autonomous action
• substitution of judgment

Assistance supports understanding; it does not act.

⸻

Sensemaking (Used, but constrained)
Related term: Interpretive Assistance

Rationale
“Sensemaking” is used narrowly to mean:
• rendering options legible
• surfacing tradeoffs
• reflecting implications

It explicitly excludes:
• optimization
• prediction
• goal inference

Where cognitive load may be high, “interpretive assistance” is preferred.

⸻

Continuity (Chosen)
Rejected alternatives: Profiling, Alignment, Modeling (unqualified)

Rationale
“Continuity” describes:
• preservation of context over time
• non-inferential coherence

Rejected terms implied:
• behavioral inference
• predictive modeling
• optimization targets

Continuity preserves; it does not predict.

⸻

Governance (Chosen)
Rejected alternatives: Control, Management, Authority

Rationale
“Governance” in NICE means:
• enforcement of declared constraints
• accountability without discretion

Rejected terms implied:
• command authority
• unilateral decision-making

Governance constrains; it does not empower.

⸻

Platform (Chosen, but bounded)
Rejected alternatives: System, Network, Service (unqualified)

Rationale
“Platform” is used only with explicit constraints:
• replaceable
• non-owning
• non-authoritative

Where ambiguity remains, “implementation” is preferred.

⸻

Final Note
If a future change requires introducing a new term, it must be documented here before being used elsewhere.

If a term’s meaning changes, the change must be recorded here and versioned explicitly.

Terminology drift is constitutional drift.
