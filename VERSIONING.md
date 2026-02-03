
⸻

VERSIONING.md

NICE Constitutional Artifacts — Versioning & Amendment Rules

This document defines how changes to the NICE Constitutional artifacts are proposed, evaluated, and adopted.

The purpose of versioning is not convenience.
It is protection against silent drift, implicit authority, and accidental erosion of human standing.

⸻

1. Scope of Versioning

This versioning policy applies to all artifacts in this repository, including:
	•	Constitutional participation planes
	•	Constitutional boundaries
	•	Constitutional declarations
	•	Constitutional standards (CS-n)
	•	Hostile-reader defenses
	•	Appendices that affect interpretation or enforcement

It does not apply to:
	•	Platform implementations
	•	Interface specifications
	•	Protocol selections
	•	SDKs or tooling

Those belong in downstream repositories and must conform to the constitution as versioned here.

⸻

MAJOR.MINOR.PATCH

2.1 MAJOR — Constitutional Change (Breaking)

Increment MAJOR when a change:
	•	Alters where authority originates
	•	Weakens or redefines human standing
	•	Changes evaluation vs execution boundaries
	•	Adds, removes, or materially redefines a constitutional plane
	•	Changes the meaning or scope of a CS-n standard
	•	Introduces or removes a declaration type

MAJOR changes are rare by design.
They require explicit human review and collective ratification (see §5).

⸻

2.2 MINOR — Clarification or Extension (Non-Breaking)

Increment MINOR when a change:
	•	Clarifies language without changing meaning
	•	Adds explanatory text or diagrams
	•	Adds new declaration types that do not weaken existing constraints
	•	Adds new Commons root categories without altering inheritance rules
	•	Adds defensive language against newly identified misreadings

MINOR changes must not:
	•	Reduce protections
	•	Add implicit authority
	•	Change execution semantics

⸻

2.3 PATCH — Editorial or Corrective

Increment PATCH when a change:
	•	Fixes typos or formatting
	•	Improves readability
	•	Corrects internal references
	•	Resolves ambiguity without changing interpretation

PATCH changes must be provably non-semantic.

⸻

3. What Constitutes a Breaking Constitutional Change

A change is breaking if it causes any conforming implementation to become non-conforming without changing its behavior.

Examples:
	•	Allowing inferred intent where it was previously prohibited
	•	Permitting execution where only evaluation was allowed
	•	Allowing platforms to originate authority “in limited cases”
	•	Reclassifying declarations as executable or routable

If there is doubt, the change is breaking.

⸻

4. Amendment Process (How Changes Happen)

4.1 Proposal

All changes must be proposed as:
	•	A pull request (PR)
	•	With an explicit Amendment Summary at the top

The summary must state:
	•	What is changing
	•	Why it is necessary
	•	Whether it is MAJOR, MINOR, or PATCH
	•	Which constitutional invariants are affected

⸻

4.2 Hostile Reader Review (Mandatory)

Before merge, the proposal must pass the Hostile Reader Checklist.

At minimum, reviewers must be able to answer “no” to:
	•	Does this imply inferred intent?
	•	Does this enable push-based authority?
	•	Does this blur evaluation and execution?
	•	Does this create hidden gatekeeping?
	•	Does this introduce optimization or automation of human judgment?

If any answer is “maybe,” the change must be revised or rejected.

⸻

4.3 Ratification Thresholds
	•	PATCH: Maintainer approval
	•	MINOR: Maintainer + documented review
	•	MAJOR: Explicit ratification process (to be defined externally)

No MAJOR change may be merged silently.

⸻

5. Non-Regression Rule

Constitutional protections may not be weakened by amendment.

Changes may:
	•	Clarify
	•	Strengthen
	•	Make implicit protections explicit

They may not:
	•	Reduce human authority
	•	Introduce inferred agency
	•	Centralize discretion
	•	Convert evaluation into execution

If a future need appears to require weakening a protection, the correct response is a new layer or system, not a constitutional rollback.

⸻

6. Forward Compatibility Rule

Implementations must assume that:
	•	Future constitutional versions may add constraints
	•	Silence is not permission
	•	Absence of a declaration does not imply allowance

This prevents “version pinning” as an escape hatch.

⸻

7. Why This Exists

The NICE Constitution is not a feature set.
It is a load-bearing constraint system.

Versioning exists to ensure that:
	•	Power cannot creep in unnoticed
	•	Optimizations cannot quietly replace consent
	•	Human agency cannot be eroded by convenience

Every version is a promise — and a boundary.

⸻

8. Definition of “v0 Stable”

Version 0.x indicates:
	•	Structural completeness
	•	Defensive clarity
	•	Known areas of future refinement

Version 1.0 will only be declared when:
	•	The constitution survives sustained hostile review
	•	Multiple independent implementations conform without divergence
	•	No unresolved authority ambiguities remain

Until then, caution is a feature.
