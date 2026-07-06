# MYTHIC FORGE STUDIOS
## Mythic Forge Knowledge Base
### Version 1.0 — Studio Home Page

**Forging Worlds. Creating Legends.**

This is the central source of truth for Mythic Forge Studios' documentation ecosystem. It does not contain lore, canon, or process rules itself — it **indexes, connects, and governs how existing documents relate to each other**. When in doubt about where something lives, start here.

Status legend used throughout: ✅ Complete &nbsp;|&nbsp; 🔄 In Progress &nbsp;|&nbsp; 📋 Planned &nbsp;|&nbsp; ⬜ Not Started

---

## 1. Executive Overview

Mythic Forge Studios is building one original fantasy universe (**The Shattered Realms**) across YouTube animation, web novel, comic, and future game/merch formats. Three foundational documents exist today; everything else — future series, registries, production assets — is designed to slot into the structure this Knowledge Base defines.

| Field | Value |
|---|---|
| **Purpose** | Single entry point for all studio documentation |
| **Owner** | Founder (Creative Director + COO) |
| **Primary Documents** | This document |
| **Dependencies** | None — this is the root |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | As team roles are filled (Studio OS Section 29), ownership of individual sections below should transfer from "Founder" to the named role |

---

## 2. Documentation Architecture

Four document types exist, each with a distinct job. None should duplicate another's content — if it does, that's a documentation bug, flag it via the Review Workflow (Section 34).

| Document Type | Job | Current Instance(s) |
|---|---|---|
| **Knowledge Base** | Navigation and system rules only — never authoritative on content | This document |
| **Studio OS** | How the studio *works* — process, workflow, standards | `studio-os/Studio_OS_v1.0.md` |
| **World Bible** | What the universe *is* — canon law | `bible/Mythic_Bible_v2.0.md` |
| **Series Bible** | How one specific series tells its story within the universe | `series/01-kael-the-shattered-realms/Series_Bible_v1.0.md` |

| Field | Value |
|---|---|
| **Purpose** | Define the four document types and their non-overlapping responsibilities |
| **Owner** | Founder (Creative Director + COO) |
| **Primary Documents** | All three completed documents (Section 11) |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | A fifth type — **Registry** (character/relic/kingdom trackers) — is planned (Section 13) and will slot in beneath Series Bibles |

---

## 3. Master Navigation Index

| Document | Path | Governs | Version | Status |
|---|---|---|---|---|
| Mythic Forge Knowledge Base | `README.md` | Navigation & system rules | 1.0 | ✅ Complete |
| Studio Operating System | `studio-os/Studio_OS_v1.0.md` | Company process, workflow, standards | 1.0 | ✅ Complete |
| Mythic Bible — The Shattered Realms | `bible/Mythic_Bible_v2.0.md` | Universe canon | 2.0 | ✅ Complete |
| Kael: The Shattered Realms — Series Bible | `series/01-kael-the-shattered-realms/Series_Bible_v1.0.md` | Series 01 story canon | 1.0 | ✅ Complete |

**[LIVING]** — every new document created for Mythic Forge Studios must be added to this table on the day it's created. An undocumented document does not count as part of the ecosystem.

---

## 4. Folder Structure

```
/                                    → this Knowledge Base (README.md)
/bible/                              → world canon (Mythic Bible)
/studio-os/                          → operational process documents
/series/                             → one subfolder per series
  /01-kael-the-shattered-realms/     → Series 01 bible and future scripts
/registries/                         → [PLANNED] living trackers: characters, relics, kingdoms, monsters
/scripts/                            → [PLANNED] episode/chapter scripts, by season/arc
/production/                         → [PLANNED] storyboards, VO, footage, art
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

**Standard practice:** `main` holds published, current documentation. Substantial revisions (new document versions, major canon changes) are developed on a feature branch and merged via pull request so changes are reviewable before they become canon — mirroring the Lore Consistency / Canon Change SOPs (Bible Section 56, Studio OS Section 18).

---

## 6. Documentation Hierarchy

Authority flows top to bottom. A lower tier may add detail; it may never contradict a higher one without going through the Review Workflow (Section 34).

1. **Mythic Bible** (`bible/`) — highest authority on anything world-related
2. **Studio OS** (`studio-os/`) — highest authority on anything process-related
3. **Series Bibles** (`series/`) — authoritative for their own series only; subordinate to the Mythic Bible
4. **Registries / Production Docs** (`registries/`, `production/`, `scripts/`) — implementation detail; subordinate to all of the above
5. **Knowledge Base** (this document) — authoritative on *navigation only*, never on content

| Field | Value |
|---|---|
| **Purpose** | Resolve "which document wins" questions before they become arguments |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | All indexed documents |
| **Dependencies** | Section 2 |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | When a second series/universe is added, define whether it shares the Mythic Bible or introduces its own — this is a founder-level decision, not a default |

---

## 7. Source of Truth Rules

| Conflict Type | Resolution |
|---|---|
| World lore vs. Series Bible | Mythic Bible wins; Series Bible is corrected |
| Series Bible vs. production script | Series Bible wins; script is corrected |
| Process question (Studio OS) vs. lore question (Bible) | Each is authoritative in its own domain — they should never actually conflict; if they appear to, it's a documentation bug |
| Two Series Bibles (future) | Mythic Bible arbitrates; neither Series Bible outranks the other |

| Field | Value |
|---|---|
| **Purpose** | Give writers/artists a fast answer when two documents disagree |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Bible Section 56, Studio OS Section 18 |
| **Dependencies** | Section 6 |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
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

Consolidates Studio OS Section 17 (operational asset naming) and Mythic Bible Section 53 (in-world phonetic naming) into one reference point.

| Asset Type | Convention | Example |
|---|---|---|
| World document | `bible/{Document_Name}_v{X.X}.md` | `bible/Mythic_Bible_v2.0.md` |
| Series document | `series/{NN}-{series-slug}/{Document_Name}_v{X.X}.md` | `series/01-kael-the-shattered-realms/Series_Bible_v1.0.md` |
| Registry entry | `registries/{type}/{realm}_{name}.md` | `registries/characters/duskmarch_kael.md` |
| Episode script | `scripts/S{season}E{episode}_{slug}.md` | `scripts/S01E04_the-bout.md` |
| In-world proper nouns | Follow Realm phonetic profile | Bible Section 53 |

| Field | Value |
|---|---|
| **Purpose** | One naming standard for both operational files and in-world names |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Section 17, Bible Section 53 |
| **Dependencies** | Section 4 |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Add conventions for game-development assets when Phase 3 (Studio OS Section 28) begins |

---

## 10. Document Status Tracker

| Document | Version | Status | Last Updated | Owner |
|---|---|---|---|---|
| Mythic Forge Knowledge Base | 1.0 | ✅ Complete | 2026-07-06 | Founder |
| Studio OS | 1.0 | ✅ Complete | 2026-07-06 | Founder |
| Mythic Bible | 2.0 | ✅ Complete | 2026-07-06 | Founder |
| Kael: The Shattered Realms Series Bible | 1.0 | ✅ Complete | 2026-07-06 | Founder |
| Character Registry | — | ⬜ Not Started | — | Unassigned |
| Relic Registry | — | ⬜ Not Started | — | Unassigned |
| Kingdoms & Politics companion doc | — | ⬜ Not Started | — | Unassigned |
| Visual Style Guide | — | ⬜ Not Started | — | Unassigned |
| Season One Scripts (S01E01–S01E20) | — | ⬜ Not Started | — | Unassigned |

---

## 11. Current Completed Documents

| Document | Version | One-Line Summary |
|---|---|---|
| Studio OS | 1.0 | Operational handbook: vision, values, workflows, QA, IP protection, roadmap |
| Mythic Bible | 2.0 | 60-section world canon for The Shattered Realms, plus Kael's franchise profile |
| Kael: The Shattered Realms Series Bible | 1.0 | Series 01's premise, cast, and full Season One (20-episode) outline |

| Field | Value |
|---|---|
| **Purpose** | Quick reference for what already exists and doesn't need to be rebuilt |
| **Owner** | Founder |
| **Primary Documents** | The three listed above |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Add each new document here the day it's finished, not retroactively |

---

## 12. Documents In Progress

**None currently.** All three foundational documents are at a stable, complete v1.0/v2.0 state.

| Field | Value |
|---|---|
| **Purpose** | Track active documentation work so effort isn't duplicated |
| **Owner** | Founder |
| **Primary Documents** | N/A |
| **Dependencies** | Section 13 (a document moves from Planned → In Progress → Complete) |
| **Status** | ⬜ Not Started (nothing in progress) |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | The first candidates to enter this section are the Character and Relic Registries once Season One production begins |

---

## 13. Planned Documents

| Planned Document | Purpose | Trigger to Begin |
|---|---|---|
| Character Registry | Individual reference pages per named character | Cast grows beyond the Series 01 core six (Kael + Section 6 of Series Bible) |
| Relic Registry | Catalog named Relics as they're introduced in-story | First named Relic appears in a script |
| Monster/Bestiary Registry | Full per-Realm creature catalog | Production needs grounded creature detail beyond Bible Sections 23–25 |
| Kingdoms & Politics Companion | Detailed dynasties, local wars, treaties | Referenced as needed by Bible Section 14 |
| Visual Style Guide | Sigil alphabet, per-Realm palettes, character reference sheets | Art production begins |
| Season Two Series Bible | Season Two of Kael: The Shattered Realms | Season One is in production/nearing completion |
| Prompt Library files | Reusable AI prompts (Studio OS Section 16) | First production pass begins |

| Field | Value |
|---|---|
| **Purpose** | Prevent planned work from being forgotten or duplicated |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Studio OS Section 16, Bible Sections 19/23–25, Series Bible Section 12 |
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
| **Primary Documents** | `bible/Mythic_Bible_v2.0.md` Appendix A (Kael, world-level); `series/01-kael-the-shattered-realms/Series_Bible_v1.0.md` Sections 6–9 and Appendix A (full Series 01 cast) |
| **Dependencies** | Section 13 (Character Registry, planned) |
| **Status** | 🔄 In Progress — documented inline, not yet in a standalone registry |
| **Version** | Tracks source documents (2.0 / 1.0) |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Migrate to `registries/characters/` once cast size makes inline documentation unwieldy — see Character Tracker below |

**Character Tracker**

| Character | Realm | Documented In | Status |
|---|---|---|---|
| Kael | The Duskmarch | Bible Appendix A; Series Bible Appendix A | ✅ Complete |
| Sella Rook | The Ironroot Expanse (transplant) | Series Bible Section 6 | ✅ Complete |
| Reyth | The Duskmarch | Series Bible Section 6 | ✅ Complete |
| Warden Ansel Vray | The Duskmarch | Series Bible Section 6 | ✅ Complete |
| High Warden Serath | The Duskmarch | Series Bible Section 6 | ✅ Complete |
| Instructor Halvard Ossic | The Duskmarch | Series Bible Section 7 | ✅ Complete |
| Former High Warden Yselde Cray | The Duskmarch | Series Bible Section 7 | ✅ Complete |
| Aris | N/A (Echo) | Series Bible Section 6 | ✅ Complete |

---

## 15. Realm Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to where each of the Seven Great Realms is documented |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | `bible/Mythic_Bible_v2.0.md` Sections 3, 5–8, 26–30 |
| **Dependencies** | None |
| **Status** | 🔄 In Progress — all seven named and profiled; deep per-Realm detail is a living section |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Deep-dive one Realm per season of production focus, per Series Bible Section 12 |

**Realm Tracker**

| Realm | Aspect | Anchor Kingdom | Detail Level |
|---|---|---|---|
| Emberfall | Flame / Ambition | The Pyrion Crown | Profiled |
| The Tidewrought | Tide / Memory | The Maren Thalassocracy | Profiled |
| The Ironroot Expanse | Stone / Endurance | The Ironroot Concord | Profiled |
| The Windmere Reaches | Wind / Freedom | The Skyward Free Fleets | Profiled |
| The Duskmarch | Shadow / Death | The Duskmarch Wardenate | Deepest detail (Series 01 setting) |
| The Solvane Dominion | Light / Judgment | The Solvane Dominion | Profiled |
| The Verdant Wilds | Growth / Life | The Evergreen Courts | Profiled |

---

## 16. Creature Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to all creature/monster canon |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Bible Sections 23–25 |
| **Dependencies** | Section 13 (Bestiary Registry, planned) |
| **Status** | 🔄 In Progress — categories and two Legendary Beasts defined; full bestiary pending |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Expand per-Realm as episodic needs arise (Bible Section 24) |

**Monster/Creature Tracker**

| Entry | Category | Realm | Status |
|---|---|---|---|
| Voidspawn | Category | Any (Rift-origin) | Defined (category only) |
| Curdled Echoes | Category | Any | Defined (category only) |
| Realm-beasts | Category | Per-Realm | Defined (category only) |
| Sigil-constructs | Category | Solvane / Ironroot | Defined (category only) |
| The Cinderwake | Legendary Beast | Emberfall | Named, undeveloped in-story |
| The Hollow King | Legendary Beast | The Duskmarch | Named; foreshadowed in Series Bible Episode 14 |

---

## 17. Timeline Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to the master historical timeline |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Bible Section 14 |
| **Dependencies** | None |
| **Status** | ✅ Complete (spine); 🔄 detail is living |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Series Bible Section 10–11 nests Season One's specific events inside the Fourth Age; future series should nest the same way rather than editing the master timeline directly |

---

## 18. Power System Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to all magic/power canon (Essence, Sigils, Echoes, Relics, Paths) |
| **Owner** | Founder (Creative Director) |
| **Primary Documents** | Bible Sections 15–22 |
| **Dependencies** | None |
| **Status** | ✅ Complete (framework); 🔄 catalog detail (named Relics, Sigils) is living |
| **Version** | 2.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | Relic Registry (Section 13) will house individually named Relics as they're introduced |

---

## 19. Story Documentation Index

| Field | Value |
|---|---|
| **Purpose** | Point to all series/story-level documentation |
| **Owner** | Founder (Creative Director / Head Writer) |
| **Primary Documents** | `series/01-kael-the-shattered-realms/Series_Bible_v1.0.md` |
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
| **Primary Documents** | Studio OS Section 13 |
| **Dependencies** | Section 19 (scripts must exist before production) |
| **Status** | ⬜ Not Started — process defined, no assets produced yet |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | `/production/` folder to be created when Episode S01E01 enters storyboard stage |

---

## 21. Prompt Library Index

| Field | Value |
|---|---|
| **Purpose** | Track reusable AI prompts for lore, script, visual, and voice generation |
| **Owner** | Founder → future role owners per prompt category |
| **Primary Documents** | Studio OS Section 16 |
| **Dependencies** | None |
| **Status** | ⬜ Not Started |
| **Version** | 1.0 (process only) |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | First entries expected once script/visual drafting for Season One begins |

**Prompt Tracker**

| Prompt Category | File (planned) | Status |
|---|---|---|
| Lore drafting | `studio-os/prompts/lore.md` | ⬜ Not Started |
| Script drafting | `studio-os/prompts/scripts.md` | ⬜ Not Started |
| Visual generation | `studio-os/prompts/visual.md` | ⬜ Not Started |
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
| **Purpose** | Track compositions, licenses, and per-Realm musical motifs |
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
| **Primary Documents** | Studio OS Section 22 |
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
| **Primary Documents** | Studio OS Section 5 (Creative Philosophy — Originality Decision Framework), Section 16 (Prompt Library) |
| **Dependencies** | Section 21 |
| **Status** | 🔄 In Progress — governing principle defined (AI drafts, never auto-approves); prompt-level detail pending |
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
| **Primary Documents** | Bible Section 56 (Lore Consistency Rules), Studio OS Section 18 (Lore Documentation Standards) |
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
| **Status** | ✅ Complete — already in active use (see changelog blocks in all three completed documents) |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | This Knowledge Base's own changelog is at the bottom of this document |

---

## 39. Risk Register

| Risk | Category | Likelihood | Impact | Mitigation |
|---|---|---|---|---|
| Single-founder bottleneck across all creative and operational decisions | Operational | High | High | Studio OS Section 29 role map defines hand-off points as hiring begins |
| Documentation drift (a doc changes but the Knowledge Base index isn't updated) | Documentation | Medium | Medium | Section 3 and Section 10 must be updated the same day any document changes |
| Canon contradiction between a future Series Bible and the Mythic Bible | Creative | Medium | High | Section 7 (Source of Truth Rules) and Bible Section 56 Canon Change SOP |
| Originality drift from AI-assisted drafting | Legal / Creative | Medium | High | Studio OS Section 5 Originality Decision Framework is mandatory, not optional, on every AI-assisted asset |
| Platform dependency (YouTube algorithm/policy changes) | Business | Medium | Medium | Studio OS Section 28 phased roadmap treats YouTube as Phase 1 of several planned formats, not the sole channel |
| IP exposure before formal registration | Legal | Low (pre-revenue) | High | Studio OS Section 27 — git history serves as a timestamped authorship record until formal registration is justified |

| Field | Value |
|---|---|
| **Purpose** | Track known risks to the studio and documentation ecosystem in one place |
| **Owner** | Founder (COO) |
| **Primary Documents** | Studio OS Sections 5, 27, 29 |
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
| **Primary Documents** | Studio OS Section 28 (Phased Roadmap), Bible Section 57 (Future Expansion Opportunities) and Section 60 (Unanswered Questions), Series Bible Section 12 (Future Season Plans) |
| **Dependencies** | All prior sections |
| **Status** | ✅ Complete (as an index — the underlying roadmaps themselves are living) |
| **Version** | 1.0 |
| **Last Updated** | 2026-07-06 |
| **Future Expansion Notes** | When a second universe or series is greenlit, this section gains a second roadmap table rather than replacing the first |

---

## Dashboards

### Studio Progress

```
Vision & Values .......... [██████████] 100%  ✅ Complete
Creative Canon ............ [██████████] 100%  ✅ Complete (v2.0)
Series 01 Story Bible ...... [██████████] 100%  ✅ Complete (v1.0)
Team / Roles ............... [██░░░░░░░░]  20%  🔄 Solo founder; roles mapped, unfilled
Production Pipeline ........ [░░░░░░░░░░]   0%  ⬜ Not started
Publishing ................. [░░░░░░░░░░]   0%  ⬜ Not started
```

### Documentation Progress

```
Foundational Docs (KB, OS, Bible, Series Bible) [██████████] 100%  ✅ 4 / 4 complete
Registries (Character, Relic, Bestiary, etc.)   [░░░░░░░░░░]   0%  ⬜ 0 / 3 planned started
Production Companion Docs                       [░░░░░░░░░░]   0%  ⬜ Not started
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

### Episode Progress (Season One — Kael: The Shattered Realms)

```
Outlined ................ [██████████] 100%  20 / 20  ✅ Complete (Series Bible Section 11)
Scripted ................. [░░░░░░░░░░]   0 / 20  ⬜ Not started
Produced ................. [░░░░░░░░░░]   0 / 20  ⬜ Not started
Published ................. [░░░░░░░░░░]   0 / 20  ⬜ Not started
```

### Series Progress

```
Series 01 — Kael: The Shattered Realms
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
| Elysia / the Fracture / the Aurothi | Core cosmology | Bible Sections 2–4, 12 | ✅ Locked |
| Seven Great Realms | Core cosmology | Bible Section 5 | ✅ Locked |
| Essence System (7 Aspects) | Power system | Bible Section 16 | ✅ Locked |
| Sigils / Echoes / Relics | Power system | Bible Sections 17–19 | ✅ Locked |
| The Reassembly theory | Ongoing mystery | Bible Section 45, 60 | 🔄 Deliberately unresolved |

### Episodes Tracker

See **Episode Progress** dashboard above and Series Bible Section 11 for full per-episode detail (Title, Objective, Conflict, Growth, Twist, Cliffhanger).

### Realms / Artifacts / Monsters / Prompts / Assets / Brand Files / Marketing / Automation Trackers

See Sections 15, 16, 21–23, 28, 31 above — each carries its own tracker table to avoid duplicating the same data in two places.

---

*End of Mythic Forge Knowledge Base Version 1.0. This document is the home page — update its indexes and trackers the same day any other document changes.*

---

### Changelog
`[v1.0 — 2026-07-06] Initial Knowledge Base established: 40-section index, dashboards, and master trackers covering Studio OS v1.0, Mythic Bible v2.0, and the Kael: The Shattered Realms Series Bible v1.0.`
