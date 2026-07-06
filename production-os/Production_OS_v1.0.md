# MYTHIC FORGE STUDIOS
## PRODUCTION OPERATING SYSTEM
### Version 1.0

**Classification:** Internal — Production Manual
**Companion documents:** `studio-os/Studio_OS_v1.0.md` (company-level process — this document is its technical/pipeline layer), `bible/Fracture_Protocol_Master_System_Prompt_v1.0.md` and `bible/Fracture_Protocol_World_Bible_v1.1.md` (world canon), `series/*/Series_Bible_v1.1.md` (story canon)

---

### How to use this document

This is not a story document and not a lore document — it is the manual every department follows to turn a Series Bible episode outline into a published video without losing quality or consistency as volume scales into the hundreds of episodes. Studio OS Section 13 defines the production pipeline at a company-policy level; this document defines it at the step-by-step, department level.

Tags follow the studio-wide convention:
- **[LOCKED]** — founder/Technical Director sign-off required to change.
- **[LIVING SECTION]** — expected to evolve as the pipeline is proven in practice.

Every SOP in this document lists: **Purpose, Inputs, Outputs, Responsible Role, Checklist, Estimated Time, Quality Standard, Dependencies, Version.**

---

## 1. Production Overview **[LOCKED]**

Mythic Forge Studios produces original animated episodes for *The Fracture Protocol* (Series 01, featuring protagonist Kael) and future series within the same or future universes, using an AI-assisted pipeline supervised at every stage by a human creative authority. This document governs everything from "episode outline exists" (Series Bible Section 11) through "episode is published and measured" (Studio OS Sections 23–24). It does not govern *what* the story is — only *how it gets made*.

## 2. Production Philosophy **[LOCKED]**

1. **AI drafts, humans approve.** No AI output enters a published episode without a human quality and canon check.
2. **Every asset is reusable.** Characters, environments, and props are built once, referenced many times — not redrawn per episode.
3. **Consistency beats speed.** A missed upload date is recoverable; a canon-breaking or off-model episode erodes audience trust (Studio OS Section 3).
4. **Every stage has a visible cost and a visible owner.** If a stage's time/effort isn't estimated (Section 39) and assigned (Section 4), it isn't a real stage yet.
5. **Version everything.** Scripts, assets, and prompts all carry version numbers (Section 32) — nothing is "final" without a number attached.

## 3. Production Pipeline **[LOCKED spine]**

```
 [Series Bible Episode Entry]
          │
          ▼
 1. PRE-PRODUCTION  ──▶ 2. SCRIPT  ──▶ 3. STORYBOARD  ──▶ 4. SCENE PLANNING
                                                                  │
                                                                  ▼
 8. VOICE  ◀── 7. ANIMATION  ◀── 6. IMAGE GENERATION  ◀── 5. ASSET PLANNING
    │
    ▼
 9. MUSIC & SFX ──▶ 10. EDIT ──▶ 11. COLOR GRADE ──▶ 12. SUBTITLES
                                                            │
                                                            ▼
                              13. THUMBNAIL ──▶ 14. QA ──▶ 15. UPLOAD ──▶ 16. PUBLISH
                                                                                │
                                                                                ▼
                                                                17. ANALYTICS REVIEW
```

Each numbered stage below maps to an SOP in this document (Sections 6–28).

## 4. Department Responsibilities **[LIVING SECTION]**

| Department | Owns Stages | Current Owner | Future Role (Studio OS Section 29) |
|---|---|---|---|
| Story | 1–2 | Founder (Creative Director) | Writer(s) |
| Story Art | 3–4 | Founder | Storyboard Artist |
| Asset/Visual Dev | 5–6 | Founder | Animation Lead |
| Animation | 7 | Founder | Animation Lead |
| Voice | 8 | Founder | Voice Lead |
| Audio | 9 | Founder | Voice Lead / Audio Lead |
| Post-Production | 10–13 | Founder | Editor |
| QA | 14 | Founder | QA Owner |
| Publishing | 15–17 | Founder | Publishing/SEO Owner |

## 5. Production Stages **[LOCKED gates]**

| Stage | Gate to Proceed |
|---|---|
| Pre-Production → Script | Concept approved against Series Bible outline (Section 6) |
| Script → Storyboard | Script passes canon check (Section 7) |
| Storyboard → Scene Planning | Shot list approved (Section 8) |
| Scene Planning → Asset Planning | Scene blocking locked (Section 9) |
| Asset Planning → Image Generation | Registry checked for reusable assets first (Section 10) |
| Image Generation → Animation | Originality Check passed (Section 14) |
| Animation → Voice | Motion/consistency review passed (Section 15) |
| Voice → Music/SFX | Performance approved (Section 17) |
| Edit → Color Grade → Subtitles → Thumbnail | Rough cut locked before polish passes begin |
| Thumbnail/Subtitles → QA | All prior stages complete |
| QA → Upload → Publish | Full QA checklist passed (Section 38) |

---

## 6. Pre-Production SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Confirm an episode is ready to move from Series Bible outline to active production |
| **Inputs** | Series Bible episode entry (Title, Objective, Conflict, Growth, Twist, Cliffhanger) |
| **Outputs** | Approved production brief; stage-gate sign-off |
| **Responsible Role** | Creative Director |
| **Checklist** | ☐ Episode entry exists in Series Bible ☐ No open Canon Change requests affect this episode ☐ Required assets identified at a high level ☐ Target runtime confirmed (Series Bible Section 24) |
| **Estimated Time** | 30 min |
| **Quality Standard** | Brief traces cleanly to its Series Bible entry with zero ambiguity about objective |
| **Dependencies** | Series Bible Section 11 |
| **Version** | 1.0 |

## 7. Script Writing SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Expand a Series Bible episode entry into a full shootable script |
| **Inputs** | Pre-production brief; World Bible; Series Bible cast/relationship data |
| **Outputs** | Versioned script file (`scripts/S{season}E{episode}_{slug}.md`) |
| **Responsible Role** | Writer / Creative Director |
| **Checklist** | ☐ Follows Series Bible's Objective/Conflict/Growth/Twist/Cliffhanger for the episode ☐ Passes Originality Check (Studio OS Section 5) ☐ No contradiction with Locked Bible or Series Bible sections ☐ Dialogue meets Dialogue Standards (Series Bible Section 23) ☐ Runtime estimate within target (8–15 min) |
| **Estimated Time** | 3–6 hrs (AI-assisted draft + human revision passes) |
| **Quality Standard** | A second reader unfamiliar with the draft can summarize the episode's one central revelation correctly |
| **Dependencies** | Section 6 |
| **Version** | 1.0 |

## 8. Storyboarding SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Convert the script into a shot-by-shot visual sequence |
| **Inputs** | Approved script |
| **Outputs** | Shot list / storyboard panels |
| **Responsible Role** | Storyboard Artist (currently Founder) |
| **Checklist** | ☐ Every script beat has a corresponding shot ☐ Shot count is proportionate to runtime target ☐ Camera Movement Standards followed (Section 16) ☐ No new assets introduced without flagging Asset Planning (Section 10) |
| **Estimated Time** | 2–4 hrs |
| **Quality Standard** | Storyboard alone (no dialogue) communicates the scene's core action |
| **Dependencies** | Section 7 |
| **Version** | 1.0 |

## 9. Scene Planning SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Lock blocking, pacing, and shot count per scene before asset/animation work begins |
| **Inputs** | Approved storyboard |
| **Outputs** | Scene plan (shot durations, transitions, blocking notes) |
| **Responsible Role** | Storyboard Artist / Editor |
| **Checklist** | ☐ Scene durations sum to target runtime ☐ Pacing Standards followed (Studio OS Section 24 / Series Bible Section 24) ☐ Every scene assigned to a specific Zone's Visual Consistency Rules (World Bible Section 3, Art Bible `environment-design-rules.md`, Studio OS Section 19) |
| **Estimated Time** | 1–2 hrs |
| **Quality Standard** | No scene's planned duration is later found to require significant rework in Editing (Section 20) |
| **Dependencies** | Section 8 |
| **Version** | 1.0 |

## 10. Asset Planning SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Determine what new visual assets (if any) an episode requires, and check for reuse first |
| **Inputs** | Scene plan; existing Asset/Character/Environment registries (Knowledge Base Sections 14–16, 22) |
| **Outputs** | Asset requirement list, split into "reuse" and "new build" |
| **Responsible Role** | Asset/Visual Dev Lead (currently Founder) |
| **Checklist** | ☐ Registry checked before requesting any new asset ☐ Every "new build" item justified by the script ☐ New characters/environments/props flagged to Sections 11–13 respectively |
| **Estimated Time** | 30–60 min |
| **Quality Standard** | Zero duplicate assets created for something the registry already has |
| **Dependencies** | Section 9, Knowledge Base Section 13 |
| **Version** | 1.0 |

## 11. Character Asset SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Produce a new character's visual reference sheet |
| **Inputs** | Character Creation Rules (World Bible Section 14), Series Bible character description |
| **Outputs** | Reference sheet (turnaround, expression sheet, signature prop/detail) |
| **Responsible Role** | Animation Lead |
| **Checklist** | ☐ Silhouette readability test passed ☐ Originality Check passed ☐ Matches megacity visual identity (Art Bible `color-language.md`, `materials-and-textures.md`) ☐ Logged in Character Registry (Knowledge Base Section 14) |
| **Estimated Time** | 2–4 hrs |
| **Quality Standard** | Character is identifiable in solid-black silhouette alone |
| **Dependencies** | Section 10 |
| **Version** | 1.0 |

## 12. Environment Asset SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Produce a new environment/location asset |
| **Inputs** | World Bible Section 3 (Megacity Structure) |
| **Outputs** | Environment concept art / background plate |
| **Responsible Role** | Animation Lead |
| **Checklist** | ☐ Matches assigned Zone's palette/architecture (Art Bible `environment-design-rules.md`) ☐ No silhouette/palette overlap with another Zone's established environments (Studio OS Section 19) ☐ Logged in Asset Registry (Knowledge Base Section 22) |
| **Estimated Time** | 2–4 hrs |
| **Quality Standard** | Recognizable as its Zone without a caption |
| **Dependencies** | Section 10 |
| **Version** | 1.0 |

## 13. Prop Asset SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Produce a new prop, Cipher, or Root Artifact visual |
| **Inputs** | World Bible Sections 7 (Cipher-work), 11 (Root Artifacts) |
| **Outputs** | Prop concept art |
| **Responsible Role** | Animation Lead |
| **Checklist** | ☐ Cipher marks match the cyan/icy-blue color language (Art Bible `color-language.md`) ☐ Named Root Artifacts logged in the Relic Registry (Knowledge Base Section 13) with their cost/limitation documented (World Bible Section 7) |
| **Estimated Time** | 1–3 hrs |
| **Quality Standard** | A recurring prop is visually identical across every future appearance |
| **Dependencies** | Section 10 |
| **Version** | 1.0 |

## 14. Image Generation SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Generate production-ready frames/plates using AI image tools while preserving character and world consistency |
| **Inputs** | Approved character/environment/prop reference sheets; storyboard |
| **Outputs** | Final or near-final frame art per shot |
| **Responsible Role** | Animation Lead |
| **Checklist** | ☐ Reference sheet used as the generation anchor for every recurring character/asset ☐ Originality Check passed on final output, not just the prompt ☐ No visible AI-generation artifacts (extra limbs, garbled text, inconsistent Cipher marks) ☐ Prompt logged per Section 34 |
| **Estimated Time** | Varies by shot count; budget 5–15 min per shot including review |
| **Quality Standard** | A character/asset is visually identical to its reference sheet across every shot in the episode |
| **Dependencies** | Sections 11–13, Section 34 |
| **Version** | 1.0 |

## 15. Animation SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Bring generated frames/assets into motion |
| **Inputs** | Approved frame art; scene plan (Section 9) |
| **Outputs** | Animated shot sequences |
| **Responsible Role** | Animation Lead |
| **Checklist** | ☐ Motion matches Camera Movement Standards (Section 16) ☐ No off-model drift mid-shot ☐ Timing matches scene plan durations |
| **Estimated Time** | 1–3 hrs per minute of finished animation (varies heavily by complexity) |
| **Quality Standard** | No perceptible inconsistency in character proportions/color between the first and last frame of a shot |
| **Dependencies** | Section 14 |
| **Version** | 1.0 |

## 16. Camera Movement Standards **[LIVING SECTION]**

```
STATIC SHOT ──▶ used for dialogue-heavy, emotional beats
PAN / TILT  ──▶ used for environment reveals (new Zone, new location)
PUSH-IN     ──▶ used to land an emotional beat or a twist reveal
TRACKING    ──▶ used for action/movement sequences only
```

**Rule:** No more than one "big" camera move (push-in, dramatic tracking shot) per scene, to preserve their impact — mirrors Series Bible Section 24's "one major revelation per episode" pacing rule.

## 17. Voice Production SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Cast, direct, and record character voice performances |
| **Inputs** | Script; character voice/speech-pattern notes (Series Bible Appendix A, Studio OS Section 21) |
| **Outputs** | Final voice audio files per character per episode |
| **Responsible Role** | Voice Lead |
| **Checklist** | ☐ Casting/direction template completed (character, Zone, want, reference reads, pronunciation notes — Studio OS Section 21) ☐ Pronunciation of in-world proper nouns confirmed against World Bible Section 13 (Terminology Reference) ☐ No accent used as a lazy "foreign/other" shortcut |
| **Estimated Time** | 1–2 hrs per episode (recording + selects) |
| **Quality Standard** | Performance matches the character's documented Speech Style without deviation |
| **Dependencies** | Section 7 |
| **Version** | 1.0 |

## 18. Music Production SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Score episodes with original or fully licensed music |
| **Inputs** | Rough cut; Zone/character musical motifs (Studio OS Section 20) |
| **Outputs** | Final music stems |
| **Responsible Role** | Audio Lead |
| **Checklist** | ☐ No unlicensed or IP-soundalike temp music makes it to final ☐ Zone leitmotif used consistently where established ☐ Logged in `publishing/audio-licenses.md` |
| **Estimated Time** | 2–5 hrs per episode |
| **Quality Standard** | Dialogue intelligibility is never compromised by the score (Studio OS Section 20) |
| **Dependencies** | Section 20 (rough cut) |
| **Version** | 1.0 |

## 19. Sound Effects SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Add and maintain a consistent SFX library (Cipher activation sounds, Breach ambience, Zone-specific ambience) |
| **Inputs** | Rough cut; existing SFX library |
| **Outputs** | Final SFX layer |
| **Responsible Role** | Audio Lead |
| **Checklist** | ☐ Recurring effects (a specific Cipher, a Breach) reuse the same source file every time ☐ New SFX logged into the library with a clear name (Section 29) |
| **Estimated Time** | 1–3 hrs per episode |
| **Quality Standard** | The same in-world phenomenon sounds identical across every episode it appears in |
| **Dependencies** | Section 20 |
| **Version** | 1.0 |

## 20. Editing SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Assemble animation, voice, music, and SFX into a locked cut |
| **Inputs** | Animated shots, voice files, music stems, SFX |
| **Outputs** | Rough cut → locked cut |
| **Responsible Role** | Editor |
| **Checklist** | ☐ Runtime within target window ☐ Pacing Standards followed (Series Bible Section 24) ☐ Cliffhanger lands on the final frame/line, not before (Series Bible Section 25) |
| **Estimated Time** | 3–6 hrs per episode |
| **Quality Standard** | A first-time viewer can follow the episode without needing prior context re-explained mid-cut |
| **Dependencies** | Sections 15, 17–19 |
| **Version** | 1.0 |

## 21. Color Grading SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Apply final color treatment consistent with each Zone's visual identity |
| **Inputs** | Locked cut; Zone palette guide (Art Bible `color-language.md`, Studio OS Section 19) |
| **Outputs** | Color-graded final picture |
| **Responsible Role** | Editor / Colorist |
| **Checklist** | ☐ Palette matches the episode's Zone(s) ☐ No two Zones appear visually identical in the same episode ☐ Consistent grade across all shots (no scene-to-scene color drift) |
| **Estimated Time** | 1–2 hrs per episode |
| **Quality Standard** | A muted-color screenshot from any point in the episode is still identifiable by Zone |
| **Dependencies** | Section 20 |
| **Version** | 1.0 |

## 22. Subtitle Standards **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Provide accurate, accessible captions for every episode |
| **Inputs** | Locked script; final audio |
| **Outputs** | Caption file (SRT/VTT) |
| **Responsible Role** | Editor |
| **Checklist** | ☐ Timed to final audio, not the script draft ☐ In-world proper nouns spelled per World Bible Section 13 (Terminology Reference) ☐ Reviewed for reading speed (no more than ~2 lines / ~40 characters per line held on screen too briefly) |
| **Estimated Time** | 30–60 min per episode |
| **Quality Standard** | Zero misspelled proper nouns; captions match final audio exactly |
| **Dependencies** | Section 20 |
| **Version** | 1.0 |

## 23. Thumbnail SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Produce the episode's thumbnail |
| **Inputs** | Final episode; brand frame/template (Studio OS Section 22) |
| **Outputs** | Thumbnail image, up to two A/B variants |
| **Responsible Role** | Publishing/SEO Owner |
| **Checklist** | ☐ Depicted moment actually occurs in the episode ☐ Readable at mobile thumbnail size ☐ On-brand palette/typography ☐ Logged in Thumbnail Library (Knowledge Base Section 26) |
| **Estimated Time** | 30–60 min |
| **Quality Standard** | Passes the mobile-size readability test at first glance |
| **Dependencies** | Section 20 |
| **Version** | 1.0 |

## 24. Shorts Production SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Produce Shorts content per Studio OS Section 10's content buckets |
| **Inputs** | Mainline episode footage, or purpose-built short concept |
| **Outputs** | Sub-60-second vertical video |
| **Responsible Role** | Editor |
| **Checklist** | ☐ Hook lands within 1.5 seconds ☐ No canon contradiction with mainline content ☐ Clear CTA to mainline episode or web novel |
| **Estimated Time** | 30–90 min |
| **Quality Standard** | Meets the Shorts Checklist in full (Studio OS Section 10) |
| **Dependencies** | Section 20 (if cut from mainline footage) |
| **Version** | 1.0 |

## 25. SEO SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Write title, description, and tags for maximum discoverability without misrepresenting content |
| **Inputs** | Final episode; SEO Standards (Studio OS Section 23) |
| **Outputs** | Publish-ready metadata |
| **Responsible Role** | Publishing/SEO Owner |
| **Checklist** | ☐ Title formula followed ☐ Description includes spoiler-safe synopsis and cross-links ☐ Tags include series, Zone(s), recurring characters |
| **Estimated Time** | 20–30 min |
| **Quality Standard** | Metadata accurately represents episode content — no clickbait |
| **Dependencies** | Section 20 |
| **Version** | 1.0 |

## 26. Upload SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Technically upload the finished, QA-passed episode to the publishing platform |
| **Inputs** | Final render, thumbnail, subtitle file, metadata |
| **Outputs** | Scheduled or live upload |
| **Responsible Role** | Publishing/SEO Owner |
| **Checklist** | ☐ Correct resolution/format for platform spec ☐ Captions attached ☐ Thumbnail attached ☐ Scheduled per Publishing Workflow (Section 27) |
| **Estimated Time** | 15–20 min |
| **Quality Standard** | Zero upload-stage errors (wrong file version, missing captions) |
| **Dependencies** | Section 38 (QA must pass first) |
| **Version** | 1.0 |

## 27. Publishing SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Sequence release across formats per Studio OS Section 12 |
| **Inputs** | Uploaded episode; corresponding web novel chapter/comic page if applicable |
| **Outputs** | Coordinated multi-format release |
| **Responsible Role** | Publishing/SEO Owner |
| **Checklist** | ☐ No format contradicts another (Studio OS Section 12) ☐ Release order follows the staggered schedule, not simultaneous premieres, until capacity supports it |
| **Estimated Time** | 15 min coordination overhead |
| **Quality Standard** | Any discrepancy found post-publish is corrected against the Bible as source of truth, not left standing |
| **Dependencies** | Section 26 |
| **Version** | 1.0 |

## 28. Asset Management SOP **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Keep every produced asset findable, versioned, and non-duplicated |
| **Inputs** | All assets produced under Sections 11–13 |
| **Outputs** | Up-to-date Asset Registry (Knowledge Base Section 22) |
| **Responsible Role** | Animation Lead |
| **Checklist** | ☐ Every new asset logged the same day it's finalized ☐ Version number attached ☐ Superseded asset versions archived, not deleted |
| **Estimated Time** | 10–15 min per asset |
| **Quality Standard** | Any team member can locate the current version of any asset without asking the original creator |
| **Dependencies** | Sections 11–13 |
| **Version** | 1.0 |

---

## 29. File Naming Standards **[LOCKED]**

Extends Knowledge Base Section 9 with production-specific file types:

| Asset Type | Convention | Example |
|---|---|---|
| Script | `scripts/S{season}E{episode}_{slug}.md` | `scripts/S01E04_the-bout.md` |
| Character reference sheet | `production/assets/characters/{zone}_{name}_v{X.X}.png` | `production/assets/characters/lower-sector_kael_v1.0.png` |
| Environment plate | `production/assets/environments/{zone}_{location-slug}_v{X.X}.png` | `production/assets/environments/lower-sector_ward-station-seven_v1.0.png` |
| Raw render | `production/renders/S{season}E{episode}_v{X.X}.mp4` | `production/renders/S01E04_v1.0.mp4` |
| SFX file | `production/audio/sfx/{category}_{name}.wav` | `production/audio/sfx/sigil_ember-cast.wav` |
| Thumbnail | `publishing/thumbnails/S{season}E{episode}_v{variant}.png` | `publishing/thumbnails/S01E04_vA.png` |

## 30. Folder Structure **[LOCKED spine, LIVING subfolders]**

```
/production/
  /assets/
    /characters/
    /environments/
    /props/
  /storyboards/
  /renders/
  /audio/
    /voice/
    /music/
    /sfx/
/scripts/
/publishing/
  /thumbnails/
  /metadata/
```

**[LIVING]** — create each subfolder at the point real content exists for it, per Knowledge Base Section 4's rule against speculative scaffolding.

## 31. Backup Strategy **[LOCKED]**

- All text-based canon and process documents (Bible, Studio OS, Series Bible, scripts, this document) live in this git repository — full history is the backup.
- Large binary production assets (renders, raw audio, source art files) should not be committed directly to this documentation repository; they belong in dedicated cloud storage with its own versioning, referenced from the Asset Registry by link/ID, not embedded.
- **Rule:** no single-location storage for any final asset — every finished episode's source files should exist in at least two places before the working copy is cleared.

## 32. Version Control **[LOCKED]**

All production documents and assets use the studio-wide **v{major}.{minor}** convention (Studio OS Section 30). For binary assets, the version number lives in the filename (Section 29) since git diffing doesn't apply meaningfully to images/video/audio.

## 33. GitHub Workflow **[LOCKED]**

- This repository holds documentation, scripts, and lightweight text assets only (per Section 31).
- Substantial documentation changes go through a feature branch and pull request, per Knowledge Base Section 5, before merging to `main`.
- Production/asset management systems for binary files (Section 31) are a separate, non-git tooling decision to be made when asset volume justifies it — not yet required at current (pre-production) scale.

## 34. Prompt Management **[LIVING SECTION]**

| Field | Value |
|---|---|
| **Purpose** | Store and organize every reusable AI prompt so quality/tone doesn't have to be re-derived each time |
| **Inputs** | Any prompt used more than once across script, image, or voice generation |
| **Outputs** | Entry in the Prompt Library (Studio OS Section 16) |
| **Responsible Role** | Whoever originates the prompt; Creative Director reviews for tone/canon fit |
| **Checklist** | ☐ Purpose documented ☐ Example output attached ☐ Known failure modes noted (Studio OS Section 16) |
| **Estimated Time** | 5–10 min per prompt |
| **Quality Standard** | A team member unfamiliar with the prompt can use it correctly from its documentation alone |
| **Dependencies** | Studio OS Section 16 |
| **Version** | 1.0 |

## 35. Prompt Versioning **[LIVING SECTION]**

- Prompts are versioned the same way documents are: `v{major}.{minor}`.
- A prompt that changes its intended output category (e.g., from "character concept" to "environment concept") is a new prompt, not a version bump of the old one.
- Track which prompt version produced any given production asset, so a later prompt refinement doesn't silently invalidate the reasoning behind an already-approved asset.

```
PROMPT FLOW:
  Draft prompt → Test on sample output → Check against Originality Framework (Studio OS Section 5)
       → Log in Prompt Library (Section 34) → Version-tag → Reuse
```

## 36. AI Tool Documentation **[LIVING SECTION]**

| Category | Tool | Status |
|---|---|---|
| Script drafting | *(to be specified when selected)* | 📋 Planned |
| Image generation | *(to be specified when selected)* | 📋 Planned |
| Voice generation | *(to be specified when selected)* | 📋 Planned |
| Animation | *(to be specified when selected)* | 📋 Planned |

**Rule:** every tool entered here must have its output subject to the Originality Decision Framework (Studio OS Section 5) regardless of which vendor or model produced it — this table exists to track *what's in use*, not to endorse any tool as exempt from review.

## 37. Automation Opportunities **[LIVING SECTION]**

| Opportunity | Value | Status |
|---|---|---|
| Automated thumbnail A/B upload | Saves manual publishing steps | 📋 Candidate — not yet built |
| Metadata templating (title/description/tags scaffolding) | Reduces SEO SOP time | 📋 Candidate |
| Scheduled publishing/release calendar | Enforces Publishing SOP cadence automatically | 📋 Candidate |
| Registry-sync check (flag unlogged assets) | Prevents Asset Management SOP drift | 📋 Candidate |

**Rule:** no automation is built before its manual SOP has been run successfully at least once — automate a working process, not a hypothetical one.

## 38. Quality Assurance Checklist **[LOCKED]**

Extends Studio OS Section 14 with production-technical checks:

- [ ] Originality Check passed (Studio OS Section 5)
- [ ] No contradiction with Locked Bible/Series Bible sections
- [ ] Correct resolution, frame rate, and format for the publishing platform
- [ ] Audio levels normalized, dialogue intelligible, no clipping
- [ ] Lip-sync/timing acceptable throughout
- [ ] No visible AI-generation artifacts
- [ ] Captions match final audio exactly, correct proper-noun spelling
- [ ] Thumbnail depicts an actual in-episode moment
- [ ] SEO metadata complete and accurate
- [ ] Final watch-through by someone other than the primary creator, when feasible

## 39. Production Time Estimates **[LIVING SECTION]**

| Stage | Estimated Time (per 8–15 min episode) |
|---|---|
| Pre-Production | 0.5 hr |
| Script | 3–6 hrs |
| Storyboard | 2–4 hrs |
| Scene Planning | 1–2 hrs |
| Asset Planning | 0.5–1 hr |
| Image Generation | Varies by shot count (est. 3–8 hrs) |
| Animation | Varies heavily (est. 6–20 hrs) |
| Voice | 1–2 hrs |
| Music/SFX | 3–8 hrs |
| Edit | 3–6 hrs |
| Color Grade | 1–2 hrs |
| Subtitles | 0.5–1 hr |
| Thumbnail | 0.5–1 hr |
| QA | 0.5–1 hr |
| Upload/Publish | 0.5 hr |
| **Total (rough order of magnitude)** | **~25–55 hrs per episode at current solo-founder scale** |

**[LIVING SECTION]** — these are pre-production estimates with no completed episode yet to calibrate against; revise after the first 3 episodes ship (see Section 47).

## 40. Common Failure Points **[LIVING SECTION]**

| Failure Point | Where It Happens | Root Cause |
|---|---|---|
| Character off-model drift | Image Generation / Animation | Reference sheet not used consistently as anchor |
| Canon contradiction slips through | Script | Canon check skipped under deadline pressure |
| Voice/character mismatch | Voice Production | Speech Style notes not referenced during direction |
| Pacing runs long/short | Editing | Scene Planning durations not followed |
| Originality drift | Any AI-assisted stage | Originality Check treated as a formality instead of a gate |
| Unlogged asset | Asset Planning/Management | Registry update skipped in the rush to move to the next stage |

## 41. Troubleshooting Guide **[LIVING SECTION]**

| Symptom | Likely Cause (Section 40 ref) | Fix |
|---|---|---|
| A character looks "off" in some shots | Reference sheet not re-used as generation anchor | Regenerate using the reference sheet explicitly; do not "eyeball" consistency |
| A reviewer flags a canon contradiction post-script | Canon check skipped | Add a mandatory Bible/Series Bible cross-check step before Storyboarding begins |
| Episode runs significantly over/under target | Scene Planning not followed in Edit | Re-anchor the edit to the locked scene plan durations before making further cuts |
| An asset gets rebuilt from scratch unnecessarily | Registry not checked | Re-run Asset Planning SOP Section 10 checklist before any new build request |

## 42. Future Team Roles **[LIVING SECTION]**

Extends Studio OS Section 29 with production-specific granularity:

| Role | Owns |
|---|---|
| Storyboard Artist | Sections 8–9 |
| Animation Lead | Sections 10–15, 21, 28 |
| Voice Lead | Section 17 |
| Audio Lead | Sections 18–19 |
| Editor | Sections 20, 22, 24 |
| Publishing/SEO Owner | Sections 23, 25–27 |
| QA Owner | Section 38 |

## 43. Weekly Sprint Workflow **[LIVING SECTION]**

Extends Studio OS Section 25 with a production-stage lens:

1. Identify which pipeline stage (Section 3) each in-flight episode currently sits at.
2. Confirm the next stage's Responsible Role (Section 4) has capacity this week.
3. Flag any episode stuck at the same stage for more than one sprint — investigate against Section 40/41.
4. Confirm the publish date is still realistic given remaining stages and their time estimates (Section 39).

## 44. Monthly Production Review **[LIVING SECTION]**

Extends Studio OS Section 26 with:
1. Actual vs. estimated time per stage (Section 39) — recalibrate estimates.
2. Failure points encountered this month (Section 40) — update the Troubleshooting Guide (Section 41) if a new pattern emerged.
3. Registry health check — any unlogged assets found?
4. Automation opportunities (Section 37) — has any manual SOP now run often enough to justify automating it?

## 45. KPI Dashboard **[LIVING SECTION]**

```
Episodes in Pipeline ............ [░░░░░░░░░░]  0 active (pre-production stage)
Average Cycle Time / Episode .... Not yet measured — no completed episode
QA Pass Rate (first pass) ....... Not yet measured
Asset Reuse Rate ................ Not yet measured
On-Time Publish Rate ............ Not yet measured
```

**[LIVING SECTION]** — activate real tracking the moment S01E01 enters Pre-Production.

## 46. Production Metrics **[LIVING SECTION]**

| Metric | Definition | Target (initial, to be calibrated) |
|---|---|---|
| Cycle Time | Pre-Production start → Publish, per episode | Establish baseline after first 3 episodes |
| Rework Rate | % of assets/shots requiring a redo after QA | < 15% |
| Asset Reuse Rate | % of episode's assets pulled from registry vs. newly built | Increase over the season as the registry grows |
| QA First-Pass Rate | % of episodes passing full QA checklist without a second pass | > 80% |

## 47. Improvement Process **[LOCKED]**

**SOP:**
1. After each episode ships, log actual time-per-stage against the estimates in Section 39.
2. At each Monthly Production Review (Section 44), identify the single largest gap between estimate and actual.
3. Update the relevant SOP's Estimated Time field and, if the gap reveals a process issue (not just an estimation issue), propose a Section 40/41 update.
4. Version-bump this document (Section 32) whenever an SOP's steps — not just its time estimate — change.

## 48. Studio Expansion Plan **[LIVING SECTION]**

Mirrors Studio OS Section 28's phased roadmap, applied to production capacity specifically:

| Trigger | Response |
|---|---|
| A single pipeline stage consistently blocks the weekly sprint (Section 43) for 3+ consecutive sprints | Prioritize filling that stage's Future Team Role (Section 42) before any other hire |
| Episode volume exceeds what solo-founder + AI tooling can sustain at target cadence (Studio OS Section 11) | Bring in contract support for the single most time-consuming stage (Section 39), not a full team at once |
| Registry/asset volume grows beyond what this repository can reasonably hold as text-adjacent files | Stand up dedicated binary-asset storage per Section 31, rather than continuing to work around it |

---

## Master Checklists

### Episode Production Checklist
- [ ] Pre-Production brief approved (Section 6)
- [ ] Script written and canon-checked (Section 7)
- [ ] Storyboard approved (Section 8)
- [ ] Scene plan locked (Section 9)
- [ ] Assets planned, registry checked (Section 10)
- [ ] Characters/environments/props built or reused (Sections 11–13)
- [ ] Frames generated and originality-checked (Section 14)
- [ ] Animation complete and consistency-reviewed (Section 15)
- [ ] Voice recorded (Section 17)
- [ ] Music and SFX complete (Sections 18–19)
- [ ] Edit locked (Section 20)
- [ ] Color graded (Section 21)
- [ ] Subtitles complete (Section 22)
- [ ] Thumbnail produced (Section 23)
- [ ] Full QA checklist passed (Section 38)
- [ ] Uploaded and published (Sections 26–27)

### Short Production Checklist
- [ ] Concept fits a Shorts content bucket (Studio OS Section 10)
- [ ] Hook lands within 1.5 seconds
- [ ] No canon contradiction with mainline content
- [ ] Clear CTA included
- [ ] QA pass completed (Section 38, abbreviated for short-form)

### Thumbnail Creation Checklist
- [ ] Depicts an actual in-episode moment
- [ ] Readable at mobile size
- [ ] On-brand palette/typography
- [ ] Logged in Thumbnail Library

### Voice Review Checklist
- [ ] Matches documented Speech Style
- [ ] Pronunciation of proper nouns confirmed
- [ ] No stereotype-based accent shortcuts
- [ ] Levels clean, no clipping

### Animation Review Checklist
- [ ] No off-model drift within or across shots
- [ ] Motion matches Camera Movement Standards (Section 16)
- [ ] Timing matches locked scene plan

### Publishing Checklist
- [ ] All formats' content cross-checked for contradiction (Studio OS Section 12)
- [ ] Metadata complete (Section 25)
- [ ] Correct file versions uploaded (Section 26)
- [ ] Release sequenced per Publishing SOP (Section 27)

### Quality Assurance Checklist
See Section 38 (full).

---

## Visual Flow Diagrams

**Content Flow**
```
Series Bible Outline → Script → Storyboard → Scene Plan → Production → Edit → Publish → Analytics → (feeds back into) Series Bible Future Season Plans
```

**Asset Flow**
```
Asset Need Identified → Registry Checked → [Exists? Reuse : Build New] → Originality Check → Logged in Registry → Available for Reuse
```

**Approval Flow**
```
Draft (any stage) → Self-check against this document's SOP checklist → Canon check (Bible/Series Bible) → Creative Director approval → Stage-gate cleared → Next stage begins
```

**Publishing Flow**
```
QA Passed → Metadata Prepared → Uploaded → Scheduled → Published → Cross-format links updated → Analytics tracked (Studio OS Section 24)
```

**Prompt Flow**
```
Draft Prompt → Test Output → Originality Framework Check → Log in Prompt Library → Version Tag → Reused Across Future Episodes
```

---

*End of Production Operating System Version 1.0. Recalibrate Section 39 estimates and Section 45 KPIs the moment real production data exists — this document is written pre-production and should not be mistaken for a document born from finished episodes.*

---

### Changelog
`[v1.0 — 2026-07-06] Initial Production Operating System established: 48-section pipeline manual covering pre-production through publishing, asset/prompt management, version control, QA, metrics, and studio expansion triggers.`
`[v1.0 — 2026-07-06] Synced terminology to The Fracture Protocol pivot: "Realm" references changed to "Zone," Sigil/Relic/Rift references changed to Cipher/Root Artifact/Breach, and stale numbered citations to the retired fantasy Mythic Bible corrected to point at the new World Bible and Art Bible files.`
