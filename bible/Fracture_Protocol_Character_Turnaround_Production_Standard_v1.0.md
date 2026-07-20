# THE FRACTURE PROTOCOL — CHARACTER TURNAROUND PRODUCTION STANDARD

**Classification:** Internal — Production Standard (**Compiled — Pending Founder Review**)
**Status:** Compiled 2026-07-20 per "Founder Directive — Character Turnaround Standard v1.0," continuing from the FPP-CHAR-001 Turnaround Pre-Production plan, Phase 6A.5 Character Standards, Phase 6K.0 v2.2, Production OS, and Studio OS. **Governs production workflow only. Does not modify story canon, character canon, or visual design.** No artwork created; no character redesigned.
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md` (Character Standards, names "Turnaround" as a required category without defining its content) → `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (v2.2) → `Fracture_Protocol_FPP_CHAR_001_Turnaround_Pre_Production_v1.0.md` (Step 1, which first identified this gap) → `Fracture_Protocol_Concept_Art_Technical_Standard_Decision_v1.0.md` (governance-placement precedent) → this standard.

---

## Step 1 — Production Standard: Minimum Required Turnaround Views

**No Locked Canon defines this** — confirmed again directly, not assumed, per the Turnaround Pre-Production plan's own Step 1 finding. This is therefore established here explicitly as a **production specification**, not story, character, or visual canon. It changes no character's appearance; it only defines how many views a Turnaround deliverable must contain.

**Minimum required views: three — Front, Side (profile), Back.**

**Justified by production efficiency and downstream dependency only:**

- **Downstream dependency (Animation Reference and future 3D production, Step 4 below):** Front/Side/Back is the standard minimum orthographic triad needed to resolve a character's full three-dimensional form without ambiguity — front alone leaves depth and rear costume/hair undefined; front-plus-¾ still leaves the true side profile and rear undefined. Three views is the smallest set that leaves no rotational axis undocumented.
- **Downstream dependency (Poses, Color Reference, Material Reference):** each of these categories needs full costume/silhouette coverage that a single-angle still cannot provide (already demonstrated directly: the Approved Calm-state still is a bust crop and cannot answer any question about Kael's back or side profile). Three views is the minimum that resolves this without requiring a fourth, more expensive angle.
- **Production efficiency (why not four or more):** a ¾ view is valuable for promotional/narrative stills (already the register used for the Approved Calm-state deliverable) but is not strictly necessary for orthographic/technical reference purposes once true front, side, and back exist — adding it as a fourth mandatory view would increase per-character production cost (one additional generation, validation, and certification pass) without resolving any dependency the other three leave open. It is **not excluded** — see the Deliverable Layout note below — but it is not part of the *minimum*.
- **Bilateral symmetry assumption, flagged:** a single side view is specified, not two, on the production-efficiency assumption that a character's design is left/right symmetric unless a specific character's own Locked canon states otherwise (e.g., an asymmetric holster, scar, or accessory confined to one side). Nothing in Kael's Locked Costume Canon establishes any such asymmetry. This assumption is stated explicitly so it can be overridden per-character if a future character's design requires it — not treated as a silent, permanent rule.

---

## Step 2 — Deliverable Layout

**Required views:** Front, Side (profile), Back — three individually-produced, individually-validated files per Turnaround, per Step 1.

**Sheet organization:** **Individual files per view, not a single composited multi-panel sheet.** This follows directly from the Turnaround Pre-Production plan's own Step 4 conclusion (multiple prompts, one per view, each independently generated) and from this production's own established practice (every FPP-CHAR-001 deliverable to date has been a single image per file, individually validated under the Two-Stage framework). Compositing three independently-generated, independently-certified files into one canvas is not itself defined as a deliverable requirement — a non-canonical **review preview** composite may optionally be assembled downstream from the already-Approved individual files for human at-a-glance review, but it is not the master deliverable and is not separately certified.

**Labeling standard:** extends, rather than replaces, the naming convention already established and Approved for FPP-CHAR-001 (`FPP-CHAR-001_Kael_Primary_Outfit_Concept_Art_Calm_v1.0.png`):

```
<AssetID>_<CharacterName>_Turnaround_<View>_<EmotionState>_v<Version>.<ext>
```

Example: `FPP-CHAR-001_Kael_Turnaround_Front_Calm_v1.0.png`, `FPP-CHAR-001_Kael_Turnaround_Side_Calm_v1.0.png`, `FPP-CHAR-001_Kael_Turnaround_Back_Calm_v1.0.png`. This is a direct extension of the already-Approved pattern — no new naming philosophy introduced, consistent with Phase 6A.5's own general `Category_ID_Name_Version` convention and the FPP-CHAR-001-prefixed precedent already in use (with the still-open, previously-flagged FPP-CHAR-00X vs. CHR-000X discrepancy unaffected either way).

**Artwork itself is not defined here** — no pose, camera angle beyond the named view, lighting, or composition detail is specified, per this directive's own "do not define artwork" instruction.

---

## Step 3 — Character Coverage

**No clean three-tier Main/Supporting/Background hierarchy exists in Locked Canon** — this is reported directly rather than assumed to exist because the directive's own example list suggested it. What **is** established, and what this standard is scoped to:

- **`Fracture_Protocol_Phase6B2_Human_Character_Visual_Canon_v1.0.md`'s own "four active principal characters"** — Kael, Mira, Cassian, and the Guardian — are the only characters currently carrying complete visual production authority (full Character Production Packages under Phase 6B, Phase 6B.2, and Phase 6B.3). **This standard applies to these four.**
- **Titan is explicitly excluded** from costume/visual production canon per Phase 6B.3's own changelog ("Titan remains excluded"), consistent with his deceased, pre-Season-One narrative status — not in scope for this standard.
- **No "Background Characters" category exists anywhere in Locked Canon.** If minor/background characters are ever intended to require Character Standard deliverables, that requires its own future Founder decision defining such a tier — not assumed or invented here.

---

## Step 4 — Future Compatibility

| Downstream category | Compatibility | Basis |
|---|---|---|
| Pose Sheets | **Supported** | The Front/Side/Back triad establishes the proportion and silhouette baseline any new pose can be checked against for consistency — exactly the gap the Turnaround Pre-Production plan identified as blocking Poses. |
| Material Sheets | **Supported, with an inherited dependency** | Front/Side/Back gives full upper-body and silhouette coverage, but full compatibility still depends on the lower-body costume specification gap already flagged in the Turnaround Pre-Production plan (Step 3, Founder-decision item 2) — this standard does not resolve that gap, it only confirms the view structure is compatible once it is resolved. |
| Lighting Sheets | **Supported** | Lighting Reference typically holds one pose/angle constant while varying lighting conditions; the Turnaround's Front view is the natural, already-established baseline candidate for this. |
| Animation Reference | **Supported** | Front/Side/Back is the standard minimum reference triad for rigging and motion-interpolation reference — directly informing, not merely compatible with, this category's needs. |
| Future 3D production | **Supported** | Front/Side/Back orthographic views are the conventional reference-image input for building a 3D character model manually or via photogrammetry-adjacent methods — this is the primary justification for choosing exactly this triad over a two- or four-view alternative. |

---

## Step 5 — Governance Placement

**This standard belongs as its own standalone production-standard document — this one — cross-referenced by, and subordinate to, both `Fracture_Protocol_Phase6A5_Asset_Production_Standards_v1.0.md` (which names the Turnaround category without defining it) and `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (Approval Authority). It should not be merged into Phase 6A.5's own Locked Canon text.**

Justified by direct precedent, not invented governance philosophy: `Fracture_Protocol_Concept_Art_Standard_Canon_Placement_Decision_v1.0.md` already established exactly this pattern for the Concept Art Resolution and Color-Management Standards — administrative, production-experience-dependent technical specifications are kept at a lighter governance tier (their own document, subject to the lighter Revision Rule) rather than promoted into Art Bible or Character Standards Locked Canon, specifically because they are provisional and may need revision once real production experience with them exists. This Turnaround view-count standard is the same category of decision: this production has not yet produced a single Turnaround under it, so treating it as immediately Locked, permanent Canon would be premature in exactly the way the Canon Placement Decision already reasoned through for a parallel case.

**This document is not created as Locked Canon by this directive — per Step 5's own "do not create it yet" instruction, this section identifies where it belongs; the document you are reading is the compiled standard itself, pending the Founder Review below before it takes effect.**

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — the view-count recommendation is justified exclusively by production efficiency and downstream dependency, per this directive's own instruction; no story, character, or visual-design fact was touched. |
| Alignment Audit | PASS — no artwork created; no character redesigned; Character Coverage (Step 3) reported only what existing production hierarchy actually supports, rather than assuming the example three-tier structure the directive offered; Governance Placement (Step 5) identified only, not created as Locked Canon. |

**Determination: PASS.**

## Dependency Verification

| Check | Result |
|---|---|
| Every Step 4 compatibility claim traces to a specific, named downstream need | PASS — each row cites the specific gap or requirement it resolves, not a general assertion of usefulness. |
| The Material Sheets dependency on the still-open lower-body costume gap is disclosed, not hidden | PASS — explicitly flagged as "supported, with an inherited dependency" rather than marked a clean pass. |
| Governance Placement recommendation matches an already-decided precedent, not a new philosophy | PASS — directly traced to the Concept Art Standard Canon Placement Decision's own reasoning. |

**Determination: PASS.**

---

### Changelog
`[v1.0 — 2026-07-20] Compiled per "Founder Directive — Character Turnaround Standard v1.0." Established the minimum required Turnaround view set (Front, Side, Back) as a production specification, not story or character canon, justified exclusively by production efficiency and downstream dependency (Animation Reference and future 3D production's orthographic-triad needs; Poses/Color/Material Reference's full-coverage needs; a single side view assumed by symmetry unless a character's own canon states otherwise). Defined the deliverable layout as individual per-view files (not a composited sheet), extending FPP-CHAR-001's own already-Approved naming convention with a View and re-affirmed EmotionState segment. Determined Character Coverage applies to Phase 6B.2's own "four active principal characters" (Kael, Mira, Cassian, the Guardian) — reported that no Main/Supporting/Background tier exists in Locked Canon, rather than assuming the directive's example structure. Verified Future Compatibility with Pose/Material/Lighting/Animation Reference and future 3D production, disclosing Material Reference's inherited dependency on the still-open lower-body costume gap rather than marking it a clean pass. Identified Governance Placement as its own standalone, lighter-tier standard document (this one), cross-referenced by but not merged into Phase 6A.5 or Phase 6K.0 Locked Canon, directly following the precedent already set by the Concept Art Standard Canon Placement Decision. No artwork created; no character redesigned; no story, character, or visual-design canon modified. Status: "Compiled — Pending Founder Review."`
