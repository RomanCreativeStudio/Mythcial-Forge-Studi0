# MYTHIC FORGE STUDIOS
## Mythic Forge Knowledge Base
### Version 2.0 — Studio Home Page

**Forging Worlds. Creating Legends.**

This is the central source of truth for Mythic Forge Studios' documentation ecosystem. It does not contain lore, canon, or process rules itself — it **indexes, connects, and governs how existing documents relate to each other**. When in doubt about where something lives, start here.

Status legend used throughout: ✅ Complete &nbsp;|&nbsp; 🔄 In Progress &nbsp;|&nbsp; 📋 Planned &nbsp;|&nbsp; ⬜ Not Started

---

## 1. Executive Overview

Mythic Forge Studios is building one original sci-fi dystopian universe (**The Fracture Protocol**) across YouTube animation and future web novel/comic/game/merch formats. A locked Master System Prompt anchors every other document so the universe never drifts; everything else — future series, registries, production assets — slots into the structure this Knowledge Base defines.

| Field | Value |
|---|---|
| **Purpose** | Single entry point for all studio documentation |
| **Owner** | Founder (Creative Director + COO) |
| **Primary Documents** | This document |
| **Dependencies** | None — this is the root |
| **Status** | ✅ Complete |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | As team roles are filled (Studio OS Section 29), ownership of individual sections below should transfer from "Founder" to the named role |

---

## 2. Documentation Architecture

Six document types exist, each with a distinct job. None should duplicate another's content — if it does, that's a documentation bug, flag it via the Review Workflow (Section 34).

| Document Type | Job | Current Instance(s) |
|---|---|---|
| **Master System Prompt** | The absolute, compressed anti-drift firewall — the single source of truth every other document must never contradict | `bible/Fracture_Protocol_Master_System_Prompt_v1.0.md` |
| **Knowledge Base** | Navigation and system rules only — never authoritative on content | This document |
| **Studio OS** | How the studio *works* — company-level process, workflow, standards | `studio-os/Studio_OS_v1.0.md` |
| **Production OS** | How an episode actually gets made — step-by-step department SOPs | `production-os/Production_OS_v1.0.md` |
| **Art Bible** | How everything *looks* — visual law across camera, light, color, materials, and system-effect VFX | `mythic-forge-art-bible/` (10 files, indexed in Section 3) |
| **World Bible** | What the universe *is* — canon law, expanding on the Master System Prompt | `bible/Fracture_Protocol_World_Bible_v1.1.md` |
| **Series Bible** | How one specific series tells its story within the universe | `series/01-the-fracture-protocol/Series_Bible_v1.1.md` |

| Field | Value |
|---|---|
| **Purpose** | Define the document types and their non-overlapping responsibilities |
| **Owner** | Founder (Creative Director + COO) |
| **Primary Documents** | All completed documents (Section 11) |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | A **Registry** type (character/artifact trackers) is planned (Section 13) and will slot in beneath Series Bibles |

---

## 3. Master Navigation Index

| Document | Path | Governs | Version | Status |
|---|---|---|---|---|
| Mythic Forge Knowledge Base | `README.md` | Navigation & system rules | 2.0 | ✅ Complete |
| Fracture Protocol Master System Prompt | `bible/Fracture_Protocol_Master_System_Prompt_v1.0.md` | Absolute canon lock / anti-drift firewall | 1.0 | ✅ Complete |
| Studio Operating System | `studio-os/Studio_OS_v1.0.md` | Company process, workflow, standards | 1.0 | ✅ Complete |
| Production Operating System | `production-os/Production_OS_v1.0.md` | Department-level production SOPs, pipeline, QA | 1.0 | ✅ Complete |
| Mythic Forge Art Bible (10 files) | `mythic-forge-art-bible/` | Visual law: camera, lighting, color, materials, environment, system-effect VFX, mood, forbidden elements, consistency, prompt library | 3.0 | ✅ Complete |
| Fracture Protocol World Bible | `bible/Fracture_Protocol_World_Bible_v1.1.md` | Universe canon | 1.1 | ✅ Complete |
| The Fracture Protocol — Series Bible | `series/01-the-fracture-protocol/Series_Bible_v1.1.md` | Series 01 story canon | 1.1 | ✅ Complete |

**[LIVING]** — every new document created for Mythic Forge Studios must be added to this table on the day it's created. An undocumented document does not count as part of the ecosystem.

**Art Bible file breakdown:**

| File | Path |
|---|---|
| Visual Development Guide (master index) | `mythic-forge-art-bible/visual-development-guide.md` |
| Camera Language | `mythic-forge-art-bible/camera-language.md` |
| Lighting System | `mythic-forge-art-bible/lighting-system.md` |
| Color Language | `mythic-forge-art-bible/color-language.md` |
| Materials and Textures | `mythic-forge-art-bible/materials-and-textures.md` |
| Environment Design Rules | `mythic-forge-art-bible/environment-design-rules.md` |
| System Interference Visual Rules | `mythic-forge-art-bible/system-interference-visual-rules.md` |
| Cinematic Mood Guide | `mythic-forge-art-bible/cinematic-mood-guide.md` |
| Forbidden Elements | `mythic-forge-art-bible/forbidden-elements.md` |
| Global Consistency Rules | `mythic-forge-art-bible/global-consistency-rules.md` |
| Prompt Library | `mythic-forge-art-bible/prompt-library.md` |

---

## 4. Folder Structure

```
/                                    → this Knowledge Base (README.md)
/bible/                              → world canon: Master System Prompt + World Bible
/studio-os/                          → company-level operational process documents
/production-os/                      → department-level production SOPs and pipeline manual
/mythic-forge-art-bible/             → visual law: camera, lighting, color, materials, environment, system-effect VFX, mood, forbidden elements, consistency, prompts
/series/                             → one subfolder per series
  /01-the-fracture-protocol/         → Series 01 bible and future scripts
/registries/                         → [PLANNED] living trackers: characters, artifacts, factions
/scripts/                            → [PLANNED] episode/chapter scripts, by season/arc
/production/                         → [PLANNED] storyboards, VO, footage, art (binary assets — see Production OS Section 31)
/publishing/                         → [PLANNED] metadata, thumbnails, SEO records per release
```

| Field | Value |
|---|---|
| **Purpose** | Define where every category of file belongs |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 15 (File Organization Standards) |
| **Dependencies** | None |
| **Status** | 🔄 In Progress — core folders exist; production/publishing/registries not yet created |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Create `/registries/`, `/scripts/`, `/production/`, `/publishing/` at the point actual content exists for them — do not scaffold empty folders speculatively |

---

## 5. Repository Structure

| Field | Value |
|---|---|
| **Purpose** | Define how the repository itself is used (branching, review, merge) |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 30 (Version Control & Documentation Update Process) |
| **Dependencies** | Section 2 (Documentation Architecture) |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | As team grows, define per-role branch/PR permissions in Studio OS Section 29 |

**Standard practice:** `main` holds published, current documentation. Substantial revisions (new document versions, major canon changes) are developed on a feature branch and merged via pull request so changes are reviewable before they become canon — mirroring the Canon Change SOP (Studio OS Section 18).

---

## 6. Documentation Hierarchy

Authority flows top to bottom. A lower tier may add detail; it may never contradict a higher one without going through the Review Workflow (Section 34).

1. **Master System Prompt** (`bible/Fracture_Protocol_Master_System_Prompt_v1.0.md`) — the absolute anti-drift firewall; highest authority on anything, full stop
2. **World Bible** (`bible/Fracture_Protocol_World_Bible_v1.1.md`) — highest authority on world-related detail, subordinate only to the Master System Prompt
3. **Studio OS** (`studio-os/`) — highest authority on company-level process
4. **Series Bibles** (`series/`) — authoritative for their own series only; subordinate to the World Bible and Master System Prompt
5. **Production OS** (`production-os/`) — highest authority on how episodes get made technically; implements Studio OS Section 13 and must never contradict a Series Bible's story requirements
6. **Art Bible** (`mythic-forge-art-bible/`) — highest authority on how canon is visually rendered; never redefines what canon *means*, only how it looks
7. **Registries / Production Docs** (`registries/`, `production/`, `scripts/`) — implementation detail; subordinate to all of the above
8. **Knowledge Base** (this document) — authoritative on *navigation only*, never on content

| Field | Value |
|---|---|
| **Purpose** | Resolve "which document wins" questions before they become arguments |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | All indexed documents |
| **Dependencies** | Section 2 |
| **Status** | ✅ Complete |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | When a second series/universe is added, define whether it shares the World Bible or introduces its own — this is a founder-level decision, not a default |

---

## 7. Source of Truth Rules

| Conflict Type | Resolution |
|---|---|
| Master System Prompt vs. anything | Master System Prompt always wins |
| World Bible vs. Series Bible | World Bible wins; Series Bible is corrected |
| Series Bible vs. production script | Series Bible wins; script is corrected |
| Process question (Studio OS) vs. lore question (World Bible) | Each is authoritative in its own domain — they should never actually conflict; if they appear to, it's a documentation bug |
| Two Series Bibles (future) | World Bible arbitrates; neither Series Bible outranks the other |

| Field | Value |
|---|---|
| **Purpose** | Give writers/artists a fast answer when two documents disagree |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Master System Prompt Section 10, Studio OS Section 18 |
| **Dependencies** | Section 6 |
| **Status** | ✅ Complete |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Extend this table as new document types are introduced |

---

## 8. Version Control Standards

All documents use **v{major}.{minor}** versioning (Studio OS Section 30). Major bump = locked-section/canon change requiring founder sign-off; minor bump = additive, living-section update. Every version bump appends a one-line changelog entry to the bottom of the changed document. This Knowledge Base follows the same rule and is versioned independently of the documents it indexes.

| Field | Value |
|---|---|
| **Purpose** | Keep version history auditable across the entire documentation ecosystem |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 30 |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Once multiple contributors exist, require changelog entries to include author initials |

---

## 9. Naming Conventions

Consolidates Studio OS Section 17 (operational asset naming) and World Bible Section 13 (in-world terminology) into one reference point.

| Asset Type | Convention | Example |
|---|---|---|
| World document | `bible/{Document_Name}_v{X.X}.md` | `bible/Fracture_Protocol_World_Bible_v1.1.md` |
| Series document | `series/{NN}-{series-slug}/{Document_Name}_v{X.X}.md` | `series/01-the-fracture-protocol/Series_Bible_v1.1.md` |
| Registry entry | `registries/{type}/{zone}_{name}.md` | `registries/characters/lower-sector_kael.md` |
| Episode script | `scripts/S{season}E{episode}_{slug}.md` | `scripts/S01E04_the-bout.md` |
| In-world terminology | Follow the Terminology Reference | World Bible Section 13 |

| Field | Value |
|---|---|
| **Purpose** | One naming standard for both operational files and in-world terminology |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 17, World Bible Section 13 |
| **Dependencies** | Section 4 |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Add conventions for game-development assets when Phase 3 (Studio OS Section 28) begins |

---

## 10. Document Status Tracker

| Document | Version | Status | Last Updated | Owner |
|---|---|---|---|---|
| Mythic Forge Knowledge Base | 2.0 | ✅ Complete | 2026-07-06 | Founder |
| Fracture Protocol Master System Prompt | 1.0 | ✅ Complete | 2026-07-06 | Founder |
| Studio OS | 1.0 | ✅ Complete | 2026-07-06 | Founder |
| Production OS | 1.0 | ✅ Complete | 2026-07-06 | Founder |
| Mythic Forge Art Bible | 3.0 | ✅ Complete | 2026-07-06 | Founder |
| Fracture Protocol World Bible | 1.1 | ✅ Complete | 2026-07-06 | Founder |
| The Fracture Protocol Series Bible | 1.1 | ✅ Complete | 2026-07-06 | Founder |
| Character Registry | — | ⬜ Not Started | — | Unassigned |
| Root Artifact Registry | — | ⬜ Not Started | — | Unassigned |
| Season One Scripts (S01E01–S01E20) | — | ⬜ Not Started | — | Unassigned |

---

## 11. Current Completed Documents

| Document | Version | One-Line Summary |
|---|---|---|
| Fracture Protocol Master System Prompt | 1.0 | Compressed, absolute canon lock: universe identity, Kael's visual/age lock, world structure, system rules, prompt system, anti-drift firewall |
| Studio OS | 1.0 | Operational handbook: vision, values, workflows, QA, IP protection, roadmap |
| Production OS | 1.0 | 48-section department-level production manual: SOPs, pipeline, QA, metrics |
| Mythic Forge Art Bible | 3.0 | 10-file visual law: single sanctioned register (semi-realistic anime cinematic hybrid), megacity color system, system-interference VFX rules, prompt library |
| Fracture Protocol World Bible | 1.1 | Lean world canon: the megacity's four layers, Authority System, Signal/Cipher-work/Fragment-Sync/Static-Reading/Fragments/Root Artifacts, the Reassembly, the Salvage Line, Terminology Reference |
| The Fracture Protocol Series Bible | 1.1 | Series 01's premise, cast, and full Season One (20-episode) outline, plus Coda (Salvage Line broker, Static-Reader) reserved for Season Two |

| Field | Value |
|---|---|
| **Purpose** | Quick reference for what already exists and doesn't need to be rebuilt |
| **Owner** | Founder |
| **Primary Documents** | The six listed above |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Add each new document here the day it's finished, not retroactively |

---

## 12. Documents In Progress

**None currently.** All six foundational documents are at a stable, complete v1.0/v3.0 state.

| Field | Value |
|---|---|
| **Purpose** | Track active documentation work so effort isn't duplicated |
| **Owner** | Founder |
| **Primary Documents** | N/A |
| **Dependencies** | Section 13 (a document moves from Planned → In Progress → Complete) |
| **Status** | ⬜ Not Started (nothing in progress) |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | The first candidates to enter this section are the Character and Root Artifact Registries once Season One production begins |

---

## 13. Planned Documents

| Planned Document | Purpose | Trigger to Begin |
|---|---|---|
| Character Registry | Individual reference pages per named character | Cast grows beyond the Series 01 core six (Kael + Section 6 of Series Bible) |
| Root Artifact Registry | Catalog named Root Artifacts as they're introduced in-story | First named Root Artifact appears in a script |
| Fragment/Anomaly Registry | Full catalog of Fragments and corrupted-Fragment entities | Production needs grounded detail beyond World Bible Sections 8, 10 |
| Cipher Glyph Companion | Detailed visual glyph designs implementing Art Bible `color-language.md`/`system-interference-visual-rules.md` | Art production begins |
| Season Two Series Bible | Season Two of The Fracture Protocol | Season One is in production/nearing completion |

| Field | Value |
|---|---|
| **Purpose** | Prevent planned work from being forgotten or duplicated |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | World Bible Sections 8, 10–11, Series Bible Section 12 |
| **Dependencies** | Section 12 |
| **Status** | 📋 Planned |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Re-review this list at every Monthly Review (Section 36) |

---

## 14. Character Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to where every character is documented today, ahead of a dedicated registry |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Master System Prompt Section 4 (Kael canon lock); `series/01-the-fracture-protocol/Series_Bible_v1.1.md` Sections 6–9 and Appendix A (full Series 01 cast) |
| **Dependencies** | Section 13 (Character Registry, planned) |
| **Status** | 🔄 In Progress — documented inline, not yet in a standalone registry |
| **Version** | Tracks source documents (1.1) |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Migrate to `registries/characters/` once cast size makes inline documentation unwieldy — see Character Tracker below |

**Character Tracker**

| Character | Zone | Documented In | Status |
|---|---|---|---|
| Kael | Lower Sector | Master System Prompt Section 4; Series Bible Appendix A | ✅ Complete |
| Sella Rook | Lower Sector | Series Bible Section 6 | ✅ Complete |
| Reyth | Lower Sector | Series Bible Section 6 | ✅ Complete |
| Ward Ansel Vray | Lower Sector | Series Bible Section 6 | ✅ Complete |
| Division Director Serath | Lower Sector | Series Bible Section 6 | ✅ Complete |
| Technician Halvard Ossic | Lower Sector | Series Bible Section 7 | ✅ Complete |
| Former Division Director Yselde Cray | Lower Sector | Series Bible Section 7 | ✅ Complete |
| Aris | N/A (Fragment) | Series Bible Section 6 | ✅ Complete |
| Coda | The Substrate | Series Bible Section 12 | ✅ Complete (reserved for Season Two) |

---

## 15. Zone Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to where each of the megacity's four layers is documented |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | `bible/Fracture_Protocol_World_Bible_v1.1.md` Section 3 |
| **Dependencies** | None |
| **Status** | ✅ Complete (framework); 🔄 deep per-Zone detail is a living section |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Deep-dive one Zone per season of production focus, per Series Bible Section 12 |

**Zone Tracker**

| Zone | Function | Detail Level |
|---|---|---|
| Upper Grid | Authority governance infrastructure | Profiled |
| Mid Zone | Civilian population layer | Profiled |
| Lower Sector | Fracture zone; home to Ward Station Seven | Deepest detail (Series 01 setting) |
| Unknown Layer | Unmapped; origin of Fractures | Deliberately undetailed — never fully explained by design |

---

## 16. Creature / Anomaly Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to all Fragment/anomaly canon |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | World Bible Section 8 (Fragments), Section 5 (Fracture Anomaly Subjects) |
| **Dependencies** | Section 13 (Fragment/Anomaly Registry, planned) |
| **Status** | 🔄 In Progress — core categories defined; full catalog pending |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Expand as episodic needs arise |

**Fragment/Anomaly Tracker**

| Entry | Category | Status |
|---|---|---|
| Clean Fragment | Category | Defined (World Bible Section 8) |
| Corrupted Fragment | Category | Defined (World Bible Section 8) |
| Aris | Named Fragment | Fully documented (Series Bible Section 6) |
| The Hollow King | Named system-entity | Referenced/foreshadowed (Series Bible Episode 14); not yet formally defined in the World Bible — do not over-expand ahead of story need |

---

## 17. Timeline Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to what's confirmed about the setting's history |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | World Bible Section 2 (The Fracture — Founding Event) |
| **Dependencies** | None |
| **Status** | 🔄 Deliberately minimal — the founding event's cause is permanent unresolved scaffolding, not a gap to fill |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | A detailed historical timeline was not carried over from the retired fantasy Bible — do not reintroduce one without founder sign-off, per the Master System Prompt's "reject unauthorized expansions" rule |

---

## 18. Power System Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to all Signal/Cipher-work/Fragment-Sync/Static-Reading/Root Artifact canon |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | World Bible Sections 7–11 |
| **Dependencies** | None |
| **Status** | ✅ Complete (framework, now three disciplines); 🔄 catalog detail (named Root Artifacts) is living |
| **Version** | 1.1 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Root Artifact Registry (Section 13) will house individually named artifacts as they're introduced; Static-Reading (World Bible Section 7) is rare enough that Coda (Section 12/14) is currently its only named practitioner |

---

## 19. Story Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to all series/story-level documentation |
| **Owner** | Founder (Creative Director / Head Writer) |
| **Primary Documents** | `series/01-the-fracture-protocol/Series_Bible_v1.1.md` |
| **Dependencies** | Section 6 (Documentation Hierarchy) |
| **Status** | 🔄 In Progress — Series 01 fully outlined; scripts not yet written |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Each future series gets its own `series/{NN}-{slug}/` folder; add to Master Navigation Index (Section 3) on creation |

---

## 20. Production Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to production pipeline documentation |
| **Owner** | Founder → future Animation/Editor leads |
| **Primary Documents** | `production-os/Production_OS_v1.0.md` (department SOPs, pipeline, QA, metrics); Studio OS Section 13 (company-level pipeline policy) |
| **Dependencies** | Section 19 (scripts must exist before production) |
| **Status** | ✅ Complete (manual); ⬜ no assets produced against it yet |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | `/production/` folder to be created when Episode S01E01 enters storyboard stage (Production OS Section 8) |

---

## 21. Prompt Library Index

| Field | Value |
|---|---|
| **Purpose** | Track reusable AI prompts for visual generation (and, in future, script/voice) |
| **Owner** | Founder → future role owners per prompt category |
| **Primary Documents** | `mythic-forge-art-bible/prompt-library.md`; Studio OS Section 16; Production OS Sections 34–35 |
| **Dependencies** | None |
| **Status** | 🔄 In Progress — visual prompt templates complete (Kael base, emotion modifiers, world, thumbnail); script/voice prompts not yet started |
| **Version** | 2.0 (visual templates) |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | First script/voice prompt entries expected once Season One production begins |

**Prompt Tracker**

| Prompt Category | File | Status |
|---|---|---|
| Kael Base Prompt | `mythic-forge-art-bible/prompt-library.md` | ✅ Complete |
| Emotion Modifiers | `mythic-forge-art-bible/prompt-library.md` | ✅ Complete |
| World Prompt Template | `mythic-forge-art-bible/prompt-library.md` | ✅ Complete |
| Thumbnail Prompt Template | `mythic-forge-art-bible/prompt-library.md` | ✅ Complete |
| Script drafting | `studio-os/prompts/scripts.md` | ⬜ Not Started |
| Voice generation | `studio-os/prompts/voice.md` | ⬜ Not Started |

---

## 22. Asset Library Index

| Field | Value |
|---|---|
| **Purpose** | Track visual/production assets once they exist |
| **Owner** | Founder → future Animation Lead |
| **Primary Documents** | Studio OS Section 19 |
| **Dependencies** | Section 20 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Populate once first character reference sheets are produced |

**Asset Tracker**

| Asset | Type | Status |
|---|---|---|
| — | — | No assets produced yet |

---

## 23. Brand Asset Index

| Field | Value |
|---|---|
| **Purpose** | Track studio branding assets (logo, wordmark, color system) |
| **Owner** | Founder |
| **Primary Documents** | Studio OS Section 4 (Brand Personality) |
| **Dependencies** | None |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | A formal brand asset kit is a reasonable Phase 1 deliverable per Studio OS Section 28 |

**Brand Files Tracker**

| File | Type | Status |
|---|---|---|
| — | — | No brand files produced yet |

---

## 24. Music & Audio Library

| Field | Value |
|---|---|
| **Purpose** | Track compositions, licenses, and Zone-specific musical motifs |
| **Owner** | Founder → future Audio/Voice Lead |
| **Primary Documents** | Studio OS Section 20 |
| **Dependencies** | Section 20 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | `publishing/audio-licenses.md` to be created with first production pass (Studio OS Section 20) |

---

## 25. Voice Library

| Field | Value |
|---|---|
| **Purpose** | Track casting, direction notes, and pronunciation guides per character |
| **Owner** | Founder → future Voice Lead |
| **Primary Documents** | Studio OS Section 21 |
| **Dependencies** | Section 14 (Character Documentation Index) |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | First entries expected alongside Season One VO recording |

---

## 26. Thumbnail Library

| Field | Value |
|---|---|
| **Purpose** | Track thumbnail assets and A/B test results per episode |
| **Owner** | Founder → future Publishing/SEO Owner |
| **Primary Documents** | Studio OS Section 22; `mythic-forge-art-bible/prompt-library.md` (Thumbnail Prompt Template) |
| **Dependencies** | Section 19 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Populate starting with S01E01's release |

---

## 27. Animation Library

| Field | Value |
|---|---|
| **Purpose** | Track finished animation assets per episode |
| **Owner** | Founder → future Animation Lead |
| **Primary Documents** | Studio OS Section 13, Section 19 |
| **Dependencies** | Section 20 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | — |

---

## 28. Marketing Documentation

| Field | Value |
|---|---|
| **Purpose** | Track launch plans, campaign copy, and cross-platform promotion |
| **Owner** | Founder → future Community Manager |
| **Primary Documents** | Studio OS Section 4 (Brand Personality), Section 11 (YouTube Strategy) |
| **Dependencies** | Section 23 (Brand Asset Index) |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | First marketing documentation expected ahead of S01E01 launch |

**Marketing Tracker**

| Campaign/Asset | Status |
|---|---|
| — | Nothing produced yet |

---

## 29. Analytics Documentation

| Field | Value |
|---|---|
| **Purpose** | Track channel/content performance once published |
| **Owner** | Founder → future Publishing/SEO Owner |
| **Primary Documents** | Studio OS Section 24 |
| **Dependencies** | Section 30 (Publishing Documentation) |
| **Status** | ⬜ Not Started — no content published yet |
| **Version** | 1.0 (process only) |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Activate the Weekly/Monthly review cadence (Sections 35–36) the day S01E01 publishes |

---

## 30. Publishing Documentation

| Field | Value |
|---|---|
| **Purpose** | Track release metadata, SEO records, and cross-format release sequencing |
| **Owner** | Founder → future Publishing/SEO Owner |
| **Primary Documents** | Studio OS Sections 12, 23 |
| **Dependencies** | Section 20 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | `/publishing/` folder to be created alongside the first scheduled release |

---

## 31. Automation Documentation

| Field | Value |
|---|---|
| **Purpose** | Document any scripted/automated tooling (publishing pipelines, batch asset processing, etc.) |
| **Owner** | Founder (COO) |
| **Primary Documents** | None yet — new category, not covered explicitly by Studio OS v1.0 |
| **Dependencies** | Section 20, Section 30 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Once any automation exists (e.g., scheduled publishing, batch rendering), document it here before relying on it operationally |

**Automation Tracker**

| Automation | Purpose | Status |
|---|---|---|
| — | — | None built yet |

---

## 32. AI Workflow Documentation

| Field | Value |
|---|---|
| **Purpose** | Document how AI tools are used across writing, art, and voice production, and the guardrails around them |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Studio OS Section 5 (Creative Philosophy — Originality Decision Framework), Master System Prompt Section 10 (Consistency Enforcement System) |
| **Dependencies** | Section 21 |
| **Status** | 🔄 In Progress — governing principle defined (AI drafts, never auto-approves; Master System Prompt rejects unauthorized expansions); prompt-level detail growing |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Every AI-assisted deliverable must still pass the Originality Check before entering canon — this rule should never be relaxed as tooling scales |

---

## 33. Quality Assurance Documentation

| Field | Value |
|---|---|
| **Purpose** | Track the pre-publish QA checklist and its pass/fail history |
| **Owner** | Founder → future QA Owner |
| **Primary Documents** | Studio OS Section 14 |
| **Dependencies** | Section 20 |
| **Status** | ✅ Complete (checklist defined); ⬜ no items run through it yet |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | First real QA pass expected on S01E01 |

---

## 34. Review Workflow

| Field | Value |
|---|---|
| **Purpose** | Define how canon changes and document revisions get approved |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Master System Prompt Section 10, Studio OS Section 18 (Lore Documentation Standards) |
| **Dependencies** | Section 7 (Source of Truth Rules) |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | As more writers join, add a designated second reviewer for Locked-section changes |

---

## 35. Sprint Planning

| Field | Value |
|---|---|
| **Purpose** | Weekly planning cadence and template |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 25 |
| **Dependencies** | None |
| **Status** | ✅ Complete (process defined); ⬜ not yet run in practice |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Begin logging actual Weekly Sprint Logs once production starts |

---

## 36. Monthly Review System

| Field | Value |
|---|---|
| **Purpose** | Monthly retro/strategy cadence and agenda |
| **Owner** | Founder |
| **Primary Documents** | Studio OS Section 26 |
| **Dependencies** | Section 35 |
| **Status** | ✅ Complete (process defined); ⬜ not yet run in practice |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | First Monthly Review should audit this Knowledge Base's Document Status Tracker (Section 10) for drift |

---

## 37. Quarterly Planning

| Field | Value |
|---|---|
| **Purpose** | Longer-horizon planning cadence bridging Monthly Review and the annual Vision check-in |
| **Owner** | Founder |
| **Primary Documents** | None yet — **identified gap**, not currently defined in Studio OS v1.0 |
| **Dependencies** | Section 36 |
| **Status** | ⬜ Not Started |
| **Version** | N/A |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Recommend adding a "Quarterly Planning" section to Studio OS v1.1, sitting between Monthly Review (Section 26) and the annual Vision/Mission check-in referenced in Studio OS Section 1 |

---

## 38. Change Log System

| Field | Value |
|---|---|
| **Purpose** | Standardize how every document records its own history |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 30 |
| **Dependencies** | Section 8 (Version Control Standards) |
| **Status** | ✅ Complete — already in active use (see changelog blocks in every completed document) |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | This Knowledge Base's own changelog is at the bottom of this document |

---

## 39. Risk Register

| Risk | Category | Likelihood | Impact | Mitigation |
|---|---|---|---|---|
| Single-founder bottleneck across all creative and operational decisions | Operational | High | High | Studio OS Section 29 role map defines hand-off points as hiring begins |
| Documentation drift (a doc changes but the Knowledge Base index isn't updated) | Documentation | Medium | Medium | Section 3 and Section 10 must be updated the same day any document changes |
| Canon contradiction between a future Series Bible and the World Bible | Creative | Medium | High | Section 7 (Source of Truth Rules) and Master System Prompt Section 10 (Consistency Enforcement System) |
| Originality drift from AI-assisted drafting | Legal / Creative | Medium | High | Studio OS Section 5 Originality Decision Framework is mandatory, not optional, on every AI-assisted asset |
| Uncontrolled creative expansion (new factions/characters/systems introduced without sign-off) | Creative | Medium | Medium | Master System Prompt Section 10 explicitly rejects unauthorized expansions |
| Platform dependency (YouTube algorithm/policy changes) | Business | Medium | Medium | Studio OS Section 28 phased roadmap treats YouTube as Phase 1 of several planned formats, not the sole channel |
| IP exposure before formal registration | Legal | Low (pre-revenue) | High | Studio OS Section 27 — git history serves as a timestamped authorship record until formal registration is justified |

| Field | Value |
|---|---|
| **Purpose** | Track known risks to the studio and documentation ecosystem in one place |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Sections 5, 27, 29; Master System Prompt Section 10 |
| **Dependencies** | None |
| **Status** | ✅ Complete (initial register); 🔄 living — review every Monthly Review |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Add a "Date Identified" and "Date Resolved" column once the register has enough entries to need chronological tracking |

---

## 40. Future Expansion Roadmap

| Field | Value |
|---|---|
| **Purpose** | Point to where long-term studio and canon roadmaps already live, rather than duplicating them here |
| **Owner** | Founder (Creative Director + COO) |
| **Primary Documents** | Studio OS Section 28 (Phased Roadmap), Series Bible Section 12 (Future Season Plans), Series Bible Section 15 (Running Mysteries) |
| **Dependencies** | All prior sections |
| **Status** | ✅ Complete (as an index — the underlying roadmaps themselves are living) |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Any expansion here must be checked against the Master System Prompt's "reject unauthorized expansions" rule before being added |

---

## Dashboards

### Studio Progress

```
Vision & Values .......... [██████████] 100%  ✅ Complete
Master System Prompt ..... [██████████] 100%  ✅ Complete (v1.0, absolute canon lock)
Creative Canon ............ [██████████] 100%  ✅ Complete (World Bible v1.0)
Series 01 Story Bible ...... [██████████] 100%  ✅ Complete (v1.0)
Team / Roles ............... [██░░░░░░░░]  20%  🔄 Solo founder; roles mapped, unfilled
Production Pipeline ........ [░░░░░░░░░░]   0%  ⬜ Not started
Publishing ................. [░░░░░░░░░░]   0%  ⬜ Not started
```

### Documentation Progress

```
Foundational Docs (KB, Master Prompt, OS, World Bible, Series Bible) [██████████] 100%  ✅ 6 / 6 complete
Registries (Character, Root Artifact, Fragment/Anomaly)              [░░░░░░░░░░]   0%  ⬜ 0 / 3 planned started
Production Companion Docs                                            [░░░░░░░░░░]   0%  ⬜ Not started
```

### Production Progress

```
Season One Scripts (S01E01–S01E20) ... [░░░░░░░░░░]   0 / 20 written
Storyboards ........................... [░░░░░░░░░░]   0 / 20
Voice Recording ........................ [░░░░░░░░░░]   0 / 20
Animation .............................. [░░░░░░░░░░]   0 / 20
Edited/Final Episodes .................. [░░░░░░░░░░]   0 / 20
```

### Publishing Progress

```
Channel Setup .......... ⬜ Not documented in this repository
Upload Cadence Target ... 🔄 Defined (Studio OS Section 11) — not yet active
Episodes Published ...... [░░░░░░░░░░]   0 / 20 (Season One)
```

### Asset Progress

```
Brand Assets ............ [░░░░░░░░░░]   0%  ⬜ Not started
Character Reference Sheets [░░░░░░░░░░]   0 / 8 (Series 01 named cast)
Music/Audio ............. [░░░░░░░░░░]   0%  ⬜ Not started
Thumbnails .............. [░░░░░░░░░░]   0 / 20
```

### Episode Progress (Season One — The Fracture Protocol)

```
Outlined ................ [██████████] 100%  20 / 20  ✅ Complete (Series Bible Section 11)
Scripted ................. [░░░░░░░░░░]   0 / 20  ⬜ Not started
Produced ................. [░░░░░░░░░░]   0 / 20  ⬜ Not started
Published ................. [░░░░░░░░░░]   0 / 20  ⬜ Not started
```

### Series Progress

```
Series 01 — The Fracture Protocol (protagonist: Kael)
  World canon ........... [██████████] 100%  ✅ Complete
  Series Bible .......... [██████████] 100%  ✅ Complete
  Season One outline .... [██████████] 100%  ✅ Complete (20 / 20 episodes)
  Season One production . [░░░░░░░░░░]   0%  ⬜ Not started

Series 02+ .............. ⬜ Not yet planned (see Section 40)
```

---

## Master Trackers

### Lore Tracker (Locked Cosmology Entries)

| Entry | Type | Source | Status |
|---|---|---|---|
| The Fracture Protocol / Authority System | Core cosmology | Master System Prompt Sections 3–5; World Bible Sections 2, 4 | ✅ Locked |
| Megacity Structure (4 layers) | Core cosmology | Master System Prompt Section 5; World Bible Section 3 | ✅ Locked |
| Signal / Cipher-work / Fragment-Sync / Static-Reading | Power system | World Bible Section 7 | ✅ Locked (three disciplines, Two-Discipline Cap) |
| Fragments / Root Artifacts | Power system | World Bible Sections 8, 11 | ✅ Locked |
| The Reassembly theory | Ongoing mystery | World Bible Section 9; Series Bible Section 15 | 🔄 Deliberately unresolved |
| The Salvage Line | Faction | World Bible Section 16 | 🔄 Living — new, founder-approved (Coda is its first named member) |
| Kael's visual/age/anomaly-subject lock | Character canon | Master System Prompt Section 4 | ✅ Locked |

### Episodes Tracker

See **Episode Progress** dashboard above and Series Bible Section 11 for full per-episode detail (Title, Objective, Conflict, Growth, Twist, Cliffhanger).

### Zones / Artifacts / Fragments / Prompts / Assets / Brand Files / Marketing / Automation Trackers

See Sections 15, 16, 21–23, 28, 31 above — each carries its own tracker table to avoid duplicating the same data in two places.

---

*End of Mythic Forge Knowledge Base Version 2.0. This document is the home page — update its indexes and trackers the same day any other document changes.*

---

### Changelog
`[v1.0 — 2026-07-06] Initial Knowledge Base established: 40-section index, dashboards, and master trackers covering Studio OS v1.0, Mythic Bible v2.0, and the Kael: The Shattered Realms Series Bible v1.0.`
`[v1.0 — 2026-07-06] Indexed Production OS v1.0: added as a document type, added to Master Navigation Index, Folder Structure, Documentation Hierarchy, Document Status Tracker, Current Completed Documents, Production Documentation Index, and Prompt Library Index.`
`[v1.0 — 2026-07-06] Indexed Mythic Forge Art Bible v1.0 (10 files): added as a document type, added to Master Navigation Index (with file breakdown), Folder Structure, Documentation Hierarchy, and status trackers.`
`[v1.0 — 2026-07-06] Synced references for the nested-reveal creative pivot (Mythic Bible v3.0, Series Bible v2.0, Art Bible v2.0, restricted True Reality Codex v1.0).`
`[v2.0 — 2026-07-06] Full pivot to The Fracture Protocol per the final "Phase 2 Master Prompt" canon lock: retired the fantasy Mythic Bible v3.0 and the restricted True Reality Codex entirely (no more nested reveal — the sci-fi setting is now overt from Episode 1). Added the Fracture Protocol Master System Prompt v1.0 as the new top-of-hierarchy document. Replaced with the Fracture Protocol World Bible v1.0 and a fully reskinned Series Bible v1.0 (series/01-the-fracture-protocol/). Retitled "Realm Documentation Index" to "Zone Documentation Index" (four megacity layers replacing the Seven Great Realms), updated the Character Tracker's roles and titles, replaced the Lore Tracker and all dashboards accordingly, and updated Studio OS/Production OS cross-references throughout.`
`[v2.0 — 2026-07-06] Founder-approved additive expansion: World Bible bumped to v1.1 (added Static-Reading as a third recognized discipline, and The Salvage Line as a new faction alongside Authority/Ward Division/the Reassembly); Series Bible bumped to v1.1 (added Coda, a Season Two supporting character — Salvage Line broker and Static-Reader — explicitly scoped as non-competing with Kael per System Rule 4). Season One's 20-episode outline is unchanged. Synced all cross-references, the Character Tracker, the Power System Documentation Index, and the Lore Tracker accordingly.`
