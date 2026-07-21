# Prompt Library
### Mythic Forge Art Bible v2.0

**Governs:** reusable AI image-generation prompt templates for both animated-footage reference and promotional stills (thumbnails, character concept stills, social/marketing images) — a single register now governs both (`visual-development-guide.md`). Logged per Production OS Section 34 (Prompt Management SOP): each entry lists Purpose, the template itself, an example modifier set, and known failure modes. The base templates below are canon-locked verbatim in the Master System Prompt, Section 9 — this file expands them with modifiers and failure-mode notes.

---

## Kael Base Prompt Template **[LOCKED — Master System Prompt Section 9]**

**Purpose:** Generate a consistent, on-model still of Kael.

**Template:**
```
Late teen to early adult male protagonist named Kael (17–20), semi-realistic anime
cinematic style, futuristic dystopian megacity environment, dark techwear outfit
with subtle cyan accents, glowing icy-blue cyan eyes, emotional expression focus,
cinematic lighting, high detail face, shallow depth of field, moody atmosphere,
sci-fi identity theme
```

**Known failure modes:**
- Generic image models will often default to flat cel-shading if "anime" is emphasized too strongly without "semi-realistic" and "cinematic" also present — always keep both qualifiers in the prompt together.
- Eye color drifts toward generic blue without "icy," "cyan," and an explicit glow-intensity modifier (see below) — always pair with an Emotion Modifier.
- Outfit silhouette can drift toward unrelated genre tropes if "dark techwear" and the specific silhouette cues from `materials-and-textures.md` aren't included.
- Age can drift outside the 17–20 canon range if the numeric range is dropped from the prompt — always include it explicitly.

---

## Emotion Modifiers **[LOCKED]**

**Purpose:** Append to the Kael Base Prompt to produce the correct eye-glow state per `color-language.md`'s Kael Eye-Glow Specification. Never used standalone.

| State | Modifier |
|---|---|
| Calm | soft stable eye glow, calm expression, gentle lighting |
| Conflict | flickering unstable eye glow, tense expression, slight visual distortion |
| Activation | intense sharp eye glow, sharp contrast lighting, focused/powerful expression |
| Breakdown | fragmented unstable eye glow, visual noise, motion blur, distressed expression |

**Known failure modes:** using an Activation or Breakdown modifier without the base prompt's "shallow depth of field" and "cinematic lighting" phrases tends to produce over-busy, unreadable compositions — keep the full base prompt intact and only append the modifier.

---

## Mira Base Prompt Template **[LOCKED — Phase 1.2 Mira Prompt Foundation]**

**Purpose:** Generate a consistent, on-model still of Mira Solenne Valeris. Sourced entirely from her Character Production Package, Phase 6B.2 (Visual Canon), and Phase 6B.3 (Costume Canon) — no detail invented beyond what those documents already Lock. Not yet cross-referenced into the Master System Prompt's own Section 9, unlike Kael's — flagged so this template isn't mistaken for the same authority tier until a future Founder directive promotes it there.

**Template:**
```
Young adult female civilian reconstruction specialist named Mira (age 20), of
Spanish heritage, semi-realistic anime cinematic style, futuristic dystopian
megacity environment, practical civilian work-wear in warm earth tones and
work-wear neutrals, ordinary steady human eyes, high-detail hands visibly
marked by hands-on reconstruction work (calluses, small working scars),
emotional expression focus, cinematic lighting, high detail face, shallow
depth of field, grounded warm atmosphere, sci-fi identity theme
```

**Deliberate deviation from Kael's template, disclosed rather than silently mirrored:** Kael's template includes "glowing icy-blue cyan eyes" as its signature-feature clause; that clause is **omitted for Mira**, replaced with "ordinary steady human eyes" and a parallel "high-detail hands" clause. This is not a stylistic choice — Phase 6B.2 §4 item 20 (Do Not Do) explicitly states "never assign her a Signal/eye-glow system — that remains exclusively Kael's," and item 15 confirms "her hands... are her equivalent of Kael's eye-glow: the one feature that visually encodes her entire identity." The base atmosphere clause is "grounded warm atmosphere" rather than Kael's "moody atmosphere," matching her Locked baseline Emotional Presence ("warm and steady by default, quiet rather than performative," Phase 6B.2 item 14) rather than importing his tonal word by default.

**Updated 2026-07-21 per "Founder Directive — Mira Character Canon Amendment (Spanish Heritage)":** added ", of Spanish heritage" directly after her age, mirroring the placement/weight Kael's template gives his own age-range anchor. This is the only content change — it deliberately does not add or fix any specific hair color, eye color, or skin tone; those remain open per Phase 6B.2's own Production Notes and are now further governed by Phase 6B.2 Amendment v1.4's ancestry-informed *range* guidance, not a single mandated look.

**Known failure modes:**
- Any cyan/icy-blue tint drifting into her eyes, outfit, or lighting is a direct Locked-canon violation (Phase 6B.2 Do Not Do; `color-language.md`'s reservation of cyan/icy-blue exclusively to Kael's Signal-linked phenomena) — never pair this template with any cyan-glow language from Kael's own Emotion Modifiers.
- Omitting the "high-detail hands... calluses, small working scars" clause risks generic, unmarked "clean" hands — a direct violation of her single strongest distinguishing feature (Phase 6B.2 item 10, item 20 Do Not Do).
- Generic image models will default to a idealized/glamorous civilian look if "practical," "unglamorous," and "work-wear" aren't all present together — always keep the full civilian-worker silhouette language intact (Phase 6B.2 item 3).
- Age can drift from her Locked single value (20, not a range like Kael's 17–20) if dropped from the prompt — always include it explicitly.
- "Of Spanish heritage" should never be over-specified into a single narrow phenotype or stereotyped iconography by an external generation pass — per Phase 6B.2 Amendment v1.4, it names a real ancestral range, not a fixed look; if a generation tool defaults to one narrow trope, correct at the Creative Validation stage, not by editing this template.

---

## Mira Emotion Modifiers **[LOCKED — Phase 1.2 Mira Prompt Foundation]**

**Purpose:** Append to the Mira Base Prompt to produce the correct expression/lighting/atmosphere state. **Structurally different from Kael's Emotion Modifiers, disclosed explicitly:** Kael's four states are built around his own Locked eye-glow diagnostic system (`color-language.md`'s Kael Eye-Glow Specification); no equivalent system exists for Mira (Phase 6B.2 §4 item 7, item 20). These four modifiers instead draw on her own Locked Expression Library (Character Production Package, Section 5), her Locked Posture rule (Phase 6B.2 item 12), and the general-purpose Emotional Lighting Modes every human character shares (`lighting-system.md`: Grounded / Charged / Wounded — three modes, not four, so Conflict and Activation both draw on Charged, differentiated by expression and atmosphere rather than by a fourth lighting mode that doesn't exist). Never used standalone; never combined with any eye-glow language from Kael's own modifiers.

| State | Modifier | Grounding |
|---|---|---|
| Calm | steady open expression, grounded natural lighting, quiet unguarded posture | Phase 6B.2 item 12 (open/grounded by default); `lighting-system.md` Grounded mode (naturalistic, motivated, low contrast). |
| Conflict | guarded tense expression, charged directional lighting, closed protective posture | Phase 6B.2 item 12 (visibly closes/guards in displacement-backstory or trust-tension scenes); `lighting-system.md` Charged mode (heightened contrast, strong directional key light). |
| Activation | focused determined expression, charged purposeful lighting, hands-engaged working posture | Character Production Package Expression Library, "Focused"/"Determined" entries (Episode 33 reconstruction/technical work, her active-role beginning); `lighting-system.md` Charged mode, same as Conflict but distinguished by expression and posture, not lighting — carries no Signal/Cipher-work meaning, unlike Kael's Activation. |
| Breakdown | quiet grief-touched expression, wounded desaturated lighting with one warm light source retained, restrained emotional weight | Character Production Package Expression Library, "Grief" entry; `lighting-system.md` Wounded mode (desaturated, harsh single-source/top-down light) and its own Locked Rule that at least one warm light source must remain visible even in a Wounded-lit scene; her Voice Requirements guidance that unresolved pain is "carried, not cured" — deliberately restrained, not the fragmented/glitching visual-noise treatment Kael's Breakdown modifier uses, since that treatment specifically represents his Signal system failing, which has no Mira equivalent. |

**Known failure modes:** applying "visual noise," "motion blur," or any glow/glitch-eye language to Mira's Breakdown state imports Kael's Signal-failure visual grammar onto a character who has no Signal system — always keep her Breakdown restrained and human, per the Wounded lighting mode's own desaturated-not-distorted definition.

---

## World Prompt Template **[LOCKED — Master System Prompt Section 9]**

**Purpose:** Generate megacity environment concept stills.

**Template:**
```
Futuristic controlled dystopian megacity with layered vertical structure, sterile
upper zones, regulated mid zones, corrupted lower fracture zones, cinematic
lighting, surveillance-controlled society, emotional sci-fi atmosphere
```

**Layer-specific variant fields** (fill in from `environment-design-rules.md`, `color-language.md`): specify which of the four layers (Upper Grid / Mid Zone / Lower Sector / Unknown Layer) the still depicts, and pull that layer's palette/architectural cues rather than leaving the prompt generic.

**Known failure modes:** omitting the specific-layer field causes generic "cyberpunk city" output that doesn't read as this world's four-layer structure specifically — always specify which layer, and cross-check the palette against `color-language.md`'s three-color system (black/charcoal, cyan/icy-blue, white) rather than letting the model default to neon-rainbow cyberpunk palettes.

---

## Thumbnail Prompt Template **[LOCKED — Master System Prompt Section 9]**

**Purpose:** Generate on-brand, non-misleading thumbnails per Production OS Section 23 (Thumbnail SOP).

**Template:**
```
Extreme close-up of Kael's face, glowing cyan eyes, emotional intensity, cinematic
lighting contrast, dark futuristic background, high detail, dramatic framing,
YouTube thumbnail composition, sci-fi anime cinematic hybrid
```

**Rule:** the emotion modifier state used must match a moment that actually occurs in the referenced episode (Production OS Thumbnail Checklist) — never generate an Activation or Breakdown thumbnail for an episode where that state doesn't occur on-screen.

**Known failure modes:** thumbnail-style prompts tend to over-saturate the eye glow beyond the Saturation Restriction (`color-language.md`) if "extreme close-up" and "dramatic" aren't balanced against the specific emotion modifier's intensity — always pull the exact modifier from the Emotion Modifiers table rather than improvising intensity language.

---

*Cross-references: `visual-development-guide.md`, `color-language.md`, `forbidden-elements.md`, Production OS Sections 34–36.*

### Changelog
`[v1.0 — 2026-07-06] Initial prompt library established for the Promotional Still Register, with a futuristic-megacity Kael variant flagged as restricted pending an in-story reveal.`
`[v2.0 — 2026-07-06] Full pivot to The Fracture Protocol: the megacity framing is no longer restricted — it is the sole, overt setting. Templates updated to match the Master System Prompt's Section 9 verbatim base prompts. Single register now governs both footage reference and promotional stills.`
`[v3.0 — 2026-07-21] Added Mira's Base Prompt Template and four Emotion Modifiers per "Founder Directive — Phase 1.2: Mira Prompt Foundation," continuing from the Phase 1.1 Asset Identifier Governance Standard. Extracted only already-Locked visual information from Mira's Character Production Package, Phase 6B.2 (Visual Canon), and Phase 6B.3 (Costume Canon) — no detail invented. Built the Base Prompt Template mirroring Kael's structure (role/age, rendering style, environment, outfit, signature-feature clause, expression-focus, lighting, detail focus, depth of field, atmosphere, theme) with content specific to Mira, disclosing one deliberate structural deviation: Kael's "glowing icy-blue cyan eyes" clause is omitted entirely and replaced with "ordinary steady human eyes" plus a parallel "high-detail hands" clause, since Phase 6B.2's own Do Not Do rule explicitly forbids assigning her any Signal/eye-glow system and instead identifies her hands as her visual-identity equivalent. Built four Emotion Modifiers (Calm/Conflict/Activation/Breakdown) grounded in her own Locked Expression Library, Posture rule, and the general three-mode Emotional Lighting System (Grounded/Charged/Wounded) rather than any eye-glow behavior — disclosed that this is a structurally different modifier system from Kael's, not a literal mirror, because no equivalent diagnostic system exists for her; Conflict and Activation both draw on the Charged lighting mode (only three modes exist, not four) and are differentiated by expression/posture instead; Breakdown is deliberately restrained (quiet grief, not visual noise/motion blur/glitch), since Kael's Breakdown treatment specifically depicts his Signal system failing, which has no Mira equivalent. Verified against Character Canon, Costume Canon, Color Language (confirmed zero cyan/icy-blue anywhere in either the template or modifiers), Forbidden Elements, and Rendering Register — no contradiction found. Did not modify any Kael content in this file. Not yet cross-referenced into the Master System Prompt's own Section 9 — flagged as a distinct, lower authority tier than Kael's Section-9-Locked template until a future Founder directive promotes it.`
`[v3.1 — 2026-07-21] Updated Mira's Base Prompt Template per "Founder Directive — Mira Character Canon Amendment (Spanish Heritage)," reflecting her new Locked ancestry fact (Character Bible v1.17; Phase 6B.2 Amendment v1.4). Added ", of Spanish heritage" directly after her age, the only content change — no hair, eye, or skin color value added or fixed, consistent with Phase 6B.2 Amendment v1.4's own range-not-fixed-value guidance. Added a known-failure-mode entry warning against over-specifying this into a single narrow phenotype or stereotyped iconography. Emotion Modifiers unchanged; Kael's content unaffected.`
