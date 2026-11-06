
⸻

04-standards/interface-standards-index.md

Purpose

This document indexes interface standards used to realize constitutional declarations across platform boundaries.

Interface standards specify how systems communicate while remaining fully subordinate to constitutional constraints.

⸻

What qualifies as an Interface Standard

An interface standard in NICE:
	•	Realizes a constitutional declaration or boundary
	•	Enables interoperability without transferring authority
	•	Is observable, inspectable, and replaceable
	•	May evolve independently of the constitution

Interface standards are constrained, not empowered.

⸻

Interface Boundary Categories (v0)

Interface standards may exist at the following boundaries:
	1.	Human ↔ Platform Interfaces
	•	Declaration inspection
	•	Consent expression
	•	Visibility observation
	2.	Platform ↔ IX Mediation Interfaces
	•	Declaration publication
	•	Availability visibility
	•	Eligibility evaluation results
	3.	Platform ↔ Commons Governance Interfaces
	•	Governance constraint propagation
	•	Accountability reporting
	•	Outcome attestation
	4.	Peer ↔ Peer Mediation Interfaces
	•	Observed participation availability
	•	Mediated message delivery
	•	Pull-based coordination

⸻

Pull-Based Requirement

All interface standards must support pull / observe semantics.

No interface may:
	•	Push authority
	•	Implicitly grant permission
	•	Trigger execution

⸻

Explicit Non-Coverage

Interface standards do not define:
	•	Internal platform logic
	•	Execution venues
	•	Optimization or inference routing
	•	Trust heuristics or scoring

⸻

IS-PERS-DECLARE

Boundary: Human Authority & Personal Trust → Declared Participation Mediation

Purpose:
• declaration submission and inspection

Must not:
• imply push-based authority
• infer intent
• trigger execution

⸻

IS-IX-RELAY

Boundary: Declared Participation Mediation

Purpose:
• publication of participation visibility

Must not:
• route execution
• grant permission
• imply obligation

⸻

IS-IX-MATCH

Boundary: Declared Participation Mediation

Purpose:
• eligibility reconciliation

Must not:
• rank participants
• optimize outcomes
• enforce decisions

⸻

IS-IX-JOURNAL

Boundary: Declared Participation Mediation

Purpose:
• commitment and provenance recording

Must not:
• act as a control plane
• gate participation

⸻

IS-COMMONS-GOVERN

Boundary: Governed Collective Participation

Purpose:
• enforcement of declared collective constraints

Must not:
• originate authority
• bypass human participation

⸻

🔒 v0 LOCKED

⌷

Enumerated Interface Standards (v0.1.5)

Registry listing - the concrete Interface Standard labels of the platform system.

- PERS: NICE-IS-PERS-INTENT-SUBMIT, NICE-IS-PERS-EXECUTE, NICE-IS-PERS-EXECUTION-ATTEST, NICE-IS-PERS-VAULT, NICE-IS-PERS-GUIDANCE, NICE-IS-PERS-TIX (bundle)
- TIX: NICE-IS-TIX-REGISTER, NICE-IS-TIX-MATCH, NICE-IS-TIX-ATTEST; journal receipts: NICE-IS-TIX-JOURNAL-REGISTER, NICE-IS-TIX-JOURNAL-MATCH, NICE-IS-TIX-JOURNAL-ATTEST, NICE-IS-TIX-JOURNAL-ROUTE
- COMMONS: NICE-IS-COMN-GOV-CONSTRAINTS, NICE-IS-COMN-EXEC-ROUTING, NICE-IS-COMN-RUNTIME-DECLARE, NICE-IS-COMN-RUNTIME-RECEIPT, NICE-IS-COMN-RULES-ACCOUNTABILITY, NICE-IS-COMN-JOURNAL-STANDING, NICE-IS-COMN-TIX-CONTEXT
