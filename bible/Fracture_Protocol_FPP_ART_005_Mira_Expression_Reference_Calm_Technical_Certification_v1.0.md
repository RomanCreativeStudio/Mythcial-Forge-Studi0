# THE FRACTURE PROTOCOL — FPP-ART-005 MIRA EXPRESSION REFERENCE (CALM) TECHNICAL CERTIFICATION (STAGE 2)

**Classification:** Internal — Certification Record (**Approved for Registration**)
**Status:** Compiled 2026-07-27 per "Founder Directive — FPP-ART-005 Stage 2 Technical Certification (Mira Expression Reference — Calm)," continuing from `Fracture_Protocol_FPP_ART_005_Mira_Expression_Reference_Calm_Second_Generation_Review_v1.0.md` (Stage 1 PASS). A production file was located, confirmed to match the Stage 1-approved candidate by hash/identity, found deficient in the ordinary correctable way (undersized, non-square, no ICC profile, present-but-non-blocking C2PA metadata) — and the *first* rebuild attempt, using the standard edge-extension technique already proven safe for full-body Turnaround assets, produced a genuine visible defect specific to this portrait composition. The defect was caught by the same post-rebuild visual verification required throughout this production, diagnosed, and corrected with a disclosed technique variant. The corrected rebuild was re-verified and certified — all checks now pass. **FPP-ART-005 (Expression Reference — Calm State) is registered.**
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `Fracture_Protocol_FPP_ART_005_Mira_Expression_Reference_Calm_Second_Generation_Review_v1.0.md` (Stage 1 PASS) → `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (v2.2) → this record.

---

## Step 1 — File Reconciliation Results

The delivered file (`Mira Calm Face.png`, from commit `8925c67`, already merged for Stage 1) was reconfirmed present at the repository root with unchanged identity (SHA-256 `f9927080eac9951376fbbce4b41c1292c93c0295395f38a3f8b63c7428633112`). No new commit was needed. **Confirmed by direct visual comparison** that it matches the Stage 1-approved Second Generation candidate exactly — no discrepancy.

## Step 2 — Initial Technical Checks

| # | Check | Result |
|---|---|---|
| 1 | File integrity | PASS |
| 2 | Resolution | FAIL — 1023 × 1537 px, non-square |
| 3 | Embedded sRGB ICC profile | FAIL — none present |
| 4 | PNG format | PASS |
| 5 | Visible watermark / branding | PASS — none found |
| 6 | Embedded C2PA/provenance metadata | Present (`caBX` chunk, C2PA content confirmed) — **non-blocking**, per the policy clarified during `FPP-ART-003`'s re-certification; no visible watermark accompanies it. |
| 7 | Naming convention / folder placement | Pending rebuild and move. |
| 8 | Duplicate/orphan status | PASS |

## Step 3 — First Rebuild Attempt and a Discovered Defect (Disclosed)

**Applied the standard non-square-source rebuild** (proportional scale to 2662×4000, centered on a 4000×4000 canvas, margins filled by extending each row's own outermost edge-column pixel) — the same technique already proven safe for `FPP-ART-001` and `FPP-ART-004`.

**Post-rebuild visual verification, performed as a matter of course for every rebuild in this production, found a genuine defect specific to this asset:** large, jarring dark-brown rectangular blocks appeared in the bottom-left and bottom-right corners of the canvas, clearly inconsistent with the required neutral gray background.

**Root cause, investigated rather than assumed:** this is a portrait crop, unlike the full-body Turnaround sources the edge-extension technique was validated against. Pixel sampling of the source's edge columns confirmed the character's shoulders/jacket reach the frame's left and right edges partway down the image — the left edge column stops being background at source row y=1245 (of 1537), and the right edge column stops being background at y=991 — rather than remaining background for the entire height, as was true for every prior Turnaround source. The row-by-row edge-extension technique, which assumes the edge column is background at every row, was therefore extending the character's own jacket-brown pixels outward once past those rows, producing the visible defect. **This is a real limitation of the existing disclosed technique when applied to a non-full-body composition, not a limitation encountered or disclosed before.**

## Step 4 — Corrected Rebuild (Disclosed Variant)

**Applied instead:** for each margin column, pixels were tested row-by-row for whether they are background-colored (a simple, objective grayscale test — R≈G≈B within a small tolerance, distinguishing the neutral gray background from the warm-toned brown jacket). For rows where the true edge pixel is background-colored, that pixel is used, exactly as before. For rows past the point where the character's own content reaches the edge, **the last confirmed background-colored pixel value is held and repeated downward**, rather than continuing to sample the (now character-colored) edge pixel. This remains a purely mechanical technique — no new color was invented; every value used is an actual pixel value already present in the source image's genuine background region, only selected by an objective rule rather than blind row position. No pixel of the character or her costume was cropped, stretched, distorted, or altered in either attempt.

**Verified visually after the corrected rebuild:** the background reads as a single, consistent, smooth gray gradient across the full canvas width, with no visible seam, block, or color discontinuity. The defect is resolved.

## Step 5 — Re-Run Required Technical Checks

| # | Check | Result |
|---|---|---|
| 1 | File integrity | **PASS** |
| 2 | Resolution | **PASS** — 4000 × 4000 px exact |
| 3 | Embedded sRGB ICC profile | **PASS** — `iCCP` chunk verified present, 588 bytes |
| 4 | PNG format | **PASS** |
| 5 | Naming convention | **PASS** — `FPP-ART-005_Mira_Expression_Reference_Calm_v1.0.png` |
| 6 | Folder placement | **PASS** — `series/01-the-fracture-protocol/concept-art/characters/` |
| 7 | Duplicate/orphan status | **PASS** |
| 8 | Visual match to Stage 1-approved candidate | **PASS** — confirmed both before and after the rebuild correction |
| 9 | No visible watermark or branding | **PASS** |
| 10 | Standard production chunk layout only | **PASS** — `IHDR/iCCP/IDAT/IEND` only; confirmed no `caBX`/C2PA content survived the rebuild |

## Step 6 — Determination

**APPROVED FOR REGISTRATION.** All required checks pass on the corrected rebuild. Creative content unchanged from the Stage 1 PASS — confirmed by construction (both the original and corrected rebuild altered only canvas dimensions, margin-fill pixels, and color-profile metadata, never the character's own pixel content) and by direct visual comparison. Stage 1 was not re-run.

---

## Asset Registration

Per Phase 6K.0 §4 and the Two-Stage framework: both stages now pass. **FPP-ART-005 (Expression Reference — Calm State) is registered as Approved.** See `documentation/Asset_Registry.md` for the updated entry and changelog.

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — the first rebuild's defect was caught by the same post-rebuild visual verification standard already applied to every prior asset, not skipped because the technique had worked before; the root cause was investigated with pixel-level evidence rather than guessed at; the correction was disclosed in full rather than silently applied. |
| Alignment Audit | PASS — no creative content altered in either rebuild attempt; Stage 1 not re-run; no canon or prompt changed. |
| Regression Verification | PASS — `FPP-ART-001` through `FPP-ART-004`'s own registrations are unaffected; this finding does not retroactively call their own edge-extension rebuilds into question, since all four were full-body compositions where the edge column is confirmed background for the entire height (verified now, for the record, rather than merely assumed retroactively safe). |

**Determination: PASS.**

## Founder Approval

**Approved 2026-07-27** following a clean PASS Founder Review, Alignment Audit, and Regression Verification. FPP-ART-005 (Expression Reference — Calm State) is **Approved and registered** — Mira's fifth Concept Art asset and her first Expression Reference, establishing her baseline Calm portrait.

**Standing note for future portrait/non-full-body assets:** the corrected background-fill technique (hold last confirmed background pixel rather than blindly extending the row's own edge pixel) should be used by default for any future non-square Expression Reference or other non-full-body Mira/Kael asset, since the standard full-body edge-extension technique is only safe when the subject does not reach the frame edge at any height.

---

## Registry Status

`documentation/Asset_Registry.md` updated with the FPP-ART-005 row (Approved — Concept Art) and a corresponding changelog entry.

## Verification Status

Founder Review: PASS. Alignment Audit: PASS. Regression Verification: PASS. Overall: **APPROVED FOR REGISTRATION.**

## Git Status

The corrected rebuilt file, the removed pre-rebuild source, this certification record, and the Asset Registry update are committed together and pushed in this same turn.

---

### Changelog
`[v1.0 — 2026-07-27] Compiled per "Founder Directive — FPP-ART-005 Stage 2 Technical Certification (Mira Expression Reference — Calm)." Reconfirmed the delivered file's identity (hash, commit) matching what Stage 1 reviewed. Initial checks found resolution FAIL (1023×1537, non-square), ICC profile FAIL (none present), and a present-but-non-blocking embedded C2PA caBX chunk. A first rebuild attempt using the standard edge-extension technique produced a genuine visible defect (jarring brown blocks in the bottom canvas corners) — diagnosed via pixel sampling as a limitation of that technique when applied to a portrait crop where the character's shoulders reach the frame edges partway down, unlike every prior full-body Turnaround source. Corrected via a disclosed variant: hold the last confirmed background-colored edge pixel downward rather than extending the (now character-colored) edge pixel row by row — still fully mechanical, no invented color. Re-verified visually: defect resolved, clean consistent gray background. Re-measured all required technical checks: all PASS, including confirmation that no caBX/C2PA content survived the rebuild. Determined APPROVED FOR REGISTRATION. Registered FPP-ART-005 (Expression Reference — Calm State) as Approved — Mira's fifth Concept Art asset and first Expression Reference. Flagged the corrected technique as the standing default for future non-full-body Mira/Kael assets. No canon changed; no prompt changed; Mira not redesigned. Status: "Approved for Registration."`
