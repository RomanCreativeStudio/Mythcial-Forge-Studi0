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
