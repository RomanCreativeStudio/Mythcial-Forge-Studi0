# BRA-0001 — Vector Draft Review Package
## v0.10 — Reference-Trace Geometry Rebuild

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Built, rendered, and tested against the same rigorous methodology used for every prior pass. **This is a competing alternative candidate to v0.9, not a refinement of it — see "A Contradiction, Flagged" below before treating this as the default path forward.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md`, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.9.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.9_Creative_Confirmation.md`.
**Trigger:** "BRA-0001 FINAL LOGO PRODUCTION CONVERSION" instruction (submitted with a photorealistic concept-board reference image, twice): use the reference image as "the single source of truth," "match it first, apply Brand Bible rules second," preserve the reference's silhouette, fracture placement/structure, and detached shard "exactly," while converting only the *execution* to clean flat-vector, removing the silver/chrome material appearance, keeping Fracture Cyan as the accent, and maintaining Space Grotesk.

---

## A Contradiction, Flagged

The turn immediately prior to this one confirmed v0.9's existing geometry (angular horn, single-diagonal fracture) as correct and said to "continue development as a refinement of BRA-0001 v0.9 toward final approval." This turn's instruction asks for something geometrically different: "preserve exactly" the reference image's curved horn, rounded arch cutout, and jagged multi-point fracture, and explicitly says "do not change the fracture shape" — referring to the reference's shape, not v0.9's.

These two instructions cannot both be honored as "refine v0.9." I followed the more recent, more specific, more emphatic instruction literally: trace the reference's actual forms into flat vector. That is what this document describes. It is a **new, second candidate**, not a v0.9 update — v0.9 is untouched and still stands as its own fully-tested, Founder-confirmed candidate. Founder should treat this as "candidate B" alongside v0.9's "candidate A," not as v0.9's successor, unless and until told otherwise.

---

## What Was Built

**Mass silhouette (new):** Horn rebuilt as a single smooth curve (`C` bezier) from a tapered tip up to the face's top-left corner, replacing v0.1–v0.9's angular, multi-segment horn. A rounded arch cutout was added to the base's bottom edge (a traditional anvil detail present in the reference image, absent from every prior version) — built as a second bezier curve indenting the bottom boundary, not a separate hole (it's part of the mass's own single outer path, since it's a boundary notch, not enclosed material). Face, waist, and base flare are unchanged in spirit from v0.9 (flat face table, tapering waist, flared base) but every coordinate was rebuilt from scratch to accommodate the new horn and base.

**Fracture (new):** Replaced v0.9's single diagonal with a jagged, 4-segment centerline (entry on the top face edge, three zigzag direction changes, exit on the base's bottom-right edge) — matching the reference's lightning-bolt-like crack rather than v0.9's one clean stroke. Built with the same knocked-out-gap technique used since v0.6: a second subpath inside the mass's own `<path>` element, combined via `fill-rule="evenodd"`, tapering from a 2.4-unit gap at entry to a 6.6-unit gap at exit. **Every one of the 4 segments was verified by ray-segment intersection against a polyline approximation of the mass boundary before the file was built**, confirming each segment stays inside solid material for its full length with zero premature exits — the same computational check that caught a real bug in v0.8's planning stage was run again here and found this path clean on the first geometry attempt.

**Shard (relocated, not redesigned):** Same detachment + rotation + steel-white-fill-with-cyan-hot-edge technique validated in v0.7–v0.9, recomputed for the new exit point and exit angle (38.7°, vs. v0.9's 50.3°), with the same ~8.5° tumble offset and a ~3-unit gap so it reads as broken free rather than still attached. **One shard, not several** — the reference shows a primary shard plus multiple smaller floating chip fragments; I built only the primary shard. Scattered secondary fragments read as debris/particle effect, which both the standing "do not adopt: particle effects" rule (from the prior confirmed decision) and this turn's own "do not add sparks, do not add energy effects" rule argue against. This is a deliberate, disclosed scope-narrowing, not an oversight.

**Technical compliance — verified, not assumed:** `grep -inE "gradient|filter|feGaussianBlur|feDropShadow|feBlend|blur|shadow"` and a second pass for `chrome|3d|particle|spark|glow` across all 6 deliverable files: zero matches (the only hits were the word "shadows" and "--" inside my own explanatory comments, not markup). Space Grotesk confirmed declared on both text elements in all three lockup files. Void Black (#0A0B0D), Authority White (#F5F7FA), and Fracture Cyan (#00E5FF) are the only fill colors used anywhere — no new colors introduced.

---

## Test Results — Measured, Not Assumed

| Check | Result |
|---|---|
| XML validity | All 6 files parse clean (two files hit the project's recurring `--`-in-comment bug on first write; caught and fixed the same way as every prior occurrence, re-verified clean) |
| Effects/material grep | Zero gradients, filters, blurs, shadows, chrome, 3D, particle, spark, or glow keywords in any markup across all 6 files |
| 64px render | Pass — anvil, jagged fracture, and shard all read cleanly |
| 28px render | Pass — fracture is a legible zigzag, shard and cyan edge both visible |
| **16px render** | **Fails — the fracture collapses into ambiguous visual noise, and the silhouette itself is harder to parse as an anvil than v0.9's was at the same size.** See "The 16px Finding" below. |
| 32px favicon render | Pass — comparable to v0.9's 32px+ profile |
| Monochrome (single ink, 28px) | Pass — fracture and shard remain legible through geometry alone, no color dependency |
| YouTube avatar circular crop (800×800) | Same top-right corner clipping found in every version since v0.5 — confirmed, again, to be a property of the mass's asymmetric bounding box relative to its own icon frame, not of this pass's fracture or horn changes. Unchanged conclusion: correctly scoped to a future derived avatar asset with extra padding, not a defect in this file. |
| Embroidery minimum width (50mm patch, 1 unit = 0.5mm) | Narrowest gap 2.4 units = **1.2mm**, below the ~1.5mm safe minimum. Identical finding, same magnitude, as v0.7/v0.8/v0.9. Unchanged conclusion: correctly scoped to a future embroidery-specific digitized export. |

---

## The 16px Finding — A Real, Avoidable Trade-off

This is the one finding in this pass that is **not** a carried-forward, unavoidable constraint (unlike the avatar-crop and embroidery findings above, which are properties of the mass geometry and physical medium respectively, and would exist regardless of fracture design). This one is different: it is a **direct, measured consequence of literally matching the reference's jagged fracture**, and it is worse than a problem this project already solved once.

Context: the v0.8 Founder QA Audit identified 16px legibility as v0.8's one hard, measurable failure, caused by its 2-segment (one-kink) fracture. v0.9 was built specifically to fix this — the Founder Direction Override that produced v0.9 replaced the multi-segment fracture with a single diagonal, and it worked: v0.9's 16px render was directly re-tested and confirmed improved.

This pass's fracture has 4 segments — twice the complexity of the path that already failed at 16px in v0.8. Rendered at true 16×16px (not estimated, not scaled down from a larger render), the result is a fracture that reads as noise, not a crack, and a silhouette that is harder to parse than v0.9's was at the same size. This is the expected, predictable outcome given the v0.8 precedent, and the render confirms it rather than assumes it.

This is a genuine conflict between two things this brief asks for at once: "match the reference's fracture shape exactly" and this project's own established small-size production standard (which the reference itself, being a static concept board, was never tested against). I have not silently resolved this either direction. The master file in this delivery carries the literal jagged fracture, per this turn's explicit "match it first" instruction. The 16px cost is real and is flagged here, in the file-level comments, and in my direct summary to the Founder — not buried.

**Recommendation on this specific point:** if this jagged-fracture direction is confirmed as the path forward, route 16px/favicon-scale contexts to a simplified derived asset (a 2-point or single-diagonal fracture reduction, applied only at that export size) rather than trying to force the full jagged path to survive 16px — the same "master serves full contexts, small derived assets serve small contexts" pattern already established for the avatar crop.

---

## Recommendation

**Do not treat this as replacing v0.9.** Present both to the Founder as two live candidates:

- **v0.9** — angular horn, single-diagonal fracture, one shard. Passes 16px cleanly. A refinement of the original flat-vector design language built up since v0.1.
- **v0.10 (this file)** — curved horn, rounded arch cutout, jagged 4-point fracture, one shard (chip fragments deliberately omitted as particle-effect risk). Traces the reference image's literal forms. Fails 16px on measured evidence.

Both are fully flat-vector, fully Locked-color-compliant, fully Space-Grotesk-compliant, and contain zero gradients/chrome/glow/shadows/3D/particles/sparks. The choice between them is a **design-direction decision, not a compliance decision** — both comply. I am not recommending one over the other; that choice sits with the Founder, given the immediately preceding instruction confirmed v0.9 and this instruction asks for something else.

---

### Changelog
`[v0.10 — 2026-07-08] Built as a second, competing candidate per the "BRA-0001 FINAL LOGO PRODUCTION CONVERSION" instruction, which asked for a literal trace of the submitted reference image's silhouette/fracture/shard converted to flat vector -- a different request from the immediately prior turn's "refine v0.9 toward final approval," and flagged as such rather than silently merged. Rebuilt the mass silhouette with a curved (bezier) horn and a new rounded arch cutout in the base, both present in the reference and absent from v0.1-v0.9. Rebuilt the fracture as a jagged 4-segment path (vs. v0.9's single diagonal), using the established knocked-out-gap fill-rule="evenodd" technique with tapering 2.4-to-6.6-unit gap width; every segment verified by ray-segment intersection against the mass boundary before construction, zero premature exits found. Relocated (not redesigned) the shard using the v0.7-v0.9 detach/rotate/hot-edge technique at the new exit point and angle. Deliberately built one shard, not the reference's multiple floating chip fragments, as scattered debris reads as a particle effect prohibited by both the standing and current briefs. Verified zero gradients/filters/blurs/shadows/chrome/3D/particle/spark/glow markup across all 6 deliverable files by direct grep. Tested 64px (pass), 28px (pass), 16px (fails -- fracture collapses to noise, a measured and predictable regression given the v0.8 precedent this project already solved once by simplifying to a single diagonal), 32px favicon (pass), monochrome (pass), avatar circular crop (same pre-existing top-right clipping as every version since v0.5, unchanged conclusion), embroidery (1.2mm narrowest at 50mm patch, same finding as v0.7-v0.9, unchanged conclusion). Produced all 6 requested deliverables: primary white (transparent), primary dark, primary light, icon-only (transparent), icon monochrome, and the icon-dark file as the final SVG master asset. Recommendation: present as a second live candidate alongside v0.9, not as its replacement -- the 16px finding is a real, disclosed trade-off between literal reference fidelity and this project's own established small-size legibility standard, and the choice between v0.9 and v0.10 is a design-direction decision for the Founder, not a compliance decision, since both fully comply with every Locked Brand Bible rule.`
