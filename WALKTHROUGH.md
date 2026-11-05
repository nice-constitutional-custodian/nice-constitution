# Constitutional Walkthrough Ledger — deck ↔ constitution consistency

Guides (pinned, NON-NORMATIVE): Agency & Standing @ sha256 f6e164cbc0f7f66a8071f32be6331a61475e1cda25dd3877fbb8a4b372416813 · User Journey Map @ sha256 8fb3bc6f6aca47d2cdf39dec1c7b59bdd9f05a3d9e4b1359f8bc8261b4793234

Method: artifact-by-artifact. Each pass records: coverage verdict — divergences — rulings needed. Rulings recorded here feed amendments under VERSIONING.md. This ledger = the documented review record.

## PASS 1 — structural coverage (2026-11-05, post-amendment-branch state)

### Coverage matrix (constitution ↔ deck)
- 00 introduction / purpose / scope: covered by deck title + framing slides — aligned in spirit; deep-echo check in pass 2.
- 01 participation model (three planes; authority originates once): ALIGNED — deck Participation Map = plane-1/2/3 structure; check plane-3's "physically realized through human participation via PERS acting in role" language against deck Governed Coordination slide (pass 2).
- 02 boundaries: ALIGNED structurally. OPEN NAMING: deck says "Intermediation Boundary for Declared Participation" AND "Declaration Evaluation & Eligibility Boundary"; constitution names the boundary "declared-participation-mediation-boundary" — harmonization ruling needed.
- 03 declarations (availability · visibility · eligibility · conformance · commitment+provenance): ALIGNED as families. OPEN: the deck's Participation-Declaration ENVELOPE model (8 sections: purpose/inputs/constraints/execution-scope/privacy/oversight/receipts/remuneration) has no clear constitutional home yet — CHECK pass 2 (remuneration language absent from constitution today).
- 04 standards indexes: categories aligned to deck RS/IS structure; ENUMERATION of concrete NICE-RS-*/NICE-IS-* labels still pending (anchor-slug amendment v0.1 family).
- 05 hostile reader: present in constitution; absent as a deck slide — fine (process, not architecture).
- 06 appendices (amendment, glossary, terminology): process-only — no deck counterpart needed.
- 08 inherited infrastructure: ALIGNED (physical compute / transport / substrate + invariants). CHECK: deck's "resiliency and environmental sustainability" line — verify constitution carries resiliency/stewardship invariants (found: stewardship invariant present; sustainability phrasing check pass 2).

### Divergences & defects (deck-side — replacement images/words)
1. IX slide body-text error: copies the COMMONS slide's text ("The COMMONS Platform Plane defines how collective participation is made operational…") where IX's own text belongs. REPLACE.
2. bApp remnants in deck Platform-System slides: IX title still expands "Bounded Apps Interchange"; "Bounded App Interchange Platform Plane"; Governed Coordination "never execute Bounded Applications". REPLACE after IX-gloss ruling.
3. Deck typos: "Consititutional" (2×), "Contitutional", "agents knows their place", "downtream". REPLACE.
4. Image replacements: flagged by Peter in advance; slides 2/3 visuals of deck + constitution 07-visuals/*.png fidelity to current structure — page-by-page image pass (Peter's eyes) after text pass.

### Rulings queue (walkthrough)
A. IX gloss (title expansion after bApp retirement) — OPEN (Inter-Xchange = flagged candidate, yours to rule).
B. Plane-2 boundary naming: deck's "Intermediation Boundary" ↔ constitution's mediation boundary — one name for both?
C. Envelope section-model's constitutional home (incl. remuneration terms).
D. Maturity spectrum incorporation — shape TBD with Peter: new chapter vs constraint-level tags inside category trees + compilations; L1 NICE-adjacent status (constitution applies when?).
E. Sustainability/resiliency wording check (08).
F. Replacement images list (Peter knows in advance).

## RULING A — IX → TIX, the Trusted Interchange (2026-11-05, Peter)

- Ruling: TIX — **Trusted Interchange**. The X = the act of mutually giving and receiving (dictionary anchor: "the act of mutually changing; the act of mutually giving and receiving; exchange").
- Namespace: `NICE-RS-TIX-*` / `NICE-IS-TIX-*` / `NICE-TIX-JOURNAL-*` replaces the `NICE-RS-IX-*` family. IX retires as a label prefix (cheap migration at stub stage).
- Gloss guard (constitutional): the interchange is trusted-OF (participants attested), never trustING — it verifies and records; never vouches, never decides, never holds, never acts unilaterally.
- Deck slide 12 ("IX - Bounded Apps Interchange"): top plane description + boxed MEDIATION line both carry copied COMMONS text — replaced per convention (text delivered 2026-11-05).
- Constitution: TIX gloss + label enumeration enter with the next amendment family (post-v0.1.4 merge).

## GUIDE RE-PIN — deck revision updated by Peter (2026-11-05 ~21:53 pptx / 21:53 pdf)

Peter migrated the expresser deck to TIX on his side. Diff verdict vs the previous pinned revision: **clean, complete migration** —
- All `IX-*` labels → `TIX-*`; `COMMONS-IX-*` → `COMMONS-TIX-*`; `NICE-IS-PERS-IX` → `NICE-IS-PERS-TIX`; `NICE-IS-COMN-IX-CONTEXT` → `NICE-IS-COMN-TIX-CONTEXT`.
- Journal receipt labels normalized to `NICE-IS-TIX-JOURNAL-*` (IS-prefix added — canonical).
- Slide-12 adopted the delivered convention text nearly verbatim (top description + boxed MEDIATION line); copied COMMONS text gone; titles read `TIX — Trusted Interchange`. `downtream` and `authority, standing, or standing` defects fixed.

Still queued (verified in this revision):
1. TIX slide bottom caption still reads "These implementation platforms realize COMMONS-GOVERNANCE constraints." (COMMONS slide's own instance is legitimate) — replace with TIX-MEDIATION wording (delivered 2026-11-05). The TIX-MEDIATION prose sentence on that slide remains correct.
2. "Participation Interface to Trusted Interchange (TX)" → should read (TIX).
3. Typos: "Consititutional" ×1, "Contitutional" ×1, "Agents that knows their place" ×2.
4. "Bounded" word-instances — juded contexts: LEGITIMATE (keep): "Bounded Owner-Hosted Resources" ×2 (PERS-HARBOR description; boundedness of resources, not the retired noun); TO REPLACE: "…execute Bounded Applications." (Governed Coordination slide, L≈468) and "never executes Bounded Apps" (Non-Authority Guardrails, L≈693) — Peter wording pending (candidates: "application contents" / "PeelPack contents").

Process note: commit 096e15d carried only the re-pinned PDF (a path slip interrupted the pptx/hashes/ledger writes); this entry completes the re-pin.

Pinned now (working set):

## VALIDATION PASS — Peter's second deck revision (2026-11-05 22:06/22:07) — RE-PIN #2

Validated via text-diff against the prior pinned revision. All queue defects RESOLVED except one flagged question:
- "Consititutional" → fixed; "Contitutional" → fixed.
- "…execute Bounded Applications." → "…execute PeelPack Contents." (Peter's wording — capitalized Contents; note for later consistency check vs lowercase "contents" elsewhere)
- "never executes Bounded Apps" → "never executes PeelPack contents."
- "(TX)" → "(TIX)".
- TIX slide bottom caption → "These implementation platforms realize TIX-MEDIATION constraints." (COMMONS slide keeps its one legitimate instance; count verified 1/1.)
- Retained as ruled-keep: "Bounded Owner-Hosted Resources" ×2 (PERS-HARBOR) — verified still present, correctly untouched.

OUTSTANDING (flagged, not blocking):
- "Agents that knows their place." ×2 — grammar quirk queued earlier as typo; twice-instanced may indicate INTENT. Peter's ruling: keep as voice, or correct to "know"?
- Minor consistency note for the image pass: "PeelPack Contents" (capitalized) vs "PeelPack contents" (lowercase) — one case-convention to pick.

Deck queue is now CLEAN for the image pass.
