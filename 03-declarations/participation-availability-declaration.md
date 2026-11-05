
⸻

Participation Availability Declaration (v0)

Purpose

The Participation Availability Declaration defines whether a PeelPack participation offering is open for consideration at a given moment.

It answers the question:

Is this participation offering currently available to be evaluated by potential participants?

This declaration exists to support time-, capacity-, or state-dependent participation without granting permission or triggering execution.

⸻

What This Declaration Declares

A Participation Availability Declaration declares:
	•	That a specific PeelPack participation offering is currently available
	•	Any temporal, capacity, or state-based constraints on availability
	•	Whether availability is:
	•	Open-ended
	•	Time-bounded
	•	Capacity-limited
	•	Condition-dependent

Availability is a fact about the offering, not about any participant.

⸻

What This Declaration Does Not Do

This declaration does not:
	•	Grant permission to participate
	•	Determine eligibility
	•	Select participants
	•	Route execution
	•	Signal readiness for execution
	•	Express intent by any participant
	•	Initiate or trigger any action

Availability is not authority.

⸻

Relationship to Other Declarations

The Participation Availability Declaration works in coordination with:
	•	Participation Visibility Declaration
(where and how the offering may be observed)
	•	Eligibility Declaration
(who may participate, if they choose to evaluate)
	•	Conformance Declaration
(whether implementations meet declared standards)

Availability is evaluated after visibility and before eligibility, but it does not enforce ordering or control flow.

⸻

Observation and Evaluation Semantics
	•	Availability declarations are observed, not pushed
	•	They may be:
	•	Polled
	•	Subscribed to
	•	Queried
	•	Observation does not imply interest, intent, or obligation

Evaluation of availability may occur within declared mediation boundaries, but no execution follows constitutionally.

⸻

Constitutional Invariants

The following invariants apply:
	•	Availability does not imply permission
	•	Availability does not imply eligibility
	•	Availability does not imply routing
	•	Availability does not imply execution
	•	Availability never transfers authority

A participation offering may be available and still never be acted upon.

Availability does not imply invitation.

⸻

Example (Non-Normative)

A Commons steward may declare that a research PeelPack:
	•	Is available for participation
	•	For the next 30 days
	•	With a maximum of 500 participants

This declaration:
	•	Makes the offering available for consideration
	•	Does not authorize participation
	•	Does not select participants
	•	Does not initiate execution

All subsequent action remains human-initiated and platform-mediated.

⸻

v0 Completion Criteria

This declaration is considered v0 complete when:
	•	Availability is clearly distinguished from visibility and eligibility
	•	No language implies permission, routing, or execution
	•	The declaration survives a hostile read without being interpreted as control
