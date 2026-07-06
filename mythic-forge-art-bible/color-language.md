# Color Language
### Mythic Forge Art Bible v2.0

**Governs:** per-Realm palette assignment, saturation and tone restrictions, the character accent-evolution system, and Kael's fixed eye-glow specification.

---

## Core Palette Rule **[LOCKED]**

Each of the Seven Great Realms carries one anchor hue family and one accent hue, derived directly from its Aspect as already established in the Mythic Bible (Section 3). No two Realms may share a dominant hue family, and an assignment below may never be reassigned once used in production (Bible Section 55, Rule "history persists," applied visually).

| Realm | Aspect | Anchor Hue Family | Accent |
|---|---|---|---|
| Emberfall | Flame / Ambition | Warm red–orange, black iron | Molten gold |
| The Tidewrought | Tide / Memory | Teal, blue-grey, pearl | Faded sea-glass green |
| The Ironroot Expanse | Stone / Endurance | Umber, ochre, granite grey | Deep copper |
| The Windmere Reaches | Wind / Freedom | Pale sky-blue, cloud-white, silver | Storm-violet |
| The Duskmarch | Shadow / Death | Ash-grey, charcoal, deep violet | Icy blue-cyan (Sigil/Echo glow) |
| The Solvane Dominion | Light / Judgment | Ivory, gold, marble-white | Deep crimson (seal/authority accent) |
| The Verdant Wilds | Growth / Life | Deep green, moss, bark-brown | Warm amber-gold |

## Saturation and Tone Restrictions **[LOCKED]**

- The baseline palette across all Realms leans **desaturated-naturalistic**. Full saturation is not a default — it is an earned accent.
- Saturation is reserved for: Essence/Sigil glow effects, Legendary Beast appearances, and any Aurothi-adjacent moment. A saturated color appearing on screen should always mean *something significant is active here* — never decorative background color.
- This restriction is the direct visual expression of "power has a cost" (Bible Section 21): color intensity is rationed the same way power is.

## Accent Evolution System **[LIVING SECTION]**

A named character's personal accent color may shift subtly as their Power Progression (Bible Section 20) advances — never abruptly, and never as a substitute for earned story progress.

**Example (Kael):** his Umbral-Essence accent (per the Duskmarch's icy blue-cyan Sigil/Echo glow) should read as a single, thin thread of light early in Season One. Once he gains a real Echo-communion foothold (Series Bible Episode 19–20), the accent may gain a second, faint secondary color thread reflecting Aris's influence — a visual signal of growth, logged on his Character Reference Sheet (Production OS Section 11) the moment the change is made canon, not before.

## Kael Eye-Glow Specification **[LOCKED]**

Kael's eyes are a fixed physical signature (Bible Appendix A, Series Bible Appendix A) — icy blue-cyan at baseline, intensifying with his Echo-Sensitivity state. This applies identically in both render registers (`visual-development-guide.md`):

| State | Glow Behavior | Color Value |
|---|---|---|
| Calm | Soft, stable glow | Muted icy cyan, low intensity |
| Conflict | Flickering, unstable glow | Icy cyan with irregular flicker, medium intensity |
| Activation (communion / strong Sigilcraft cast) | Intense, sharp glow | Saturated icy cyan-white, high intensity — subject to the Saturation Restriction above, since activation is exactly the kind of "something significant is happening" moment saturation is reserved for |
| Breakdown (bond fraying, Hollowing onset) | Fragmented, unstable glow | Icy cyan breaking into visible discontinuous fragments, with faint desaturation at the edges |

**Rule:** never render Kael's eyes at Activation intensity in a scene where his Echo-Sensitivity isn't actually active — this glow is a diagnostic readout of his internal state, not a stylistic default.

---

*Cross-references: `lighting-system.md`, `materials-and-textures.md`, `global-consistency-rules.md`, `prompt-library.md`.*

### Changelog
`[v1.0 — 2026-07-06] Initial color language established.`
`[v2.0 — 2026-07-06] Tightened Duskmarch accent to "icy blue-cyan" and added the Kael Eye-Glow Specification table (calm/conflict/activation/breakdown), syncing with Mythic Bible v3.0 Appendix A and Series Bible v2.0 Appendix A.`
