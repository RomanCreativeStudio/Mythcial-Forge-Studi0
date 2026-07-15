# Asset Registry
## Mythic Forge Studios — Master Production Asset Tracker

**Classification:** Internal — Production Record
**Governing documents:** `production-bible/Fracture_Protocol_Production_Bible_v1.1.md` Section 7 (establishes this registry and its location), `brand/Mythic_Forge_Studios_Brand_Asset_Production_Guide_v1.0.md` Section 7 (extends the schema below with the Creator/Approval Date fields and the `BRAND_ASSET` category for brand assets specifically).
**Rule (Production Bible Section 7):** no asset is "real" until it is logged here — an asset that exists only as a file with no registry entry is treated as unapproved.
**Note (per Founder Decision Resolution — Phase 3A Production Standard Promotion, 2026-07-14):** this registry is the resource referenced as "Production Registry" in Phase 3A Content Production Pipeline Integration Framework directives. No separate Production Registry exists or is needed — this Asset Registry remains the sole authoritative asset-tracking registry for the studio.

This is the first entry in this registry. It exists now because the first real asset — BRA-0001, the studio's Primary Logo — has been formally approved by the Founder, which is exactly the trigger the Production Bible names for this registry to stop being a documented-but-empty placeholder.

---

## Schema

| Field | Description |
|---|---|
| Asset ID | Stable identifier for this asset across all its versions |
| Asset Name | Human-readable name |
| Category | `BRAND_ASSET` (only category populated so far) |
| Version | Current `v{major}.{minor}` |
| Status | Draft / In Review / Approved / Locked / Superseded / Retired |
| Creator | Who produced this version |
| Approval Date | Date this version was marked Approved or Locked |
| Storage Location | File path |
| Notes | Pragmatic extension beyond the base schema — flags any disclosed scope/capability limitation attached to this specific version, so it isn't lost outside the version's own Review Package |

---

## BRAND_ASSET — BRA-0001 (Primary Logo Master)

| Asset ID | Asset Name | Version | Status | Creator | Approval Date | Storage Location | Notes |
|---|---|---|---|---|---|---|---|
| BRA-0001-ICON-DARK | Primary Logo — Icon Only, Dark Version | v1.0 | **Locked** | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/mfs-logo-icon-dark_v1.0.svg` | This is the master file Brand Bible Section 3 refers to as the Icon Version. |
| BRA-0001-ICON-ONLY | Icon Only, Transparent Background | v1.0 | Locked | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/mfs-logo-icon-only_v1.0.svg` | |
| BRA-0001-ICON-MONO | Icon Only, Monochrome (Single Ink) | v1.0 | Locked | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/mfs-logo-icon-monochrome_v1.0.svg` | |
| BRA-0001-PRIMARY-DARK | Primary Logo — Full Lockup, Dark Version | v1.0 | **Locked** | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/mfs-logo-primary-dark_v1.0.svg` | This is the master file Brand Bible Section 3 refers to as the Primary Logo. |
| BRA-0001-PRIMARY-LIGHT | Primary Logo — Full Lockup, Light Version | v1.0 | Locked | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/mfs-logo-primary-light_v1.0.svg` | |
| BRA-0001-PRIMARY-WHITE | Primary Logo — Full Lockup, White-on-Transparent | v1.0 | Locked | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/mfs-logo-primary-white_v1.0.svg` | |
| BRA-0001-APP-ICON | App Icon Master (1024×1024) | v1.0 | Approved | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/derived/mfs-app-icon_v1.0.svg` | Uses a wider safety margin than native icon scale to survive platform icon-shape masking (iOS/Android); per-platform masked exports not yet produced. |
| BRA-0001-YT-AVATAR | YouTube Avatar / Profile Picture (800×800) | v1.0 | Approved | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/youtube/channel-art/mfs-youtube-avatar_v1.0.svg` | Verified by an actual 800×800 circular-crop composite test — zero clipping, content kept within 72% of frame radius (Kit requires ≤85%). |
| BRA-0001-YT-WATERMARK | YouTube Subscribe Watermark | v1.0 | Approved | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/youtube/channel-art/mfs-youtube-watermark-icon_v1.0.png` | 300×300px export (2× the Kit's 150×150 minimum). Reduced-opacity treatment is applied at placement time, not baked into the file, per the "one master, scaled per context" rule. |
| BRA-0001-YT-BANNER | YouTube Channel Banner (2560×1440) | v1.0 | Approved | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/youtube/banners/mfs-youtube-banner-primary_v1.0.svg` | **Disclosed gap:** flat Void Black composition matching the reference's layout and safe-area placement only — does not reproduce the reference's photographic/cinematic atmosphere, since no image-generation or photo-compositing tool exists in this environment. Verified against YouTube's real 1546×423 safe area by render + overlay test. |
| BRA-0001-FAVICON | Favicon (ICO + 32×32 / 16×16 PNG) | v1.0 | Approved | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/exports/mfs-favicon_v1.0.ico`, `mfs-favicon-32x32_v1.0.png`, `mfs-favicon-16x16_v1.0.png` | 16px legibility consistent with the documented v0.11/v0.12 finding: silhouette holds, fracture detail reduces toward noise at this size. |
| BRA-0001-EXPORTS | Raster export set — PNG 1×/2×/3×, transparent PNG | v1.0 | Approved | AI-assisted (Claude), reviewed and approved by Founder | 2026-07-08 | `brand/assets/logos/exports/` | Per Brand Bible Section 14 Asset Standards. **Disclosed gap:** Print Files (CMYK-converted PDF/EPS, 300dpi) not produced — no CMYK conversion or PDF/EPS generation tool exists in this environment. |

## BRAND_ASSET — BRA-0001A (Signature Cinematic Presentation)

Per the Founder Directive amendment (`brand/Mythic_Forge_Studios_BRA-0001A_Brand_Bible_Amendment_Signature_Cinematic_Presentation.md`, Brand Bible Section 3 v1.1): all assets below are approved renderings of the same canonical BRA-0001 logo geometry, not a separate logo. Ingested into the repository across several rounds (delivered via direct upload to the branch, not through this session's chat, since this environment has no tool to export chat-submitted images to disk). Every file verified as valid and uncorrupted before registration, moved via `git mv` (no re-encoding) — actual dimensions/format measured directly from each file, never assumed from a suggested filename or a prior version's spec.

| Asset ID | Asset Name | Version | Status | Creator | Approval Date | Storage Location | Notes |
|---|---|---|---|---|---|---|---|
| BRA-0001A-CINEMATIC-LOGO | Signature Cinematic Presentation — Standalone Logo Artwork | v1.0 | **Locked** | External (submitted by Founder), reviewed by Claude, approved by Founder | 2026-07-08 | `brand/assets/reference/logo/mfs-logo-signature-cinematic_v1.0.jpg` | 841×634px, JPEG (the suggested filename specified `.png`; actual delivered file is JPEG, so the `.jpg` extension was used instead of misrepresenting the format). Structural geometry (double horn, notch-origin fracture, shard-above-notch) verified consistent with the Locked BRA-0001 v1.0 master, based on repeated visual comparison during the v0.11/v0.12 tracing work. Pixel-exact geometric equivalence still not verifiable (raster, not vector data). |
| BRA-0001A-CINEMATIC-BANNER | Signature Cinematic Presentation — Official YouTube Banner | v1.0 | **Superseded** | External (submitted by Founder), reviewed by Claude, approved by Founder | 2026-07-08 | *File removed by Founder* — was `brand/assets/reference/youtube/mfs-youtube-banner-signature-cinematic_v1.0.jpg` | Wrong aspect ratio for the banner canvas (1982×368px, 5.39:1, vs. the 2560×1440 canvas's 1.78:1). Deleted directly from the repository by the Founder (`git log`: "Delete brand/assets/reference/youtube/mfs-youtube-banner-signature-cinematic_v1.0.jpg") after v1.1 superseded it. Recorded as Superseded rather than silently dropped, per the "nothing disappears without a record" rule. |
| BRA-0001A-CINEMATIC-BANNER | Signature Cinematic Presentation — Backup/Alternate Banner | v1.1 | **Approved** (kept as backup, not primary) | External (submitted by Founder), reviewed by Claude, approved by Founder | 2026-07-08 | `brand/assets/reference/youtube/mfs-youtube-banner-signature-cinematic_v1.1.png` | Corrected replacement for v1.0's aspect-ratio problem: PNG, 1672×941px, 1.7768:1 — matches the 2560×1440 canvas's 16:9 ratio. Below the specified 2560×1440 master resolution (correct proportions, would need upscaling for exact spec). Uses the correct Locked tagline ("Forging Worlds. Creating Legends."), verified by direct inspection. **Downgraded from Locked to Approved (kept, not primary) 2026-07-08** at explicit Founder request when v1.2 was designated the official banner — "I'll keep the other one but have this in case." Not deleted; available as an alternate. |
| BRA-0001A-CINEMATIC-BANNER | Signature Cinematic Presentation — Official YouTube Banner | v1.2 | **Locked** | External (submitted by Founder), reviewed by Claude, approved by Founder | 2026-07-08 | `brand/assets/reference/youtube/mfs-youtube-banner-signature-cinematic_v1.2.png` | **Current official banner**, per explicit Founder designation. PNG, 1672×941px, 1.7768:1 — same aspect-ratio profile as v1.1 (matches the 2560×1440 canvas's 16:9 ratio; same disclosed resolution-shortfall gap as v1.1, would need upscaling for exact 2560×1440 spec). Same scene composition as v1.1 with a small added ornamental divider beneath the tagline. Correct Locked tagline ("Forging Worlds. Creating Legends.") verified by direct inspection. Structural logo geometry (double horn, notch-origin fracture, shard-above-notch) consistent with the Locked BRA-0001 v1.0 master. |

---

## FRACTURE_PROTOCOL_PRODUCTION — Character & Environment Backlog

**Added per "Founder Directive — Phase 6.0 & Phase 6A Production Planning Framework (v1.0)," Phase 6A's own explicit "Asset Registry Population" instruction: populate using only Approved Screenplay requirements, invent nothing, flag rather than fabricate any missing information.**

Every item below is sourced directly from the 36 Approved Phase 5B screenplays' own Section 5 (Asset Requirements) tables, cross-referenced against `bible/Fracture_Protocol_Phase6A_Master_Production_Roadmap_v1.0.md`. None of these assets exist as production files yet — no Creator, Approval Date, or Storage Location can be populated for any of them, so a new status value, **Required — Not Yet Produced**, is used rather than misrepresenting them as Draft/In Review/Approved (all of which imply work has begun). This category will migrate entries into the standard schema above as each asset actually enters production.

### Characters

| Asset ID | Asset Name | Category | Status | Priority | Episodes Used | Notes |
|---|---|---|---|---|---|---|
| FPP-CHAR-001 | Kael Aurelian Veyr | Character | Required — Not Yet Produced | 1 (highest) | All 36 episodes | No costume, expression-sheet, or variant detail specified in any screenplay beyond narrative production notes (e.g., "rank-marker variant," "strain/injury state variant") flagged in Episodes 24–25 — not a formal spec. Flagged, not fabricated. |
| FPP-CHAR-002 | Cassian Veyrion Aurelian | Character | Required — Not Yet Produced | 2 | 16, 17, 21, 24, 26–31, 34–36 (16 episodes) | No costume or expression-sheet detail specified in any screenplay. |
| FPP-CHAR-003 | Mira Solenne Valeris | Character | Required — Not Yet Produced | 2 | 5, 19, 20, 24–26, 33–36 (11 episodes) | No costume or expression-sheet detail specified in any screenplay. |
| FPP-CHAR-004 | The Guardian | Character | Required — Not Yet Produced | 2 | 4, 8, 18, 20, 24, 25, 32, 34, 36 (9 episodes) | No production design spec exists in any screenplay; non-humanoid per World Bible/Character Bible framing only, not a model spec. |
| — | Titan Aurel Veyran | N/A | **Not applicable — no physical asset required** | N/A | Referenced only (6, 26, 36) | Confirmed zero on-screen speaking or physical appearances across all 36 screenplays (Phase 5C, Pass 2); legacy-only per Phase 5A.2's own rule. |

### Environments (Priority 1–2, highest reuse)

| Asset ID | Asset Name | Category | Status | Priority | Episodes Used | Notes |
|---|---|---|---|---|---|---|
| FPP-ENV-001 | Ward Station Seven | Environment | Required — Not Yet Produced | 1 (highest) | Season One recurring (1–12), 22, 23, 27 | Saga's most-used single location. |
| FPP-ENV-002 | Cassian's Private Interior (Ascendant Core) | Environment | Required — Not Yet Produced | 2 | 17, 24, 25, 28, 30, 31 | |
| FPP-ENV-003 | Guardian/Kael Partnership Environment | Environment | Required — Not Yet Produced | 2 | 18, 20, 24, 25, 32, 34, 36 | |
| FPP-ENV-004 | Reconstruction-Work Environment | Environment | Required — Not Yet Produced | 2 | 19, 24, 25, 33, 34, 35, 36 | |
| FPP-ENV-005 | Formal Meeting Environment | Environment | Required — Not Yet Produced | 2 | 16, 17, 21 | |

### Environments (Priority 3–4, moderate/single use)

| Asset ID | Asset Name | Category | Status | Priority | Episodes Used | Notes |
|---|---|---|---|---|---|---|
| FPP-ENV-006 | Night Haven Institutional Space | Environment | Required — Not Yet Produced | 3 | 14, 22 | |
| FPP-ENV-007 | Ascendant Network World-Scale Environment | Environment | Required — Not Yet Produced | 3 | 15, 22 | |
| FPP-ENV-008 | Doctrine Institutional Environment | Environment | Required — Not Yet Produced | 3 | 27, 34 | Distinct from Cassian's private interior. |
| FPP-ENV-009 | Neutral Private Meeting Environment | Environment | Required — Not Yet Produced | 4 (lowest) | 29 | |
| FPP-ENV-010 | Populated Civilian Area (Lower Sector/Mid Zone) | Environment | Required — Not Yet Produced | 4 (lowest) | 22, 23 | |
| FPP-ENV-011...n | Remaining single/low-frequency Season One and Arc Two institutional and civilian environments (~18 additional locations) | Environment | Required — Not Yet Produced | 4 (lowest) | Various, 1–2 episodes each | Individually enumerable from each screenplay's own Location List when production reaches that episode; not itemized further here to avoid inventing IDs for locations not yet needed. |

### Props, Technology, VFX

**No entries.** Zero specific props, weapons, vehicles, technology items, or new visual effects are named in any of the 36 Approved screenplays (each states "None required beyond what's already Locked" or equivalent). Nothing is logged here because nothing exists in Approved material to log — flagged as confirmed-empty, not omitted.

### Audio

**No entries.** No specific music theme, sound effect, or voice-cast asset exists yet for any of the 4 core characters. Voice casting is flagged as an open production dependency in `bible/Fracture_Protocol_Phase6A_Master_Production_Roadmap_v1.0.md` (Audio Production Plan) — not logged here as an asset since no casting decision has been made to log.

---

**Superseded (retained for historical record, not deleted):**

| Asset ID | Version | Status | Storage Location | Superseded By |
|---|---|---|---|---|
| BRA-0001-CANDIDATE-A | v0.9 | Superseded | `brand/assets/logos/drafts/*_v0.9.svg` | BRA-0001-ICON-DARK v1.0 |
| BRA-0001-CANDIDATE-B | v0.10 | Superseded | `brand/assets/logos/drafts/*_v0.10.svg` | BRA-0001-ICON-DARK v1.0 |
| BRA-0001-CANDIDATE-C | v0.11 | Superseded | `brand/assets/logos/drafts/*_v0.11.svg` | v0.12 (then promoted to v1.0) |
| BRA-0001-AVATAR-DRAFT | v0.12 | Superseded | `brand/assets/logos/derived/mfs-logo-avatar_v0.12.svg` | BRA-0001-YT-AVATAR v1.0 (wider safety margin) |
| BRA-0001-BANNER-DRAFT | v0.12 | Superseded | `brand/assets/logos/derived/mfs-youtube-banner_v0.12.svg` | BRA-0001-YT-BANNER v1.0 (same content, moved to documented folder/naming) |

---

### Changelog
`[2026-07-08] Asset Registry created — first entry in this registry, triggered by Founder Approval of BRA-0001 (Primary Logo Master). Logged 12 Approved/Locked v1.0 assets (6 core logo files, app icon, YouTube avatar/watermark/banner, favicon set, raster export set) and 5 superseded prior versions, per Production Bible Section 7 and Brand Asset Production Guide Section 7's schema. Two capability gaps disclosed in the Notes column rather than omitted: the YouTube banner is a flat-vector composition only, not a reproduction of the approved reference's photographic/cinematic atmosphere (no image-generation or photo-compositing tool available); Print Files (CMYK PDF/EPS) were not produced (no CMYK conversion or PDF/EPS tool available). No story canon or Locked governance rule touched.`
`[2026-07-08] BRA-0001A logged: two Signature Cinematic Presentation assets (standalone logo artwork, official YouTube banner) approved per Founder Directive amending Brand Bible Section 3 to permit a second rendering style of the same canonical BRA-0001 geometry. Both entries explicitly document that no repository file exists for them -- this environment has no tool to export chat-submitted images to disk, so these are reference-only registry entries pending a real file being added from outside this session. Structural geometry verified consistent with the Locked v1.0 master using real evidence from prior tracing work; three specific technical items (safe-area placement, mobile-crop legibility, focal-contrast) remain open QA items, disclosed rather than silently closed.`
`[2026-07-08] BRA-0001A asset ingestion completed. Both Signature Cinematic Presentation files were delivered via direct upload to the branch (outside this session's chat, confirmed by `git log` showing an external "Add files via upload" commit) and pulled in. Verified both as valid, uncorrupted images before registering -- moved via `git mv` (no re-encoding, byte-identical) into `brand/assets/reference/logo/` and `brand/assets/reference/youtube/` per the Founder's directed structure, with filenames using the actual delivered format (`.jpg`) rather than the originally suggested `.png`, since renaming to misrepresent format was judged worse than a minor filename deviation. Measured actual dimensions directly rather than assuming compliance with the suggested filenames: the logo file (841x634 JPEG) has no dimension concerns; the banner file (1982x368 JPEG) does not match the specified 2560x1440 canvas or the 1546x423 safe-area aspect ratio, and this mismatch is disclosed prominently in its registry entry rather than silently accepted. Both entries updated to Locked status per the Founder's explicit registration directive, "not stored in repository" placeholder notes removed and replaced with real paths.`
`[2026-07-08] Banner corrected replacement registered as BRA-0001A-CINEMATIC-BANNER v1.1. Two upload rounds occurred after the v1.0 JPEG banner was registered: an intermediate file (never committed or registered here -- caught before registration and subsequently deleted by the Founder) used a tagline ("Forge Your Legend. Build the Myth.") that conflicted with the Locked Studio Motto/Tagline (Studio OS Section 1, Brand Bible Section 2, both Locked); rather than silently register a Locked-element conflict, that file was held pending clarification and never marked Approved. A corrected file arrived next with the proper Locked tagline ("Forging Worlds. Creating Legends."), verified by direct inspection -- registered as v1.1, Locked. v1.1 also corrects v1.0's aspect-ratio mismatch: PNG, 1672x941px, 1.7768:1, matching the 2560x1440 canvas's 16:9 ratio exactly (v1.0 was 1982x368px JPEG at 5.39:1). One gap remains, disclosed: v1.1's actual pixel count is below the specified 2560x1440 master resolution, correct proportions but would need upscaling for exact spec compliance. v1.0 marked Superseded, not deleted, per the archive-don't-delete rule.`
`[2026-07-08] v1.2 registered as the official YouTube banner at explicit Founder designation ("Add it to the repo as a official banner and i'll keep the other one but have this in case"). v1.2 is a variant of v1.1 (same scene, correct Locked tagline, matching 16:9 aspect ratio) with a small added ornamental divider under the tagline. v1.1 downgraded from Locked to Approved-kept-as-backup rather than Superseded or deleted, honoring the Founder's explicit instruction to retain it as an available alternate rather than archive it as replaced history. v1.0's file was separately deleted directly from the repository by the Founder; its registry entry retained and updated to reflect the file's removal, per the standing "nothing disappears without a record" rule.`
`[2026-07-14] Added a header note (per "Founder Decision Resolution — Phase 3A Production Standard Promotion," Decision 3) clarifying that this registry is the resource referenced as "Production Registry" in Phase 3A Content Production Pipeline Integration Framework directives. No new registry was created; no schema, asset entry, or scope changed. Resolves the naming gap flagged during Phase 3A's Founder Review & Alignment Audit and carried as an open item through its certification cycle.`
`[2026-07-15] Added FRACTURE_PROTOCOL_PRODUCTION backlog category per "Founder Directive — Phase 6.0 & Phase 6A Production Planning Framework (v1.0)," Phase 6A's own Asset Registry Population instruction. Logged 4 character assets requiring production (Kael, Cassian, Mira, the Guardian) and confirmed Titan requires none (zero on-screen appearances across all 36 screenplays); logged 10 individually-identified environment assets plus a flagged remainder of ~18 lower-frequency locations not yet itemized by ID. All entries use a new "Required — Not Yet Produced" status, distinct from the existing Draft/In Review/Approved/Locked schema, since none of these assets exist as production files. Confirmed zero props, weapons, vehicles, technology, or new VFX assets are named in any Approved screenplay — logged as confirmed-empty categories, not omitted. Confirmed no voice cast, music theme, or SFX asset exists yet — flagged in the companion Phase 6A roadmap rather than logged as a placeholder entry here. Every entry sourced directly from the 36 screenplays' own Asset Requirements tables; nothing invented, nothing fabricated. No story canon touched.`
