# THE FRACTURE PROTOCOL — KAEL EXPRESSION REFERENCE PRODUCTION PACKAGE

**Classification:** Internal — External Production Handoff Document (**Compiled — Pending Founder Review**)
**Status:** Compiled 2026-07-21 per "Founder Directive — Kael Expression Reference Production Package," continuing from FPP-CHAR-001 (Approved, Calm State), FPP-CHAR-002/003/004 (Approved, Turnaround Front/Side/Back), the Kael Turnaround Set Completion Audit (Set Complete and Consistent), Phase 6A.5 Character Standards, and Phase 6K.0 v2.2. **No artwork generated. The Locked production prompts are quoted verbatim, unmodified. No canon modified. No asset registered.**
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `mythic-forge-art-bible/prompt-library.md` (Kael Base Prompt Template, Emotion Modifiers — both `[LOCKED]`) → `mythic-forge-art-bible/color-language.md` (Kael Eye-Glow Specification, `[LOCKED]`) → `Fracture_Protocol_Phase6B2_Human_Character_Visual_Canon_v1.0.md` (v1.3) → `Fracture_Protocol_Phase6B3_Costume_Wardrobe_Visual_Canon_v1.0.md` (v3.0) → `Fracture_Protocol_Phase6B_Character_Kael_Aurelian_Veyr_v1.0.md` (Section 5, Expression Library) → `Fracture_Protocol_Concept_Art_Technical_Standard_Decision_v1.0.md` → `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (v2.2) → this package.

---

## Step 1 — Expression Coverage Audit

Checked directly against `mythic-forge-art-bible/prompt-library.md`'s Locked Emotion Modifiers table (four states, fixed list — no fifth state exists anywhere in Locked Canon):

| State | Coverage | Evidence |
|---|---|---|
| Calm | ✅ **Complete** | FPP-CHAR-001 (Approved, Primary Outfit, Calm State) — uses the Calm Emotion Modifier. |
| Conflict | ❌ **Missing** | No registered or attempted asset uses the Conflict Emotion Modifier. |
| Activation | ❌ **Missing** | No registered or attempted asset uses the Activation Emotion Modifier. |
| Breakdown | ❌ **Missing** | No registered or attempted asset uses the Breakdown Emotion Modifier. |

**No fifth or additional emotional state exists anywhere in Locked Canon** (`prompt-library.md`'s Emotion Modifiers table, `color-language.md`'s Kael Eye-Glow Specification table, and `Fracture_Protocol_Phase6B_Character_Kael_Aurelian_Veyr_v1.0.md` Section 3 all independently enumerate the same fixed four-state list) — consistent with this directive's own instruction not to add states without Founder approval; none are added here.

**Noted, not acted on:** Kael's Character Production Package (Section 5) also carries a separate, broader **10-expression Expression Library** (Neutral, Focused, Concerned, Determined, Hopeful, Fear, Grief, Anger, Compassion, Reflection), each mapped to one of these same four governing eye-glow states. This directive's own scope is the four Emotion Modifier *states* themselves (of which three are missing), not the full 10-expression matrix — flagged here so the distinction isn't lost, not expanded into scope this directive didn't request.

**Determination: 3 of 4 Locked emotional states have no Expression Reference deliverable — Conflict, Activation, Breakdown.**

## Step 2 — Expression Reference Standard

Every Conflict/Activation/Breakdown deliverable must preserve, unchanged from the Approved FPP-CHAR-001–004 baseline:

**Character (unchanged across all states):**
- Kael's identity, established silhouette and proportions (Phase 6B.2 v1.3)
- Same hairstyle as FPP-CHAR-001–004
- Same facial structure
- Same eye color (icy blue-cyan base hue) — only glow *behavior/intensity* changes per state, never the underlying hue family, per `color-language.md`'s Kael Eye-Glow Specification
- Eye-glow rules locked per state: Conflict = flickering, unstable, irregular flicker, medium intensity; Activation = intense, sharp, saturated icy cyan-white, high intensity; Breakdown = fragmented glitch glow, discontinuous fragments, faint edge desaturation

**Costume (unchanged across all states):**
- Approved Primary Outfit (Phase 6B.3 v3.0), matte materials, no redesign
- No added symbols, logos, patches, or insignia of any kind — same zero-tolerance rule enforced at every prior Creative Validation
- No new costume detail invented for any state — emotion modifiers govern expression/lighting/eye-glow only, never costume

**Rendering (unchanged across all states):**
- Semi-realistic anime cinematic hybrid register (`visual-development-guide.md`, `forbidden-elements.md`) — same visual language as the Approved FPP-CHAR-001–004 assets
- No flat cel-shading (automatic QA failure per Forbidden Elements)

**State-specific only (the only permitted variation):** expression, eye-glow behavior/intensity, and lighting/atmosphere cues exactly as specified by each state's own Locked Emotion Modifier phrase — nothing beyond what that modifier phrase itself specifies.

## Step 3 — Production Format Determination

**Format: individual expression files, one per state — not a combined expression sheet.** This follows the same precedent already established for the Turnaround Set (individual per-view files, not a composited sheet, per `Fracture_Protocol_Character_Turnaround_Production_Standard_v1.0.md`) and directly mirrors FPP-CHAR-001's own format (a single bust/portrait Concept Art still per Emotion Modifier state), rather than the Turnaround Set's full-body orthographic format — flagged as an interpretive continuation of precedent, not a Founder-specified value: expression reference is fundamentally a facial/eye-glow deliverable (the Base Prompt's own "high detail face" and "emotional expression focus" phrases), so it follows FPP-CHAR-001's bust-format precedent rather than the Turnaround Set's full-body format.

**Asset ID assignment:** continuing the same distinct-ID-per-deliverable pattern already established and repeatedly flagged-not-objected-to across FPP-CHAR-001 through FPP-CHAR-004:

| Asset ID | State |
|---|---|
| FPP-CHAR-005 | Conflict |
| FPP-CHAR-006 | Activation |
| FPP-CHAR-007 | Breakdown |

**Naming convention (following the FPP-CHAR-001 pattern exactly):**

```
FPP-CHAR-005_Kael_Expression_Reference_Conflict_v1.0.png
FPP-CHAR-006_Kael_Expression_Reference_Activation_v1.0.png
FPP-CHAR-007_Kael_Expression_Reference_Breakdown_v1.0.png
```

**Required technical specifications** (unchanged from every prior Concept Art asset, per `Fracture_Protocol_Concept_Art_Technical_Standard_Decision_v1.0.md`):

| Specification | Value |
|---|---|
| Resolution | 4000 × 4000 px |
| Master format | PNG |
| Color space | sRGB (embedded, verifiable ICC profile) |

**Folder destination:**

```
series/01-the-fracture-protocol/concept-art/characters/
```

**No artwork generated at this step.**

## Step 4 — External Production Package

Each Final Production Prompt is assembled from exactly two Locked components — the Kael Base Prompt Template and the relevant Emotion Modifier — both quoted verbatim, concatenated in the same order already used for FPP-CHAR-001, with no View Modifier appended (Step 3's format determination: bust/portrait, not a Turnaround view) and no word altered from either source.

### FPP-CHAR-005 — Conflict State

```
Late teen to early adult male protagonist named Kael (17–20), semi-realistic anime
cinematic style, futuristic dystopian megacity environment, dark techwear outfit
with subtle cyan accents, glowing icy-blue cyan eyes, emotional expression focus,
cinematic lighting, high detail face, shallow depth of field, moody atmosphere,
sci-fi identity theme, flickering unstable eye glow, tense expression, slight
visual distortion
```

### FPP-CHAR-006 — Activation State

```
Late teen to early adult male protagonist named Kael (17–20), semi-realistic anime
cinematic style, futuristic dystopian megacity environment, dark techwear outfit
with subtle cyan accents, glowing icy-blue cyan eyes, emotional expression focus,
cinematic lighting, high detail face, shallow depth of field, moody atmosphere,
sci-fi identity theme, intense sharp eye glow, sharp contrast lighting,
focused/powerful expression
```

### FPP-CHAR-007 — Breakdown State

```
Late teen to early adult male protagonist named Kael (17–20), semi-realistic anime
cinematic style, futuristic dystopian megacity environment, dark techwear outfit
with subtle cyan accents, glowing icy-blue cyan eyes, emotional expression focus,
cinematic lighting, high detail face, shallow depth of field, moody atmosphere,
sci-fi identity theme, fragmented unstable eye glow, visual noise, motion blur,
distressed expression
```

**Verification against current Locked Canon (all three prompts):**

| Category | Result |
|---|---|
| Character Canon (Phase 6B.2 v1.3) | PASS — identical to the already-Approved FPP-CHAR-001 prompt on every character-identity word; only the Emotion Modifier clause changes per state. |
| Costume Canon (Phase 6B.3 v3.0) | PASS — no costume word present in any of the three prompts differs from FPP-CHAR-001's own Approved text; costume compliance remains a post-generation Canon Compliance criterion, not a prompt-text element, exactly as already established. |
| Color Language / Kael Eye-Glow Specification | PASS — each modifier's glow-behavior language is quoted verbatim from `color-language.md`'s own Locked table; no intensity or color invented beyond what that table specifies for each state. |
| Rendering Register | PASS — no rendering-style word altered from FPP-CHAR-001's own Approved prompt. |
| Forbidden Elements | PASS — no blacklist item present in any of the three prompt texts. |
| Known failure-mode guardrails (`prompt-library.md`) | Carried forward explicitly: Activation/Breakdown modifiers require the base prompt's "shallow depth of field" and "cinematic lighting" phrases to stay intact to avoid over-busy compositions — both phrases are present unaltered in all three prompts above. |

**A distinct rule, checked and found not to apply here:** the Thumbnail Prompt Template's own rule ("the emotion modifier state used must match a moment that actually occurs in the referenced episode... never generate an Activation or Breakdown thumbnail for an episode where that state doesn't occur on-screen," `prompt-library.md`) governs the separate Thumbnail Prompt Template specifically, not the Base-Prompt-plus-Emotion-Modifier reference-still combination this package uses — the same combination already used, without episode-specific gating, for FPP-CHAR-001's Calm State. These are Expression Reference stills, not episode thumbnails; the episode-matching rule does not block this package.

**No new contradiction found on any axis.**

### Validation Process (unchanged from precedent)

Per Phase 6K.0 v2.2's Two-Stage framework, once external generation occurs:

- **Stage 1 (Creative Validation):** Canon Compliance, Character Compliance, Costume Compliance, Rendering Register, Forbidden Elements, Overall Artistic Direction — plus, specific to this package, direct verification that each state's eye-glow behavior/intensity and expression match its own Locked Emotion Modifier and Kael Eye-Glow Specification exactly (not merely "some cyan glow present"). May proceed on a Founder-attached chat image without that image existing as a repository file.
- **Stage 2 (Technical Certification):** Resolution, File Format, Color Space, Naming Convention, Folder Placement, File Integrity — requires the actual original production file delivered to the repository.
- No asset may be registered until both stages pass, exactly as enforced for FPP-CHAR-001 through FPP-CHAR-004.

**No artwork generated. No asset registered.**

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — all three prompt components verified against their own Locked/Approved source, not re-derived or paraphrased; the Production Format decision is explicitly flagged as interpretive precedent-continuation, not presented as a Founder-specified value. |
| Alignment Audit | PASS — no artwork generated; no canon modified; no asset registered; no new emotional category created (the four-state list is confirmed closed, not expanded). |

**Determination: PASS.**

## Dependency Verification

| Check | Result |
|---|---|
| Package correctly depends on the same Base Prompt Template and Emotion Modifiers already governing FPP-CHAR-001 | PASS — cited directly in the Absolute Authority chain; no modifier reworded. |
| No costume, silhouette, or Turnaround-view content introduced | PASS — this package addresses expression/eye-glow states only. |
| No re-verification gap silently skipped | PASS — Character Canon, Costume Canon, Color Language, Rendering Register, and Forbidden Elements were each checked again for all three specific prompts, not assumed carried over from FPP-CHAR-001 because the wording is similar. |
| Coverage audit performed against the actual Locked Emotion Modifiers table, not assumed | PASS — Step 1 confirms exactly three gaps exist and no fourth or fifth state exists anywhere in Locked Canon. |

**Determination: PASS.**

## Founder Approval

**Pending Founder Review.** This package defines and verifies three Final Production Prompts (Conflict, Activation, Breakdown), an Expression Reference Standard, a production format determination, and a validation process — no artwork has been generated, no canon touched, and no asset registered. Ready for external generation upon Founder authorization, following the same path already proven for FPP-CHAR-001 through FPP-CHAR-004.

---

### Changelog
`[v1.0 — 2026-07-21] Compiled per "Founder Directive — Kael Expression Reference Production Package." Audited Expression coverage against the Locked Emotion Modifiers table (`prompt-library.md`) and found 3 of 4 states missing (Conflict, Activation, Breakdown) — confirmed no fifth state exists anywhere in Locked Canon, consistent with the directive's own instruction not to add states without approval. Noted, without expanding scope, that Kael's Character Production Package separately carries a broader 10-expression Expression Library mapped onto these same four governing states. Defined an Expression Reference Standard preserving character identity, costume, and rendering register unchanged across all three missing states, with only expression/eye-glow/lighting varying per each state's own Locked Emotion Modifier. Determined production format as individual bust/portrait files (following FPP-CHAR-001's own precedent, not the Turnaround Set's full-body format), assigned FPP-CHAR-005/006/007 per the established distinct-ID-per-deliverable pattern, and set naming convention, output specs (4000×4000px, PNG, sRGB), and folder destination identical to all prior Concept Art assets. Assembled and verified three Final Production Prompts (Base Prompt Template + the relevant Locked Emotion Modifier, each quoted verbatim, no View Modifier) against Character Canon, Costume Canon, Color Language/Eye-Glow Specification, Rendering Register, and Forbidden Elements — no contradiction found on any axis. Confirmed the Thumbnail Prompt Template's episode-matching rule does not apply to this Base+Emotion-Modifier reference-still format. Restated the unchanged Two-Stage Validation process. No artwork generated; no canon modified; no asset registered; no new emotional category created. Status: "Compiled — Pending Founder Review."`
