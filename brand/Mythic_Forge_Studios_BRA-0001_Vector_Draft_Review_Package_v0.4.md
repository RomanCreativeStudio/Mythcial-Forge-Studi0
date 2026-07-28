# BRA-0001 — Vector Draft Review Package
## v0.4 — Quality Refinement Pass

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Silhouette strengthened, rendered, and re-tested. **Not approved. Not locked. Not registered.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` Section 3–4, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.3.md` (this package's baseline).
**Trigger for this pass:** an explicit instruction not to optimize for matching the reference concept board, but for the strongest original mark — using the board only as inspiration for silhouette clarity, while preserving Concept 5 and every Locked Brand Bible decision.

---

## Approach

This pass is a critique of v0.3 **on its own terms**, independent of how closely it resembled the reference board. The board's job was already done in v0.3 (it pushed the silhouette from an abstract two-block shape toward a recognizable anvil); this pass asks whether that result is actually the *strongest* mark Mythic Forge Studios could have, not whether it matches anything external.

**Honest critique of v0.3, looking at its own render:**
1. **The horn was a thin knife-point.** Tapering to a true point reads as fragile, not forged — a strange quality for a mark whose whole meaning is "made by hand, deliberately." It also loses crispness fastest at small render sizes, the opposite of what a horn should do in an icon meant to survive down to 28px.
2. **The face-to-body shoulder was a wide, flat 16-unit ledge.** In the actual render, this read closer to a flag or an arrow-tail than an anvil's table overhang — a silhouette-clarity problem, not a taste preference.
3. **The composition sat off-center** in its bounding frame, an avoidable imbalance.

None of this is about resembling the board more or less — it's a direct critique of v0.3's own silhouette quality.

---

## What Changed From v0.3

**Horn:** rebuilt as a blunted trapezoid instead of a knife-point triangle — flat 3-unit tip instead of tapering to nothing, and a taller attachment (17 units instead of 14) so it reads as a solid, confident mass rather than a sliver. This is a targeted fix to the recognizability *and* small-size robustness problem identified above, not a stylistic change.

**Shoulder:** shortened the flat ledge between the face and the body from 16 units to 8 — the anvil's characteristic overhang is still present and still reads correctly, but no longer dominates the silhouette's right side or competes visually with the horn's leftward mass.

**Composition:** recentered — margins are now close to balanced on all four sides rather than the mark sitting visibly left-of-center.

**Fracture:** recomputed fresh for the refined silhouette using the same validated knockout-gap-plus-tapering-shard technique (unchanged mechanism, third time this exact technique has been re-verified against a new mass shape). Entry `(45,25.5)`, kink `(48,48)`, one deflection to a 36° exit angle, landing on the base's right edge — confirmed computationally against every boundary edge before the file was built.

**A real construction bug was caught and fixed during this pass, not shipped:** an initial attempt to blunt the horn (extending the v0.3 triangle's tip into a flat edge by simply adding two points) produced a self-intersecting "bowtie" shape at the tip — visible immediately in the test render, not caught by the math alone. It was fixed by rebuilding the horn as its own simple, independently-valid quadrilateral (in the same multi-shape-union technique validated in v0.3) rather than patching the single-boundary-walk version. This is exactly the kind of error the render-and-inspect step exists to catch, and it was caught before reaching the delivered files.

---

## Draft Assets (v0.4)

| File | Content |
|---|---|
| `mfs-logo-icon-dark_v0.4.svg` | Refined anvil icon, Dark Version |
| `mfs-logo-icon-monochrome_v0.4.svg` | Refined anvil icon, Monochrome |
| `mfs-logo-primary-dark_v0.4.svg` | Icon + wordmark lockup, Dark Version |
| `mfs-logo-primary-light_v0.4.svg` | Icon + wordmark lockup, Light Version |

All four validated as well-formed XML and rendered in a real browser engine; both icon-only files re-tested at true 28×28px; both lockups re-verified for wordmark clipping against the changed icon geometry, not assumed to still be fine because v0.2/v0.3's canvas fix worked before.

---

## Test Results

**Large scale:** the horn now reads as a solid, deliberate mass rather than a thin point; the shoulder transition is subtler and no longer competes with the horn for attention; the fracture and its tapering shard are unchanged in technique and remain clean, with no stray fill artifacts from the knockout geometry.

**Monochrome:** re-tested — the gap remains fully legible with zero color contrast, consistent with every prior pass.

**28px:** re-tested at true small size. The thicker horn is a specific, measurable improvement here — a blunted 3-unit-wide tip survives anti-aliasing at 28px more reliably than v0.3's point did. The fracture and shard remain visible.

**Primary lockups:** re-rendered at the existing 520-wide/30px-wordmark canvas — still no clipping, confirmed by render rather than assumed from the prior fix.

---

## Design Intent Check (Repeated From v0.3, Re-Verified)

- **Recognizable stylized anvil:** yes, and stronger than v0.3 — the horn specifically reads more confidently.
- **Structural fracture:** yes — unchanged, validated technique.
- **Restrained cyan accent:** yes — same rule, same application, only the shard's exact position changed with the geometry.
- **Clean geometry:** yes — every edge remains a straight line; the horn fix used a proper simple polygon, not a curve.
- **Strongest original mark, not a board match:** this pass explicitly did not reference the board again — every change here was justified against v0.3's own render, independent of the reference image.

---

## Status

**VECTOR DRAFT v0.4 — AWAITING FINAL QA REVIEW**

Still Concept 5, "Weighted Line" — the mechanism (a contained mass with a fracture that escapes it) is unchanged across all four vector passes (v0.1–v0.4); only the mass's execution has been refined, each time for a specific, named reason. Nothing here is marked Approved or Locked.

---

### Changelog
`[v0.4 — 2026-07-07] Quality refinement pass, explicitly independent of the reference concept board -- optimized v0.3's own silhouette on its merits rather than for resemblance to anything external. Rebuilt the horn from a knife-point triangle into a blunted, taller trapezoid (fixes both a recognizability weakness and a small-size robustness weakness); shortened the face-to-body shoulder ledge from 16 to 8 units (fixed a flag/arrow-like silhouette read); recentered the composition. Recomputed the fracture's entry/kink/exit fresh against the refined silhouette using the same validated knockout-gap-plus-tapering-shard technique, verified computationally before building. Caught and fixed a self-intersecting "bowtie" construction bug in an initial horn-blunting attempt during test rendering, before it reached the delivered files -- rebuilt using the same safe multi-shape-union technique validated in v0.3 instead. All four files re-validated as well-formed XML, re-rendered at large scale, both icon files re-tested at true 28x28px, both lockups re-verified for clipping against the new geometry. No Locked brand element redefined; still Concept 5, not a new concept. Status: Vector Draft v0.4 -- Awaiting Final QA Review, not marked Approved.`
