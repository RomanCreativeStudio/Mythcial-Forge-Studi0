# THE FRACTURE PROTOCOL — FPP-CHAR-001 CHARACTER STANDARD COMPLETION PLAN

**Classification:** Internal — Production Roadmap (**Compiled — Pending Founder Review**)
**Status:** Compiled 2026-07-20 per "Founder Directive — FPP-CHAR-001 Character Standard Completion Plan," continuing from FPP-CHAR-001's Approved registration, `Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md`'s Character Standards, and Phase 6K.0 v2.2. **Planning only. No artwork created, no canon modified, no production begun.**
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md` (Character Standards) → `Fracture_Protocol_Phase6B_Character_Kael_Aurelian_Veyr_v1.0.md` → `documentation/Asset_Registry.md` → `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (v2.2) → this plan.

---

## Source Authority

Phase 6A.5's Character Standards section (`Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md`) states, Locked: *"Every character asset must include: Turnaround, Expressions, Poses, Scale Reference, Color Reference, Material Reference, Lighting Reference, Animation Reference."* Eight categories, cited verbatim — none renamed, none added.

**Interpretive note, flagged rather than treated as settled fact:** Phase 6A.5 names these eight categories but does not define an exact deliverable format/template for each (e.g., how many angles a Turnaround requires, how many poses a Poses set requires). Where this plan reasons about a category's content or dependencies, that reasoning is stated as interpretation grounded in the category's own name and this production's existing precedent (e.g., the Exploration document's own prior citation of "Scale Reference" as a distinct, lower-fidelity category), not asserted as a second Locked definition.

---

## Current Character Completion

| # | Category | Status | Evidence |
|---|---|---|---|
| 1 | Scale Reference | **Satisfied** | `FPP-CHAR-001_Kael_Silhouette_Proportion_Reference_v1.0.svg` — explicitly self-identified as this category in its own Exploration record. |
| 2 | Expressions | **Partially satisfied (1 of 4 Locked Emotion Modifier states)** | The newly Approved `FPP-CHAR-001_Kael_Primary_Outfit_Concept_Art_Calm_v1.0.png` depicts the **Calm** state only. **Conflict, Activation, and Breakdown remain unproduced.** |
| 3 | Turnaround | **Not satisfied** | Only a single front/three-quarter angle exists (in the Approved still); no side, back, or full multi-angle set exists. |
| 4 | Poses | **Not satisfied** | The Approved still depicts one static bust/shoulders pose; no dedicated pose set exists. |
| 5 | Color Reference | **Not satisfied as a dedicated deliverable** | The Approved still incidentally shows real rendered color (jacket, eyes, hair, skin) but is not structured as a reference sheet, and covers only the upper body — lower-body costume elements (per Phase 6B.3 §2: boots, belt, full trouser/leg coverage) are entirely unaddressed. |
| 6 | Material Reference | **Not satisfied as a dedicated deliverable** | Same limitation as Color Reference — jacket material is visible in the Approved still, but no dedicated material/texture sheet exists, and lower-body materials are unaddressed. |
| 7 | Lighting Reference | **Not satisfied** | The Approved still uses a single scene lighting setup (per its Calm-state prompt: "gentle lighting"); no set testing the character under multiple defined lighting conditions exists. |
| 8 | Animation Reference | **Not satisfied** | No motion/pose-sequence reference exists. |

**Summary: 1 of 8 categories fully satisfied (Scale Reference); 1 of 8 partially satisfied at 25% (Expressions, 1/4 states); 6 of 8 categories entirely unstarted as dedicated deliverables**, though two of them (Color Reference, Material Reference) now have a genuine, if partial and non-dedicated, upper-body data point from the Approved still.

---

## Remaining Deliverables

1. **Expressions — Conflict, Activation, Breakdown states** (3 of 4 Emotion Modifier states, per `color-language.md`'s Kael Eye-Glow Specification and `prompt-library.md`'s Emotion Modifiers table).
2. **Turnaround** — full multi-angle reference (front already partially covered by the Approved still; side, back, and any additional angles remain undefined by Locked Canon and would need their own scope directive).
3. **Poses** — a dedicated set of distinct poses beyond the single static bust pose already produced.
4. **Color Reference** — a dedicated, structured color/palette reference sheet covering the full costume, not just the upper body.
5. **Material Reference** — a dedicated, structured material/texture reference sheet covering the full costume.
6. **Lighting Reference** — a set testing the character under the Locked Emotional Lighting Modes (Grounded/Charged/Wounded, per `lighting-system.md`) and/or other defined lighting conditions.
7. **Animation Reference** — motion/pose-sequence reference supporting the Animation Requirements already Locked in Kael's Character Production Package (Section 7: idle, walk, run, turn, look, conversation, combat, reaction, facial).

---

## Dependency Order

Reasoned from each category's own content requirements, not asserted as a Locked production-pipeline rule:

1. **Turnaround** — foundational. Establishes the character's full multi-angle form (front/side/back), which every category needing full-body or non-frontal coverage depends on.
2. **Expressions (remaining 3 states)** — largely independent of Turnaround; these are facial-focus, single-angle stills of the same kind as the already-Approved Calm still, and can proceed in parallel with Turnaround rather than waiting on it.
3. **Poses** — depends on Turnaround, since a dynamic pose set needs an established full-body silhouette/proportion reference to maintain consistency across non-frontal angles.
4. **Color Reference** — depends on Turnaround, since the lower-body costume elements it must cover (per Phase 6B.3 §2) are not visible in any currently-Approved asset.
5. **Material Reference** — depends on Turnaround, for the same reason as Color Reference.
6. **Lighting Reference** — depends on having a stable reference pose (most naturally Turnaround's front view, or another already-established still) to hold constant while lighting conditions vary.
7. **Animation Reference** — most downstream; depends on Turnaround (full form), Poses (range of motion cues), and Material Reference (how the jacket/costume behaves in motion) all being established first.

**Dependency graph, summarized:** Turnaround → {Poses, Color Reference, Material Reference, Lighting Reference} → Animation Reference. Expressions runs in a parallel, largely independent track.

---

## Rank by Downstream Impact

| Rank | Category | Downstream impact |
|---|---|---|
| 1 | **Turnaround** | Highest — directly unlocks or substantially informs 4 of the remaining 6 categories (Poses, Color Reference, Material Reference, Lighting Reference), and indirectly Animation Reference through them. |
| 2 | Expressions (remaining states) | Moderate — high narrative/production importance (Kael's signature diagnostic system) but low unlocking effect on other categories, since it doesn't block any of them. |
| 3 | Poses | Moderate — required for Animation Reference, but does not itself unlock Color/Material/Lighting Reference. |
| 4 | Color Reference | Lower — informs downstream production consistency (future storyboards, animation, marketing) but doesn't gate other Character Standard categories. |
| 5 | Material Reference | Lower — same profile as Color Reference; also informs Animation Reference's material-behavior needs. |
| 6 | Lighting Reference | Lower — useful for downstream cinematography consistency but not a blocker for any other Character Standard category. |
| 7 | Animation Reference | Lowest priority to attempt now — the most downstream category, dependent on the most prerequisites. |

---

## Recommended Next Deliverable

**Turnaround.** It is the single highest-downstream-impact remaining category — the only one whose completion directly unlocks or substantially informs four of the other six remaining deliverables. Completing it first minimizes the risk of producing Poses, Color Reference, Material Reference, or Lighting Reference work that later needs revision once full-body/multi-angle coverage exists.

**Every later deliverable that depends on Turnaround, confirmed:**
- Poses
- Color Reference
- Material Reference
- Lighting Reference
- Animation Reference (indirectly, through Poses and Material Reference)

**Not dependent on Turnaround:** Expressions (remaining 3 states) — may proceed independently, on its own track, whenever separately scoped.

**This plan does not itself authorize production of Turnaround or any other deliverable** — per this directive's own explicit "Do not begin production" instruction, a separate scope directive is required before any artwork is created.

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — all eight Character Standard categories traced directly to Phase 6A.5's own Locked text; current completion status for each traced directly to the Asset Registry's actual entries, not assumed. |
| Alignment Audit | PASS — no artwork created; no canon modified; no production begun; the one interpretive judgment made (exact deliverable content/format per category) is explicitly flagged as interpretation, not presented as a second Locked definition. |

**Determination: PASS.**

## Dependency Verification

| Check | Result |
|---|---|
| Dependency reasoning grounded in category content, not asserted arbitrarily | PASS — each dependency (e.g., Color/Material Reference needing full-body coverage Turnaround provides) traces to a concrete content gap in the currently-Approved asset, cited directly. |
| No circular dependency | PASS — the graph (Turnaround → {Poses, Color, Material, Lighting} → Animation; Expressions independent) contains no cycle. |
| Recommended deliverable matches the highest-impact node in the graph | PASS — Turnaround is confirmed, by direct count, to unlock more downstream categories (4 direct, 1 indirect) than any other remaining category. |

**Determination: PASS.**

---

### Changelog
`[v1.0 — 2026-07-20] Compiled per "Founder Directive — FPP-CHAR-001 Character Standard Completion Plan." Listed all 8 Locked Character Standard categories (Phase 6A.5) and audited FPP-CHAR-001's current completion against the Asset Registry's actual entries: Scale Reference fully satisfied; Expressions 25% satisfied (Calm state only, 3 states remaining); the other 6 categories unstarted as dedicated deliverables, though Color Reference and Material Reference now have a partial, non-dedicated upper-body data point from the Approved still. Reasoned a dependency order (Turnaround as the foundational node feeding Poses, Color Reference, Material Reference, and Lighting Reference, with Animation Reference most downstream, and Expressions running on an independent parallel track) and ranked all 7 remaining categories by downstream impact. Recommended Turnaround as the next deliverable, confirming the 5 later deliverables (4 direct, 1 indirect) that depend on it. Planning only — no artwork created, no canon modified, no production begun. Status: "Compiled — Pending Founder Review."`
