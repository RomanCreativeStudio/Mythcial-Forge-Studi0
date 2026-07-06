# MYTHIC FORGE STUDIOS — ART BIBLE
## Visual Development Guide
### Version 2.0 — Master Index

**Classification:** Internal — Visual Law
**Scope:** Governs the visual rendering of every Mythic Forge Studios property, starting with *Kael: The Shattered Realms*.
**Relationship to other documents:** The Mythic Bible (`bible/Mythic_Bible_v3.0.md`) and Series Bibles are authoritative on *what things mean*. This Art Bible is authoritative on *how everything looks*. Where a production decision is purely visual, this document outranks personal taste — "what looks cool" loses to "what this document specifies" (see `global-consistency-rules.md`).

---

### Core Visual Identity — Two Registers

Mythic Forge Studios uses **two deliberately distinct visual registers**, each with its own job. Neither replaces the other; using the wrong one for the wrong purpose is a Quality Assurance failure (Production OS Section 38).

**1. Production Render Register — Painterly Cinematic 3D.** Governs the actual animated footage. Semi-stylized 3D rendering with painterly light and texture treatment — visible brushwork-like surface quality, soft directional light falloff, atmospheric depth. This sits deliberately between flat cel-shading and photoreal hyperrealism: prestige animated-feature realism. No shot may shift render register without a documented, deliberate exception (`global-consistency-rules.md`).

**2. Promotional Still Register — Semi-Realistic Cinematic.** Governs standalone AI-generated stills that are never part of the animated footage itself: thumbnails, character concept art, and social/marketing images. This register is detailed, painterly-lit, and cinematic like the Production register, and may carry a semi-realistic anime-influenced illustration quality — but it is not flat, TV-style cel-shading, and it still obeys every other rule in this Art Bible (color, lighting, forbidden elements). See `forbidden-elements.md` for the precise line between "anime-influenced illustration" (permitted here) and "flat anime-signature rendering" (forbidden everywhere). See `prompt-library.md` for the reusable prompt templates that implement this register.

Both registers share the same Color Language, Lighting System, Materials, and Magic Visual Rules — a character or Realm must be recognizably the same subject whether seen in a rendered episode or a promotional still.

### The Five Pillars

1. **Cost is visible.** Every use of power must look like it costs something — strain, light dimming under exertion, fatigue — never a free, decorative flourish (`magic-visual-rules.md`).
2. **Realism grounds the myth.** Materials, light, and physics behave plausibly; stylization lives in color and mood, never in broken material logic (`materials-and-textures.md`, `lighting-system.md`).
3. **Every Realm has a distinct visual signature.** No two of the Seven Great Realms may share a dominant palette, architectural language, or silhouette family (`color-language.md`, `environment-design-rules.md`).
4. **Light carries emotion.** Lighting mode is chosen by story beat, not by scene convenience (`lighting-system.md`, `cinematic-mood-guide.md`).
5. **Nothing non-diegetic.** No modern branding, sci-fi tech, or out-of-world visual language intrudes on the frame (`forbidden-elements.md`).

### File Index

| File | Purpose |
|---|---|
| `camera-language.md` | Lens choice, framing, composition, camera movement |
| `lighting-system.md` | Natural, night, and magical lighting; the three emotional lighting modes |
| `color-language.md` | Per-Realm palette assignments, saturation rules, character accent evolution |
| `materials-and-textures.md` | Surface behavior for stone, cloth, metal, wood; imperfection requirements |
| `environment-design-rules.md` | Ruins, settlements, temples, and environmental storytelling logic |
| `magic-visual-rules.md` | Allowed vs. forbidden magic visuals; intensity scaling by Path/Sigil tier |
| `cinematic-mood-guide.md` | Per-Realm emotional key; brand-tone translation into visuals |
| `forbidden-elements.md` | Strict blacklist enforced across all production |
| `global-consistency-rules.md` | Cross-document "never changes" rules and conflict resolution |
| `prompt-library.md` | Reusable AI image-generation prompt templates (Promotional Still Register) |

### Authority and Versioning

This Art Bible follows the studio-wide `v{major}.{minor}` convention (Studio OS Section 30). A **[LOCKED]** rule requires founder/Creative Director sign-off to change; a **[LIVING]** rule may be expanded within its existing framework via the same Review Workflow used for world canon (Bible Section 56).

All character designs — including Kael and the full Series 01 cast — must obey every file in this Art Bible without exception.

---

*End of Visual Development Guide v2.0.*

### Changelog
`[v1.0 — 2026-07-06] Initial Art Bible established across all 10 files.`
`[v2.0 — 2026-07-06] Introduced the two-register system (Production Render Register: Painterly Cinematic 3D; Promotional Still Register: Semi-Realistic Cinematic) to reconcile the animated show's painterly identity with mandatory semi-realistic anime-influenced prompt templates for thumbnails and promotional stills. Added prompt-library.md to the File Index. Synced world canon reference to Mythic Bible v3.0.`
