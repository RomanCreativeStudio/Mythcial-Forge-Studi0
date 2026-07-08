# BRA-0001 — Vector Draft Review Package
## v0.8 — Full-Depth Fracture Refinement (Pre-Lock)

**Classification:** Internal — Brand Asset Production Record (Stage 4 output)
**Status:** Fracture re-planned to run genuinely top-to-bottom, rendered, and validated. **Recommendation: promote to BRA-0001 — Primary Logo Master SVG v1.0.**
**Governing documents:** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md`, `brand/Mythic_Forge_Studios_BRA-0001_Primary_Logo_Master_SVG_Production_Record_v1.1.md`, `brand/Mythic_Forge_Studios_BRA-0001_Vector_Draft_Review_Package_v0.7.md` (this package's baseline).
**Scope discipline:** the anvil silhouette is unchanged. This pass is scoped to the fracture's path and, as a direct consequence, the shard's exit location — nothing else.

---

## What Was Actually Wrong With v0.7

Worth stating plainly, since this pass's brief described the fracture as still reading as "a surface crack or decorative line" despite the taper and detachment work already done in v0.6/v0.7: **the previous fracture entered at the top edge but exited through the base's side edge, not the bottom edge.** It ran through roughly the upper two-thirds of the anvil's height and stopped partway down. That's a real, specific, geometric reason a full break didn't fully read — the crack never actually finished crossing the object. This wasn't a rendering-technique problem (the knockout-gap approach was already correct); it was a path-planning problem.

---

## The New Fracture Path

**Re-planned from scratch, not patched.** Three segments, two deflections, verified computationally against the mass's actual boundary before building:

- Entry `(49, 25.5)` — top edge, unchanged from every prior version.
- Kink 1 `(52, 48)` — unchanged from v0.1–v0.7, already inside the face/upper body.
- **Kink 2 `(58, 58)` — new.** Needed because the anvil's waist is narrow enough that a single straight run from kink 1 toward the bottom edge would exit through the waist's side wall before reaching the base at all. This was checked directly, not assumed: an early candidate path was tested against every edge of the mass polygon and found to exit prematurely through the waist. The second kink exists because the geometry requires it, not for its own sake.
- **Exit `(66.78, 76)` — new, on the actual bottom edge.** Confirmed by the same edge-intersection check used throughout this asset's production history.

Angles: 82.4° → 59° → 64°. The second deflection (59° to 64°) is a gentle 5° correction — clean and controlled. The first (82.4° to 59°) is the same sharper deflection this asset has used since v0.1. No jagged, multi-directional "rock crack" pattern was introduced — two clean corrections across a path now roughly twice as long as before.

**Width profile:** tapers from half-width 1.2 at the entry to 3.6 at the exit — narrower throughout than v0.7's profile, specifically to satisfy the explicit instruction that the two sides must "remain close enough that the icon is still instantly recognizable as one anvil" and must not become "two completely separate floating objects." Confirmed by render: the horn, face, waist, and base all still read as one continuous, connected silhouette — the crack is unmistakable but the anvil is not visually broken into independent pieces.

---

## Shard

The shard now falls from the bottom edge rather than from the base's side — a direct, correct consequence of the fracture's new exit point, not a separate design decision. Same validated technique from v0.7 (steel-white fill, thin cyan "hot break" edge, independent rotation for a tumbling read) applied at the new location. Verified by zoomed render: clean geometry, no artifacts from the more complex 12-point gap polygon this path required.

**Incidental finding:** in the YouTube avatar circular-crop test, the shard's new position (falling toward the icon's own center-bottom rather than out to the side) sits more comfortably within the circular frame than v0.7's side-positioned shard did. Not the reason for this change, but worth recording since it was measured.

---

## Full Validation

| Check | Result |
|---|---|
| ✓ 28px | Passes — re-rendered; anvil, fracture, and shard all remain legible as distinct elements |
| ⚠ Favicon (16px) | Marginal — unchanged finding from every prior version; not caused or worsened by this pass |
| ⚠ YouTube avatar (circular crop) | The pre-existing top-right corner clipping (mass geometry, unchanged since v0.5) is still present. The shard itself now sits more comfortably within the circular frame than in v0.7 — an incidental improvement, not a fix for the underlying note, which remains scoped to the future Channel Avatar asset |
| ✓ Monochrome | Passes — re-rendered, the longer/more complex gap path remains fully legible with zero color contrast |
| ✓ Website header | Passes trivially at large format |
| ✓ Merchandise (print/vinyl) | Passes — flat vector, no new constraint introduced |
| ⚠ Embroidery | Re-measured for the new gap profile: at a 50mm (2-inch) patch, narrowest point is 1.2mm (was 1.3mm in v0.7 — essentially unchanged), widest is 3.6mm. Same pre-existing finding, same recommendation: route to a future embroidery-specific export, not a defect in this master |

---

## Recognition Check — The Actual Risk This Pass Ran

A fracture spanning the full height of the icon is a real recognition risk if handled carelessly — this was tested directly, not assumed safe. At every size checked (large, 28px, monochrome, circular crop), the anvil's defining features — the flat-topped horn, the table, the tapering waist, the flared base — all remained intact and connected around the crack. The gap's narrow, controlled width (never exceeding 3.6 half-width, versus the icon's ~65-unit overall footprint) is what keeps this true. Had the brief's own instruction ("if a full-depth fracture harms recognition, refine the gap until both goals are achieved") actually been triggered, the fix would have been narrowing the gap further, not abandoning the top-to-bottom path — but that fallback wasn't needed here.

---

## Final Comparison — v0.7 vs. v0.8

| | v0.7 | v0.8 |
|---|---|---|
| Fracture entry | Top edge | Top edge (unchanged) |
| Fracture exit | Base's side edge | **Base's bottom edge** |
| Path segments | 1 kink | 2 kinks (second one required by the waist's geometry, verified computationally) |
| Reads as | Anvil cracked partway through | **Anvil split fully through, top to bottom** |
| Shard origin | Base's side | Bottom edge, directly beneath the break |
| Anvil silhouette | Unchanged | Unchanged |

This is the change the brief actually asked for, delivered as a genuine path re-plan rather than a cosmetic adjustment to the existing one.

---

## Recommendation

**BRA-0001 — PRIMARY LOGO MASTER SVG v1.0**

**Status: READY FOR FOUNDER APPROVAL**

The fracture now runs uninterrupted from the top edge to the bottom edge, verified computationally rather than assumed, and confirmed by render to keep the anvil recognizable as one connected object at every tested size. Two QA notes (16px favicon, avatar circular-crop) and one production note (embroidery minimum-width) remain — all pre-existing, all unchanged in kind from v0.7, all correctly scoped to future work rather than defects in this master. This document recommends Lock; it does not grant it — Founder sign-off remains the outstanding step.

---

### Changelog
`[v0.8 — 2026-07-07] Full-depth fracture refinement, pre-lock. Anvil silhouette unchanged. Re-planned the fracture's path from scratch rather than patching v0.7's: previous versions entered the top edge but exited through the base's side edge, never actually completing a full top-to-bottom split. New path: entry (49,25.5, unchanged) -> kink (52,48, unchanged) -> new kink (58,58) -> new exit (66.78,76) on the actual bottom edge. The second kink was added because it's geometrically required -- an early candidate straight run from kink 1 toward the bottom was checked against the mass boundary and found to exit prematurely through the narrow waist; corrected before finalizing. Gap width tapers 1.2 to 3.6 half-width, narrower than v0.7's profile specifically to keep the anvil reading as one connected object rather than two floating pieces, confirmed by render at every tested size. Shard relocated to fall from the new bottom-edge exit point, same v0.7-validated rotate/steel-white/cyan-edge technique reapplied at the new location. Re-ran full validation: 28px, monochrome, merchandise, and website-header all pass; embroidery re-measured for the new profile (1.2mm narrowest at a 50mm patch, essentially unchanged from v0.7, same routing recommendation); 16px favicon and avatar circular-crop notes are unchanged and pre-existing, though the shard's new position incidentally sits better within the circular crop than before. No Locked brand element redefined; still Concept 5, "Weighted Line." Recommendation: promote to BRA-0001 -- Primary Logo Master SVG v1.0, status Ready for Founder Approval.`
