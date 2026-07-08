# MYTHIC FORGE STUDIOS
## YouTube Brand Kit
### Version 1.1

**Classification:** Internal — Production Branding Specification
**Status:** Standards and specifications only. Defines rules for producing YouTube-facing assets — it does not generate, describe, or contain any artwork. Introduces zero story canon, zero worldbuilding, zero characters, zero factions, zero locations, zero technologies, zero lore.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` — this document is subordinate to it in all cases and carries no canon authority of its own.
**Absolute authority (brand-specific):** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` — this document is subordinate to it in all cases. It does not redefine the studio's logo, color palette, or typography; it only adds YouTube-channel-specific application depth beneath what the Brand Bible already establishes. Where this document and the Brand Bible ever appear to disagree, the Brand Bible wins and this document is corrected.
**Companion documents:** `studio-os/Studio_OS_v1.0.md` (Sections 1–4, 22–23 — brand personality, thumbnail, and SEO policy this Kit executes at YouTube-specific detail), `production-bible/Fracture_Protocol_Production_Bible_v1.1.md` (Section 13 — Episode Completion Checklist, thumbnail/export gate conditions), `governance/Fracture_Protocol_Studio_Governance_Manual_v1.1.md` (approval authority), `README.md` (Studio Wiki — navigation).

---

### How to use this document

The Brand Bible defines what Mythic Forge Studios *is*, visually and verbally, everywhere. This document defines how that identity is applied, at production-ready specification, to one specific surface: the official YouTube channel. Nothing here is a second brand system — every color, typeface, and logo variant named below is cited from the Brand Bible, never redefined. What's new here is the YouTube-specific detail the Brand Bible deliberately left at a high level: exact pixel dimensions, exact safe areas, exact timing, exact export formats.

Tags: **[LOCKED]** — founder/Creative Director sign-off required to change. **[LIVING SECTION]** — expected to evolve as actual channel assets are produced and real platform behavior is observed.

---

## 1. Brand Identity **[LOCKED]**

The channel's identity is not a separate identity from the studio's — it is the studio's identity (Brand Bible Sections 1–2), applied consistently to one platform. This section states only the channel-specific reading of it.

**Channel Personality:** the same as the studio's Brand Personality (Studio OS Section 4) — earnest, cinematic, quietly confident — expressed through consistency and craft rather than through upload frequency or algorithmic tricks.

**Audience Experience:** a viewer arriving at the channel for the first time should be able to tell, from the banner and the first three thumbnails alone, that this is a serious, original, long-form storytelling project — not a clip channel, not a reaction channel, not AI-generated filler.

**Emotional Tone:** matches the Franchise Design Manifesto's Emotional Experience Goals (Section 4) — the channel should feel like it respects the viewer's attention, never manufacturing urgency to earn a click.

**Cinematic Identity:** every channel-level visual (banner, thumbnail frame, motion graphics) reads as an extension of the show's own cinematic register (Art Bible `visual-development-guide.md`), never a generic YouTube-template look.

**Premium Positioning:** the channel should visually read as closer to a studio's dedicated show page than to an individual creator's channel — restraint, consistency, and craft are the differentiators, not production budget signaling (gold foil, excessive motion, loud thumbnails).

**Long-Term Brand Perception:** every channel asset produced today should still look correct next to an asset produced five seasons from now (Franchise Design Manifesto Section 17, Long-Term Vision) — nothing here should be trend-dependent.

---

## 2. Channel Logo Standards **[LOCKED]**

The logo itself — its design, its variants, its color rules — is defined exclusively in Brand Bible Section 3 and is not redefined here. This section specifies which variant is used where on the channel, and the YouTube-specific application rules around each use.

| Application | Variant Used | Specification |
|---|---|---|
| **Avatar (profile picture)** | Icon Version (Brand Bible Section 3) | 800×800px master, Void Black background — composed with generous internal padding, since YouTube crops all avatars to a circular mask; nothing structurally important in the mark may sit within the outer 15% of the frame, or it will be clipped by the circular crop. |
| **Watermark** | Icon Version, monochrome or full-color | 150×150px minimum (YouTube's subscribe-watermark spec), bottom-right corner, reduced opacity (Brand Bible Section 10) |
| **Primary Logo (channel page, About tab)** | Primary Logo, Dark Version (Brand Bible Section 3) | Full lockup, used wherever space allows a complete wordmark |
| **Secondary Logo (constrained UI space)** | Secondary Logo (wordmark only) | Used only where the Primary Logo's icon would be illegible at the available size |

**Clear Space Rules:** unchanged from Brand Bible Section 3 — minimum clear space equals the icon's own height on every side, with no exception for YouTube's UI chrome.

**Minimum Size:** the Avatar use case is itself the practical minimum-size test for the Icon Version — if the mark doesn't read correctly at YouTube's smallest rendered avatar size (as low as 28×28px in some UI contexts, e.g., comment threads), it fails this standard and must be revised, not force-fit.

**Scaling:** the logo is never manually redrawn or re-simplified for small YouTube contexts — the same master Icon Version file (Brand Bible Section 14) is scaled down, never redrawn, so there is exactly one Icon Version in circulation at any time.

**Incorrect Usage:** beyond Brand Bible Section 3's general improper-usage rules, YouTube-specific misuse to avoid: placing the full Primary Logo where YouTube's own UI (video progress bar, live badge, notification bell) will overlap the wordmark; using the Light Version logo against YouTube's dark-theme UI without testing actual on-platform contrast first, since YouTube's own chrome color is not identical to the Brand Bible's Void Black.

**Background Compatibility:** the Icon Version (avatar, watermark) must remain legible against both YouTube's light-theme and dark-theme UI chrome — verified against both before any avatar/watermark asset is approved (Section 15, Brand Quality Assurance Checklist).

---

## 3. YouTube Banner Standards **[LOCKED]**

Extends Brand Bible Section 10's banner entry (2560×1440px master, 1546×423px safe area) with the full per-device breakdown that entry deliberately left general:

| Zone | Approximate Dimensions (within the 2560×1440px canvas) | Notes |
|---|---|---|
| **Full canvas** | 2560×1440px | Master file; never all simultaneously visible on any single device |
| **TV-safe area** | ~2560×424px, centered | Widest strip reliably shown on TV-app playback |
| **Desktop-visible area** | Up to ~2560×423–576px, centered, varies with browser window width | Widest browsers show close to the full TV-safe strip; narrower windows crop further |
| **Mobile-safe area** | 1546×423px, centered | The only area guaranteed visible on every device — all critical content (logo, tagline) must sit inside this zone |

**Note:** platform safe-area specs are set by YouTube and have changed over time — this table is a working specification, not a permanent platform guarantee. Verify against YouTube's current official channel-art guidance before final export (Section 15).

**Logo Placement:** Horizontal Logo (Brand Bible Section 3), Dark Version — **or, as of v1.1 (Founder Directive, BRA-0001A, 2026-07-08), the Signature Cinematic Presentation of the same Locked geometry, permitted specifically for this banner context** — centered within the mobile-safe area — never placed only in the wider desktop/TV zones, since it would then be invisible to mobile viewers.

**Text Placement:** the tagline (Brand Bible Section 2) sits directly beneath the logo lockup, also within the mobile-safe area; no other text is placed on the banner.

**Composition:** asymmetric framing is permitted in the full-canvas zones outside the mobile-safe area (e.g., a subtle background treatment extending wider), but the mobile-safe area itself follows a centered, symmetric layout — the one context where the Brand Bible's asymmetry preference (Section 6) is deliberately overridden, because cropping unpredictability makes asymmetric safe-area content too risky.

**Lighting:** Grounded lighting mode (Brand Bible Section 6) — confident, even, never the higher-contrast Charged mode, which is reserved for launch-specific assets only (Section 10, Channel Trailer Branding).

**Depth:** minimal by default — the banner is a graphic/typographic composition, not a rendered scene; avoid deep perspective or simulated camera depth that could misread at banner aspect ratio. **Exception (v1.1, BRA-0001A):** when using the Signature Cinematic Presentation, atmospheric depth (environment, lighting, effects) is permitted around the logo specifically because that presentation style exists for exactly this kind of context — the logo itself, and the mobile-safe-area text, must still remain the unambiguous focal point, not competed with by the environment.

**Color Balance:** Void Black base (Brand Bible Section 4) with Fracture Cyan reserved for the logo's fracture accent only — the banner must never use Fracture Cyan as a large background fill, consistent with the "earned, not decorative" accent rule.

**Negative Space:** at least 40% of the mobile-safe area remains clean, undecorated space — tighter than Section 6's general 20% minimum, because banner space is small and crowding reads immediately as off-brand.

**Visual Hierarchy:** logo first, tagline second, nothing else competes — the banner is not a place for episode promotion, schedule information, or secondary calls-to-action.

---

## 4. Color System **[LOCKED]**

The palette itself is Brand Bible Section 4 and is not redefined here — Fracture Cyan `#00E5FF`, Void Black `#0A0B0D`, Authority White `#F5F7FA`, Charcoal Steel `#2A2E35`, Signal Blue `#1E3A5F`, and the Steel neutral ramp remain the only colors in use across every YouTube asset.

**Gradient Rules (new — not defined in the Brand Bible):** where a gradient is used at all (e.g., a subtle vignette behind thumbnail text), it transitions only between two adjacent values on the Steel neutral ramp, or between Void Black and Charcoal Steel — never a gradient between Fracture Cyan and any other color, since that would read as a decorative use of the accent rather than an earned highlight.

**Glow Usage (new):** a soft glow effect on Fracture Cyan elements (logo accent, thumbnail highlight callouts) is permitted only to reinforce the accent's "system-active" meaning (echoing Art Bible `color-language.md`'s eye-glow specification, cited not restated) — never applied to Authority White or Steel-ramp elements, and never at an intensity that overwhelms surrounding content.

**Highlight Colors:** Fracture Cyan is the only highlight/callout color used in thumbnail or motion-graphic overlays — no secondary highlight color is introduced for this purpose.

**Accessibility Considerations:** unchanged from Brand Bible Section 4 — WCAG AA minimums apply to any text rendered in these assets (channel description, community posts), and thumbnail text specifically should additionally be tested for legibility at YouTube's smallest rendered thumbnail size (as low as ~120×68px in mobile feed contexts).

---

## 5. Typography System **[LOCKED]**

The typefaces themselves are Brand Bible Section 5 (Space Grotesk, Inter, IBM Plex Mono) and are not redefined here.

| Use | Typeface / Weight |
|---|---|
| **Headline (video titles, banner tagline)** | Space Grotesk Bold |
| **Subtitle (playlist names, description headers)** | Space Grotesk Medium |
| **Body (descriptions, community posts)** | Inter Regular |
| **Thumbnail text (when used at all)** | Space Grotesk Bold only — no other weight or typeface reads reliably at thumbnail scale |

**Spacing:** thumbnail text uses looser line spacing than standard body copy (Brand Bible Section 5) to preserve legibility at small render sizes; headline tracking follows the Brand Bible's tight-to-neutral rule unchanged.

**Hierarchy:** exactly one text emphasis level per thumbnail — a thumbnail with a headline and a sub-label competing for attention has violated this rule regardless of how each individually looks.

**Capitalization Rules:** video titles use Sentence case (matching the studio's earnest, non-hype brand voice, Brand Bible Section 12) — never ALL CAPS, which reads as manufactured urgency; on-thumbnail text (when used) may use Title Case for a headline-style treatment, but never ALL CAPS for the same reason.

---

## 6. Thumbnail Design System **[LOCKED]**

In-episode thumbnail *content* (what image is depicted) remains exclusively governed by the Art Bible's Thumbnail Prompt Template (`prompt-library.md`) and Production Bible Section 13 — this document does not touch content. This section governs the *layout template* every approved thumbnail image is placed inside.

**Layout:** a safe-zone grid reserving the bottom-right ~15% of frame entirely clear, since YouTube overlays its own video-duration badge there on every thumbnail — no brand element or text may be placed in that corner.

**Episode Numbering:** where an episode number is displayed on a thumbnail at all, it uses a small, consistent badge (Space Grotesk Bold, Fracture Cyan on a Void Black chip) in the same corner position on every thumbnail in a season — never a different position episode-to-episode.

**Character Placement (layout only — no character content defined here):** the template reserves either the left or right third of frame for the primary subject, with the opposite third available for a headline if one is used — which side is used may vary by episode, but the frame's compositional grid (rule-of-thirds subject placement, one clear focal point) does not.

**Background Treatment:** background must never compete with the subject for attention — this is a layout/contrast rule; the background's actual content is Art Bible's domain.

**Lighting:** thumbnail lighting follows the Art Bible's Charged lighting mode logic in spirit (higher contrast, clear directional key) — this document does not redefine that mode, only confirms it's the appropriate register for thumbnail work specifically, since thumbnails need to read instantly at small size.

**Contrast:** minimum perceptual contrast between subject and background sufficient to remain legible at the smallest common render size (~120×68px) — tested before approval (Section 15).

**Readability:** any thumbnail text must be legible at that same minimum render size — if it isn't, the text is removed rather than shrunk further.

**Emotion:** the thumbnail's single most important job is communicating the episode's emotional register at a glance — a technically perfect thumbnail that reads as tonally flat has failed this standard.

**Branding Consistency:** the icon-bug and episode-number badge (both defined above) appear in the same position on every thumbnail, season to season, so the channel's thumbnail grid reads as unmistakably one show even before any individual image is examined.

**Click-Through Optimization:** optimization never means misrepresentation — Studio OS Section 4's rule ("no manufactured urgency") and Production Bible's thumbnail gate ("depicted moment actually occurs in the episode") both apply in full; a thumbnail is optimized by being clear and emotionally accurate, never by exaggerating or misleading.

---

## 7. Intro System **[LOCKED]**

Extends the Brand Bible's brief "2–3 second logo activation bumper" (Section 8) into a full channel intro specification. This is an original motion concept, built entirely from marks and motifs already established in this repository — it does not reference, resemble, or adapt any existing studio's intro or any copyrighted intro sequence.

**Recommended Duration:** 5–8 seconds total, opening every mainline episode.

**Logo Reveal Timing:** approximately seconds 1–3: the fracture line (Brand Bible Section 3) draws on in a single stroke against a Void Black field; seconds 3–5: the mark settles into its steady glow state (Brand Bible Section 8); seconds 5–8: the full Primary Logo lockup and tagline hold on screen before cutting to the episode's own cold open.

**Motion Style:** measured and deliberate throughout (Brand Bible Section 8) — no bounce, no spin, no particle burst; the only motion is the single fracture-line draw-on and a slow, subtle brightness settle.

**Transition Style:** a hard cut, or the signature glitch/static-resolve wipe (Brand Bible Section 8), into the episode's own cold open — never a crossfade.

**Audio Direction:** the Studio Audio Logo (Brand Bible Section 9) plays in full, timed to land its resolved tone exactly as the logo reaches its steady glow state (around second 3–4).

**Music Tone:** the Studio Audio Logo is self-contained and requires no additional underscore — no separate "intro music" is layered beneath it.

**End Frame:** the intro's final frame (before the cut to cold open) is the full Primary Logo lockup, Dark Version, centered on Void Black — this exact frame is reused, unaltered, across every episode, so it functions as a consistent visual anchor rather than a per-episode variable.

---

## 8. Outro System **[LOCKED]**

**Duration:** 15–20 seconds, matching YouTube's supported end-screen element window.

**End Screen Layout:** the logo settles to its steady glow state (Brand Bible Section 8) in the upper-left or upper-right third of frame, keeping the lower-right and center clear for YouTube's own end-screen elements (subscribe button, video/playlist cards), which YouTube overlays automatically and which this document cannot control the exact placement of — the brand layout is designed to leave room for them, not to compete with them.

**Subscribe Placement:** reserved space, lower-right or center-lower third, per YouTube's own end-screen element sizing — the brand background must not place any of its own text or graphics in this zone.

**Playlist Placement:** a second reserved zone (upper or lower third, whichever the subscribe element isn't using) for a "next episode" or "continue the season" playlist card.

**Background Animation:** minimal — the fracture-line background pattern (Brand Bible Section 6) at low opacity, subtly animated (a slow drift, never a distracting loop), consistent with the studio's restrained motion philosophy (Section 7, Motion Style).

**Music Continuation:** the episode's own score fades naturally into a short reprise of the Studio Audio Logo's tonal signature (Brand Bible Section 9) rather than cutting hard to silence or to a jarring new cue.

**Transition into YouTube End Cards:** the last few seconds of the outro's own on-screen graphics fade out just before YouTube's end-screen elements become interactive, so nothing brand-authored visually fights with the platform's own UI at the moment a viewer can actually click something.

---

## 9. Motion Graphics Standards **[LIVING SECTION]**

Scoped strictly to **channel/brand-level** motion graphics (behind-the-scenes segments, community updates, channel trailers) — in-episode motion graphics and any in-fiction UI/system-interference visuals remain exclusively the Art Bible's domain (`system-interference-visual-rules.md`) and are never defined here.

**Lower Thirds:** brand typography (Section 5) and color (Section 4) only, used for channel-level content (e.g., identifying a segment or update), never used to caption in-fiction dialogue.

**Title Cards:** Space Grotesk Bold on Void Black or Charcoal Steel, following the same restraint principles as the banner (Section 3).

**Chapter Transitions:** the signature glitch/static-resolve wipe (Section 7) is the one approved transition device for channel-level video content — no stock transition packs.

**HUD Graphics / UI Overlays:** if a channel video ever needs an on-screen data/stat display (e.g., a behind-the-scenes production-update graphic), it uses the IBM Plex Mono display typeface (Brand Bible Section 5) in the brand palette — this is a distinct, brand-level "data" treatment and must never be styled to resemble the show's own in-fiction Cipher-work interface, which would blur the line between real-world channel content and fiction.

**Camera Overlays:** any camera-frame graphic (e.g., a "recording" indicator on behind-the-scenes footage) uses brand typography/color only.

**Cinematic Transitions:** for channel trailers/behind-the-scenes content that isn't a hard cut or the glitch wipe, a slow push-in (Brand Bible Section 8's camera philosophy) is the only other approved transition style.

**Particle Effects:** not used in channel/brand motion graphics — reserved exclusively for in-fiction Cipher-work/Fragment effects (Art Bible), which this document does not touch and does not imitate.

**Glitch Effects:** permitted only as the specific, singular "static-resolve" transition device already defined (Section 7) — never as a generic stylistic flourish elsewhere, to keep the effect meaningful rather than decorative.

---

## 10. Channel Trailer Branding **[LIVING SECTION]**

**Opening:** the full Intro System (Section 7) plays in full at the start of any official channel trailer — trailers do not get a shortened or alternate intro.

**Middle Pacing:** measured, not rapid-fire — cuts follow the same "no cut faster than the content needs" restraint principle as the rest of the brand's motion philosophy (Brand Bible Section 8); a trailer that feels frantic has violated brand tone even if every individual shot is otherwise approved.

**Ending:** settles into the standard Outro System (Section 8), with the Subscribe/Playlist reserved zones intact.

**Logo Timing:** beyond the standard intro/outro placements, a trailer may include one additional mid-point logo mark (small, Icon Version only, corner placement, low opacity) if the trailer runs long enough to need a brand anchor partway through — never more than one additional mid-point mark.

**Call-to-Action:** exactly one CTA per trailer (Brand Bible Section 12's "one clear CTA" rule) — typically "the series begins [date/season]" framing, never a stacked list of asks.

**Music Style:** follows Brand Bible Section 9's Music Direction (restrained, moody-confident, no generic "epic trailer" bombast) — a trailer is the single highest-risk asset for accidentally violating this rule, so it receives extra scrutiny at Section 15's QA gate.

**Visual Flow:** establishes tone and world before revealing any specific plot content, mirroring the show's own "audience as investigator, never ahead" principle (Franchise Design Manifesto Section 5) applied to marketing pacing.

---

## 11. Cross-Platform Branding **[LIVING SECTION]**

Extends Brand Bible Section 11's Social Branding table with the specific consistency check this Kit is responsible for: a viewer moving from YouTube to any other platform should never perceive a different studio.

| Platform | YouTube-Kit-Specific Note |
|---|---|
| **YouTube** | The full system defined in this document |
| **Instagram / TikTok** | Vertical crops of the same Icon Version and color system (Brand Bible Section 11) — never a redesigned mark for short-form platforms |
| **X** | Profile/header assets pulled from the same master files as YouTube's avatar/banner, cropped per platform spec, never recreated independently |
| **Discord** | Server icon uses the same Icon Version master file as the YouTube avatar |
| **Website** | Hero lockup matches the YouTube channel page's Primary Logo placement in spirit — same asset, consistent prominence |
| **GitHub** | Where this repository or any public-facing GitHub presence displays a social preview image, it uses the same Icon Version and color system — no separate "developer-facing" visual identity |
| **Future platforms** | Inherit this same rule by default (Section 16) — a new platform never gets a bespoke identity without a Founder Override Command, consistent with Brand Bible Section 15 |

---

## 12. Export Standards **[LOCKED]**

Extends Brand Bible Section 14's general asset-export standards with YouTube-specific technical specifications:

| Asset | Format | Specification |
|---|---|---|
| **Banner** | PNG or JPG | 2560×1440px, under 6MB |
| **Logo (channel use)** | PNG (transparent), SVG master | Per Brand Bible Section 14 |
| **Watermark** | PNG (transparent) | 150×150px minimum |
| **Thumbnail** | JPG or PNG | 1280×720px (16:9), under 2MB, minimum width 640px |
| **Motion graphics (overlays)** | MOV with alpha channel, or MP4 | Matching the episode master's resolution and frame rate |
| **Intro / Outro** | MP4 (ProRes master retained in archive) | Matching the episode master's resolution and frame rate |
| **Trailer** | MP4 | Platform-standard resolution (1080p minimum, 4K where available) |
| **Social graphics** | PNG or JPG, per-platform dimensions | Cropped from the same master files (Section 11) — never independently recreated |

---

## 13. Asset Naming Standards **[LOCKED]**

Extends the naming pattern already established in Brand Bible Section 14 and Production Bible Section 5 — this Kit does not invent a separate naming philosophy.

Convention: `mfs-youtube-{asset-type}-{descriptor}_v{X.X}.{ext}`

| Asset Type | Example |
|---|---|
| Banner | `mfs-youtube-banner-primary_v1.0.png` |
| Watermark | `mfs-youtube-watermark-icon_v1.0.png` |
| Thumbnail | `mfs-youtube-thumbnail-s{season}e{episode}_v1.0.jpg` |
| Intro | `mfs-youtube-intro-master_v1.0.mov` |
| Outro | `mfs-youtube-outro-master_v1.0.mov` |
| Trailer | `mfs-youtube-trailer-{descriptor}_v1.0.mp4` |

---

## 14. Folder Structure **[LOCKED spine, LIVING subfolders]**

Extends Brand Bible Section 14's `/brand/assets/` reservation with the YouTube-specific subtree — documented now, created only once real files exist (Studio Wiki Section 15's rule against speculative scaffolding):

```
/brand/assets/youtube/
  /logos/
  /banners/
  /channel-art/
  /thumbnails/
  /intros/
  /outros/
  /trailers/
  /motion-graphics/
  /exports/
  /archives/
  /templates/
  /marketing/
```

No subfolder here exists yet — this structure is documented in advance so the first real asset has a defined home rather than an improvised one.

---

## 15. Brand Quality Assurance Checklist **[LOCKED]**

Every YouTube-facing asset passes this checklist before publish, in addition to Production Bible Section 9's general QA checklist:

- [ ] Visual consistency — matches the Brand Bible's logo/color/typography exactly, with no unauthorized substitution
- [ ] Brand consistency — reads unmistakably as Mythic Forge Studios next to every other channel asset already published
- [ ] Spacing — clear space and safe-area rules (Sections 2–3) observed exactly
- [ ] Lighting — correct mode (Grounded vs. Charged, Section 3/6) for the asset type
- [ ] Readability — text and key visual elements legible at the smallest realistic render size for that asset type (Section 4, 6)
- [ ] Resolution — meets Section 12's export specification for its asset type
- [ ] Professional appearance — no visible compression artifacts, no off-model brand elements
- [ ] Cross-platform compatibility — tested against both YouTube's light and dark UI themes (Section 2) where applicable

---

## 16. Future Expansion Rules **[LIVING SECTION]**

A new asset type (a channel feature YouTube adds, a new content format) is added to this Kit the same way a new category is added anywhere else in this repository — appended, never restructuring what already exists (Studio Wiki Section 24; Brand Bible Section 16). A second flagship show's channel (if the studio ever runs one) either extends this same Kit or receives its own, per the same Founder Override bar as any other sub-brand decision (Brand Bible Section 16) — this Kit does not pre-decide that question.

---

## 17. Relationship to Existing Documents **[LOCKED]**

- **Brand Bible:** absolute authority over this document (front matter) — this Kit only applies the Brand Bible's logo, color, and typography systems to YouTube specifically; it never redefines them.
- **Production Bible:** governs in-episode asset production and the Episode Completion Checklist (Section 13) that gates a finished episode, including its thumbnail's *content*; this Kit governs the channel-level frame and platform presentation around that content.
- **Studio OS:** Sections 1–4 (Vision, Mission, Values, Brand Personality) and Sections 22–23 (Thumbnail Standards, SEO Standards) remain upstream authorities this Kit executes at YouTube-specific technical detail — never restated, never overridden.
- **Studio Wiki:** indexes this document like every other one; the Wiki never restates its content, only points to it.
- **Governance Manual:** this Kit carries no governance authority of its own — a Locked-section change here follows the same Founder Authority and Change Request Workflow (Governance Manual Sections 6, 11) as any other process document.

This document governs **YouTube channel branding only**. It introduces no authority over story canon, no authority over studio governance, and no authority beyond what the Brand Bible has already granted it as an execution layer.

---

## 18. Final Validation

- **No canon introduced.** No character, faction, location, technology, power mechanic, or world fact appears anywhere in this document.
- **No existing governance modified.** The Master System Prompt, Studio Governance Manual, Studio OS, Production Bible, and Brand Bible are unchanged by this document's creation — this Kit only cites them.
- **Compatible with every existing Bible and Manual.** Checked against Brand Bible Sections 2–4, 6, 8–12, 14–16; Studio OS Sections 1–4, 22–23; Production Bible Sections 9, 13; Studio Governance Manual Sections 6, 11; Art Bible `prompt-library.md`, `system-interference-visual-rules.md` (cited for domain boundaries only, never duplicated). No contradictions found.
- **Uses Version Control correctly.** Follows the studio-wide `v{major}.{minor}` convention (Brand Bible Section 14 / Production Bible Section 6).
- **Uses LOCKED/LIVING sections appropriately.** Structural and brand-defining sections (Sections 1–8, 12–15, 17) are Locked; sections expected to evolve with actual platform experience (Sections 9–11, 16) are Living.
- **No artwork generated.** Every section defines a specification or a rule — no image, video, or audio file was produced or described as if it already exists.

---

**Version:** 1.1
**Status:** Complete — real YouTube-facing assets now exist at `/brand/assets/youtube/` (avatar, banner, watermark, all v1.0, logged in `documentation/Asset_Registry.md`). Section 3 (Banner Standards) amended to permit the Signature Cinematic Presentation (Brand Bible Section 3, v1.1) for the official banner specifically.
**Authority:** Subordinate to the Master System Prompt and the Brand Bible; governed operationally by the Studio Governance Manual (Section 17)
**Scope:** YouTube channel branding only — logo application, banner, color/typography application, thumbnails, intro/outro, motion graphics, trailer branding, cross-platform consistency, export/naming/folder standards, and QA. Explicitly excludes all story canon, lore, and episode content, and does not redefine any Brand Bible-level identity element.

---

### Changelog
`[v1.0 — 2026-07-07] Initial YouTube Brand Kit established: 17 substantive sections (Brand Identity through Relationship to Existing Documents) plus Final Validation, providing YouTube-specific production specification beneath the Brand Bible — logo application rules, full banner safe-area breakdown, gradient/glow color extensions, thumbnail layout template, intro/outro system (original, non-derivative motion concept), channel-level motion graphics standards (explicitly excluding in-fiction UI, which remains Art Bible's domain), channel trailer branding, cross-platform consistency, and export/naming/folder/QA standards. Introduces zero story canon and zero artwork. Does not modify the Brand Bible or any existing governance document — every shared fact (palette, typefaces, logo variants) is cited, never redefined.`
`[v1.1 — 2026-07-08] FOUNDER DIRECTIVE — BRAND BIBLE AMENDMENT (BRA-0001A). Amended Section 3 (YouTube Banner Standards): Logo Placement now permits the Signature Cinematic Presentation (Brand Bible Section 3, v1.1) as an alternative to the Dark Version for the official banner; the Depth rule's "not a rendered scene" default now carries an explicit exception for that presentation style, on the condition that the logo and mobile-safe-area text remain the unambiguous focal point. Both amendments cite the same Founder sign-off recorded in the Brand Bible's own v1.1 changelog entry, per this Kit's own governance (Section 17) deferring logo-identity questions to the Brand Bible rather than redefining them here.`
