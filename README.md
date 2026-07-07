# MYTHIC FORGE STUDIOS
## Studio Wiki
### Version 3.2 — Master Navigation System

**Forging Worlds. Creating Legends.**

This is the master navigation system for the entire Mythic Forge Studios repository. **It is not a Bible. It introduces no canon. It contains no lore. It makes no creative decisions.** Its sole purpose is to help contributors locate information quickly — where something is, who owns it, whether it's approved, what depends on it, whether it can be edited, whether it touches canon, and where to go next. Every answer here should take seconds to find. Where this document would need to restate lore, story, characters, powers, or world detail to answer a question, it links to the authoritative document instead.

Status legend used throughout: ✅ Complete &nbsp;|&nbsp; 🔄 In Progress &nbsp;|&nbsp; 📋 Planned &nbsp;|&nbsp; ⬜ Not Started

---

## 1. Welcome

If this is your first time in this repository: **start with Section 23 (Contributor Onboarding)**, not here. This page is a reference you'll return to, not a document you read start to finish.

Mythic Forge Studios is building one original sci-fi dystopian universe, **The Fracture Protocol**, across YouTube animation and future web novel/comic/game/merch formats. Everything in this repository exists to either (a) define what that universe *is*, (b) define how the studio *works*, or (c) define how an episode actually gets *made*. This Wiki's only job is to tell you which of those three buckets a given question belongs to, and which exact document answers it.

| Field | Value |
|---|---|
| **Purpose** | Orient a contributor arriving at this repository for the first time |
| **Owner** | Founder (Creative Director + COO) |
| **Dependencies** | None — this is the root |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 2. Repository Overview

Mythic Forge Studios currently maintains **ten core documents** across four tiers — canon, governance, studio process, and production process — plus this Wiki, which indexes all of them. Nothing "canon" lives outside the Bible tier (Section 5); nothing "operational" lives outside the governance or process tiers (Sections 6–7, 25).

**At a glance:**

| Layer | Answers | Current State |
|---|---|---|
| Canon (the Bibles) | What is the universe, and what happens in it? | Master System Prompt v1.2, World Bible v1.1, Series Bible v1.1 (Season One fully outlined, 20/20 episodes), Art Bible v3.0 (11 files), Proposal Vault v1.0 (7 entries pending decision) |
| Governance | Which process document governs what, and who can change it? | Studio Governance Manual v1.0 *(new — Section 25)* |
| Studio Process | How does the studio operate day to day? | Studio OS v1.0 |
| Production Process | How does an episode actually get made? | Production OS v1.0, Production Bible v1.0 *(new — see Section 6 and the Governance Manual's Section 3 for the current relationship between these two)* |
| Production Output | What's actually been made? | Nothing yet — Season One is fully outlined and not yet in active production (Section 18) |

| Field | Value |
|---|---|
| **Purpose** | Single-glance snapshot of what exists and what stage the studio is at |
| **Owner** | Founder (Creative Director + COO) |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 3. Canon Hierarchy

This is the order canon authority flows in. When two documents disagree, the higher one wins and the lower one is corrected — a disagreement is always a documentation bug, never a judgment call.

```
Master System Prompt  (bible/Fracture_Protocol_Master_System_Prompt_v1.2.md)
        │  absolute authority — includes the Canon Governance System (Sec. 12)
        │  and the Founder Override Protocol (Sec. 13)
        ▼
World Bible  (bible/Fracture_Protocol_World_Bible_v1.1.md)
        │  highest authority on world-related detail
        ▼
Series Bible(s)  (series/{NN}-{slug}/Series_Bible_v{X.X}.md)
        │  authoritative for their own series only
        ▼
Art Bible  (mythic-forge-art-bible/)
        │  authoritative on how canon is visually rendered — never what it means
        ▼
Production scripts / assets — implementation detail, subordinate to all of the above
```

**Special case — the Proposal Vault** (`bible/Fracture_Protocol_Proposal_Vault_v1.0.md`): sits entirely outside this hierarchy. It has zero authority over canon — every entry is "Proposed — Not Canon" until the creator explicitly approves it via the Founder Override Protocol (Master System Prompt Section 13). Approved content is then implemented in the appropriate tier above; the Vault entry itself is never deleted — it stays in place with its status updated, per the Vault's own rule.

**Conflict resolution table:**

| Conflict Type | Resolution |
|---|---|
| Master System Prompt vs. anything | Master System Prompt always wins |
| World Bible vs. Series Bible | World Bible wins; Series Bible is corrected |
| Series Bible vs. production script | Series Bible wins; script is corrected |
| Two Series Bibles (future) | World Bible arbitrates; neither outranks the other |
| Studio/Production process doc vs. lore question | Each is authoritative in its own domain — an apparent conflict is a documentation bug |

For the full governance mechanics (Drift Detection, Proposal Workflow, Founder Override Commands, Change Impact Reports, Minor/Major classification) see the Master System Prompt directly, Sections 12–13 — this Wiki does not restate them.

| Field | Value |
|---|---|
| **Purpose** | Resolve "which document wins" before it becomes a debate |
| **Owner** | Founder (Creative Director) |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 4. Studio Hierarchy

This Wiki does not restate role definitions or approval chains — all three already have a single authoritative home:

- **Team roles, responsibilities, and the approval hierarchy:** Production Bible Section 2 (Studio Organization) — this is the current, most complete version.
- **Company-level role roadmap (future hires):** Studio OS Section 29 (Studio Roles).
- **Founder / Creative Director / AI authority boundaries, and who approves what kind of change:** Studio Governance Manual Sections 5–8 — this is the authoritative source for jurisdiction questions specifically.
- **Creator authority over canon specifically:** Master System Prompt Section 12, Rule 1.

**Current state, in one line:** solo founder holding every role (Creative Director, Production Manager, and every department lead) until roles are filled per Studio OS Section 29's future role map.

| Field | Value |
|---|---|
| **Purpose** | Point to the single authoritative source for "who does what and who approves what" |
| **Owner** | Founder |
| **Dependencies** | Production Bible Section 2, Studio OS Section 29, Studio Governance Manual Sections 5–8 |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 5. Bible Index

| Document Name | Fracture Protocol Master System Prompt |
|---|---|
| **Purpose** | Absolute canon lock / anti-drift firewall; Canon Governance System and Founder Override Protocol |
| **Owner** | Founder (Creative Director) |
| **Current Version** | 1.2 |
| **Status** | ✅ Complete |
| **Locked or Living** | Locked (entire document) |
| **Dependencies** | None — this is the root of canon |
| **Related Documents** | World Bible, Series Bible, Art Bible, Proposal Vault |
| **Repository Location** | `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` |
| **Last Updated** | 2026-07-07 |

| Document Name | Fracture Protocol World Bible |
|---|---|
| **Purpose** | Universe canon — the megacity's structure, Authority System, Signal/Cipher-work/Fragment-Sync/Static-Reading, Fragments, Root Artifacts, factions, terminology reference |
| **Owner** | Founder (Creative Director) |
| **Current Version** | 1.1 |
| **Status** | ✅ Complete |
| **Locked or Living** | Mixed — see in-document `[LOCKED]` / `[LIVING]` tags per section |
| **Dependencies** | Master System Prompt |
| **Related Documents** | Series Bible, Art Bible, Proposal Vault |
| **Repository Location** | `bible/Fracture_Protocol_World_Bible_v1.1.md` |
| **Last Updated** | 2026-07-06 |

| Document Name | The Fracture Protocol — Series Bible (Series 01) |
|---|---|
| **Purpose** | Series 01 story canon — premise, cast, villains, relationships, full 20-episode Season One outline, future season plans |
| **Owner** | Founder (Creative Director / Head Writer) |
| **Current Version** | 1.1 |
| **Status** | ✅ Complete (Season One outline); scripts not yet written |
| **Locked or Living** | Mixed — see in-document `[LOCKED]` / `[LIVING SECTION]` tags per section |
| **Dependencies** | Master System Prompt, World Bible |
| **Related Documents** | World Bible, Art Bible |
| **Repository Location** | `series/01-the-fracture-protocol/Series_Bible_v1.1.md` |
| **Last Updated** | 2026-07-06 |

| Document Name | Mythic Forge Art Bible (11 files) |
|---|---|
| **Purpose** | Visual law — how canon is rendered: camera, lighting, color, materials, environment, system-effect VFX, mood, forbidden elements, consistency rules, prompt library |
| **Owner** | Founder (Creative Director) |
| **Current Version** | 3.0 (master index); individual files versioned independently — see file table below |
| **Status** | ✅ Complete |
| **Locked or Living** | Mixed — see in-document tags per file |
| **Dependencies** | Master System Prompt, World Bible |
| **Related Documents** | Prompt Library (Section 12), Production Bible Section 8 |
| **Repository Location** | `mythic-forge-art-bible/` |
| **Last Updated** | 2026-07-06 |

**Art Bible file breakdown:**

| File | Version | Repository Location |
|---|---|---|
| Visual Development Guide (master index) | 3.0 | `mythic-forge-art-bible/visual-development-guide.md` |
| Camera Language | 2.0 | `mythic-forge-art-bible/camera-language.md` |
| Lighting System | 2.0 | `mythic-forge-art-bible/lighting-system.md` |
| Color Language | 3.0 | `mythic-forge-art-bible/color-language.md` |
| Materials and Textures | 2.0 | `mythic-forge-art-bible/materials-and-textures.md` |
| Environment Design Rules | 2.0 | `mythic-forge-art-bible/environment-design-rules.md` |
| System Interference Visual Rules | 2.0 | `mythic-forge-art-bible/system-interference-visual-rules.md` |
| Cinematic Mood Guide | 2.0 | `mythic-forge-art-bible/cinematic-mood-guide.md` |
| Forbidden Elements | 3.0 | `mythic-forge-art-bible/forbidden-elements.md` |
| Global Consistency Rules | 3.0 | `mythic-forge-art-bible/global-consistency-rules.md` |
| Prompt Library | 2.0 | `mythic-forge-art-bible/prompt-library.md` |

For what any of these documents actually *say*, open the document — this index only tells you that it exists, what it's for, and where it lives.

**Planned:** a Season Two Series Bible, to be broken out once Season One is in production/nearing completion (Series Bible Section 12) — will be added as a new row above the day it's created.

---

## 6. Production Document Index

| Document Name | Fracture Protocol Production Bible |
|---|---|
| **Purpose** | Production operating manual — philosophy, studio organization, pipeline, folder structure, naming, version control, asset management, QA, risk management, review workflow, readiness/completion checklists, archiving |
| **Owner** | Founder (Creative Director / Production Manager) |
| **Current Version** | 1.0 |
| **Status** | ✅ Complete |
| **Locked or Living** | Mixed — see in-document tags per section |
| **Dependencies** | Master System Prompt (subordinate to it; never overrides canon) |
| **Related Documents** | Studio OS, Production OS |
| **Repository Location** | `production-bible/Fracture_Protocol_Production_Bible_v1.0.md` |
| **Last Updated** | 2026-07-07 |

| Document Name | Production Operating System |
|---|---|
| **Purpose** | 48-section department-level SOP manual: pre-production through publishing, asset/prompt management, version control, QA, metrics, troubleshooting |
| **Owner** | Founder (Technical Director) |
| **Current Version** | 1.0 |
| **Status** | ✅ Complete |
| **Locked or Living** | Mixed — see in-document tags per section |
| **Dependencies** | Studio OS, Master System Prompt, World Bible |
| **Related Documents** | Production Bible |
| **Repository Location** | `production-os/Production_OS_v1.0.md` |
| **Last Updated** | 2026-07-06 |

**Known open item:** the Production Bible and Production OS currently cover substantially overlapping ground (both define pipeline stages, folder structure, naming, version control, asset management, and QA). This was identified at the Production Bible's creation and intentionally left unresolved as a founder decision — see Production Bible Section 15 for the three reconciliation options on the table. The Studio Governance Manual's Section 3 now formally documents the interim jurisdiction split (Production Bible: organization, governance integration, risk management; Production OS: granular department-by-department implementation detail) as a provisional default, not a resolution — the founder's consolidate/delineate/leave-as-is decision is still open.

---

## 7. Studio OS Index

| Document Name | Mythic Forge Studios — Studio Operating System |
|---|---|
| **Purpose** | Company-level operational handbook: vision, values, creative philosophy, storytelling principles, brand, QA, IP protection, roles, roadmap |
| **Owner** | Founder (Creative Director + COO) |
| **Current Version** | 1.0 |
| **Status** | ✅ Complete |
| **Locked or Living** | Mixed — see in-document tags per section |
| **Dependencies** | Master System Prompt, World Bible |
| **Related Documents** | Production OS, Production Bible |
| **Repository Location** | `studio-os/Studio_OS_v1.0.md` |
| **Last Updated** | 2026-07-06 |

Key jump points inside Studio OS, so you don't have to read all 30 sections to find one: Vision (§1), Mission (§2), Creative Philosophy / Originality Framework (§5), Worldbuilding Standards (§7), Lore Documentation Standards / Canon Change SOP (§18), Studio Roles (§29), Version Control (§30).

---

## 8. Character Document Index

This Wiki does not restate any character's biography, personality, or arc — every row below is a pointer only.

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

**Fragment / Anomaly tracker** (Fragments are near-character entities, not props — indexed here rather than in Section 10):

| Entry | Category | Status |
|---|---|---|
| Clean Fragment | Category | Defined (World Bible Section 8) |
| Corrupted Fragment | Category | Defined (World Bible Section 8) |
| Aris | Named Fragment | Fully documented (Series Bible Section 6) |
| The Hollow King | Named system-entity | Referenced/foreshadowed (Series Bible Episode 14); not yet formally defined in the World Bible — do not over-expand ahead of story need |

| Field | Value |
|---|---|
| **Purpose** | Point to where every named character and Fragment/anomaly is documented, ahead of a dedicated Character Registry |
| **Owner** | Founder (Creative Director) |
| **Dependencies** | Section 10 (Prop Index shares the same registry-planned pattern), Section 16 (Naming Convention Reference) |
| **Related Documents** | Series Bible, Master System Prompt Section 4, World Bible Sections 5, 8, 14 (Character Creation Rules) |
| **Status** | 🔄 In Progress — documented inline; standalone Character/Fragment Registry not yet built |
| **Last Updated** | 2026-07-07 |

---

## 9. Environment Document Index

| Zone | Function | Documented In |
|---|---|---|
| Upper Grid | Authority governance infrastructure | World Bible Section 3; Art Bible `environment-design-rules.md` |
| Mid Zone | Civilian population layer | World Bible Section 3; Art Bible `environment-design-rules.md` |
| Lower Sector | Fracture zone; home to Ward Station Seven (Series 01 primary setting) | World Bible Section 3, Section 6; Art Bible `environment-design-rules.md` |
| Unknown Layer | Unmapped; origin of Fractures — deliberately undetailed by design | World Bible Section 2, Section 3 |

| Field | Value |
|---|---|
| **Purpose** | Point to where each of the megacity's four layers is documented |
| **Owner** | Founder (Creative Director) |
| **Dependencies** | None |
| **Related Documents** | World Bible Section 3, Art Bible `environment-design-rules.md` |
| **Status** | ✅ Complete (framework); deep per-Zone story detail is living |
| **Last Updated** | 2026-07-06 |

---

## 10. Prop Index

No individually named props or Root Artifacts exist in canon yet. This index will populate the moment one is introduced in a script.

| Entry | Type | Status |
|---|---|---|
| — | Named Root Artifact | None named yet |

**Planned companion document:** a Cipher Glyph Companion (detailed visual glyph designs implementing Art Bible `color-language.md`/`system-interference-visual-rules.md`) is planned to begin once Art production starts — it will be indexed here and in Section 5 (Bible Index) the day it's created.

| Field | Value |
|---|---|
| **Purpose** | Point to named prop/Root Artifact canon once it exists |
| **Owner** | Founder (Creative Director) |
| **Dependencies** | Section 11 (Asset Registry Index — planned Root Artifact Registry) |
| **Related Documents** | World Bible Section 11 (Root Artifacts); Art Bible `materials-and-textures.md` (Root Artifact Exception); Production Bible Section 5 (prop file naming) |
| **Status** | 📋 Planned — populates on first named prop |
| **Last Updated** | 2026-07-07 |

---

## 11. Asset Registry Index

| Field | Value |
|---|---|
| **Purpose** | Track visual/production assets (characters, environments, props) once they exist |
| **Owner** | Founder → future Animation Lead |
| **Dependencies** | Production Bible Section 7 (Asset Management — defines the Asset Registry's lifecycle: creation, review, approval, revision, retirement, archival) |
| **Related Documents** | Production Bible Section 7, Production OS Section 28 |
| **Status** | ⬜ Not Started — no assets produced yet |
| **Last Updated** | 2026-07-07 |

**Planned registries** (populate at the trigger noted, per Production Bible Section 7 — no reusable asset is built without checking this first):

| Registry | Trigger to Begin |
|---|---|
| Character Registry | Cast grows beyond the Series 01 core (Kael + the six Section 6 supporting cast) |
| Root Artifact Registry | First named Root Artifact appears in a script |
| Fragment/Anomaly Registry | Production needs detail beyond World Bible Sections 8, 10 |

---

## 12. Prompt Library Index

| Field | Value |
|---|---|
| **Purpose** | Track reusable AI prompts for visual generation (and, in future, script/voice) |
| **Owner** | Founder → future role owners per prompt category |
| **Current Version** | 2.0 |
| **Status** | 🔄 In Progress — visual templates complete; script/voice prompts not started |
| **Locked or Living** | Locked (base templates, per Master System Prompt Section 9) |
| **Dependencies** | Master System Prompt Section 9 (verbatim base prompts) |
| **Related Documents** | Production Bible Sections 8–10 |
| **Repository Location** | `mythic-forge-art-bible/prompt-library.md` |
| **Last Updated** | 2026-07-06 |

| Prompt Category | Status |
|---|---|
| Kael Base Prompt | ✅ Complete |
| Emotion Modifiers | ✅ Complete |
| World Prompt Template | ✅ Complete |
| Thumbnail Prompt Template | ✅ Complete |
| Script drafting prompts | ⬜ Not Started |
| Voice generation prompts | ⬜ Not Started |

This Wiki does not reproduce the templates themselves — they're canon-locked verbatim in the Master System Prompt and fully detailed with modifiers/failure-modes in `prompt-library.md`. Open that file directly.

---

## 13. Proposal Vault Index

| Field | Value |
|---|---|
| **Purpose** | Non-canon archive of future ideas — zero authority until the creator explicitly approves an entry |
| **Owner** | Founder (Creative Director) |
| **Current Version** | 1.0 |
| **Status** | 🔄 7 entries pending decision |
| **Locked or Living** | N/A — every entry is Proposed, not canon, by definition |
| **Dependencies** | Master System Prompt Section 12 (Rule 5, Proposal Workflow) |
| **Related Documents** | Master System Prompt Section 13 (Founder Override Protocol governs promotion to canon) |
| **Repository Location** | `bible/Fracture_Protocol_Proposal_Vault_v1.0.md` |
| **Last Updated** | 2026-07-06 |

**Current entries** (status only — open the Vault directly for each entry's full Purpose/Impact/Recommendation):

| # | Entry | Logged |
|---|---|---|
| 1 | A Hidden Organization Secretly Controlling the Authority System | 2026-07-06 |
| 2 | Currency & Economic System | 2026-07-06 |
| 3 | Formalize "Authority Central" | 2026-07-06 |
| 4 | Named Locations | 2026-07-06 |
| 5 | Zone Enforcement Beyond Ward Division | 2026-07-06 |
| 6 | Mid Zone Daily Life / Culture Note | 2026-07-06 |
| 7 | Continuum Recovery Group (new faction) | 2026-07-06 |

All seven remain **Proposed — Not Canon**, awaiting an explicit Founder Override Command (Master System Prompt Section 13) before any could enter canon.

---

## 14. Archive Index

Nothing in this repository is ever deleted outright — superseded and retired material is preserved, either in git history or in a clearly marked retired state.

| Retired Item | Superseded By | Where It Lives |
|---|---|---|
| Fantasy-era "Mythic Bible" (Shattered Realms cosmology, all versions) | Master System Prompt v1.0+ (The Fracture Protocol) | Git history only |
| Fantasy-era "True Reality Codex" (nested-reveal structure) | Master System Prompt v1.0 (no nested reveal; sci-fi overt from Episode 1) | Git history only |
| Fantasy-era Series Bible versions ("Kael: The Shattered Realms") | Series Bible v1.0+ (The Fracture Protocol) | Git history only |
| Fantasy-era Art Bible content (Seven Realms palette, magic-visual-rules.md, etc.) | Art Bible v2.0+ per file | Git history only; each current file's changelog documents what it replaced |

For production-asset archival going forward (retired character designs, deprecated prompts, superseded episode exports), see Production Bible Section 14 (Archive & Preservation) — that document defines the live process; this index only tracks documentation-level retirements.

| Field | Value |
|---|---|
| **Purpose** | Track what's been retired and where to find it if needed |
| **Owner** | Founder |
| **Dependencies** | Production Bible Section 14 |
| **Status** | ✅ Complete (documentation retirements); 📋 asset-level archive not yet populated |
| **Last Updated** | 2026-07-07 |

---

## 15. Folder Structure Index

**Current, on-disk structure:**

```
/                                    → this Wiki (README.md)
/bible/                              → Master System Prompt, World Bible, Proposal Vault
/studio-os/                          → Studio OS
/production-os/                      → Production OS
/production-bible/                   → Production Bible
/mythic-forge-art-bible/             → Art Bible (11 files)
/series/
  /01-the-fracture-protocol/         → Series 01 Bible and future scripts
```

**Planned, not yet created** (per Section 11 above and Production Bible Section 4 — created only when real content exists for them, never scaffolded speculatively):

```
/registries/     → character, Root Artifact, and Fragment/Anomaly trackers
/scripts/        → episode scripts, by season/arc
/production/     → storyboards, VO, footage, art
/publishing/     → metadata, thumbnails, SEO records
```

For the fully detailed future production-asset tree (episodes/assets/audio/prompts/thumbnails/exports/archives), see Production Bible Section 4 — this index does not duplicate it.

| Field | Value |
|---|---|
| **Purpose** | Define where every category of file belongs |
| **Owner** | Founder (COO) |
| **Dependencies** | Production Bible Section 4 |
| **Status** | 🔄 In Progress — core folders exist; production/publishing/registries not yet created |
| **Last Updated** | 2026-07-07 |

---

## 16. Naming Convention Reference

The authoritative naming convention for production assets is **Production Bible Section 5** — this index does not duplicate its table, only points to it.

For documentation and in-world terminology naming specifically:

| Asset Type | Convention | Authoritative Source |
|---|---|---|
| Bible/process document | `{Document_Name}_v{X.X}.md` | Studio OS Section 30 |
| Series document | `series/{NN}-{series-slug}/{Document_Name}_v{X.X}.md` | Studio OS Section 17 |
| In-world terminology | Follow the Terminology Reference | World Bible Section 13 |
| Production assets (all types) | See Production Bible Section 5 in full | Production Bible Section 5 |

| Field | Value |
|---|---|
| **Purpose** | One entry point for every naming question, pointing to whichever document actually owns the answer |
| **Owner** | Founder (COO) |
| **Dependencies** | Production Bible Section 5, World Bible Section 13 |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 17. Document Dependency Map

```
Master System Prompt
  └── World Bible
        └── Series Bible (per series)
              └── Art Bible
  └── Proposal Vault (outside the canon hierarchy — see Section 3)
  └── Studio Governance Manual (governs process-document jurisdiction only)
        └── Studio OS
        └── Production OS
        └── Production Bible

This Wiki (README.md)
  └── depends on every document above being current;
      indexes all of them, authoritative on none of them
```

**Reading this map:** an arrow means "must never contradict the document above it, and is checked against it before anything changes." If you're editing any document, check what points *at* it (its dependents) before assuming a change is isolated.

| Field | Value |
|---|---|
| **Purpose** | Show at a glance what breaks if a given document changes |
| **Owner** | Founder (Creative Director) |
| **Dependencies** | Section 3 (Canon Hierarchy) |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 18. Version History Index

**Master document table** — the single source for every document's current version and status. When in doubt about what's live, check here first.

| Document | Version | Status | Locked/Living | Last Updated |
|---|---|---|---|---|
| Studio Wiki (this document) | 3.2 | ✅ Complete | Mixed | 2026-07-07 |
| Fracture Protocol Master System Prompt | 1.2 | ✅ Complete | Locked | 2026-07-07 |
| Fracture Protocol Proposal Vault | 1.0 | 🔄 7 entries pending | N/A | 2026-07-06 |
| Fracture Protocol World Bible | 1.1 | ✅ Complete | Mixed | 2026-07-06 |
| The Fracture Protocol Series Bible | 1.1 | ✅ Complete | Mixed | 2026-07-06 |
| Mythic Forge Art Bible | 3.0 (index) | ✅ Complete | Mixed | 2026-07-06 |
| Studio Governance Manual | 1.0 | ✅ Complete | Mostly Locked | 2026-07-07 |
| Studio Governance Index | 1.0 | ✅ Complete | Living | 2026-07-07 |
| Studio OS | 1.0 | ✅ Complete | Mixed | 2026-07-06 |
| Production OS | 1.0 | ✅ Complete | Mixed | 2026-07-06 |
| Production Bible | 1.0 | ✅ Complete | Mixed | 2026-07-07 |

**Production status** (kept here, not duplicated in Production OS's own KPI Dashboard — Production OS Section 45 is the authoritative live tracker once episodes enter the pipeline):

| Milestone | State |
|---|---|
| Season One outline | ✅ Complete (20/20 episodes, Series Bible Section 11) |
| Season One scripts | ⬜ 0/20 written |
| Season One production | ⬜ Not started |
| Season One publishing | ⬜ Not started |

**Per-document changelogs are not restated here** — every document ends with its own changelog block; this table only tells you the current version so you know which changelog entry is "latest."

| Field | Value |
|---|---|
| **Purpose** | Single place to check current version/status of anything without opening every document |
| **Owner** | Founder (COO) |
| **Dependencies** | Studio OS Section 30 (Version Control) |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 19. Glossary

This is a glossary of **Wiki and production-process terms** — it does not define in-world/canon terminology (Signal, Cipher-work, Fragment, Breach, etc.). For those, go to **World Bible Section 13 (Terminology Reference)** — this Wiki never restates them.

| Term | Meaning |
|---|---|
| **Locked** | Founder/Creative Director sign-off required to change this section |
| **Living / Living Section** | May evolve through normal use without a full sign-off, as long as it doesn't contradict Locked material |
| **Canon** | Official, approved story/world fact — anything in the Bible tier (Section 5) that isn't tagged Proposed |
| **Proposed / Proposal** | An idea logged in the Proposal Vault; has zero canon authority until explicitly approved |
| **Drift Detection** | The check (Master System Prompt Section 12, Rule 3) that flags whether a requested change adds something new or contradicts something locked |
| **Founder Override Command** | An explicit creator phrase (Master System Prompt Section 13) required before any structural canon change is implemented |
| **Change Impact Report** | The 7-point pre-change summary (Master System Prompt Section 13) required before a canon change is made |
| **Minor / Major Canon Update** | The two-tier classification (Master System Prompt Section 13) determining how much process a canon change requires |
| **Stage Gate** | The approval checkpoint between two production pipeline stages (Production Bible Section 3) |
| **Asset Registry** | The living tracker of every produced asset's status, version, and approval (Production Bible Section 7) |

| Field | Value |
|---|---|
| **Purpose** | Define the process vocabulary this Wiki and the process documents use, without duplicating in-world terminology |
| **Owner** | Founder |
| **Dependencies** | World Bible Section 13 (in-world terms — separate, not duplicated here) |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 20. FAQ

**Where do I find out what a character/Zone/faction/power is?**
World Bible or Series Bible — see the Character/Environment indices (Sections 8–9) for the exact pointer.

**Can I edit a Locked section?**
No, not without founder/Creative Director sign-off. Living sections can generally be extended without one, as long as nothing Locked is contradicted (Studio OS Section 18).

**I think something's missing from canon — what do I do?**
Do not add it directly. Log it in the Proposal Vault (Section 13) using the Status/Purpose/Impact/Recommendation format. It has no effect on canon until explicitly approved.

**How do I propose a new idea?**
Same answer as above — the Proposal Vault is the only entry point for new canon ideas, regardless of how confident you are in it.

**Does this change affect canon?**
If it touches a character, faction, institution, technology, power mechanic, location, terminology, timeline, or world structure — yes, and it needs Drift Detection (Master System Prompt Section 12, Rule 3) before anything is written down as fact.

**Where do I go to understand how an episode actually gets made?**
Production Bible Section 3 (Production Pipeline) for the stage-by-stage flow; Production OS for department-level SOP detail.

**Which document is "more right" if two seem to disagree?**
Section 3 (Canon Hierarchy) or Section 17 (Document Dependency Map) — never guess; a real disagreement between documents is itself a bug to flag, not a call to make yourself.

**I'm not sure which document to open at all.**
Section 22 (Search Guide).

| Field | Value |
|---|---|
| **Purpose** | Answer the questions a contributor asks most often, in one place |
| **Owner** | Founder |
| **Dependencies** | Sections 3, 8, 9, 13, 17, 22 |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 21. Quick Links

| I need... | Go to |
|---|---|
| Absolute canon lock | `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` |
| World mechanics | `bible/Fracture_Protocol_World_Bible_v1.1.md` |
| Season One story/cast/episodes | `series/01-the-fracture-protocol/Series_Bible_v1.1.md` |
| Visual rules | `mythic-forge-art-bible/visual-development-guide.md` |
| Reusable AI prompts | `mythic-forge-art-bible/prompt-library.md` |
| Company process/values | `studio-os/Studio_OS_v1.0.md` |
| Department-level SOPs | `production-os/Production_OS_v1.0.md` |
| Production philosophy/pipeline/checklists | `production-bible/Fracture_Protocol_Production_Bible_v1.0.md` |
| To propose a new idea | `bible/Fracture_Protocol_Proposal_Vault_v1.0.md` |
| "Which document wins?" (canon) | Section 3 above |
| "Which document wins?" (process/jurisdiction) | `governance/Fracture_Protocol_Studio_Governance_Manual_v1.0.md`, Section 3 |
| One-page map of everything | `governance/Fracture_Protocol_Studio_Governance_Index_v1.0.md` |

| Field | Value |
|---|---|
| **Purpose** | Fastest possible jump table for the most common destinations |
| **Owner** | Founder |
| **Dependencies** | None |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 22. Search Guide

1. **Know the topic but not the document?** Check Sections 5–13 (the index sections) — each is scoped to one category (Bibles, Production, Studio OS, Characters, Environments, Props, Assets, Prompts, Proposals).
2. **Know the document but not the section?** Every Bible/OS document has an internal numbered-section structure and its own table of contents at the top — open the file and scan its headers; section numbers are referenced consistently across this Wiki so a cross-reference like "World Bible Section 7" always means the same thing.
3. **Looking for a specific term?** Grep the repository for the exact term first — in-world terms resolve fastest via World Bible Section 13 (Terminology Reference); process terms via Section 19 (Glossary) above.
4. **Not sure if something exists yet?** Check Section 18 (Version History Index) for what's Complete vs. Planned vs. Not Started before assuming a gap needs filling.
5. **Still stuck?** Section 20 (FAQ), then Section 3 (Canon Hierarchy) for "which document is authoritative on this."

| Field | Value |
|---|---|
| **Purpose** | Teach the search strategy, not just list destinations |
| **Owner** | Founder |
| **Dependencies** | Sections 5–13, 18–20 |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 23. Contributor Onboarding

**Read in this order, regardless of your role:**

1. This Wiki, Sections 1–4 (orientation + hierarchy).
2. Master System Prompt — the whole document; it's short by design.
3. World Bible — the whole document.
4. Series Bible (whichever series you're working on).
5. Art Bible `visual-development-guide.md` (master index), then whichever specific file your work touches.

**Then, based on your role:**

| Role | Read Next |
|---|---|
| Writer | Series Bible Sections 19–30 (writing/dialogue/pacing standards), Studio OS Section 5 (Originality Framework) |
| Artist / Animator | Full Art Bible, Production Bible Sections 7–8 |
| Voice/Audio | Production OS Sections 17–19, Production Bible Section 8 |
| Editor/QA | Production Bible Sections 9, 11–13 |
| Publishing/SEO | Studio OS Sections 10–12, 22–24; Production OS Sections 23–27 |

**Before your first contribution touches anything Locked:** re-read Section 3 (Canon Hierarchy) and the Master System Prompt's Section 12–13 in full. This is not optional for any role — it's the one rule set every contribution is checked against regardless of department.

| Field | Value |
|---|---|
| **Purpose** | Give a new contributor a fixed, role-aware reading order instead of an open-ended "read everything" |
| **Owner** | Founder |
| **Dependencies** | Sections 1–4 |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 24. Maintenance Rules

- This Wiki is updated **the same day** any indexed document changes — a new document, a version bump, a status change, or a retirement all require an update here before the change is considered complete (mirrors Production Bible Section 6, Version Control).
- This Wiki never grows lore, character, or world content — if you find yourself about to restate something a Bible already says, stop and add a link instead (this is the single most important rule in this document).
- New document types get a new index section, with the same required fields (Document Name, Purpose, Owner, Version, Status, Locked/Living, Dependencies, Related Documents, Location, Last Updated) as every existing one. Insert it wherever it reads best contextually, but prefer appending immediately before Final Validation over inserting mid-document — a mid-document insertion renumbers every section after it and breaks every external cross-reference to those numbers (as happened once already; see Production OS's changelog). Appending before Final Validation costs one renumber (Final Validation itself) instead of a dozen.
- A new series gets a row in Section 5 (Bible Index) and an entry in Section 17 (Document Dependency Map) the day its Series Bible is created.
- Version this document the same way every other document is versioned (Studio OS Section 30): a structural reorganization (like this v3.0 rewrite) is a major bump; routine updates to an existing table are minor bumps.
- Known open items (like the Production Bible/Production OS overlap, Section 6) stay visible here until the founder resolves them — they are never quietly dropped from the index.
- **Repository branching workflow:** `main` holds published, current documentation. Substantial revisions (new document versions, major canon changes) are developed on a feature branch and merged via pull request so changes are reviewable before they become canon.
- **Retired from this Wiki, not lost:** a standalone Risk Register and a Lore Tracker existed in the prior (v2.0) Knowledge Base structure. Both are out of scope for a pure navigation document under this rewrite's design philosophy — the Lore Tracker's content is now covered structurally by Sections 3 and 5; the Risk Register has no clean equivalent in the new structure and is recommended for relocation into Studio OS (which doesn't currently have one) rather than being silently dropped. Not yet implemented — flagged here per Section 25.

| Field | Value |
|---|---|
| **Purpose** | Keep this Wiki from drifting out of date the way a navigation document quietly can |
| **Owner** | Founder (COO) |
| **Dependencies** | Studio OS Section 30 |
| **Status** | ✅ Complete |
| **Last Updated** | 2026-07-07 |

---

## 25. Governance Manual Index

| Document Name | Fracture Protocol Studio Governance Manual |
|---|---|
| **Purpose** | Constitutional document for the studio's operating system — jurisdiction between process documents, approval authority, version control policy, change/conflict/audit/retirement procedure |
| **Owner** | Founder |
| **Current Version** | 1.0 |
| **Status** | ✅ Complete |
| **Locked or Living** | Mostly Locked — see in-document tags per section |
| **Dependencies** | Master System Prompt (subordinate to it; has no authority over canon) |
| **Related Documents** | Studio OS, Production OS, Production Bible — this Manual defines the jurisdiction between all three |
| **Repository Location** | `governance/Fracture_Protocol_Studio_Governance_Manual_v1.0.md` |
| **Last Updated** | 2026-07-07 |

This is the authoritative source for "which process document governs what" (its own Section 3, Document Authority Hierarchy) — this Wiki's Sections 4 and 6 point here rather than restating that table. It also carries the current, explicitly provisional interim jurisdiction split between the Production Bible and Production OS (Section 6 above) — see the Manual's own Section 3 for the full statement.

| Document Name | Fracture Protocol Studio Governance Index |
|---|---|
| **Purpose** | One-page visual map (diagrams/tables only) of how every operating document relates to every other one — a derived summary, not a source of truth |
| **Owner** | Founder |
| **Current Version** | 1.0 |
| **Status** | ✅ Complete |
| **Locked or Living** | Living — regenerated from the Governance Manual and this Wiki whenever either changes a fact it displays |
| **Dependencies** | Studio Governance Manual, this Wiki — cites both for every fact it shows |
| **Related Documents** | Every document in this Wiki; functions as a compact companion to Section 25 above, not a replacement for it |
| **Repository Location** | `governance/Fracture_Protocol_Studio_Governance_Index_v1.0.md` |
| **Last Updated** | 2026-07-07 |

---

## 26. Final Validation

1. **No canon introduced.** This document defines no character, faction, location, technology, power mechanic, or world fact — every substantive answer is a pointer to an existing Bible section, not a restatement of it.
2. **No lore duplicated.** Character, environment, and prop entries (Sections 8–10) are pointer tables only (name, category, document, status) — no biography, personality, mechanic, or story detail is restated anywhere in this document.
3. **Alignment with the Canon Governance System and Founder Override Protocol.** Section 3 (Canon Hierarchy) and Section 13 (Proposal Vault Index) both defer entirely to Master System Prompt Sections 12–13 for mechanics and never restate or reinterpret them; the FAQ (Section 20) directs every canon-adjacent question back to the Proposal Vault rather than answering it inline.
4. **Compatible with all existing documents.** Every version and status listed (Section 18) was checked directly against each document's own header/changelog at time of writing; the Production Bible and the new Studio Governance Manual are both fully indexed (Sections 6, 21, 25).
5. **Structural future-proofing.** The index sections (5–13, 25) are additive by design (Section 24) — a new series, a new registry, a new production document, or hundreds of new assets each get a new row or a new section without requiring this document's structure to change. Nothing here assumes a fixed number of episodes, characters, or contributors.
6. **Open items carried forward, not hidden.** The Production Bible/Production OS overlap is now formally tracked with a provisional interim split in the Studio Governance Manual's Section 3, rather than only living in this Wiki's Section 6 — this is a documentation, not a resolution, of that open item. The retired Risk Register (Section 24) remains a second, smaller open item — content preserved by reference, relocation not yet implemented.

---

*End of Studio Wiki Version 3.2. This document is the home page — update it the same day any other document changes (Section 24).*

---

### Changelog
`[v1.0 — 2026-07-06] Initial Knowledge Base established: 40-section index, dashboards, and master trackers covering Studio OS v1.0, Mythic Bible v2.0, and the Kael: The Shattered Realms Series Bible v1.0.`
`[v1.0 — 2026-07-06] Indexed Production OS v1.0: added as a document type, added to Master Navigation Index, Folder Structure, Documentation Hierarchy, Document Status Tracker, Current Completed Documents, Production Documentation Index, and Prompt Library Index.`
`[v1.0 — 2026-07-06] Indexed Mythic Forge Art Bible v1.0 (10 files): added as a document type, added to Master Navigation Index (with file breakdown), Folder Structure, Documentation Hierarchy, and status trackers.`
`[v1.0 — 2026-07-06] Synced references for the nested-reveal creative pivot (Mythic Bible v3.0, Series Bible v2.0, Art Bible v2.0, restricted True Reality Codex v1.0).`
`[v2.0 — 2026-07-06] Full pivot to The Fracture Protocol per the final "Phase 2 Master Prompt" canon lock: retired the fantasy Mythic Bible v3.0 and the restricted True Reality Codex entirely (no more nested reveal — the sci-fi setting is now overt from Episode 1). Added the Fracture Protocol Master System Prompt v1.0 as the new top-of-hierarchy document. Replaced with the Fracture Protocol World Bible v1.0 and a fully reskinned Series Bible v1.0 (series/01-the-fracture-protocol/). Retitled "Realm Documentation Index" to "Zone Documentation Index" (four megacity layers replacing the Seven Great Realms), updated the Character Tracker's roles and titles, replaced the Lore Tracker and all dashboards accordingly, and updated Studio OS/Production OS cross-references throughout.`
`[v2.0 — 2026-07-06] Founder-approved additive expansion: World Bible bumped to v1.1 (added Static-Reading as a third recognized discipline, and The Salvage Line as a new faction alongside Authority/Ward Division/the Reassembly); Series Bible bumped to v1.1 (added Coda, a Season Two supporting character — Salvage Line broker and Static-Reader — explicitly scoped as non-competing with Kael per System Rule 4). Season One's 20-episode outline is unchanged. Synced all cross-references, the Character Tracker, the Power System Documentation Index, and the Lore Tracker accordingly.`
`[v2.0 — 2026-07-06] Phase 2 Finalization / Canon Governance pass: Master System Prompt bumped to v1.1 (permanent Canon Guardian role framing; added Section 12, Canon Governance System — Rules 1-6). Added the Fracture Protocol Proposal Vault v1.0 as a new document type (non-canon, currently empty — founder confirmed no existing canon required retroactive rollback). Reconciled Studio OS Section 18's separate Canon Change SOP to defer to the new Canon Governance System instead of maintaining a competing DRAFT-based process. Full-repo audit found and fixed residual fantasy-era terminology ("Realm," "Essence affinity," "the Kindling," Emberfall/Duskmarch examples) in Studio OS Sections 8, 10, 11, 17, 19, and 20, and one stale Two-Discipline Cap phrasing in the Series Bible that pre-dated Static-Reading. Verified all cross-referenced file paths resolve and all declared versions match file headers.`
`[v2.0 — 2026-07-06] Full continuity audit (post Proposal Vault expansion to 7 entries): corrected two stale "Art Bible (10 files)" labels (Documentation Architecture Section 2, Master Navigation Index Section 3) to the correct "(11 files)," matching the Art Bible's own 11-file breakdown table which was already accurate. Fixed a wording contradiction in Section 6 (Documentation Hierarchy) where the Proposal Vault special-case note implied approved entries are "removed from Vault status" — reworded to match the Vault's own explicit rule that entries are never deleted, only marked resolved in place. Re-verified: no Proposal Vault entry content has leaked into any canon document; all cross-document version references match current file headers; no Locked-rule contradictions or duplicate rule sets found (Studio OS Section 18 and Series Bible Section 19/20 correctly restate rather than compete with Master System Prompt Section 12 and the World/System Rules).`
`[v2.0 — 2026-07-06] Founder-authored permanent addition: Master System Prompt bumped to v1.2 (renamed `Fracture_Protocol_Master_System_Prompt_v1.2.md`), adding Section 13, Founder Override Protocol — explicit Founder Override Command phrases, a 7-point Change Impact Report format, Minor/Major Change Classification, an expanded 9-step Execution Workflow, and a 9-point Final Validation checklist, all cross-linked to and reconciled with the existing Section 12 Canon Governance System so the two read as one non-contradictory system. Propagated the version bump across every cross-reference repo-wide. Also caught and fixed several stale version mentions a prior file-path-only sweep had missed: the Document Status Tracker and Current Completed Documents tables still showed Master System Prompt as 1.1, the Proposal Vault's one-line summary still said "currently empty" despite 7 logged entries, the Art Bible summary still said "10-file," and the Studio Progress dashboard still displayed v1.0-era version tags for the Master System Prompt, World Bible, and Series Bible.`
`[v3.0 — 2026-07-07] Full structural rewrite per the "Studio Wiki" specification: reorganized from the prior 40-section Knowledge Base into the 25 required sections (Welcome through Final Validation), converted every document entry to the full required metadata fields (Purpose, Owner, Version, Status, Locked/Living, Dependencies, Related Documents, Repository Location, Last Updated), added the new Production Bible v1.0 to the Bible/Production indices, added a Prop Index and Document Dependency Map (neither existed before), consolidated the prior Document Status Tracker and Current Completed Documents tables into a single Version History Index, and removed duplicated progress-dashboard content in favor of pointing to Production OS Section 45 (KPI Dashboard) for live production tracking once it exists. No document version other than this one was changed by this rewrite; the Production Bible/Production OS overlap flagged in the prior session remains open and is now tracked in Section 6 and this document's own Final Validation section.`
`[v3.1 — 2026-07-07] Indexed the new Studio Governance Manual v1.0 as a new document type and tier ("Governance," alongside Canon/Studio Process/Production Process — Section 2). Added Section 25 (Governance Manual Index), bumping the former Section 25 (Final Validation) to Section 26 — the only renumbering this update required, per the revised insertion rule now stated in Section 24. Updated Sections 2, 4, 6, 17, 18, and 21 to point to the Governance Manual for jurisdiction/authority questions rather than restating them. The Governance Manual's Section 3 now formally documents the Production Bible/Production OS interim jurisdiction split as a provisional default — this remains an open founder decision, not a resolution.`
`[v3.2 — 2026-07-07] Indexed the new Studio Governance Index v1.0 (Section 25) — a one-page diagram/table-only summary of the Governance Manual and this Wiki, built deliberately thin (cites both rather than restating them) since every element it requested already existed in full elsewhere. Added a row to Section 18 (Version History Index) and Section 21 (Quick Links).`
