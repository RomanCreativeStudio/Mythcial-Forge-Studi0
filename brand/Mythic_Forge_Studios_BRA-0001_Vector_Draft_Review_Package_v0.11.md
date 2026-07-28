# BRA-0001 — Vector Draft Review Package
## v0.11 — Second Reference Image, Double-Horn Geometry Rebuild

> **STATUS: SUPERSEDED — 2026-07-08.** Superseded by v0.12 (a precision refinement of this same trace), which was then approved by the Founder as the official BRA-0001 logo — see `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md` for the Approval record and `brand/assets/logos/mfs-logo-icon-dark_v1.0.svg` for the Locked asset. Retained as historical record.

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Built, rendered, and tested against the same rigorous methodology used for every prior pass. **This is a third candidate alongside v0.9 and v0.10, tracing a newly submitted, explicitly "approved" reference image that shows a different composition from the one v0.10 traced.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md`, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.9.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.10.md`.
**Trigger:** A new instruction ("BRA-0001 CONCEPT RECREATION — PHASE 1") submitted a single clean concept image described as "the definitive BRA-0001 logo concept" and asked for a near-1:1 photorealistic recreation. No image-generation tool exists in this environment, so a best-effort SVG gradient/glow approximation was built and shown instead, with that limitation disclosed directly. The follow-up instruction then said explicitly: "do not continue iterating the photorealistic SVG approximation... treat that image as the visual source of truth... manually redraw the logo as a production-quality SVG by matching the approved reference image as closely as possible... ignore the photorealistic rendering effects... the deliverable is a clean, scalable SVG that faithfully matches the approved concept's shapes." This document is that redraw.

---

## A Third Candidate, Not a Merge

This reference image shows a **different composition** from the one v0.10 traced:

| Element | v0.10's reference | v0.11's reference (this pass) |
|---|---|---|
| Horns | One curved horn (left only) | Two horns, left and right (symmetric double-horn) |
| Base | Rounded arch cutout | Two separate feet with a true negative-space gap between them |
| Fracture | Enters top face, exits bottom-right edge | Originates from a shallow notch at top-center, runs straight down through the waist into the base plate |
| Shard | Falls away from the bottom-right exit | Floats above the top notch, where the crack originates |

Both source images were presented as reference material for the same asset (BRA-0001), but they are not the same design. I traced this one faithfully rather than merging it with v0.10's geometry, per the explicit instruction to treat this image as the sole source of truth for shape. v0.9 and v0.10 are untouched. There are now three live candidates; reconciling them into one is a Founder decision, not something I resolved by picking or blending.

---

## What Was Built

**Mass silhouette:** Built with the established multi-shape-union technique (safer than one long boundary walk): two horn wedges (left and right, each a simple 4-point polygon) deliberately overlapping into the central body/waist/base-plate shape, plus two separate rectangular feet beneath the base plate with a genuine gap between them — matching the reference's twin-footed base rather than v0.9/v0.10's single continuous base. The central body/waist/base-plate is one path with a shallow notch cut into its top edge, where the fracture originates.

**Fracture:** A jagged 5-segment centerline from the top-center notch down through the waist into the base plate, built with the same knocked-out-gap `fill-rule="evenodd"` technique used since v0.6, tapering from a 2.0-unit gap at entry to 8.0 at the base. **Every one of the 5 segments was verified by ray-segment intersection against the mass boundary before construction** — zero premature exits found on the first geometry attempt (full verification output in the build log).

**Shard:** A single solid quadrilateral floating above the top notch — not falling from a lower exit point, since this reference's composition places the break at the top, not the bottom-right. Steel fill with a cyan hot-edge sliver on the side facing the crack, same construction principle as v0.7–v0.10, repositioned to match this reference's actual composition rather than reused wholesale.

**Technical compliance — verified, not assumed:** `grep -inE "gradient|filter|feGaussianBlur|feDropShadow|feBlend|blur|shadow|chrome|particle|spark|glow"` across all 6 deliverable files: zero matches outside my own explanatory comments. Space Grotesk confirmed declared on both text elements in all three lockup files. Only Void Black, Authority White, and Fracture Cyan used.

---

## Test Results — Measured, Not Assumed

| Check | Result |
|---|---|
| XML validity | All 6 files parse clean |
| Effects/material grep | Zero gradients, filters, blurs, shadows, chrome, particle, spark, or glow keywords in any markup |
| 64px render | Pass — strong, clean silhouette; crack and shard both read clearly |
| 28px render | Pass — the wide double-horn silhouette is unusually legible at this size; crack reads as a visible jagged mark |
| **16px render** | **Silhouette recognition holds better than v0.10's** — the wide horn shape is a strong enough signature that the icon still reads as "anvil-like" at 16px even though the crack's jagged internal detail collapses toward noise, the same fracture-detail limitation found in every jagged multi-segment path since v0.8. This is a genuinely different, more favorable result than v0.10's 16px finding, and it's specific to this silhouette's proportions, not a general fix. |
| Monochrome (single ink, 28px) | Pass — fracture and shard remain fully legible through geometry alone |
| **YouTube avatar circular crop (800×800)** | **New, more severe finding.** Both horn tips are clipped by the circular crop, not just a corner as in every prior version. This silhouette is roughly 96 units wide by 77 tall — a much more landscape-oriented shape than v0.9/v0.10's (75×62) — and a wide/short mark does not fit a circular or square frame without either cropping the horns or shrinking the mark until most of the frame is empty. This is a direct, measured consequence of this reference's composition, not an oversight in construction. |
| Embroidery minimum width (50mm patch, 1 unit = 0.5mm) | Narrowest gap 2.0 units = **1.0mm**, below the ~1.5mm safe minimum, and narrower than every prior version's finding (v0.7–v0.10 all measured 1.2–1.3mm). Same conclusion: correctly scoped to a future embroidery-specific digitized export, but worth noting this composition's narrow entry gap is a slightly tighter constraint than before. |

---

## Recommendation

**Present as a third live candidate, not a replacement for v0.9 or v0.10.** All three are fully flat-vector, fully Locked-color-compliant, fully Space-Grotesk-compliant, with zero gradients/chrome/glow/shadows/3D/particles/sparks. The differences are structural, not quality-related:

- **v0.9** — single curved-to-angular horn, single diagonal fracture, one shard falling from the base. Best 16px legibility of the crack itself. Best fit for circular/square contexts (narrowest, tallest silhouette of the three).
- **v0.10** — curved horn, arch-cutout base, jagged fracture, one shard falling from the base. Traces the first reference image.
- **v0.11 (this file)** — double horn, twin-footed base, jagged fracture, one shard floating above the top notch. Traces the second, "approved" reference image. Strongest large/medium-size silhouette recognition of the three, but the widest aspect ratio and the most severe circular-crop clipping.

I am not recommending one over the others. The three reference images given across this project describe three different anvils, and only the Founder can decide which one — or whether some future synthesis — becomes the actual BRA-0001 master.

---

### Changelog
`[v0.11 — 2026-07-08] Built as a third candidate per an explicit "the reference image is now the source of truth" instruction, tracing a newly submitted, single clean concept image distinct from the multi-panel photorealistic board used for v0.10. A prior attempt at a photorealistic SVG gradient/glow approximation of that same new image was explicitly stopped by the Founder in favor of a clean geometry-only redraw. Built the silhouette with the multi-shape-union technique: two horn wedges (left and right, double-horn composition, unlike v0.9/v0.10's single horn) overlapping a central body/waist/base-plate path, plus two separate feet with a true negative-space gap (unlike v0.9's angular base or v0.10's arch cutout). Built a jagged 5-segment fracture originating from a top-center notch and running into the base plate, using the established knocked-out-gap fill-rule="evenodd" technique; every segment verified by ray-segment intersection against the mass boundary before construction, zero premature exits found. Built a single solid shard floating above the top notch, matching this reference's composition (break at the top, not the base). Verified zero gradients/filters/blurs/shadows/chrome/particle/spark/glow markup by grep across all 6 deliverables; Space Grotesk and Locked colors unchanged. Tested 64px (pass), 28px (pass, strong silhouette read), 16px (silhouette recognition holds better than v0.10 due to the wide horn shape, though crack detail still collapses toward noise -- a genuinely more favorable, measured result specific to this silhouette's proportions), monochrome (pass), avatar circular crop (new, more severe finding: both horn tips clipped, not just a corner, a direct consequence of this composition's wide/short aspect ratio), embroidery (1.0mm narrowest at 50mm patch, tighter than every prior version's 1.2-1.3mm finding, same future-export scoping). No Locked brand element redefined. Recommendation: present as a third live candidate alongside v0.9 and v0.10 -- the three submitted reference images describe three structurally different anvils, and reconciling them is a Founder decision, not one resolved by this pass.`
