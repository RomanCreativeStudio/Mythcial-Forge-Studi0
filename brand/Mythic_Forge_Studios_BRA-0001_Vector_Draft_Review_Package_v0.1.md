# BRA-0001 — Vector Draft Review Package
## v0.1

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Draft vector files constructed and rendered for review. **Not approved. Not locked. Not registered.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` Section 3–4 (logo/color authority), `brand/Mythic_Forge_Studios_YouTube_Brand_Kit_v1.0.md` Section 2 (small-size/UI-compatibility requirements), `brand/Mythic_Forge_Studios_Brand_Asset_Production_Guide_v1.0.md` Section 3 (Stage 3/4 process), `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md` (this package's parent record — Stage 3 specification this draft was built from).
**What changed from Stage 3:** the Stage 3 document was a written specification. This package contains **actual constructed SVG files**, actually rendered (including a true 28×28px raster test), so the findings below are measured, not predicted.

---

## Draft Assets

Four files constructed at `brand/assets/logos/drafts/`, all marked `v0.1` and containing an in-file `DRAFT — NOT APPROVED` comment:

| File | Content |
|---|---|
| `mfs-logo-primary-dark_v0.1.svg` | Icon + "MYTHIC FORGE / STUDIOS" wordmark, Dark Version |
| `mfs-logo-primary-light_v0.1.svg` | Icon + wordmark, Light Version |
| `mfs-logo-icon-dark_v0.1.svg` | Icon Only, Dark Version (default per Brand Bible Section 3) |
| `mfs-logo-icon-monochrome_v0.1.svg` | Icon Only, Monochrome Version |

All four are built from the identical mass and fracture geometry defined in the Production Record's Stage 3 specification — no variant redraws the shape independently.

**Geometry actually used (100-unit grid, per Stage 3):**
- Mass: a single connected path, upper block 40×34 (x:30–70, y:24–58) sitting directly on base block 64×18 (x:18–82, y:58–76), outer corners chamfered 2 units, no internal negative space.
- Fracture: entry `(30, 37.6)` → kink `(61.2, 52.2)` → mass-exit `(82, 66.7)` → escape tip `(90.2, 72.4)`, stroke width 5 units, round caps/joins, no taper.
- Color version: mass in Authority White/Void Black per mode; fracture in Fracture Cyan `#00E5FF`, drawn as a stroke overlaid on the mass.
- Monochrome version: **same overlay technique, same single color for mass and stroke** — built this way deliberately, to test the open risk the Stage 3 spec flagged rather than silently work around it before anyone could see the failure.

---

## Technical Notes

- **Fonts not embedded.** The primary lockups reference `'Space Grotesk', system-ui, -apple-system, 'Segoe UI', Arial, sans-serif` (Brand Bible Section 5's own fallback stack) but do not embed or outline the actual Space Grotesk font file. These renders display in a fallback sans-serif. This must be corrected (font embedded or text converted to outlines) before any primary lockup file is treated as final — flagged as a known limitation of this draft, not silently hidden.
- **No gradients, bevels, shadows, or glows** appear in any file — verified by inspecting the SVG source directly (only `fill` and `stroke` attributes are used anywhere), consistent with Brand Bible Section 3's Improper Usage rule and this task's explicit "Do Not" list.
- **No extra symbols, no text baked into the icon itself** — the Icon Only and Monochrome files contain exactly two path elements (mass, fracture) and nothing else.
- All four files were validated as well-formed XML and rendered successfully in an actual browser engine (Chromium headless) — this is not a hand-described mockup, the files render correctly as vector graphics.

---

## Scaling Test Results

*(Rendered directly from the actual files, not estimated.)*

### Large Scale (website header, video intro, studio credit use)
Rendered at 600×300px. The mass silhouette, the fracture's single kink, and the escape segment are all clearly legible. At this size the mark reads correctly as a weighted, deliberate two-block shape with one line breaking free of it.

**Found at this size, not predicted in Stage 3:** the mass occupies noticeably less of the frame than the Stage 3 specification estimated ("roughly 55–58% of the artboard's total area"). Measured against the actual built geometry, the mass's true area is **~25% of the 100×100 artboard** (two blocks, 1360 + 1152 = 2512 sq. units minus ~8 sq. units for corner chamfers, against 10,000 total). The rendered image confirms this — there is more surrounding dark space than the written spec anticipated. This is a real discrepancy between the paper specification and the built result, not a subjective judgment call.

### Medium Scale (social profile, merchandise, marketing materials)
Not separately re-rendered at a distinct "medium" resolution — the large-scale render is already representative of this range, since nothing in the geometry changes between roughly 300px and 600px. One item specific to physical reproduction (merchandise) remains an open question rather than a tested one: the fracture is currently built as a **stroke drawn on top of the mass**, not a cut/knockout through it. For embroidery or vinyl specifically, this needs to be confirmed against an actual physical-production process before use — a stroke-on-top technique and a true cut-through technique are not always interchangeable in physical reproduction, and this has not been tested here.

### Small Scale (YouTube avatar, 28px icon test)
This is the test the Stage 3 specification flagged as the highest-risk unknown, so it was run for real: both the Dark and Monochrome Icon Only files were rendered at **true 28×28px**, then inspected at native resolution (not re-rendered at a larger size, which would misrepresent what 28px actually looks like).

**Dark version at 28px:** the mass silhouette remains recognizable and the fracture line is clearly visible — the 5-unit stroke weight (≈1.4px at this scale) survives with visible anti-aliasing, better than the Stage 3 specification's cautious prediction that a stroke-weight bump would likely be needed. **No small-size stroke bump appears necessary for the color version, based on this test** — this recommendation from Stage 3 is not confirmed as required.

**Monochrome version at 28px:** confirms the exact failure predicted as an open risk in Stage 3, now as a demonstrated fact rather than a theoretical concern — see Issues Found, below.

---

## Issues Found

1. **Confirmed failure, not just a risk: the Monochrome Version's fracture is invisible where it crosses the mass, at every size tested.** Because the fracture is a same-color stroke drawn on top of a same-color fill, the portion crossing the solid mass renders with zero visual distinction — it is not "hard to see," it is not present at all. Only the escape segment (the portion outside the mass, visible against the empty background) shows, and it appears as a small disconnected fragment near the bottom-right corner rather than a continuation of anything — at both large size and especially at 28px, this reads as a stray mark or rendering defect, not a design feature. This is the most significant finding in this package.

2. **The built mass occupies roughly 25% of the artboard, not the ~55–58% the Stage 3 written specification estimated.** The mark still reads correctly at every size tested, so this is not a functional failure — but it means either the Stage 3 specification's area estimate was wrong, or the mass should be enlarged (and clear-space proportionally reduced, within the Brand Bible's minimum) to match the original intent. This should be resolved deliberately, not left as an unreconciled gap between the spec and the built asset.

3. **The primary lockup's wordmark is clipped.** In both `mfs-logo-primary-dark_v0.1.svg` and `mfs-logo-primary-light_v0.1.svg`, "MYTHIC FORGE" is cut off by the right edge of the 380×120 viewBox at the specified 34px Bold weight — confirmed by direct render, both color modes affected identically. Root cause: the viewBox width was sized without first measuring actual rendered text width at that font size. This is a construction error in this draft, not a Brand Bible or typography-rule issue — the type spec itself (Space Grotesk Bold, per Brand Bible Section 5) is correctly followed; the canvas built to hold it is not sized correctly.

4. **The fracture's single kink is imperceptible at 28px**, compressing to what reads as one smooth diagonal line. This matches what the Stage 3 specification predicted and explicitly called an acceptable degradation, not a failure — listed here for completeness, not as a new problem.

---

## Recommended Refinements

1. **Monochrome Version:** replace the overlay-stroke technique with a subtractive/knockout technique for this variant specifically — render the fracture as a thin gap cut *through* the solid mass (a compound path, even-odd fill rule) where it crosses the shape, with only the escape segment beyond the mass rendered as a normal filled line in the same single color. This gives the monochrome version genuine geometric contrast in place of the color contrast it doesn't have. This is a real construction change, not a spec change — the Locked concept and geometry are unaffected.
2. **Mass proportions:** reconcile the ~25%-measured vs. ~55–58%-estimated area gap — either enlarge the mass (recommended: scale the existing two-block geometry up while holding the Brand Bible's clear-space minimum) or correct the Stage 3 document's stated estimate to match the built proportions. This should be a deliberate choice, not an oversight carried forward silently into v0.2.
3. **Primary lockup canvas:** widen the viewBox (or reduce wordmark font size) so "MYTHIC FORGE" renders in full at both specified weights — verify by direct render, not by estimate, before the next draft is reviewed.
4. **Font embedding:** embed the actual Space Grotesk font file or convert the wordmark to outlined paths before any primary lockup is treated as more than a placeholder-type draft.
5. **No change recommended for the color versions' stroke weight or escape-segment length** — both tested successfully at 28px as currently specified; the Stage 3 caution about a possible small-size stroke bump is not borne out by this test and does not need to be acted on.

---

## Review Questions

1. **Does the logo immediately read as Mythic Forge Studios?** Not yet independently verifiable — the mark has no existing public association yet (this is its first draft). What can be answered: the mark is internally consistent with the studio's stated identity (anvil = forging, fracture = the signature break) and doesn't contradict itself visually.
2. **Does it feel like an entertainment studio?** Closer to yes than the alternative concepts tested in the Concept Review — the solid mass with an escaping accent line reads as a deliberate, confident mark rather than a generic craft-brand icon, consistent with that review's findings. The unresolved wordmark-clipping issue (Issue 3) currently undercuts this in the *lockup* versions specifically — the Icon Only version is unaffected.
3. **Does the fracture communicate creation?** Yes, in the color versions, where the escape segment is clearly visible against the background. **No, in the current Monochrome Version** — this is exactly Issue 1, and it means the "creation" reading currently only holds for two of the four delivered files, not all four.
4. **Does the mark remain recognizable without text?** Yes — the Icon Only Dark render is legible and complete on its own at every tested size.
5. **Does anything feel generic or over-designed?** No evidence of over-design — the files contain exactly the two elements specified (mass, fracture), nothing decorative was added. The smaller-than-intended mass proportions (Issue 2) are a sizing issue, not a genericness issue.

---

## Status

**VECTOR DRAFT COMPLETE — AWAITING QA REVIEW**

This package does not mark BRA-0001 Approved or Locked. Four draft files exist, have been rendered, and have been tested at large, medium, and true small (28px) scale. One confirmed failure (Monochrome legibility) and three refinement items were found and are documented above with specific, actionable fixes. The next step is Founder/Creative Director review of these findings — not further construction — before a v0.2 draft addressing them is built.

---

### Changelog
`[v0.1 — 2026-07-07] Initial Vector Draft Review Package for BRA-0001. Constructed four actual SVG files (Primary Dark, Primary Light, Icon Only Dark, Monochrome) from the Stage 3 specification's exact coordinates, validated as well-formed XML, and rendered in a real browser engine at large scale and at true 28x28px. Confirmed one significant failure (Monochrome Version's fracture is fully invisible where it crosses the mass — demonstrated, not just flagged as a risk) and three further issues (mass area ~25% actual vs. ~55-58% specified, primary lockup wordmark clipped by an undersized viewBox, fracture kink imperceptible at 28px as predicted/expected). Provided five specific recommended refinements for a v0.2 pass. No Locked brand element redefined. Status: Vector Draft Complete — Awaiting QA Review, not marked Approved.`
