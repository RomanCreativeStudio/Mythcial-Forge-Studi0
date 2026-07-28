# BRA-0001 — Vector Draft Review Package
## v0.9 — Single Diagonal Fracture (Founder Direction Override)

> **STATUS: SUPERSEDED — 2026-07-08.** The Founder approved a different candidate (traced from a separate reference image) as the official BRA-0001 logo — see `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md` for the Approval record and `brand/assets/logos/mfs-logo-icon-dark_v1.0.svg` for the Locked asset. This document and its geometry are retained as historical record per this project's archive-don't-delete discipline; nothing below reflects the current brand identity.

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Fracture replaced per Founder Direction Override, rendered, tested, and objectively compared against v0.8. **Recommendation: adopt v0.9 as the new BRA-0001 candidate, superseding v0.8.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md`, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.8.md` (superseded by this comparison, not deleted), Founder QA Audit (previous turn — v0.8's own findings are the baseline this version is measured against).
**Scope discipline:** the anvil silhouette, color, typography, and layout are unchanged. Only the fracture path (and, as its direct consequence, the shard's position) was replaced, per explicit Founder instruction.

---

## What Changed

The fracture is now **one continuous straight diagonal** — no kinks, no direction changes — from a top-left entry point `(28, 25.5)` to a bottom-right exit point `(70, 76)` on the base's actual bottom edge, at a 50.3° angle. Verified computationally before building: the straight path was checked against every edge of the mass polygon to confirm it stays inside solid material for its entire length (it does — no premature exit through the waist, which was a real risk given the anvil's narrow midsection and was the reason v0.6–v0.8 all used multi-segment paths instead).

Gap tapers from 1.3 half-width at the entry to 3.4 at the exit — same narrow-to-wide logic as prior versions, same rationale (compression at the start, separation at the end), just applied to a single segment instead of two or three. The shard falls beyond the new exit point using the same rotate-plus-steel-white-with-cyan-edge technique validated in v0.7 and reused in v0.8 — not a new technique, relocated.

---

## Objective Comparison — v0.8 vs. v0.9

### Recognition
**v0.9 wins.** A single straight diagonal is parsed faster than a path with two direction changes — this is a basic property of visual complexity, not a style preference, and it's borne out directly in the small-size renders below. Both versions read as an anvil equally well (silhouette is identical); the difference is entirely in how quickly the fracture itself is parsed.

### Storytelling
**A genuine trade-off, not a clean win either way.** v0.8's two-kink path was built specifically to stage a "compression, then release" physical narrative across the object. v0.9's single stroke tells a simpler story — one decisive break, not a multi-stage structural failure. This is a real reduction in narrative granularity. But it is also **exactly what the Founder Direction asked for** — "simplicity and power" over the multi-segment approach — so measured against the actual goal set for this pass rather than against v0.8's own goals, v0.9 succeeds on its own terms. Recorded honestly as a trade, not inflated into an unqualified win.

### Scalability
**v0.9 wins, with direct measured evidence.** Both versions were rendered at true 16×16px. v0.8's fracture, with its two direction changes, degrades into ambiguous internal noise at this size — the crack is present but not clearly parseable as a single feature. v0.9's fracture remains a legible, continuous diagonal line at the same resolution. This is the same criterion the immediately prior Founder QA Audit flagged as v0.8's one real, measurable, hard failure (16px legibility) — v0.9 directly addresses it.

### Memorability
**v0.9 favored.** A single bold gestural stroke is a simpler shape to encode and recall than a bent multi-segment path — this is a general property of simple vs. compound shapes in mark recognition, not unique to this asset. Softer evidence than the 16px measurement above, but consistent with it.

### Production Quality
**Roughly even, slight edge to v0.9.** Both are valid, cleanly constructed vector files using the same established technique (knockout-gap taper plus detached rotated shard), verified computationally before building in both cases. Embroidery minimum-width is nearly identical (v0.9: 1.3mm narrowest at a 50mm patch; v0.8: 1.2mm) — no meaningful difference, same routing recommendation to a future embroidery-specific export. v0.9 has one fewer path vertex and no directional-change geometry to maintain, a minor simplicity advantage for future maintenance.

---

## Re-Test Results

| Check | v0.8 | v0.9 |
|---|---|---|
| 16px | Marginal — fracture detail collapses to noise (v0.8's flagged failure) | **Improved — fracture remains a legible continuous line** |
| 28px | Pass | Pass — comparably clean, arguably crisper given fewer edges |
| Monochrome | Pass | Pass — re-rendered, confirmed |
| Favicon | Fails at 16px minimum, passes at 32px+ | Same profile — passes at 32px+, meaningfully better (not perfect) at 16px |
| YouTube avatar (circular crop) | Top-right corner clipped (pre-existing, mass-geometry issue) | **Same clipping, unchanged** — confirms this finding is independent of fracture design, as expected, since it's driven by the unmodified mass silhouette |
| Embroidery | 1.2mm narrowest at 50mm patch — below safe minimum | 1.3mm narrowest at 50mm patch — same finding, no meaningful change |
| Merchandise (print/vinyl) | Pass | Pass |

---

## Recommendation

**Adopt v0.9 as the new BRA-0001 candidate, superseding v0.8.** The comparison was run objectively, not assumed: v0.9 measurably improves the one hard, evidence-backed weakness the prior Founder QA Audit identified in v0.8 (16px legibility), matches or ties v0.8 on every other production criterion, and delivers exactly the simplicity-and-power direction the Founder Override asked for. The one honest cost — a simpler, less multi-staged physical narrative — is a direct, intended consequence of the requested direction, not an unintended defect.

The two carried-forward findings (avatar circular-crop padding, embroidery minimum-width) are unchanged from v0.8, confirming they are properties of the anvil's mass geometry and physical medium constraints respectively — not of the fracture design — and remain correctly scoped to future derived assets, not to this file.

---

### Changelog
`[v0.9 — 2026-07-07] Founder Direction Override: replaced the fracture with a single continuous diagonal (no kinks), per explicit instruction. Path: entry (28,25.5) on the top-left edge to exit (70,76) on the bottom-right edge, 50.3 degrees, verified computationally to stay inside the mass for its entire length before building -- multi-segment paths were used in v0.6-v0.8 specifically because a straight run was assumed to risk exiting through the anvil's narrow waist; checked directly this time and found not to be a problem at this specific entry/exit pair. Gap tapers 1.3 to 3.4 half-width, same compression-to-separation logic as prior versions applied to one segment instead of two or three. Shard relocated to the new exit point, same v0.7/v0.8-validated technique. Objectively compared against v0.8 across recognition, storytelling, scalability, memorability, and production quality: v0.9 wins recognition and scalability with direct measured evidence (16px render comparison), is favored on memorability, ties on production quality, and trades narrative granularity for the simplicity the Founder Direction explicitly requested on storytelling -- recorded as a genuine trade-off, not inflated into an unqualified win. Re-tested 16px, 28px, monochrome, favicon, YouTube avatar, and embroidery: 16px shows a real, measured improvement over v0.8's flagged weakness; avatar circular-crop clipping and embroidery minimum-width are both unchanged, confirming those findings belong to the mass geometry and physical medium respectively, not the fracture design. No Locked brand element redefined; still Concept 5, "Weighted Line." Recommendation: adopt v0.9, superseding v0.8, as the BRA-0001 candidate.`
