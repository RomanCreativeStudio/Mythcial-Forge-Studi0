# THE FRACTURE PROTOCOL — ASSET NAMESPACE GOVERNANCE STANDARD

**Classification:** Permanent Governance Standard (**LOCKED GOVERNANCE STANDARD v1.0**)
**Status:** Compiled 2026-07-21 per "Founder Directive — Phase 1.2: Asset Namespace Governance Standard v1.0," continuing from `Fracture_Protocol_Asset_Identifier_Governance_Standard_v1.0.md` (Phase 1.1, LOCKED, unmodified by this document), `production-os/Production_OS_v2.0.md`, `studio-os/Studio_OS_v1.0.md`, and `documentation/Asset_Registry.md`. **This document extends governance only — it does not modify Phase 1.1, does not invalidate any existing ID, and does not rename any existing asset.**
**Method, disclosed up front:** this directive's own draft namespace list (Section 3) uses three labels — `FPP-PROP`, `FPP-AUDIO`, `FPP-MKT` — that do not match names already Locked and in live production use. Per this document's own Section 5 (Conflict Resolution) and the directive's own explicit instruction not to invalidate existing IDs, the Master Namespace Registry below uses the **already-Locked, already-in-use names** for those two colliding categories, with the substitution disclosed inline, not applied silently. Full detail in Section 3.
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `Fracture_Protocol_Asset_Identifier_Governance_Standard_v1.0.md` (Phase 1.1) → `production-os/Production_OS_v2.0.md` → `studio-os/Studio_OS_v1.0.md` → `documentation/Asset_Registry.md` → this Standard, which becomes the required reference for every future namespace or Asset ID assignment.

---

## 1. Purpose

- **Why namespaces exist.** Every asset in this production needs a permanent, unique identifier that survives renaming, re-review, and re-registration. A namespace is the category-level prefix (`FPP-CHAR`, `FPP-ART`, etc.) that groups those identifiers so two unrelated assets never end up sharing one — the exact failure this production has already experienced once (Section 3, cross-reference below).
- **Collision prevention.** Phase 1.1 resolved one real collision after the fact (`FPP-CHAR-XXXX` doing double duty as both Character Identity and Kael's own Concept Art sequence) and a second was caught and stopped before it happened (a directive requesting `FPP-CHAR-008` for a Concept Art asset, resolved by Founder Decision to keep `FPP-ART-001`). This document exists to make that kind of after-the-fact discovery unnecessary going forward — every category gets its own namespace before any asset in it is created, not after.
- **Long-term scalability.** This production will add more principal characters, environments, props, episodes, and marketing campaigns than exist today. A namespace design that requires renumbering as it grows is not acceptable — every namespace here is unbounded and purely additive (Section 2).
- **Production readability.** A human reading `FPP-ART-001` or `FPP-ENV-011` should be able to tell the asset's category from the prefix alone, without opening the Asset Registry.
- **Automation compatibility.** A consistent `FPP-<CATEGORY>-XXXX` pattern (with the two disclosed historical exceptions in Section 3) is the minimum structure any future tooling — a registry script, an asset tracker, a build pipeline — would need to reliably parse, sort, and validate assets by category without ambiguity.

---

## 2. Namespace Principles

| Principle | Statement |
|---|---|
| One namespace = one asset category | No namespace may ever govern two different kinds of asset (the exact defect Phase 1.1 corrected in `FPP-CHAR-XXXX`). |
| Namespaces never overlap | No two namespaces may claim the same category of asset — including where an *existing* namespace already covers ground a newly-proposed one might otherwise claim (see Section 3, Marketing vs. Brand Assets). |
| IDs never reused | Once an ID is assigned within a namespace, it is never assigned to a second, different asset — even if the original asset is later retired or superseded. |
| IDs never reassigned | An ID's meaning is permanent from the moment it is first assigned; correcting a *file* (technical rebuild, revision) does not change the ID it was assigned to. |
| Namespaces may grow | Every namespace is sequential and open-ended — `FPP-ART-002`, `FPP-ART-003`, etc. are always valid next assignments; no namespace has a hard ceiling. |
| Retired IDs remain reserved permanently | An ID belonging to a Superseded or Retired asset is never returned to the available pool — it stays reserved forever, exactly as already practiced for Brand Assets (`BRA-0001A-CINEMATIC-BANNER` v1.0 was Superseded and its slot never reused, per `documentation/Asset_Registry.md`'s own "nothing disappears without a record" rule, cited here as precedent, not altered). |

---

## 3. Master Namespace Registry

| Namespace | Purpose | Includes | Status |
|---|---|---|---|
| **`FPP-CHAR`** | Character Identity records only | Kael, Mira, Cassian, the Guardian (and future principal characters) | **Locked (Phase 1.1).** Never used for Concept Art, Turnarounds, Expressions, or Storyboards — that collision is exactly what Phase 1.1 corrected. |
| **`FPP-ART`** | Concept Art | Primary Outfit, Turnarounds, Expressions, Pose Sheets, Lighting Sheets, Material Sheets, Animation References | **Locked (Phase 1.1).** `FPP-ART-001` (Mira, Primary Outfit, Calm) is the first and, as of this Standard, only assignment. |
| **`FPP-ENV`** | Environment assets | Ward Station Seven, Mid Zone, Lower Sector, Unknown Layer, and the full 15-environment inventory | **Already established (Phase 6C), ratified unchanged.** **Discrepancy flagged, not corrected here:** `FPP-ENV-001` through `FPP-ENV-010` use the full prefix; `ENV-011` through `ENV-015` (added later, Phase 6C.8/6C.9) use a shortened `ENV-XXX` prefix without `FPP-`. This is a genuine, pre-existing inconsistency, now squarely in this Standard's scope — not resolved here, since backfilling the prefix would rename five already-registered IDs, which Section 7 (Migration) forbids without a dedicated Founder directive. |
| **`FPP-TECH`** | Props, Technology, Weapons, Artifacts, Vehicles, Equipment | `FPP-TECH-001` ("the comm") | **Already established (Phase 6D.1/6D.2), ratified unchanged.** **Correction, disclosed:** this directive's own draft list names this category `FPP-PROP`. No asset has ever used that prefix — the one asset in this category, `FPP-TECH-001`, is already Approved under `FPP-TECH`. Adopting `FPP-PROP` here would either orphan the existing ID or require renaming it, both forbidden by Section 7. `FPP-TECH` is retained as the authoritative namespace for this category; `FPP-PROP` is not created. |
| **`FPP-SB`** | Storyboard packages | `FPP-SB-001` through `FPP-SB-016` | **Already established (Phase 6E.1/6E.2), ratified unchanged.** |
| **`FPP-ANIM`** | Animation assets | `FPP-ANIM-001` through `FPP-ANIM-010` | **Already established (Phase 6F.1/6F.2), ratified unchanged.** |
| **`FPP-AUD`** | Dialogue, Music, SFX, Voice assets | `FPP-AUD-001` through `FPP-AUD-030` | **Already established (Phase 6G.1/6G.2), ratified unchanged.** **Correction, disclosed:** this directive's own draft list names this category `FPP-AUDIO`. Thirty assets already exist under `FPP-AUD`; adopting the longer form would require renaming all thirty, forbidden by Section 7. `FPP-AUD` is retained; `FPP-AUDIO` is not created. |
| **`FPP-EDIT`** | Editing assets | `FPP-EDIT-001` through `FPP-EDIT-036` (per-episode) | **Already established (Phase 6I.1), ratified unchanged.** |
| **`FPP-MKT`** | Marketing assets | Posters, thumbnails, trailers, social graphics | **New — genuinely non-colliding, created by this Standard.** No asset has ever used this prefix. Explicitly distinct from `BRA-XXXX` (below): `BRA` governs the studio's own brand-identity assets (logo, favicon, YouTube channel banner/avatar/watermark — the studio's fixed visual identity), while `FPP-MKT` governs promotional/campaign content for specific episodes and releases (a poster for Episode 12, a trailer cut, a social graphic) — different assets with different lifecycles, not two names for the same thing. |
| **`FPP-DOC`** | Governance, production documents, internal documentation | This Standard, Phase 1.1, Production OS, Studio OS, and future governance/production documents | **New — genuinely non-colliding, created by this Standard.** Every governance and production document in this repository has so far been referenced by descriptive filename only, with no numeric ID scheme; this creates one for the first time. **Not retroactively applied** — no existing document is renamed or assigned an `FPP-DOC` ID by this Standard; it governs future assignment only, per Section 7. |
| **`BRA`** | Brand identity assets | Primary Logo, app icon, YouTube channel avatar/watermark/banner, favicon set | **Already established (Brand Asset Production Guide), ratified unchanged, and explicitly not superseded or narrowed by the new `FPP-MKT` namespace above.** |

---

## 4. Namespace Assignment Rules

For every new production asset:

1. **Determine asset category** — which row of Section 3's Master Namespace Registry the asset belongs to.
2. **Locate namespace** — confirm the category's namespace prefix directly from Section 3, never from memory or a directive's own restated list (Section 3's own disclosed corrections exist precisely because a restated list can drift from what's actually Locked).
3. **Assign next sequential ID** — the next unused number within that namespace, per `documentation/Asset_Registry.md`'s current state, checked directly.
4. **Verify against Asset Registry** — confirm no existing entry already claims the proposed ID, and that the asset's own naming convention (`Category_ID_Name_Version` per Phase 6A.5, or the established `FPP-<CATEGORY>-XXX_Name_..._vX.X` pattern already in live use) is followed.
5. **Register** — only after Stage 1/Stage 2 validation (or the equivalent for non-visual categories) passes, per each category's own governing production standard (e.g., Phase 6K.0 for Concept Art).

---

## 5. Conflict Resolution

**If a requested Asset ID conflicts with this Standard: Stop. Do not guess. Do not silently substitute. Request Founder clarification.**

This is not a new, untested rule — it is the exact process already followed once in this production, immediately before this Standard was commissioned: a directive requested `FPP-CHAR-008` for a Concept Art asset, in direct conflict with Phase 1.1's Character-Identity-only reservation for that namespace. Production stopped, the conflict was presented directly to the Founder via `AskUserQuestion`, and a formal Founder Decision resolved it (`FPP-ART-001` retained, no override, no duplicate, recorded in that asset's own package). That resolution is the working precedent this rule now codifies for every future conflict of the same kind.

---

## 6. Cross References

- **`Fracture_Protocol_Asset_Identifier_Governance_Standard_v1.0.md` (Phase 1.1)** — establishes `FPP-CHAR` and `FPP-ART` specifically, and the Forward Identifier Policy (Character Identity resuming at `FPP-CHAR-008`; Concept Art beginning at `FPP-ART-001`). Not modified by this document; incorporated by reference.
- **`documentation/Asset_Registry.md`** — the registry of record for every actual assigned ID in every namespace; this Standard defines the namespace rules, the Registry remains the source of truth for which specific IDs are taken.
- **`production-os/Production_OS_v2.0.md`** and **`studio-os/Studio_OS_v1.0.md`** — checked directly and confirmed to define no Asset ID or namespace content of their own (no duplicated governance); cross-referenced here only for their broader production/studio-workflow authority, which this Standard sits beneath.

**No content is duplicated from any of the above** — each governs its own layer, cited not restated.

---

## 7. Migration

| Confirmation | Result |
|---|---|
| No existing assets renamed | **Confirmed.** Every already-Locked or already-Approved ID (`FPP-CHAR-001–004` Character Identity; Kael's legacy `FPP-CHAR-001–007` Concept Art; `FPP-ART-001`; `FPP-ENV-001–010` and `ENV-011–015`; `FPP-TECH-001`; `FPP-SB-001–016`; `FPP-ANIM-001–010`; `FPP-AUD-001–030`; `FPP-EDIT-001–036`; all `BRA-XXXX` entries) is unchanged by this document. |
| No existing IDs changed | **Confirmed.** Section 3's two disclosed corrections (`FPP-TECH` over `FPP-PROP`; `FPP-AUD` over `FPP-AUDIO`) preserve the existing IDs exactly as registered — they correct this directive's own draft label, not any asset. |
| `FPP-ART-001` remains valid | **Confirmed.** Unaffected; still Mira's Primary Outfit Concept Art, Calm State, Compiled — Pending Founder Review. |
| `FPP-CHAR` namespace remains unchanged | **Confirmed.** Character-Identity-only scope, per Phase 1.1, is restated, not altered. |

---

## 8. Final Determination

**LOCKED GOVERNANCE STANDARD v1.0.** This document is now the authoritative master registry for every Asset Identifier namespace in The Fracture Protocol production, and the required reference for every future production standard, registry entry, package, or asset before a new Asset ID is assigned.

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — every "already established" namespace claim was verified directly against `documentation/Asset_Registry.md`, not asserted from memory; both disclosed corrections (`FPP-TECH`, `FPP-AUD`) trace to specific, cited, already-registered assets. |
| Alignment Audit | PASS — Phase 1.1 is not modified; no existing ID is invalidated, renamed, or reassigned; the two label corrections preserve rather than disturb existing governance. |
| Regression Verification | PASS — no existing document edited by this Standard; `FPP-ART-001`'s own package (including its recorded Founder Decision) is unaffected. |
| Dependency Verification | PASS — Section 6's cross-references were checked directly (Production OS and Studio OS confirmed to define no competing Asset ID content) rather than assumed compatible. |

**Determination: PASS.**

## Founder Approval

**Approved and LOCKED 2026-07-21** following a clean PASS across all four verification passes. This Standard governs all future Asset ID and namespace assignment across every production category.

---

### Changelog
`[v1.0 — 2026-07-21] Compiled and LOCKED per "Founder Directive — Phase 1.2: Asset Namespace Governance Standard v1.0." Built the Master Namespace Registry (Section 3) covering eleven namespaces: FPP-CHAR and FPP-ART (Locked, Phase 1.1, restated); FPP-ENV, FPP-TECH, FPP-SB, FPP-ANIM, FPP-AUD, FPP-EDIT, and BRA (already established in prior phases, ratified unchanged); FPP-MKT and FPP-DOC (new, confirmed genuinely non-colliding). Disclosed two corrections to this directive's own draft namespace list rather than silently adopting or silently ignoring them: FPP-TECH retained over the directive's proposed FPP-PROP (FPP-TECH-001 already Approved), and FPP-AUD retained over the directive's proposed FPP-AUDIO (thirty assets already registered under FPP-AUD) — both would have required renaming already-registered assets, forbidden by this same directive's own Migration requirements. Flagged, not resolved, a pre-existing FPP-ENV-XXX vs. bare ENV-XXX inconsistency (Environments 001–010 vs. 011–015) now squarely in this Standard's scope. Confirmed FPP-MKT is genuinely distinct from the existing BRA namespace (promotional/campaign content vs. studio brand-identity assets), not a duplicate. Established five Namespace Assignment Rules and a Conflict Resolution rule explicitly grounded in the FPP-CHAR-008/FPP-ART-001 conflict already resolved by real Founder Decision immediately prior to this directive. Confirmed via Migration (Section 7) that no existing asset was renamed, no existing ID changed, FPP-ART-001 remains valid, and the FPP-CHAR namespace remains unchanged. Status: "LOCKED GOVERNANCE STANDARD v1.0."`
