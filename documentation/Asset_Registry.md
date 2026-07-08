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
