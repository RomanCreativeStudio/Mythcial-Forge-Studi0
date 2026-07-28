# BRA-0001 — Vector Draft Review Package
## v0.5 — Final Optical Polish (Pre-Lock)

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Final polish pass complete, rendered, and QA'd against every checkpoint used across this asset's history. **Not yet marked Approved by this package** — see Recommendation, below.
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` Section 3–5, `brand/Mythic_Forge_Studios_YouTube_Brand_Kit_v1.0.md` Section 2, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.4.md` (this package's baseline).
**Scope discipline:** Concept 5, "Weighted Line," remains Locked. No color, typeface, studio name, tagline, or the fracture's core mechanism (a contained mass with something escaping it) was touched. This pass only adjusted geometry (horn, shard) and text-spacing values already governed by existing Locked Brand Bible numbers.

---

## Icon Refinement

### 1. Horn

**Finding, stated plainly:** v0.4's horn was a symmetric tapering wedge (equal taper on both the top and bottom edges), which is what an axe head or hatchet blade looks like in silhouette — not what an anvil horn looks like. Real anvils (and every recognizable anvil pictogram) have a horn that's a *continuation of the flat table*, tapering only on its underside.

**Fix:** rebuilt the horn so its top edge is flush and continuous with the face's own top edge (both now sit at the same height, one unbroken line from the horn's tip to the face's right edge) — all tapering happens on the horn's underside only. No curves were introduced; this is still two straight edges, consistent with "maintain geometric simplicity."

**Result:** confirmed by render — the top of the mark now reads as a single flat table extending into a tapering horn, which is the single most identifying feature of an anvil silhouette. The axe-head read is gone.

### 2. Cyan Shard

**Finding:** the shard (added in v0.2, refined in v0.3–v0.4) was a clean three-point triangle — geometrically correct, but it reads as an arrowhead or a direction-indicator rather than a piece of material.

**Fix:** added a single facet point along the shard's outer edge, offset slightly inward, turning the clean triangle into a four-point, subtly irregular shape. This is the smallest possible change that gives it a "chipped" rather than "manufactured" quality. Verified by a zoomed render (not just the full-icon view) that the facet is actually visible, not lost in rounding.

**Explicitly not done:** the shard's size, position, or color were not changed — per the instruction not to increase its visual dominance, and because neither needed correction; only its edge quality did.

### 3. Optical Balance

**Finding:** measured directly from the v0.4 geometry, the mark's left margin (11 units) was visibly tighter than its right margin (20 units) — the composition sat left-of-center in its frame.

**Fix:** shifted the entire composition +4 units right, producing balanced 15/16 margins. This is a minimal adjustment, not a recomposition — every proportion and angle is unchanged, only the whole shape's position within the 100-unit frame moved.

---

## Wordmark Refinement

**No typeface change** — Space Grotesk retained throughout, per instruction.

**Finding, checked directly against the Brand Bible's own numbers (Section 5), not against taste:** the Brand Bible's Locked typography spec calls for "STUDIOS" to carry **+8–10% tracking** — at the wordmark's 16px size, that's **1.28–1.6 units** of letter-spacing. Every prior draft (v0.1 through v0.4) shipped `letter-spacing="3"`, roughly double the Locked spec. This was a genuine, previously uncaught deviation from an already-approved rule, not a new stylistic decision.

**Fix:** corrected to `letter-spacing="1.4"` (the midpoint of the 8–10% range).

**Headline tracking:** the Brand Bible calls for "MYTHIC FORGE" to use "tight-to-neutral (0 to -1%)" tracking. Every prior draft used the default (0%, technically within range but not using the tightening the spec allows). Added `letter-spacing="-0.3"` (-1% of 30px), for a subtle, spec-accurate tightening — barely perceptible at a glance, which is the point of a headline tracking correction at this scale.

**Custom letterforms — considered and explicitly rejected.** The instruction allowed for "distinctive but restrained treatment of one or two characters if it strengthens recognition." A custom-cut "O" (echoing the icon's fracture motif) was considered. It was not implemented: the icon mark already carries all of this identity's distinctive weight, and a modified letterform risks tipping from "typography" into "decoration" — exactly what this pass was told to avoid. Per the instruction itself ("if a proposed change does not clearly improve the design, do not make it"), this was left alone. This is a decision, not an oversight.

**Icon-to-wordmark spacing and vertical alignment:** checked by direct render against the corrected icon geometry — unchanged from v0.4's values (gap and baseline positions), confirmed still balanced with the new horn/shard shapes rather than assumed.

---

## Studio Brand Test

| Communicates | Assessment |
|---|---|
| ✓ Premium entertainment studio | Yes — flat geometric construction, restrained single accent, no illustrative noise |
| ✓ World-building | Supported structurally by the fracture (creation/transformation), not depicted literally — correct per Brand Bible Section 6's rule against borrowing in-fiction imagery |
| ✓ Craftsmanship | Yes — the anvil read is now unambiguous after the horn fix |
| ✓ Confidence | Yes — solid mass, single deliberate irregularity, no hedging or ornamentation |
| ✓ Longevity | Yes — no trend-dependent styling; flat vector construction ages the same way in five years as today |
| ✗ Blacksmith company | Avoided — the fracture and cyan accent pull it out of pure-craft-brand territory into something more conceptual |
| ✗ Gaming clan | Avoided — no aggressive angularity, no shield/blade tropes, no glow-heavy treatment |
| ✗ AI startup | Avoided — no gradient, no smoothed-blob abstraction, no generic circuit motif |
| ✗ Fantasy sports logo | Avoided — no mascot energy, no bevel/emboss, no ornamental flourish |

---

## QA

| Check | Result |
|---|---|
| ✓ Icon recognition | Passes — confirmed anvil read at large size, horn fix directly addressed the prior axe-head risk |
| ✓ 28px | Passes — re-rendered at true 28×28px, silhouette and fracture both legible |
| ✓ Monochrome | Passes — re-rendered, gap remains legible with zero color contrast |
| ✓ Dark background | Passes |
| ✓ Light background | Passes |
| ✓ Wordmark readability | Passes — re-rendered at full lockup width, no clipping, tracking now spec-accurate |
| ⚠ Favicon test (16px) | **Marginal, not a clean pass.** Rendered at true 16×16px and inspected directly: the mark is still identifiable as a blocky anvil-like form, but fine detail (the fracture's path specifically) degrades substantially — this is a real, measured limitation, not a subjective concern. 16px is below the 28px threshold this asset has been validated against throughout its production history; nothing in this pass claims 16px legibility was ever a hard requirement, but it should be recorded honestly rather than marked as passing when the render shows real degradation. |
| ⚠ YouTube avatar test (800×800, circular crop) | **Real finding, not a pass.** Composited the actual icon into an 800×800 circle exactly as YouTube's avatar crop would. The mark's current margins (adequate for a square/rectangular frame) are not sufficient for a *circular* crop specifically — the face's top-right corner is visibly clipped by the circle. This is not a flaw in the Primary Logo Master SVG itself; it is a confirmation that the **Channel Avatar** (a separate deliverable, per the Brand Asset Production Guide's First Production Pipeline, item 3) will need additional padding composed in at export time, beyond simply dropping this master icon into an 800×800 canvas unaltered. |

---

## Recommendation

**The icon and wordmark refinements in this pass measurably improved the mark**, against concrete, previously-identified weaknesses (the axe-head silhouette read, the arrowhead-like shard, an off-center composition, and a Brand-Bible-spec typography deviation that had gone uncaught across four prior drafts). Every change is justified against a specific, named problem — nothing was changed for its own sake, consistent with "if a proposed change does not clearly improve the design, do not make it."

The two QA items marked ⚠ are not reasons to keep iterating on this asset:
- The 16px favicon result is a known, expected limit of detail at extreme small sizes, not something this pass's changes made worse — and 16px was never the asset's validated target (28px was, and it passes).
- The avatar circular-crop finding is scoped to a *different, not-yet-built* asset (the Channel Avatar), not a defect in the Primary Logo Master SVG. It's recorded here so it isn't lost, not as a blocker for this asset.

**Recommendation: promote BRA-0001 to Primary Logo Master SVG v1.0 — LOCKED**, carrying the two QA notes above forward as documented implementation guidance for the Channel Avatar and any favicon-specific export (which Brand Asset Production Guide Section 3's Scalability Testing already anticipated might need its own small-size-optimized master). This recommendation is made by this package; formal Approval per Brand Asset Production Guide Stage 5 and Studio Governance Manual Sections 5–7 remains a Founder decision, not something this document can grant itself.

---

### Changelog
`[v0.5 — 2026-07-07] Final optical polish pass, pre-lock. Icon: rebuilt the horn asymmetric (flat top continuous with the face, all taper on the underside) to fix v0.4's symmetric-wedge "axe head" silhouette read; added a single facet to the escape shard so it reads as a chipped forged fragment rather than a clean arrowhead, without changing its size, position, or dominance; shifted the composition +4 units right to correct an 11/20 left/right margin imbalance to 15/16. Fracture geometry recomputed fresh against the adjusted mass using the same validated knockout-gap technique, verified computationally before building. Wordmark: corrected "STUDIOS" tracking from letter-spacing 3 (used in every prior draft) to 1.4, matching the Brand Bible's own Locked +8-10% tracking spec at 16px, which had been over-tracked by roughly double since v0.1; added a -0.3 letter-spacing to "MYTHIC FORGE" per the Brand Bible's tight-to-neutral headline tracking rule. Considered and explicitly rejected a custom-letterform treatment as unnecessary decoration on top of an already-distinctive icon mark. QA re-run in full: icon recognition, 28px, monochrome, dark/light backgrounds, and wordmark readability all pass; a true 16px favicon render and an actual 800x800 circular-crop composite were additionally tested (not previously done at this precision) -- 16px legibility is marginal but was never the asset's validated target; the circular-crop test found the master icon's margins are insufficient for a circular avatar crop specifically, which is recorded as an implementation note for the future Channel Avatar asset, not a defect in this one. No Locked brand element redefined. Recommendation: promote to Primary Logo Master SVG v1.0 -- LOCKED, pending Founder approval.`
