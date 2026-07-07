# BRA-0001 — Vector Draft Review Package
## v0.3 — Concept Refinement Pass

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Silhouette refined, rendered, and re-tested. **Not approved. Not locked. Not registered.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` Section 3–4, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.2.md` (this package's baseline).
**Trigger for this pass:** a founder-provided concept board offered as creative direction, explicitly not to be traced literally. This package documents an original vector implementation built from that direction, not a copy of the reference image.

---

## Reference Handling — Read This First

The provided concept board is creative direction only, per its own accompanying instruction. Two things from it were deliberately **not** carried into this draft:

1. **The board's color swatches do not match the Locked Brand Bible palette** and were not used:

| Board showed | Brand Bible (Locked, Section 4) | Used in this draft |
|---|---|---|
| "Deep Forge" `#0B0F14` | Void Black `#0A0B0D` | **Void Black `#0A0B0D`** |
| "Mythic White" `#FFFFFF` | Authority White `#F5F7FA` | **Authority White `#F5F7FA`** |
| "Mythic Cyan" `#00E5FF` | Fracture Cyan `#00E5FF` | Fracture Cyan `#00E5FF` (this one matches) |

Two of the three swatches on the board are different colors under different names than the studio's actual Locked palette. Per this document's own front matter and per Brand Bible Section 15 (Founder Authority over Locked elements), the Brand Bible wins — this draft uses the real palette, not the board's. If the board's colors were intended as a deliberate proposed palette change, that is a separate, explicit Founder Override decision (Brand Bible Section 15) and was not assumed here.

2. **The board's "Variant A / B / C" exploration was not implemented as three new options.** The instruction was to refine the one approved Weighted Line concept, not branch into new variant candidates — doing the latter would have reopened the Concept Review this Production Record already closed. What was carried forward is the *design quality bar* the board demonstrates (a recognizable anvil, an integrated fracture, a restrained accent), applied to Concept 5 specifically.

Everything else — the general direction toward a more recognizable anvil silhouette, a fracture that looks structurally cut rather than overlaid, and a tapering shard rather than a straight escape line — is consistent with, and was already the direction of, the v0.2 refinement. This pass extends it further.

---

## What Changed From v0.2

**Mass silhouette redesigned** (still Concept 5 — this is a refinement of the same concept's execution, not a new concept). v0.1/v0.2 used an abstract two-block "upside-down T" shape. v0.3 rebuilds the mass as a **recognizable stylized anvil** — a tapered horn, a flat table/face, a pinched waist, and a flared, chamfered base — constructed as four straight-edged polygons (a triangle, a rectangle, and two trapezoids) unioned into one silhouette. No organic curves were introduced; every edge is a straight line, consistent with the "clean geometry, no illustrative elements" rule carried through every prior stage.

**Fracture recomputed for the new geometry**, using the same knockout-gap-plus-tapering-shard technique validated in v0.2 (not a new technique): entry point `(42,26)` on the face's top edge, a single kink at `(46,50)`, deflecting from a steep ~80.5° to a shallow 32°, exiting through the base's right edge at `(72.66,66.66)`, with a 9-unit tapering shard beyond it. The angles differ from v0.2's 25°/35° because they were computed fresh against the new silhouette's actual proportions — forcing the old angles onto a differently-shaped mass would have been arbitrary, not a real specification.

**Engineering note:** the exit point was not guessed. An early attempt at a shallower exit angle was checked computationally against every edge of the new mass polygon and found to exit through the *body's* right edge almost immediately, not reach the base at all as intended — the geometry was corrected before building the final file, not after rendering revealed a problem.

---

## Draft Assets (v0.3)

| File | Content |
|---|---|
| `mfs-logo-icon-dark_v0.3.svg` | Refined anvil icon, Dark Version |
| `mfs-logo-icon-monochrome_v0.3.svg` | Refined anvil icon, Monochrome |
| `mfs-logo-primary-dark_v0.3.svg` | Icon + wordmark lockup, Dark Version |
| `mfs-logo-primary-light_v0.3.svg` | Icon + wordmark lockup, Light Version |

All four validated as well-formed XML and rendered in a real browser engine at large scale; both icon-only files additionally re-tested at true 28×28px.

---

## Test Results

**Large scale:** the anvil reads clearly and immediately — horn, face, waist, and base are all distinguishable, a significant recognizability improvement over v0.1/v0.2's abstract blocks. The fracture crosses from the face into the body and exits through the base with a visible cyan tapering shard; no stray fill artifacts appeared from the knockout-hole geometry (checked directly against the render, not assumed from the math).

**Monochrome:** re-tested with the same technique validated in v0.2 — the gap remains legible with zero color contrast, both at large size and at true 28px.

**28px:** both Dark and Monochrome icon files remain recognizable as an anvil at true small size, and the fracture is visible in both. This is a meaningfully more detailed silhouette than v0.1/v0.2's two blocks, so this was the primary risk to re-check — confirmed acceptable, not assumed.

**Primary lockups:** re-verified by render (not assumed to still work just because v0.2's canvas fix worked for the old icon shape) — "MYTHIC FORGE" displays in full in both Dark and Light versions at the same 520-wide canvas, 30px wordmark used in v0.2.

---

## Design Intent Check

- **Recognizable stylized anvil:** yes — horn, face, waist, and base are all distinguishable at both large size and true 28px, a clear improvement over the prior two-block abstraction.
- **Structural fracture:** yes — unchanged from v0.2's validated technique (a real knockout gap, not a stroke on top).
- **Restrained cyan accent:** yes — Fracture Cyan appears only on the tapering shard tip, never as a fill, consistent with Brand Bible Section 4's "never a large fill, never decorative" rule.
- **Clean geometry:** yes — every edge in the mass is a straight line; no curves, no gradients, no illustrative shading were introduced.
- **Original implementation, not a trace:** the silhouette's specific proportions, vertex coordinates, and construction (four unioned polygons) are this draft's own — built and computationally verified independently, informed by the reference board's direction rather than copied from it.

---

## Status

**VECTOR DRAFT v0.3 — AWAITING FINAL QA REVIEW**

This is a refinement of the approved Weighted Line concept's execution, not a new concept — the underlying mechanism (a contained mass with a fracture that escapes it) is unchanged from every prior stage. The two items still open from v0.2 (mass-area/clear-space proportions were superseded by this redesign and should be re-measured if that check still matters; the v0.1 kink-visibility-at-28px note remains accepted as expected degradation) are noted, not silently dropped. Nothing here is marked Approved or Locked.

---

### Changelog
`[v0.3 — 2026-07-07] Concept refinement pass, informed by a founder-provided concept board used as creative direction only (not traced). Rebuilt the mass silhouette from v0.1/v0.2's abstract two-block shape into a recognizable stylized anvil (horn, face, waist, flared base) using four straight-edged unioned polygons -- still Concept 5, "Weighted Line," not a new concept. Recomputed the fracture's entry/kink/exit geometry fresh against the new silhouette using the v0.2-validated knockout-gap-plus-tapering-shard technique (not a new technique); verified computationally that the chosen exit point actually reaches the base's edge before building the file, after an initial attempt was found to exit prematurely through the body. Used the Brand Bible's actual Locked color values throughout -- explicitly did not adopt two of the three swatch values shown on the reference board ("Deep Forge" #0B0F14 and "Mythic White" #FFFFFF), which do not match Void Black #0A0B0D and Authority White #F5F7FA. Did not implement the board's "Variant A/B/C" exploration as new options, since the instruction was to refine the one approved concept, not reopen the Concept Review. Re-verified the v0.2 lockup canvas fix against the new icon shape by render rather than assuming it would still hold. All four files re-tested at large scale and true 28x28px. No Locked brand element redefined beyond the mass silhouette's own execution, which is explicitly in scope for this refinement pass. Status: Vector Draft v0.3 -- Awaiting Final QA Review, not marked Approved.`
