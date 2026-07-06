# Prompt Library
### Mythic Forge Art Bible v1.0

**Governs:** reusable AI image-generation prompt templates for the **Promotional Still Register** only (`visual-development-guide.md`). These templates never generate in-show animation footage — they produce thumbnails, character concept stills, and social/marketing images. Logged per Production OS Section 34 (Prompt Management SOP): each entry lists Purpose, the template itself, an example modifier set, and known failure modes.

---

## Kael Base Prompt Template **[LOCKED]**

**Purpose:** Generate a consistent, on-model still of Kael for thumbnails, concept art, and promotional stills.

**Template (current, Season One/Two — the only version approved for use):**
```
Teenage male protagonist named Kael, semi-realistic anime cinematic style, Duskmarch
Wardenate monastery background, dark monastic techwear-adjacent outfit with subtle icy
cyan accents, glowing icy-blue cyan eyes, emotional expression focus, cinematic lighting,
high detail face, shallow depth of field, moody atmosphere, identity/mystery theme
```

**Restricted variant — do not use:** a futuristic-megacity background variant of this template exists conceptually as Kael's true-nature framing, tied to the restricted True Reality Codex (Bible `Fracture_Protocol_TrueReality_v1.0.md`). It is intentionally not written out here. It may not be generated, prompted, or referenced in any production or promotional asset before that reveal is earned in-story and explicitly approved via Canon Change (Series Bible Section 20, Reveal Discipline).

**Known failure modes:**
- Generic image models will often default to flat cel-shading if "anime" is emphasized too strongly without "semi-realistic," "cinematic," and "painterly light" also present — always keep all three qualifiers in the prompt together.
- Eye color drifts toward generic blue without "icy," "cyan," and an explicit glow-intensity modifier (see below) — always pair with an Emotion Modifier.
- Outfit silhouette can drift toward unrelated fantasy tropes if "Duskmarch Wardenate cadet" and the specific silhouette cues from `materials-and-textures.md` aren't included.

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

## World Prompt Template **[LOCKED]**

**Purpose:** Generate environment concept stills consistent with a specific Realm's established visual identity (`environment-design-rules.md`, `color-language.md`).

**Template:**
```
[Realm name] environment, [Realm anchor hue family from color-language.md],
[Realm architectural motif from environment-design-rules.md], cinematic fantasy
atmosphere, emotional tone lighting matching [Realm emotional key from
cinematic-mood-guide.md], high detail environment, painterly cinematic lighting,
moody atmosphere
```

**Known failure modes:** omitting the Realm-specific hue/motif fields causes generic "fantasy castle" or "generic sci-fi city" output that doesn't read as this world specifically — always fill in the bracketed fields from the referenced files rather than leaving generic descriptors.

---

## Thumbnail Prompt Template **[LOCKED]**

**Purpose:** Generate on-brand, non-misleading thumbnails per Production OS Section 23 (Thumbnail SOP).

**Template:**
```
Extreme close-up of Kael's face, glowing icy-blue cyan eyes at [emotion modifier state],
emotional intensity, cinematic lighting contrast, dark Duskmarch-toned background, high
detail, dramatic framing, YouTube thumbnail style, semi-realistic cinematic hybrid
```

**Rule:** the emotion modifier state used must match a moment that actually occurs in the referenced episode (Production OS Thumbnail Checklist) — never generate an Activation or Breakdown thumbnail for an episode where that state doesn't occur on-screen.

**Known failure modes:** thumbnail-style prompts tend to over-saturate the eye glow beyond the Saturation Restriction (`color-language.md`) if "extreme close-up" and "dramatic" aren't balanced against the specific emotion modifier's intensity — always pull the exact modifier from the Emotion Modifiers table rather than improvising intensity language.

---

*Cross-references: `visual-development-guide.md`, `color-language.md`, `forbidden-elements.md`, Production OS Sections 34–36.*

### Changelog
`[v1.0 — 2026-07-06] Initial prompt library established: Kael Base Prompt, Emotion Modifiers, World Prompt Template, Thumbnail Prompt Template — adapted for the Promotional Still Register with the futuristic-megacity framing flagged as restricted, Reveal-Discipline-gated material.`
