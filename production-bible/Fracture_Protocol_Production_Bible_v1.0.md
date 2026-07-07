# THE FRACTURE PROTOCOL — PRODUCTION BIBLE
## Version 1.0

**Classification:** Internal — Production Operating Manual
**Status:** Process document. Introduces no lore, characters, factions, locations, technologies, or world canon.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` — this document is subordinate to it in all cases and must never contradict the Canon Governance System (Section 12) or the Founder Override Protocol (Section 13).
**Companion documents:** `studio-os/Studio_OS_v1.0.md` (company-level policy — this document is scoped narrower: production only, not brand/vision/IP strategy), `production-os/Production_OS_v1.0.md` (an existing department-level SOP manual covering closely related ground — see Section 15 for how the two currently relate and a recommendation for reconciling them).
**Anticipated by:** Master System Prompt Section 7 (Bible Naming System), which reserved "Production Bible (future, optional)" for exactly this content: *"Scene factory system, episode pipeline, thumbnail generation system, YouTube workflow system."* This document fills that reserved slot.
**Scope note:** This is not one of the Locked Categories named in Master System Prompt Section 12, Rule 4 (Universe identity, Series/Art/World Bible content, character identities, etc.). It is a process document, governed the same way Studio OS and Production OS are governed — ordinary Version Control (Section 6 of this document; Studio OS Section 30) — not the Founder Override Protocol, which is scoped to story/world canon. See Section 15 for the explicit boundary between the two.

---

### How to use this document

This is the operating manual for how The Fracture Protocol gets made — not what happens in it. Where this document is silent on process, defer to Studio OS. Where it touches anything about the story or world, defer to the Master System Prompt, World Bible, Series Bible, or Art Bible — this document never overrides any of them, and any apparent conflict is a documentation bug to be corrected in this document, not in canon.

Tags used throughout, matching studio-wide convention:
- **[LOCKED]** — founder/Creative Director sign-off required to change.
- **[LIVING SECTION]** — expected to evolve as production is proven out in practice.

All examples in this document use neutral placeholders (`{season}`, `{episode}`, `{zone-slug}`, `Character A`, etc.) rather than named canon elements, so this manual stays reusable regardless of what canon exists or how it changes.

---

## 1. Production Philosophy **[LOCKED]**

### Mission
Produce every episode of The Fracture Protocol to a consistent standard of canon accuracy, visual continuity, and craft — repeatably, at scale, without the process itself becoming a bottleneck or a source of drift.

### Creative Goals
- Every published episode is indistinguishable in quality and consistency from the one before it, regardless of who or what produced any individual asset.
- The process should make it *easier* to stay consistent than to drift — consistency should never depend on any one person's memory.
- Production capacity should scale (more episodes, more contributors, more tooling) without requiring the Bibles or this manual to be rewritten from scratch.

### Production Principles
1. **Canon is upstream of production.** Nothing in this document ever decides what is true in the story — it only decides how an already-true thing gets made.
2. **Every asset traces to an approval.** No asset exists in a finished episode without a recorded checkpoint it passed (Section 9, Section 11).
3. **Reuse before creation.** Check the registry before building anything new (Section 7).
4. **Cost is visible in the process, too.** Every stage has an owner and a time estimate (Section 3) — an unowned or unestimated stage isn't a real stage.
5. **Nothing final without a version.** Every document, script, and binary asset carries a version number (Section 6).

### Quality Standards
- A first-time viewer should never be able to tell which parts of an episode were AI-assisted and which were not — quality is measured by the output, not the method.
- No published episode may contain a canon contradiction, an off-model asset, or an unresolved QA item (Section 9).
- "Good enough to publish on deadline" and "good enough to represent the studio" are the same bar — there is no lower tier for time pressure.

---

## 2. Studio Organization **[LIVING SECTION, LOCKED hierarchy]**

### Team Roles

| Role | Owns | Status |
|---|---|---|
| Creative Director | Final creative and canon-facing approval; sole Founder Override authority | Filled (Founder) |
| Production Manager | Pipeline health, stage-gate tracking, cross-department scheduling | Filled (Founder) |
| Writer(s) | Scripts | Future hire/collaborator |
| Storyboard Artist | Shot lists, scene plans | Future hire/collaborator |
| Animation/Asset Lead | Characters, environments, props, image generation, animation | Future hire/collaborator |
| Voice Lead | Casting, direction, VO recording | Future hire/collaborator |
| Audio Lead | Music, SFX | Future hire/collaborator |
| Editor | Assembly, color, subtitles | Future hire/collaborator |
| QA Owner | Pre-publish checklist | Future hire/collaborator |
| Publishing/SEO Owner | Metadata, upload, release sequencing | Future hire/collaborator |

At current scale, one person (the Founder) holds every role above except where AI tooling assists directly. The role table exists so responsibility is clear the moment any role is filled, not to imply a team that doesn't yet exist.

### Responsibilities
Each role above owns its stage(s) in the Production Pipeline (Section 3) end-to-end: producing the stage's output, checking it against the prior stage's approval, and handing off a stage-gate-ready deliverable. A role never "starts" the next stage's work — that is the next role's job, even when the same person currently holds both roles.

### Approval Hierarchy

```
Individual contributor output
        │
        ▼
Self-check against this document's relevant checklist
        │
        ▼
Department-level review (Production Manager, or peer once roles are filled)
        │
        ▼
Creative Director review — canon + quality
        │
        ▼
   [Does this touch canon?] ──No──▶ Creative Director sign-off (ordinary approval)
        │
       Yes
        │
        ▼
Founder Override Protocol (Master System Prompt Section 13) — Change Impact
Report, explicit Override Command, Execution Workflow, Final Validation
```

### Creator Authority
The Creative Director (Founder) is the final approval on every stage gate in this document. Nothing in this manual delegates canon authority to any role, tool, or automated check — Master System Prompt Section 12, Rule 1 (Creator Authority) is unaffected by anything in this document.

### Canon Governance Integration
This document never defines its own canon-approval process. Anywhere production work touches canon — a script implies a new detail, an asset needs a decision the Bibles don't cover, a contradiction surfaces — the path is always: **stop, log it as a Proposal (Master System Prompt Section 12, Rule 5, filed in the Proposal Vault), and continue production only on the parts unaffected by the open question.** This document's job is to make that handoff fast and unambiguous (see Section 10, Risk Management), never to route around it.

---

## 3. Production Pipeline **[LOCKED spine, LIVING detail]**

### Stage Sequence

```
 [Approved Story Concept]
          │
          ▼
 1. PLANNING          — confirm concept is ready, gather inputs
          │
          ▼
 2. SCRIPTING         — expand concept into a full script
          │
          ▼
 3. STORYBOARDING     — convert script into shot sequence
          │
          ▼
 4. ASSET PRODUCTION  — build/reuse characters, environments, props
          │
          ▼
 5. IMAGE GENERATION  — produce reference-anchored frame art
          │
          ▼
 6. ANIMATION         — bring frames into motion
          │
          ▼
 7. VOICE             — record/generate performances
          │
          ▼
 8. MUSIC             — score the cut
          │
          ▼
 9. EDITING           — assemble picture, audio, music into a locked cut
          │
          ▼
10. QUALITY ASSURANCE — full checklist pass (Section 9)
          │
          ▼
11. PUBLISHING        — upload, schedule, release
          │
          ▼
12. ARCHIVING         — finalize, back up, retire working files (Section 14)
```

### Stage Definitions

| # | Stage | Input | Output | Gate to Next Stage |
|---|---|---|---|---|
| 1 | Planning | Approved story concept | Production brief | Brief traces cleanly to its concept with no open canon question |
| 2 | Scripting | Production brief | Versioned script | Script passes canon check (Section 9) |
| 3 | Storyboarding | Approved script | Shot list / storyboard | Every script beat has a corresponding shot |
| 4 | Asset Production | Storyboard | Reused or newly built assets, logged in the registry | Registry checked before any new build (Section 7) |
| 5 | Image Generation | Approved assets, storyboard | Frame art per shot | Originality Check passed; matches reference sheets |
| 6 | Animation | Approved frame art | Animated shot sequences | No off-model drift within or across shots |
| 7 | Voice | Script, character voice notes | Final VO files | Matches documented speech style |
| 8 | Music | Rough cut | Music stems | No unlicensed or soundalike material |
| 9 | Editing | Animation, voice, music | Locked cut | Runtime and pacing within target |
| 10 | Quality Assurance | Locked cut + metadata | QA-passed package | Full checklist passed (Section 9) |
| 11 | Publishing | QA-passed package | Live release | Correct format, metadata, and schedule |
| 12 | Archiving | Published episode + working files | Archived project package | Logged per Section 14 |

**Rule:** no stage begins before the prior stage's gate condition is met and recorded (Section 11). A stage may run in parallel with an adjacent one only when its input doesn't depend on the other's still-changing output.

---

## 4. Folder Structure **[LOCKED spine, LIVING subfolders]**

```
/bibles/                          → canon and process documents (all "Bible"/"OS" documents)
/episodes/
  /{season}/
    /{episode}/
      script/
      storyboard/
      scene-plan/
      qa/
      metadata/
/assets/
  /characters/
    /{character-slug}/
      reference/
      revisions/
  /environments/
    /{zone-slug}/
      reference/
      revisions/
  /props/
    /{prop-slug}/
/audio/
  /voice/
    /{season}/{episode}/
  /music/
    /stems/
    /licenses/
  /sfx/
    /library/
/prompts/
  /visual/
  /script/
  /voice/
/thumbnails/
  /{season}/{episode}/
/marketing/
  /campaigns/
  /brand-assets/
/exports/
  /{season}/{episode}/
    /renders/
    /masters/
/archives/
  /{season}/{episode}/
  /retired-assets/
  /retired-prompts/
/documentation/
  /production-bible/
  /changelogs/
```

**Rules:**
- Nothing is created speculatively — a subfolder is created the first time real content exists for it, not in advance (matching Studio Wiki Section 15's existing rule).
- `/bibles/` holds documents only; binary production assets never live there.
- Every asset folder (`characters/`, `environments/`, `props/`) separates the current `reference/` copy from `revisions/` — the reference copy is always the single generation anchor (Section 7).
- `/archives/` never deletes; it is where superseded and retired material goes to remain recoverable (Section 14).

---

## 5. File Naming Convention **[LOCKED]**

| Asset Type | Convention | Example |
|---|---|---|
| Production Bible / process document | `{Document_Name}_v{X.X}.md` | `Fracture_Protocol_Production_Bible_v1.0.md` |
| Episode script | `episodes/{season}/{episode}/script/{episode}_v{X.X}.md` | `episodes/S01/E01/script/E01_v1.0.md` |
| Storyboard file | `episodes/{season}/{episode}/storyboard/{episode}_board_v{X.X}.pdf` | `episodes/S01/E01/storyboard/E01_board_v1.0.pdf` |
| Character reference sheet | `assets/characters/{character-slug}/reference/{character-slug}_ref_v{X.X}.png` | `assets/characters/character-a/reference/character-a_ref_v1.0.png` |
| Environment plate | `assets/environments/{zone-slug}/reference/{zone-slug}_plate_v{X.X}.png` | `assets/environments/zone-a/reference/zone-a_plate_v1.0.png` |
| Prop asset | `assets/props/{prop-slug}/{prop-slug}_v{X.X}.png` | `assets/props/prop-a/prop-a_v1.0.png` |
| Raw render | `exports/{season}/{episode}/renders/{episode}_v{X.X}.mp4` | `exports/S01/E01/renders/E01_v1.0.mp4` |
| Master export (publish-ready) | `exports/{season}/{episode}/masters/{episode}_master_v{X.X}.mp4` | `exports/S01/E01/masters/E01_master_v1.0.mp4` |
| Voice file | `audio/voice/{season}/{episode}/{character-slug}_{line-id}.wav` | `audio/voice/S01/E01/character-a_L012.wav` |
| Music stem | `audio/music/stems/{episode}_{cue-name}_v{X.X}.wav` | `audio/music/stems/E01_theme-a_v1.0.wav` |
| SFX file | `audio/sfx/library/{category}_{name}.wav` | `audio/sfx/library/ambience_wind-loop.wav` |
| Thumbnail | `thumbnails/{season}/{episode}/{episode}_v{variant}.png` | `thumbnails/S01/E01/E01_vA.png` |
| Prompt entry | `prompts/{category}/{prompt-name}_v{X.X}.md` | `prompts/visual/character-base_v1.0.md` |
| Revision (any asset, mid-review) | `{original-filename}_rev{N}.{ext}` | `character-a_ref_v1.0_rev2.png` |

**Rules:**
- Every filename includes a version number except revisions-in-progress, which use `_rev{N}` until they're promoted to the next full version.
- Slugs (`{character-slug}`, `{zone-slug}`, `{prop-slug}`) are lowercase, hyphen-separated, and assigned once at creation — never reused for a different asset even after retirement (matches Studio OS Section 17's naming rule).
- No asset is ever renamed after being referenced by a script, storyboard, or another asset — a name change is a new version, not an edit to the old name.

---

## 6. Version Control **[LOCKED]**

### Numbering
All documents, scripts, and binary assets use **v{major}.{minor}**:
- **Major bump** — a locked-section rewrite, a structural change to the asset, or anything requiring Creative Director sign-off beyond a routine pass.
- **Minor bump** — an additive or corrective change within the existing structure.

### Revision History
Every document ends with a changelog block (`[vX.X — YYYY-MM-DD] Summary`), appended, never edited or removed retroactively. Binary assets track the same history in the Asset Registry (Section 7) rather than in-file, since most binary formats can't hold a human-readable changelog.

### Changelog Standards
One line per change, in the past tense, naming the section(s)/asset(s) affected. A changelog entry is written the same day the change is made — never batched or backfilled later.

### Document Status
Every document and asset is in exactly one status at any time:

| Status | Meaning |
|---|---|
| Draft | In progress, not yet reviewed |
| In Review | Submitted for Creative Director / department review |
| Approved | Passed review, current canonical version |
| Superseded | Replaced by a newer approved version; retained in Archive (Section 14) |
| Retired | No longer in active use; retained in Archive, not deleted |

### Approval Workflow
Draft → In Review → (Revision Requested → Draft, or) → Approved. An asset or document cannot skip from Draft directly to Approved — every version passes through Review, even a routine one, so there is always a recorded checkpoint (Section 11).

---

## 7. Asset Management **[LOCKED process, LIVING detail]**

| Stage | What Happens |
|---|---|
| **Creation** | Requested only after the registry (below) is checked and confirms no reusable asset exists. Built against the relevant Bible/Art Bible reference, not from memory. |
| **Review** | Checked against its type's Production Standards (Section 8) and, if applicable, its Reference Sheet. Silhouette/palette/continuity checks happen here, not after animation begins. |
| **Approval** | Creative Director (or delegated department lead, once roles are filled) marks the asset Approved (Section 6) and it becomes the generation anchor for all future use. |
| **Revision** | Any change to an Approved asset is a new version, reviewed and approved the same way as the original — never a silent overwrite. |
| **Retirement** | An asset that's no longer in use (a cut character, a replaced design) is marked Retired, not deleted — it moves to Archive (Section 14) with a one-line reason. |
| **Archival** | Every asset, at every version, is retrievable after retirement — see Section 14 for the standing rule against single-location storage. |

**Asset Registry:** a living tracker (location: `/documentation/`, format to be finalized when asset volume justifies a dedicated file per type) recording, per asset: name/slug, type, current version, status, location, and originality-check result. No asset is "real" until it's logged here — an asset that exists only as a file with no registry entry is treated as unapproved.

---

## 8. Production Standards **[LOCKED]**

| Standard | Requirement |
|---|---|
| **Visual quality** | Every finished asset matches its category's Art Bible rules (color, lighting, materials, environment) with zero unexplained deviation. A deviation is either a documented, approved exception or a defect — never ambiguous. |
| **Prompt consistency** | Every reusable prompt is logged in the Prompt Library (Art Bible `prompt-library.md`) before being used a second time; ad hoc, undocumented prompt variations are not used for anything that will recur. |
| **Naming consistency** | Every asset and file follows Section 5 without exception; a misnamed file is corrected before it enters review, not after. |
| **Export settings** | A single documented export spec per output type (render resolution/frame rate, audio levels, subtitle format) is maintained in the Asset Registry (Section 7) and never varies episode to episode without a logged, approved reason. |
| **Documentation** | Every stage's output is accompanied by whatever this document requires as its "Output" (Section 3) — an undocumented deliverable is not considered complete. |
| **Backups** | No single-location storage for any final asset (Section 14) — this is a standard, not a suggestion, and is checked at the Archiving stage (Section 3, stage 12). |

---

## 9. Quality Assurance **[LOCKED]**

### Canon Consistency Checklist
- [ ] No contradiction with any Locked section of the Master System Prompt, World Bible, or Series Bible
- [ ] No unresolved Bible ambiguity (World Bible Section 2, Series Bible Section 15) accidentally resolved in passing
- [ ] Any new element encountered mid-production was routed to the Proposal Vault (Section 10), not implemented directly

### Visual Consistency Checklist
- [ ] Matches the relevant Reference Sheet(s) exactly (Section 7)
- [ ] Palette/lighting/materials match Art Bible rules for the Zone/character/asset type involved
- [ ] No forbidden element present (Art Bible `forbidden-elements.md`)

### Prompt Accuracy Checklist
- [ ] Prompt used is the logged Prompt Library version, not an undocumented variant
- [ ] Output matches the prompt's documented known-failure-mode guidance (i.e., none of the listed failure modes are present in the output)

### Continuity Checklist
- [ ] Consistent with every prior episode's established facts (World Bible Section 15, Rule 5 — history persists)
- [ ] Character/prop/environment states carried forward correctly from the last episode they appeared in

### Exports Checklist
- [ ] Correct resolution, frame rate, and format for the publishing platform
- [ ] Audio levels normalized, no clipping, dialogue intelligible
- [ ] Captions match final audio exactly, correct proper-noun spelling

### Documentation Checklist
- [ ] Every stage's required output (Section 3) exists and is logged
- [ ] Asset Registry entries current for every asset used
- [ ] Changelog entries written for anything that changed version (Section 6)

**Rule:** a full failing checklist item blocks the next stage gate (Section 11) — there is no "fix it after publish" path for a Canon Consistency or Forbidden Elements failure specifically; those two categories are hard stops.

---

## 10. Risk Management **[LOCKED procedures, LIVING detail]**

| Risk | Procedure |
|---|---|
| **Conflicting documents** (two documents appear to disagree) | Apply the Canon Hierarchy (Studio Wiki Section 3): Master System Prompt always wins; treat the lower-ranked document's content as the bug, not a decision point. Do not silently pick whichever is more convenient for the current stage. |
| **Missing assets** (a needed reference doesn't exist yet) | Do not improvise a placeholder that could be mistaken for approved canon. Halt the dependent stage, route the asset need through Section 7 (Asset Management), and resume once it's Approved. |
| **Inconsistent prompts** (a prompt drifts from its logged version, or two contributors use different unlogged variants) | Re-anchor to the Prompt Library's logged version (Art Bible `prompt-library.md`); log the drift and its fix in that file's changelog if the logged version itself needs correcting. |
| **Version conflicts** (two contributors edit the same asset/document version in parallel) | The earlier-submitted, already-Approved version wins; the later edit is resubmitted as a new version against the current Approved baseline — never merged by guesswork. |
| **Accidental canon drift** (production work implies, requires, or introduces something not already in the Bibles) | **Stop immediately.** This is not a production-process decision. Log it as a Proposal in the Proposal Vault (Master System Prompt Section 12, Rule 5) using the Status/Purpose/Impact/Recommendation format, and continue production only on parts unaffected by the open question. This document defines no alternate path around Drift Detection (Section 12, Rule 3) or the Founder Override Protocol (Section 13) — production convenience is never sufficient justification for an unapproved canon addition. |
| **Production interruptions** (a stage stalls, a contributor becomes unavailable, tooling fails) | Log the blocker against its stage in the Weekly Sprint tracking (Studio OS Section 25); an episode stuck at the same stage for more than one sprint escalates to the Production Manager for a stage-specific fix, not a silent skip. |

---

## 11. Creator Review Workflow **[LOCKED]**

### Review Stages
1. **Self-check** — the contributor checks their own output against the relevant Section 9 checklist before submitting it.
2. **Department review** — a peer or the Production Manager checks it against the same checklist plus the stage's specific gate condition (Section 3).
3. **Creative Director review** — canon accuracy and overall quality; this is the review that decides Approved vs. Revision Requested (Section 6).

### Approval Gates
Every stage transition in Section 3 requires an explicit, recorded Approved status (Section 6) before the next stage begins. "Probably fine, keep going" is never a substitute for a recorded approval — if there's no record, the gate has not been passed.

### Revision Requests
A Revision Requested outcome always includes: what specifically failed (tied to a checklist item where possible), and what the resubmission needs to satisfy. A revision is reviewed again at full Stage 3 (Creative Director review) — it does not get a lighter second pass by default.

### Final Sign-Off
Final sign-off on an episode (moving it from Quality Assurance, stage 10, into Publishing, stage 11) requires:
- Every Section 9 checklist fully passed, with no open items.
- Every asset used logged as Approved in the Asset Registry.
- No open Proposal Vault item that the episode's content depends on remaining unresolved.

Only the Creative Director gives final sign-off. If the episode's content touches canon in a way that wasn't already Approved before production began, final sign-off is blocked until that content is resolved through the Founder Override Protocol (Section 13) — sign-off itself is never used as a backdoor canon approval.

---

## 12. Production Readiness Checklist **[LOCKED]**

Every episode must pass this checklist before Planning (Section 3, stage 1) may begin:

- [ ] Story concept exists and is approved (Series Bible episode entry or equivalent)
- [ ] No open Proposal Vault item that this episode's content depends on
- [ ] Target runtime and format confirmed
- [ ] Required assets identified at a high level and checked against the registry (Section 7) for likely reuse vs. new build
- [ ] Responsible roles for each pipeline stage confirmed available (Section 2)
- [ ] Prior episode (if any) fully archived (Section 14), so continuity references are accurate and available

---

## 13. Episode Completion Checklist **[LOCKED]**

Every episode must pass this checklist before Publishing (Section 3, stage 11) may begin:

- [ ] Full Quality Assurance checklist passed (Section 9), with no open items
- [ ] Final Sign-Off recorded (Section 11)
- [ ] All assets used are Approved and logged in the Asset Registry (Section 7)
- [ ] Export package matches Production Standards (Section 8)
- [ ] Metadata (title, description, tags, thumbnail) complete and accurate
- [ ] Publishing schedule confirmed and does not contradict another format's release (Studio OS Section 12)
- [ ] Archiving plan for this episode's working files is ready to execute immediately after publish (Section 14)

---

## 14. Archive & Preservation **[LOCKED]**

### Archives
Every published episode's full project package (script, storyboard, final assets used, locked cut, export masters, QA record) is archived the same day it publishes. Archiving is stage 12 of the Production Pipeline (Section 3) — it is not optional cleanup, it is a required stage with its own gate.

### Backups
No single-location storage for any final asset or archived package (Studio OS Section 31's existing rule, restated here for production specifically): every finished episode's source files exist in at least two places before any working copy is cleared.

### Version History
Archives preserve every Approved version of every asset used, not just the final one — a later continuity question ("what did this look like in Episode {N}") must be answerable from the archive alone, without reconstructing it from memory.

### Retired Assets
An asset marked Retired (Section 7) moves into `/archives/retired-assets/` with its full version history intact and a one-line reason for retirement. It is never deleted — a retired design may become relevant again (a callback, a continuity check) even after it's out of active use.

### Deprecated Prompts
A prompt removed from active use in the Prompt Library (because it's been superseded by a better version, or the output category no longer applies) moves into `/archives/retired-prompts/` with the reason and the version it was superseded by, rather than being deleted from history.

---

## 15. Relationship to Existing Documents **[Recommendation only — not implemented]**

This document was written to fulfill Master System Prompt Section 7's reserved "Production Bible" slot. In doing so, it covers substantially the same ground as the existing `production-os/Production_OS_v1.0.md` (48 sections: pipeline stages, folder structure, file naming, version control, asset management, QA, troubleshooting, metrics) and, at a higher level, `studio-os/Studio_OS_v1.0.md` Section 13 (company-policy pipeline).

Per this task's constraints, this document does not modify, retire, or reconcile either existing document — that would be a structural decision beyond "build the Production Bible," and is flagged here as a recommendation rather than acted on.

**Recommendation for the founder's consideration (not implemented):**
1. **Consolidate** — retire `production-os/Production_OS_v1.0.md` (kept in git history, per this repository's established pattern for superseded documents) and treat this Production Bible as its sole successor; or
2. **Delineate** — keep both, with this document serving as the single production-philosophy/organization/governance layer and Production OS narrowed to serve purely as its department-level implementation detail (removing the sections that now duplicate this document — Folder Structure, File Naming, Version Control, Asset Management, QA, Risk-adjacent troubleshooting); or
3. **Leave as-is for now** — accept the duplication temporarily and revisit at the next Monthly Review (Studio OS Section 26), since duplication is a documentation-hygiene risk, not a canon-breaking one.

No option above has been applied. Two documents currently claim overlapping process authority; this is flagged as the primary open item from this Bible's creation and should be resolved before both are used in parallel on a real production pass, to avoid two contributors following two slightly different versions of "the same" pipeline.

---

## Final Validation

1. **No new canon introduced.** Every example in this document uses a neutral placeholder (`Character A`, `{zone-slug}`, `{season}/{episode}`) — no character, faction, location, technology, or world detail was created.
2. **Alignment with the Canon Governance System (Master System Prompt Section 12).** This document defines no competing approval process for canon; Section 2 (Canon Governance Integration) and Section 10 (Accidental Canon Drift) both route any canon-touching situation back to Rule 5 (Proposal Workflow) and the Proposal Vault, not around it.
3. **Alignment with the Founder Override Protocol (Master System Prompt Section 13).** Section 11 (Creator Review Workflow) explicitly distinguishes ordinary production sign-off (Creative Director approval, no Override Command required) from canon-touching decisions (which require the full Section 13 workflow) — this document does not apply Override Command machinery to routine production approvals, and does not let production sign-off substitute for one where canon is actually involved.
4. **Compatibility with all existing Bibles.** No content in this document contradicts the Master System Prompt, World Bible, Series Bible, or Art Bible — it does not reference any specific canon fact by name, only by section-number cross-reference, precisely to keep this guaranteed as canon evolves.
5. **Recommendations for future production improvement (not implemented):** see Section 15 in full. In short — reconcile this document's overlap with the existing Production OS before both are used simultaneously on a real episode; finalize the Asset Registry's file format once asset volume exists to populate it; and revisit the Team Roles table (Section 2) at the point any role beyond Founder is actually filled.

---

*End of Production Bible v1.0. This document defines process only — update it as production is proven out in practice; it should look different, and better, by v2.0.*

---

### Changelog
`[v1.0 — 2026-07-07] Initial Production Bible established per Phase 3A, Milestone 1: 15 sections covering production philosophy, studio organization, pipeline, folder structure, naming, version control, asset management, production standards, QA, risk management, creator review workflow, production readiness and episode completion checklists, and archive/preservation. Fulfills the "Production Bible (future, optional)" slot reserved in Master System Prompt Section 7. Introduces no new canon; all examples use neutral placeholders. Flagged, but did not resolve, a significant content overlap with the existing Production OS v1.0 (Section 15) — left as an explicit recommendation for founder decision.`
`[v1.0 — 2026-07-07] Synced two internal cross-references to the Knowledge Base's rework into the Studio Wiki (v3.0): "Knowledge Base Section 4" (Section 4, Folder Structure) and "Knowledge Base Section 7" (Section 10, Risk Management) updated to "Studio Wiki Section 15" and "Studio Wiki Section 3" respectively.`
