
⸻

CHANGELOG.md

NICE Constitutional Artifacts — Change History

This changelog records normative changes to the NICE Constitutional artifacts.

It exists to:
	•	Prevent silent drift
	•	Make authority-affecting changes auditable
	•	Preserve interpretive continuity across versions
	•	Support hostile-reader review over time

This is not a release notes document.
Every entry here must be traceable to a constitutional artifact change.

⸻

Versioning Policy (Summary)

This changelog follows the rules defined in VERSIONING.md.
	•	MAJOR — Breaking constitutional change
	•	MINOR — Clarification or extension (non-breaking)
	•	PATCH — Editorial or corrective (non-semantic)

If a change does not belong in this file, it does not belong in the constitution.

⸻

[0.1.0] — Initial Constitutional Baseline

Status: Locked (v0 baseline)
Date: YYYY-MM-DD

Added
	•	Full Constitutional Participation Model:
	•	Human Authority & Personal Trust (singular)
	•	Declared Participation Mediation (singular)
	•	Governed Collective Participation (plural)
	•	Constitutional boundary definitions:
	•	Declaration Evaluation & Eligibility Boundary
	•	Intermediation Boundary for Declared Participation
	•	Collective Governance Boundary
	•	Constitutional declaration set (v0):
	•	Participation Availability Declaration
	•	Participation Visibility Declaration
	•	Conformance Declaration
	•	Eligibility Declaration
	•	Commitment & Provenance Declaration
	•	Constitutional standards index (CS-1, CS-2, … placeholders)
	•	Hostile reader defenses and non-goals
	•	Explicit separation of:
	•	Authority vs execution
	•	Evaluation vs routing
	•	Assistance vs delegation

Locked Invariants
	•	Authority originates once — and only once — with the human
	•	Declarations are inspectable, not executable
	•	Participation is evaluated, never initiated by systems
	•	Sensemaking assistance is permitted but never agentic
	•	Platforms are conforming implementations, not authorities

Explicit Non-Goals (Affirmed)
	•	No protocol selection
	•	No execution logic
	•	No optimization or inference policy
	•	No platform design guidance

⸻

[0.1.1] — Terminology & Consistency Corrections

Type: PATCH
Date: YYYY-MM-DD

Changed
	•	Standardized use of constitutional surface names (no platform shortcuts)
	•	Replaced ambiguous “routing” language with “availability” and “visibility”
	•	Corrected declaration naming collisions
	•	Aligned Commons taxonomy across all references

Rationale

Prevented misreadings related to:
	•	Push-based participation
	•	Implied authority transfer
	•	Execution leakage into constitutional language

⸻

[0.2.0] — Declarative Clarity & Defensive Hardening

Type: MINOR
Date: YYYY-MM-DD

Added
	•	Explicit “Must not” blocks for all constitutional roles
	•	Defensive language clarifying:
	•	Evaluation does not imply permission
	•	Visibility does not imply routing
	•	Alignment does not imply optimization
	•	Expanded hostile-reader checklist

Clarified
	•	Distinction between:
	•	Participation Availability vs Participation Visibility
	•	Constitutional mediation vs physical realization
	•	Role of humans acting in Commons roles via personal trust boundaries

Non-Regression Statement

No protections were weakened.
All changes increase interpretive safety.

⸻

[Unreleased] — Proposed / Under Review

All proposed changes must:
	•	Declare intended version impact (MAJOR / MINOR / PATCH)
	•	State which invariants are affected
	•	Pass hostile-reader review before inclusion

No implied changes are permitted.

⸻

Amendment Discipline

If a change:
	•	Is not listed here
	•	Is not versioned
	•	Is not reviewable

It does not exist.

The constitution only changes when humans say so — explicitly.


v0.0.0 — 2026-02-03
Locked constitutional baseline
Commit: 3d67435

## v0.1.0 — 2026-02-04
Commit: 2bde09a

Added:
- Inherited infrastructure declarations
- Physical compute, transport, and substrate constraints
- Constitutional clarification of inherited layers

## v0.1.1 — 2026-02-19
Commit: 5e242e5

Added:
- Purpose and Scope (00-introduction)
- Reading Guide (00-introduction)
- Misreadings and Non-Goals (00-introduction)

Clarified:
- Constitutional purpose, scope, and interpretive posture
- Non-delegation and human-origin-of-authority principles
- Normative status of the Constitution relative to implementations

## v0.1.2 — 2026-02-23
Commit: cad351a

Clarified:
- visual that should be referenced

## v0.1.3 — 2026-02-23
Commit: b64a5a0

Added:
- Constitutional license

## v0.1.4 — 2026-11-05

MINOR — Terminology clarification: bApp → PeelPack (non-breaking, non-semantic)

Amendment Summary:

What is changing:
- All constitutional references to "bounded App (bApp)" / "bounded Apps (bApps)" are replaced with PeelPack language (12 references across 7 artifacts).
- Glossary gains "PeelPack" and records "bApp (retired)".
- Non-normative architecture guides are added (guides/architecture/), hash-pinned, explicitly labeled NON-NORMATIVE.

Why:
- Canon ruling by Peter Tittle (2026-11-03): "PeelPacks it is." The package metaphor reigns; the constitution must not refer to a retired noun.

Classification:
- MINOR. Clarifies language without changing meaning. The referenced class — a bounded, declared, non-executable capability delivered through participation — is unchanged. No declaration type is added or removed; no boundary is moved; no invariant touched.

Constitutional invariants affected: none weakened.

Hostile Reader Check (binary, all NO):
- Implies inferred intent? NO
- Enables push-based authority? NO
- Blurs evaluation and execution? NO
- Creates hidden gatekeeping? NO
- Introduces automation of human judgment? NO
## v0.1.5 - 2026-11-05

MINOR - TIX vocabulary + standards enumeration + constitutional anchor convention (non-breaking)

Amendment Summary:

What is changing:
- Glossary gains TIX (Trusted Interchange) and TIX-MEDIATION.
- The 04-standards indexes enumerate the concrete Role/Interface Standard labels of the platform system (38 labels; NICE-RS-TIX-* namespace per RULING A).
- Constitutional anchor-slug convention established (06-appendices/constitutional-anchors.md; five seed anchors), enabling standards to bind constitutional text by reference.

Why:
- RULING A (2026-11-05, Peter): TIX - Trusted Interchange; the X = the act of mutually giving and receiving. Enables standards conformance to cite constitutional text without paraphrase.

Classification:
- MINOR. Registry and clarification; adds no obligations, changes no meaning, reduces no protections, moves no boundary. Hostile Reader Check: all NO.

Deferred to walkthrough rulings (NOT in this amendment): plane-2 boundary naming harmonization; COMMONS-TIX-ONRAMP vs COMMONS-TIX-IFACE label decision.
