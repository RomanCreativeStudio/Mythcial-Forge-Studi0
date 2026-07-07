# BRA-0001 — Vector Draft Review Package
## v0.2 — Refinement Pass

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Refinement pass complete, rendered, and re-tested. **Not approved. Not locked. Not registered.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` Section 3–4, `brand/Mythic_Forge_Studios_YouTube_Brand_Kit_v1.0.md` Section 2, `brand/Mythic_Forge_Studios_Brand_Asset_Production_Guide_v1.0.md` Section 3, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.1.md` (this document's baseline — every item below is a refinement against that package's findings, not a new design).
**Scope discipline:** this is a refinement pass against the seven review items given for v0.2. **No new concept was created; the approved Concept 5 ("Weighted Line") is unchanged.** The mass silhouette's coordinates, overall proportions, position, and the fracture's centerline (entry point, 25°/35° angles, single kink, exit point) are all pixel-identical to v0.1 — only the fracture's *construction technique* and the *primary lockup canvas* changed.

---

## What Changed — Summary

v0.1 rendered the fracture as a colored stroke drawn on top of the solid mass. v0.2 replaces that with a **knocked-out gap cut through the mass itself** (a single path, two subpaths, `fill-rule="evenodd"`) plus a **solid tapering shard** occupying the space where material has broken free — sharing its base edge exactly with the gap's exit opening. This one construction change is what resolves five of the seven requested review items simultaneously (1, 2, 3, 4, 5) — they were, on inspection, the same underlying problem viewed from different angles. Items 6 and 7 were addressed separately.

---

## Updated SVG Drafts (v0.2)

| File | Change from v0.1 |
|---|---|
| `mfs-logo-icon-dark_v0.2.svg` | Fracture rebuilt as knockout gap + tapering shard (was: overlay stroke) |
| `mfs-logo-icon-monochrome_v0.2.svg` | Same technique change — this is the file that fixes the v0.1 failure |
| `mfs-logo-primary-dark_v0.2.svg` | Icon updated to v0.2 technique; viewBox widened 380→520; wordmark 34px→30px to fix clipping |
| `mfs-logo-primary-light_v0.2.svg` | Same as primary-dark, light color mode |

All four validated as well-formed XML and re-rendered in a real browser engine, including a true 28×28px raster test for both icon-only files, exactly as v0.1 was tested — no finding below is estimated.

---

## Before/After Reasoning, By Review Item

### 1. Fracture feels structurally integrated, not an overlay

**Before (v0.1):** the fracture was a stroked line drawn on top of the filled mass — visually, a colored line sitting *on* a shape, the same relationship a sticker has to the surface it's placed on.

**After (v0.2):** the fracture is a literal absence of material — a hole cut through the mass path using `fill-rule="evenodd"`, so the background shows through exactly where the crack runs. This is no longer paint on a surface; it's the surface itself parted. Confirmed by render: the dark version now shows the Void Black background visibly through the white mass along the crack's path, which was structurally impossible with the old overlay-stroke technique.

### 2. Fracture communicates creation, not damage

**Before:** the escape portion was a uniform-width stroke continuing past the mass edge — visually just "the same line, still going," which reads as an extension, not an event.

**After:** the escape is a **solid tapering shard**, wide where it meets the gap's exit opening and narrowing to a point at its tip — the same triangular base as the gap it emerged from. This reads as a distinct piece of material that separated and continues to exist on its own, which is a materially different visual claim than a scratch: something was created (a new, separate shape) rather than something merely being marked (a line across a surface).

### 3. Escape line feels intentional but does not dominate

**Before:** escape length was 10 units (14.3% of the total fracture path), rendered at uniform stroke weight — equal visual weight throughout its length.

**After:** shortened to 8 units — still comfortably above the 7.5-unit "unambiguously intentional" floor set in the Stage 3 specification — and rendered as a taper rather than a uniform stroke, so its visual weight actively *decreases* toward the tip instead of staying constant. A tapering shape reads as trailing off, not competing for attention with the mass.

### 4. Monochrome legibility improved, Brand Bible preserved

**Before:** the fracture was completely invisible in monochrome — a same-color stroke on a same-color fill has zero contrast, confirmed by direct render in the v0.1 package.

**After:** the knockout technique needs no color information at all — the gap is a geometric absence, visible as the plain background showing through, regardless of what color the mass is. Rendered in monochrome at both large size and true 28px: the crack and the escape shard's silhouette are both clearly visible. The Brand Bible's Monochrome rule ("single-color rendering, pure Void Black or pure Authority White") is unchanged and fully honored — no second color, no gradient, nothing added to satisfy legibility; the fix is purely geometric.

### 5. Icon remains recognizable at 28px

Re-rendered and inspected at true 28×28px (not estimated) for both the Dark and Monochrome Icon Only files. Both hold up — and the crack is, if anything, **more visible at small size than v0.1's approach was**, because a dark gap against a light mass (or vice versa) is inherently higher-contrast at low resolution than a thin colored stroke was. The single kink remains imperceptible at this size, compressing to a visually straight diagonal — this was already identified in the v0.1 package as an expected, acceptable degradation, not a defect, and remains true here.

### 6. Layout/clipping issues in horizontal lockups

**Before:** "MYTHIC FORGE" was cut off at the 380-unit-wide viewBox's right edge in both color modes.

**After:** viewBox widened to 520 units and the wordmark reduced from 34px to 30px. Re-rendered at full resolution and confirmed directly (not estimated, correcting the exact mistake that caused the v0.1 clipping in the first place): "MYTHIC FORGE" now displays in full in both Dark and Light versions, with visible margin remaining before the canvas edge.

### 7. Locked brand decisions and the approved concept preserved

Verified directly against the files: no hex value, typeface, studio name, abbreviation, or tagline was touched anywhere in this pass. The mass's coordinates (`M30,26 L32,24 L68,24...`) are character-for-character identical to v0.1's outer boundary. The fracture's centerline (entry `(30,37.6)`, kink `(61.2,52.2)`, mass-exit `(82,66.7)`) and its 25°/35° angles are unchanged — only how that centerline is *rendered* (gap + shard vs. overlaid stroke) changed. Concept 5's defining idea — a contained mass with something visibly escaping it — is intact and, per the findings above, more legible than in v0.1, not altered.

---

## QA Summary — v0.1 Issues, Resolved or Not

| v0.1 Issue | Status in v0.2 |
|---|---|
| 1. Monochrome fracture fully invisible against the mass | **RESOLVED** — confirmed by render at large size and true 28px |
| 2. Mass area ~25% of artboard vs. ~55–58% estimated in the Stage 3 spec | **NOT ADDRESSED** — out of scope for this pass; the seven requested review items did not include mass proportions, and changing them would touch the silhouette itself rather than the fracture's construction. Remains open for a future pass or a founder decision on which number (built or spec) should change. |
| 3. Primary lockup wordmark clipped | **RESOLVED** — confirmed by render in both color modes |
| 4. Fracture's single kink imperceptible at 28px | **UNCHANGED — still true, still not a defect.** Already categorized in the v0.1 package as expected, acceptable degradation, not something requiring a fix; not part of the seven items requested for this pass either. |

---

## Status

**VECTOR DRAFT v0.2 — AWAITING FINAL QA REVIEW**

Five of the seven requested refinements were resolved through one underlying construction change (overlay stroke → knockout gap + tapering shard); the remaining two (lockup clipping, and preserving Locked elements) were verified independently. One issue from the original v0.1 findings (mass-area discrepancy) remains open by design, since it fell outside this pass's explicit scope — it is not silently dropped, it is flagged here for a deliberate future decision. This package does not mark BRA-0001 Approved or Locked.

---

### Changelog
`[v0.2 — 2026-07-07] Refinement pass against the seven requested review items, all addressed against v0.1's exact same approved geometry (no redesign, no new concept). Rebuilt the fracture across all four files from an overlay stroke to a knockout gap (evenodd fill-rule) cut through the solid mass plus a solid tapering escape shard sharing the gap's exit edge -- this single technique change directly resolved items 1 (structural integration), 2 (creation vs. damage), 3 (escape restraint), 4 (monochrome legibility), and 5 (28px recognizability, re-confirmed by render, actually improved over v0.1). Widened the primary lockup viewBox 380->520 and reduced the wordmark to 30px, resolving item 6 (clipping), confirmed by direct render in both color modes. Verified item 7 (Locked elements and the approved concept) directly against the files -- no color, typography, naming, or mass-silhouette coordinate was changed. QA summary against the four v0.1-identified issues: two resolved (monochrome, clipping), one explicitly out of scope this pass and left open (mass-area discrepancy), one unchanged and already accepted as non-defective (kink imperceptible at 28px). Status: Vector Draft v0.2 -- Awaiting Final QA Review, not marked Approved.`
