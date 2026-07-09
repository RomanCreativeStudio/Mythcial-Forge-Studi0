# Asset Registry
## Mythic Forge Studios — Master Production Asset Tracker

**Classification:** Internal — Production Record
**Governing documents:** `production-bible/Fracture_Protocol_Production_Bible_v1.1.md` Section 7 (establishes this registry and its location), `brand/Mythic_Forge_Studios_Brand_Asset_Production_Guide_v1.0.md` Section 7 (extends the schema below with the Creator/Approval Date fields and the `BRAND_ASSET` category for brand assets specifically).
**Rule (Production Bible Section 7):** no asset is "real" until it is logged here — an asset that exists only as a file with no registry entry is treated as unapproved.

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
| BRA-0001A-CINEMATIC-BANNER | Signature Cinematic Presentation — Official YouTube Banner | v1.0 | **Superseded** | External (submitted by Founder), reviewed by Claude, approved by Founder | 2026-07-08 | `brand/assets/reference/youtube/mfs-youtube-banner-signature-cinematic_v1.0.jpg` | Superseded by v1.1 (below) — wrong aspect ratio for the banner canvas (1982×368px, 5.39:1, vs. the 2560×1440 canvas's 1.78:1). Retained per the archive-don't-delete rule. |
| BRA-0001A-CINEMATIC-BANNER | Signature Cinematic Presentation — Official YouTube Banner | v1.1 | **Locked** | External (submitted by Founder), reviewed by Claude, approved by Founder | 2026-07-08 | `brand/assets/reference/youtube/mfs-youtube-banner-signature-cinematic_v1.1.png` | Corrected replacement for v1.0: PNG, 1672×941px, 1.7768:1 aspect ratio — matches the 2560×1440 canvas's 16:9 ratio exactly (v1.0's did not). One remaining gap, disclosed: actual pixel dimensions (1672×941) are below the specified 2560×1440 master resolution — correct proportions, but would need upscaling to hit the exact spec; not a cropping/distortion risk like v1.0's mismatch was, just a resolution shortfall. An intermediate upload (since deleted by the Founder, never registered or committed here) used a different tagline ("Forge Your Legend. Build the Myth.") that conflicted with the Locked Studio Motto (Studio OS Section 1, Brand Bible Section 2); this v1.1 file uses the correct Locked tagline ("Forging Worlds. Creating Legends."), verified by direct inspection, not assumed. Structural logo geometry (double horn, notch-origin fracture, shard-above-notch) consistent with the Locked BRA-0001 v1.0 master. |

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
