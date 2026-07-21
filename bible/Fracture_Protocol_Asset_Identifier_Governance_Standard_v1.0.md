# THE FRACTURE PROTOCOL — ASSET IDENTIFIER GOVERNANCE STANDARD

**Classification:** Permanent Governance Standard (**Locked**)
**Status:** Compiled 2026-07-21 per "Founder Directive — Phase 1.1: Asset Identifier Governance Standard v1.0," resolving the `FPP-CHAR-XXXX` namespace collision surfaced by the "Founder Directive — Mira Concept Art Asset Audit." Continues from `documentation/Asset_Registry.md`, `Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md`, `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (v2.2), and all Approved Kael assets (FPP-CHAR-001 through FPP-CHAR-007). **No asset renumbered. No file renamed. No Git history modified. No approved Concept Art modified. No registered Asset ID modified.**
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md` (Asset ID Standard, partially superseded in scope by this document — see Section 2) → `Fracture_Protocol_Phase6B_Final_Reports_v1.0.md` (originally flagged, unresolved `CHR-000X` vs. `FPP-CHAR-00X` discrepancy — resolved by this document) → this Standard.

---

## 1. Collision Audit

A direct search of every `FPP-CHAR-[0-9]{3}` occurrence across `documentation/Asset_Registry.md` and `bible/` found the collision is confined entirely to the numerals **001 through 004**, and takes exactly one form: the same ID is assigned to two different kinds of record — a **Character Identity** (in the Asset Registry's Character & Environment Backlog table) and a **Production Asset** (in the Asset Registry's Concept Art table, all belonging to Kael's own Concept Art pipeline).

| ID | Character Identity assignment | Production Asset assignment | Collision type |
|---|---|---|---|
| `FPP-CHAR-001` | Kael Aurelian Veyr | Kael — Silhouette/Proportion Reference (Exploration); Kael — Primary Outfit Concept Art, Calm State (Approved) | Same-character dual-use — the character and the asset are both Kael, so the numeral doesn't point to two different people, but it still marks two structurally different record types (a character-level entry vs. a specific-deliverable entry) with one ID. |
| `FPP-CHAR-002` | Cassian Veyrion Aurelian | Kael — Turnaround, Front View (Approved) | **Cross-character collision.** The same numeral identifies two different characters depending on which Asset Registry table is consulted. |
| `FPP-CHAR-003` | Mira Solenne Valeris | Kael — Turnaround, Side View (Approved) | **Cross-character collision** (the specific case that surfaced this audit). |
| `FPP-CHAR-004` | The Guardian | Kael — Turnaround, Back View (Approved) | **Cross-character collision.** |
| `FPP-CHAR-005` | *(none — only 4 principal characters currently have a Character Identity ID)* | Kael — Expression Reference, Conflict State (Approved) | No present collision, but a **latent future collision**: the Character Backlog table's own sequential scheme would assign this exact numeral to the fifth principal character the moment one is added. |
| `FPP-CHAR-006` | *(none)* | Kael — Expression Reference, Activation State (Approved) | Same latent risk as FPP-CHAR-005. |
| `FPP-CHAR-007` | *(none)* | Kael — Expression Reference, Breakdown State (Approved) | Same latent risk as FPP-CHAR-005/006. |

**Registry references:** both tables inside `documentation/Asset_Registry.md` use the colliding numerals directly as row keys — the Character & Environment Backlog table (§"Characters") and the Concept Art table (§"Concept Art").

**Documentation references:** every one of Kael's ~25 Concept Art production/review documents (`Fracture_Protocol_FPP_CHAR_00[1-7]_*.md`) cites its own asset ID pervasively in headers, authority chains, and changelogs; the four Character Production Packages (`Fracture_Protocol_Phase6B_Character_*_v1.0.md`) each cite their own character-identity ID in the same way. Both citation families are internally consistent on their own terms — the collision only appears when the two families are read against each other, which is exactly how it surfaced (the Mira Concept Art Asset Audit needed to assign Mira's first Concept Art ID and found `FPP-CHAR-003` already claimed by Kael's Side View Turnaround).

**No other Phase 6 namespace collides.** `FPP-ENV-XXXX` (Environments), `FPP-TECH-XXXX` (Props/Technology), `FPP-SB-XXXX` (Storyboard), `FPP-ANIM-XXXX` (Animation), `FPP-AUD-XXXX` (Audio), `FPP-VFX-XXXX` (Visual Effects), and `FPP-EDIT-XXXX` (Editing) were each checked directly and found to be single-purpose already — this Standard ratifies them unchanged rather than leaving them silently unaddressed. `BRA-XXXX` (Brand Assets) is a wholly separate scheme with no overlap. Episode numbering (Episodes 01–36) has no `FPP-CHAR` involvement.

---

## 2. Governance Decision — Permanent Namespaces

Each namespace below serves exactly one purpose. No namespace may ever be reused for a second purpose.

| Namespace | Governs | Status |
|---|---|---|
| `FPP-CHAR-XXXX` | **Character Identity only** — one ID per principal character, assigned once, never reused for any asset, view, expression, or deliverable. | Re-scoped by this Standard (see Section 3 — existing Concept Art use of this range is Legacy, not current policy). |
| `FPP-ART-XXXX` | **Production/Concept Art Assets** — every individual visual deliverable (stills, turnaround views, expression references, silhouette/proportion references) for any character, sequential across the whole production, independent of which character it depicts. | **New** — created by this Standard to end the collision at its root. |
| `FPP-ENV-XXXX` | Environment Assets | Already established (Phase 6C); unchanged, ratified. |
| `FPP-TECH-XXXX` | Prop/Technology Assets | Already established (Phase 6D.1/6D.2); unchanged, ratified. The directive's "Prop Assets" category maps onto this existing namespace — a separate `FPP-PROP-` prefix is not created, to avoid manufacturing a second scheme for the same category. |
| `FPP-SB-XXXX` | Storyboard Assets | Already established (Phase 6E.1/6E.2); unchanged, ratified. |
| `FPP-ANIM-XXXX` | Animation Assets | Already established (Phase 6F.1/6F.2); unchanged, ratified. |
| `FPP-AUD-XXXX` | Audio Assets | Already established (Phase 6G.1/6G.2); unchanged, ratified. |
| `FPP-VFX-XXXX` | Visual Effects Assets | Already established (Phase 6H.1/6H.2); unchanged, ratified. |
| `FPP-EDIT-XXXX` | Editing Assets | Already established (Phase 6I.1); unchanged, ratified. |
| `BRA-XXXX` | Brand Assets | Already established, wholly separate scheme; unaffected, unchanged. |

**This also resolves the standing, previously-unresolved discrepancy** flagged in `Fracture_Protocol_Phase6B_Final_Reports_v1.0.md` between Phase 6A.5's `CHR-000X` format and the production's actual `FPP-CHAR-00X` practice: Phase 6A.5's Asset ID Standard is superseded, for Character Identity and Concept Art purposes specifically, by the two namespaces above (`FPP-CHAR-XXXX` and `FPP-ART-XXXX`), which match the `FPP-<CATEGORY>-XXXX` pattern already in live, Approved use for every other category (Environment, Prop, Storyboard, Animation, Audio, VFX, Editing). Phase 6A.5's `Category_ID_Name_Version` filename convention and Version Standard (Asset ID, Version, Creator, Creation Date, Approval Date, Episodes Used, Dependencies, Status, Last Modified) remain in force unchanged — only the specific ID-prefix examples for Character/Concept Art are superseded.

---

## 3. Legacy Compatibility Decision

**No renumbering. No file renames. No Git history changes. No modification to any Approved Concept Art file, Technical Certification, Creative Validation record, or Asset Registry entry.**

All seven of Kael's existing Concept Art assets keep their current IDs exactly as registered:

| Existing ID | Asset | Declared status |
|---|---|---|
| `FPP-CHAR-001` (Concept Art use) | Silhouette/Proportion Reference; Primary Outfit Concept Art, Calm State | **Legacy Asset Identifier** — Approved under the former identifier policy. |
| `FPP-CHAR-002` (Concept Art use) | Turnaround, Front View | **Legacy Asset Identifier** — Approved under the former identifier policy. |
| `FPP-CHAR-003` (Concept Art use) | Turnaround, Side View | **Legacy Asset Identifier** — Approved under the former identifier policy. |
| `FPP-CHAR-004` (Concept Art use) | Turnaround, Back View | **Legacy Asset Identifier** — Approved under the former identifier policy. |
| `FPP-CHAR-005` (Concept Art use) | Expression Reference, Conflict State | **Legacy Asset Identifier** — Approved under the former identifier policy. |
| `FPP-CHAR-006` (Concept Art use) | Expression Reference, Activation State | **Legacy Asset Identifier** — Approved under the former identifier policy. |
| `FPP-CHAR-007` (Concept Art use) | Expression Reference, Breakdown State | **Legacy Asset Identifier** — Approved under the former identifier policy. |

**The Character Identity use of `FPP-CHAR-001` through `FPP-CHAR-004` is not legacy** — it is the live, permanent Character Identity namespace, ratified unchanged by Section 2 (Kael = 001, Cassian = 002, Mira = 003, Guardian = 004).

**Citation rule for future documents:** any new document that must reference one of Kael's seven legacy Concept Art assets shall cite it as:

> `FPP-CHAR-00X (Legacy Concept Art Identifier — <asset description>)`

on first reference in that document — e.g., `FPP-CHAR-003 (Legacy Concept Art Identifier — Kael Turnaround Side View)` — distinguishing it unambiguously from:

> `FPP-CHAR-00X (Character Identity — <character name>)`

e.g., `FPP-CHAR-003 (Character Identity — Mira Solenne Valeris)`. Existing documents are not required to retrofit this qualifier retroactively (see Section 5) — the rule governs new writing only.

---

## 4. Forward Identifier Policy

**Character Identity (`FPP-CHAR-XXXX`):** the next principal character added to the production receives the next ID in the Character Backlog's own sequence. To fully eliminate even a qualifier-disambiguated numeral overlap going forward, **Character Identity numbering resumes at `FPP-CHAR-008`**, permanently skipping 005–007 since those numerals are now permanently claimed by Kael's legacy Concept Art (Section 3). This is the one substantive decision this Standard makes rather than merely ratifying existing practice — made here because the directive's own stated purpose is to prevent collisions *permanently*, and a same-numeral-different-meaning situation resolved only by a citation qualifier (Section 3) is a weaker guarantee than a numbering scheme with no overlap at all. 001–004 are not renumbered (Legacy Compatibility, Section 3); only the *next* assignment point moves.

**Production/Concept Art Assets (`FPP-ART-XXXX`):** every future visual deliverable — for Mira, Cassian, the Guardian, or any future character, and for any future Kael asset — receives the next sequential `FPP-ART-XXXX` ID, starting at `FPP-ART-001`, independent of character identity. This directly resolves the open question from the Mira Concept Art Asset Audit: **Mira's first Concept Art asset (a Silhouette/Proportion Reference, per that audit's own finding) will be `FPP-ART-001`, not `FPP-CHAR-008` and not `FPP-CHAR-003`.** Numbering is production-wide and sequential by creation order, not per-character blocks, matching how Kael's own seven assets were actually numbered in practice.

**Environments, Props, Storyboards, Animation, Audio, Visual Effects, Editing:** continue under their already-established, non-colliding namespaces (`FPP-ENV-`, `FPP-TECH-`, `FPP-SB-`, `FPP-ANIM-`, `FPP-AUD-`, `FPP-VFX-`, `FPP-EDIT-`), unchanged, for all future assets in those categories.

**Marketing/Brand assets:** continue under `BRA-XXXX`, unaffected — this category never collided and needs no change.

**Episodes:** continue under the existing Episode 01–36 (and future-season) numbering, which has never involved `FPP-CHAR-XXXX` and is unaffected.

**Standing rule:** no namespace prefix defined in Section 2 may be assigned a second purpose in the future. Any directive proposing a new asset category must either map onto an existing namespace above or request a new, distinct prefix through the same governance process this Standard establishes — never reuse `FPP-CHAR-` or `FPP-ART-` for anything outside their Section 2 definitions.

---

## 5. Cross-Reference Impact — Affected Documents

The following require **only a governance cross-reference note** pointing to this Standard — none require renumbering, renaming, or content rewrites:

1. **`documentation/Asset_Registry.md`** — both the Character & Environment Backlog table's `FPP-CHAR-001–004` rows and the Concept Art table's `FPP-CHAR-001–007` rows would benefit from a short header note citing this Standard as the authoritative explanation for the shared numerals, and a note that all future Concept Art entries will use `FPP-ART-XXXX`. (Not applied in this pass — this directive's own scope is the Standard itself, not its rollout; the actual edit is a natural next directive.)
2. **`bible/Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md`** — its Asset ID Standard section would benefit from a cross-reference noting that Character/Concept-Art ID prefixes are now governed by this Standard instead.
3. **`bible/Fracture_Protocol_Phase6B_Final_Reports_v1.0.md`** — its originally-flagged, unresolved `CHR-000X` vs. `FPP-CHAR-00X` discrepancy note would benefit from a cross-reference marking it resolved by this Standard.
4. **Kael's seven Concept Art document families** (`Fracture_Protocol_FPP_CHAR_00[1-7]_*.md` — Exploration, Production Attempt, External Production Package, Ingestion Attempt, Revision Package, Generation Reviews, Creative Validation, and Technical Certification records for each of the seven assets, ~25 files) — each would benefit from a single added line identifying its own asset ID as a Legacy Concept Art Identifier per Section 3, no other change.
5. **The four Character Production Packages** (`Fracture_Protocol_Phase6B_Character_Kael_Aurelian_Veyr_v1.0.md`, `..._Cassian_Veyrion_Aurelian_v1.0.md`, `..._Mira_Solenne_Valeris_v1.0.md`, `..._The_Guardian_v1.0.md`) — each would benefit from a one-line confirmation that its own `FPP-CHAR-00X` is a ratified, permanent Character Identity ID under this Standard.
6. **`bible/Fracture_Protocol_Character_Turnaround_Production_Standard_v1.0.md`** and **`bible/Fracture_Protocol_Kael_Expression_Reference_Production_Package_v1.0.md`** — both directly discussed the "distinct Asset ID per deliverable" pattern and its flagged discrepancy; a cross-reference to this Standard closes that open thread.
7. **`bible/Fracture_Protocol_FPP_CHAR_001_Turnaround_Pre_Production_v1.0.md`** and **`bible/Fracture_Protocol_FPP_CHAR_001_Character_Standard_Completion_Plan_v1.0.md`** — same, minor cross-reference only.

**No file in this list is modified by this document.** This section is a forward work-list, per the directive's own instruction that only governance-wording updates are contemplated and that no existing approved file may be modified beyond what's strictly required — none of that rollout is performed here.

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — the collision audit was performed by direct search of every `FPP-CHAR-[0-9]{3}` occurrence, not assumed; every namespace claimed "already established, unchanged" was individually verified against the Asset Registry, not asserted. |
| Alignment Audit | PASS — no asset renumbered, no file renamed, no Git history touched, no approved Concept Art or registered Asset ID modified; the one substantive new decision (Character Identity resuming at `FPP-CHAR-008`) is disclosed as a decision, not framed as a mere ratification of existing practice. |
| Regression Verification | PASS — all seven of Kael's Approved Concept Art assets and their registry entries are explicitly preserved unmodified (Section 3); no previously Approved document is edited by this Standard itself. |

**Determination: PASS.**

## Founder Approval

**Approved 2026-07-21** following a clean PASS Founder Review, Alignment Audit, and Regression Verification. This Asset Identifier Governance Standard is **Locked** as permanent governance: `FPP-CHAR-XXXX` is reserved exclusively for Character Identity going forward (resuming at `FPP-CHAR-008` for the next principal character); `FPP-ART-XXXX` is established as the permanent namespace for all future Production/Concept Art assets, beginning at `FPP-ART-001`; the seven existing Kael Concept Art assets are preserved unmodified as Legacy Asset Identifiers. **Mira's first Concept Art asset is authorized to be assigned `FPP-ART-001` under this Standard once her own production pipeline begins.**

---

### Changelog
`[v1.0 — 2026-07-21] Compiled per "Founder Directive — Phase 1.1: Asset Identifier Governance Standard v1.0," resolving the FPP-CHAR-XXXX collision surfaced by the Mira Concept Art Asset Audit. Audited every FPP-CHAR-[0-9]{3} occurrence and found the collision confined to numerals 001–004 (Character Identity vs. Kael's own Concept Art pipeline), with 005–007 carrying a latent future-collision risk. Confirmed all other Phase 6 namespaces (FPP-ENV, FPP-TECH, FPP-SB, FPP-ANIM, FPP-AUD, FPP-VFX, FPP-EDIT, BRA) are already single-purpose and collision-free. Established two permanent namespaces: FPP-CHAR-XXXX (Character Identity only) and FPP-ART-XXXX (new — Production/Concept Art Assets, sequential production-wide). Declared all seven of Kael's existing Concept Art assets Legacy Asset Identifiers, Approved under the former identifier policy, with no renumbering, renaming, or Git history change; defined a citation-qualifier rule for future documents referencing them. Set the Forward Identifier Policy: Character Identity numbering resumes at FPP-CHAR-008 (permanently skipping 005–007, now permanently claimed by Kael's legacy assets); all future Concept Art assets for any character begin at FPP-ART-001, resolving the open question from the Mira Concept Art Asset Audit — her first asset will be FPP-ART-001. Ratified all other existing namespaces unchanged. Listed seven categories of affected documents requiring only a future governance cross-reference note, none modified in this pass. This also formally resolves the standing, previously-unresolved CHR-000X vs. FPP-CHAR-00X discrepancy flagged in Fracture_Protocol_Phase6B_Final_Reports_v1.0.md. No asset renumbered; no file renamed; no Git history modified; no approved Concept Art modified; no registered Asset ID modified. Status: "Locked — Permanent Governance Standard."`
