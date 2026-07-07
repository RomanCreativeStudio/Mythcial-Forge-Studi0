# MYTHIC FORGE STUDIOS
## Brand Asset Production Guide
### Version 1.0

**Classification:** Internal — Production Workflow Specification
**Status:** Draft — ready for Founder review. Structure and workflow defined; not yet exercised against a real asset. Introduces zero story canon, zero worldbuilding, zero characters, zero factions, zero locations, zero technologies, zero lore, and no redesign of any existing brand element.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` — this document is subordinate to it in all cases and carries no canon authority of its own.
**Absolute authority (brand-specific):** `brand/Mythic_Forge_Studios_Brand_Bible_v1.0.md` — this document is subordinate to it in all cases. It does not redefine the studio name, abbreviation, tagline, logo concept, color palette, typography, motion identity, audio identity, naming conventions, or the Brand Bible/YouTube Brand Kit relationship. Where this Guide and the Brand Bible or YouTube Brand Kit ever appear to disagree on what an asset *should look like*, those documents win and this Guide is corrected.
**Companion documents:** `brand/Mythic_Forge_Studios_YouTube_Brand_Kit_v1.0.md` (defines the YouTube-specific specifications this Guide's workflow produces assets *against*, not a workflow itself), `production-bible/Fracture_Protocol_Production_Bible_v1.1.md` Section 7 (Asset Management — this Guide is that process's brand-asset-specific instance, not a competing one) and Section 6 (Version Control — this Guide inherits its status vocabulary rather than inventing a new one), `governance/Fracture_Protocol_Studio_Governance_Manual_v1.1.md` (approval authority for Locked vs. Living decisions), `README.md` (Studio Wiki — navigation).

---

### How to use this document

The Brand Bible and YouTube Brand Kit both answer the same kind of question: *what is correct?* Neither answers *how does a correct asset actually get made, checked, approved, and stored?* This Guide is that missing layer — a production workflow, not a design document. It defines stages, checklists, approval states, and registry integration. It does not, at any point, define or redecide what the logo looks like, what the palette is, or what the studio is called — those facts are imported by citation, exactly as the YouTube Brand Kit imports them from the Brand Bible.

**Relationship to the existing "policy vs. detail" pattern:** this repository already separates *what* from *how* in exactly this way — Production Bible (philosophy/pipeline) vs. Production OS (department SOP detail); Governance Manual (constitution) vs. Repository Health Guide (maintenance procedure). This Guide is that same pattern applied to brand assets: Brand Bible + YouTube Brand Kit are the *what*; this Guide is the *how*.

Tags: **[LOCKED]** — founder/Creative Director sign-off required to change. **[LIVING]** — expected to evolve as real production cycles reveal what the workflow needs.

---

## 1. Document Purpose & Authority **[LOCKED]**

**Why this guide exists:** the Brand System Audit (2026-07-07) found that the Brand Bible and YouTube Brand Kit together define a complete, internally consistent identity system with zero canon or continuity defects — but neither document, nor any other document in the repository, defines how a brand asset is actually requested, produced, reviewed, approved, versioned, or stored. That gap was the audit's single most significant finding. This Guide closes it.

**Relationship to the Brand Bible:** subordinate in full. The Brand Bible defines the identity (logo concept, color, typography, motion, audio, voice). This Guide never redefines any of it — it only defines the process by which a compliant asset embodying that identity gets made.

**Relationship to the YouTube Brand Kit:** parallel, not subordinate-to-subordinate. The Kit defines *what* a YouTube-specific asset must specify (banner dimensions, thumbnail layout, intro timing). This Guide defines the *workflow* that produces any brand asset, YouTube-specific or not — the Kit is one of the specification sources this Guide's Stage 3 (Draft Creation) checks a draft against, not something this Guide governs.

**Relationship to the Production Bible:** the Production Bible's Section 7 (Asset Management) already defines a five-stage asset lifecycle (Creation → Review → Approval → Revision → Retirement) and a general Asset Registry for show production assets. This Guide does not compete with that process — it is its brand-asset-specific instance, using the same lifecycle shape and the same registry (Section 7 below), extended with the brand-specific checks (Sections 3–5) that a show asset wouldn't need and a brand asset does.

**Relationship to the Asset Registry:** brand assets are logged in the same registry Production Bible Section 7 already establishes, under a new category (Section 7 below) — not a second, competing registry.

**Authority if conflicts appear:**

| Question | Authoritative document |
|---|---|
| What should this asset look like? | Brand Bible, then YouTube Brand Kit for YouTube-specific application |
| How does this asset get made, reviewed, and approved? | This Guide |
| Who has the authority to approve it? | Studio Governance Manual Sections 5–7 |
| Where does it live, and how is its version tracked? | Production Bible Sections 6–7, applied per Section 6 below |

This Guide has **no authority over identity** — only over workflow. A disagreement between this Guide and any identity-defining document is, by definition, a bug in this Guide.

---

## 2. Brand Asset Production Philosophy **[LOCKED]**

Mythic Forge Studios treats brand asset production with the same discipline the Brand Bible demands of the identity itself (Brand Bible Section 1, Creative Principles):

**Precision over speed.** An asset that's on-brand and late is correctable. An asset that's off-brand and fast creates cleanup work, inconsistency, and — if it reaches the public before anyone notices — a correction the audience sees happen. No asset ships to save time at the cost of accuracy against the Brand Bible or YouTube Brand Kit.

**Consistency over experimentation.** Concept exploration (Section 4) is where experimentation belongs. Once a draft enters review (Stage 4), the question is never "is this an interesting new direction?" — it's "does this match what's already specified?" A brand asset workflow is not the place to discover a new visual idea; the Brand Bible is the place ideas get approved, and only Founder Override changes it (Brand Bible Section 15).

**Controlled evolution over constant redesign.** The identity is built to last (Brand Bible Section 1, Long-Term Vision) — this Guide's job is to protect that stability through every single asset produced under it, not to introduce incremental drift one "small tweak" at a time. A hundred small unapproved deviations are indistinguishable, in the end, from one large unapproved redesign.

**In practice:** every stage in Section 3 exists to catch a deviation before it becomes a shipped asset, not after.

---

## 3. Asset Creation Workflow **[LOCKED spine, LIVING detail]**

Every brand asset — logo file, channel avatar, banner, thumbnail template, watermark, motion graphic, intro/outro element, audio logo file, or future marketing material — passes through all six stages below, in order. No stage is skipped, even for a small or routine asset; a routine asset simply moves through its stages quickly.

### Stage 1 — Asset Request

**Who can request:** the Founder/Creative Director today; any filled production role from Studio OS Section 29's role map once the studio scales (e.g., a future Community Manager requesting a Discord emoji set).

**Required information (Asset Request Template):**

```
Asset Request

Requested by:        {name/role}
Date:                 {YYYY-MM-DD}
Asset type:           {logo variant / avatar / banner / thumbnail element /
                       watermark / motion graphic / intro or outro / audio
                       logo / other — specify}
Purpose:              {why this asset is needed}
Target platform:      {YouTube / Discord / X / merchandise / website / other}
Governing spec(s):    {which Brand Bible and/or YouTube Brand Kit section(s)
                       this asset must comply with}
Urgency:              {routine / time-sensitive — and why, if time-sensitive}
Existing asset check: {confirmed no reusable existing asset already satisfies
                       this request — checked against the Asset Registry,
                       Section 7}
```

**Rule:** a request that skips the "existing asset check" field is returned, not processed — this mirrors Production Bible Section 7's Creation rule that nothing is built before the registry confirms nothing reusable already exists.

---

### Stage 2 — Concept Development

**Research process:** review the specific Brand Bible and/or YouTube Brand Kit section(s) named in the request; review any prior approved asset of the same type for precedent.

**Reference gathering:** reference material is used to inform *execution quality* (e.g., how a comparable studio's avatar reads at small size) — never as a source of *identity ideas*. A reference that suggests a new color, mark, or concept is out of scope for this stage; see Section 4 for what AI and reference material may and may not influence.

**Moodboard creation:** optional, scaled to the asset's complexity — a simple watermark crop doesn't need one; an intro animation or a genuinely new asset type benefits from one. A moodboard at this stage draws only from already-approved brand material (existing renders, the palette, the typefaces) — it is an execution aid, not a design-direction exercise.

**Draft preparation:** concept development ends with a small number of draft directions (typically 1–3) ready to enter Stage 3, each already checked against the governing spec named in the request.

**AI-assisted generation rules:** see Section 4 in full — this stage is where AI tools are most useful and most tightly bounded.

---

### Stage 3 — Draft Creation

**First draft requirements:** a draft is a candidate final asset, not a rough sketch — it should be built at (or convertible to) the actual specified format and resolution, not a placeholder standing in for one.

**Required file formats:** per the asset type's entry in Brand Bible Section 14 or YouTube Brand Kit Section 12 (Export Standards) — this Guide does not redefine formats, only requires that the draft already targets the correct one.

**Technical specifications:** exact dimensions, safe areas, timing, and resolution per the relevant Brand Bible or YouTube Brand Kit section named in the original request (Stage 1).

**Brand compliance checks (self-check before submitting to Stage 4):**
- Colors match Brand Bible Section 4 exactly — no unauthorized substitution or approximation
- Typography matches Brand Bible Section 5 exactly
- Logo usage (if applicable) matches Brand Bible Section 3 and, for YouTube assets, YouTube Brand Kit Section 2
- Tone matches Brand Voice (Brand Bible Section 12) if the asset includes any text

A draft that fails its own self-check is revised before it ever reaches Stage 4 — Stage 4 is a review of a genuine candidate, not a first-pass catch-all.

---

### Stage 4 — Internal Review

**Review checklist:**

- [ ] **Brand consistency** — matches the Brand Bible and, where applicable, the YouTube Brand Kit exactly; no unauthorized interpretation of a spec
- [ ] **Visual quality** — no compression artifacts, no off-model rendering, professional finish at its intended output resolution
- [ ] **Accessibility** — meets Brand Bible Section 4's WCAG contrast minimums wherever the asset carries text or a color-dependent distinction
- [ ] **Platform requirements** — meets every technical spec named in Stage 3 (dimensions, safe area, format, file size)
- [ ] **Long-term usability** — still reads correctly next to an asset made under a future version of this same identity (Brand Bible Section 1, Long-Term Vision); nothing trend-dependent or dated

This checklist is the general-purpose review gate. The full Brand Asset Quality Control Checklist (Section 5) is the complete, reusable version of this same review, and is what actually gets applied — this list exists here only to show where in the workflow that check happens.

---

### Stage 5 — Approval Process

**Who approves:** per Studio Governance Manual Section 5 — a change to a Locked brand element (studio name, logo concept, palette, typography, motion/audio identity, naming conventions, or the Brand Bible/YouTube Brand Kit relationship) requires Founder sign-off; approval of a routine, non-identity-changing asset produced correctly within the existing Locked framework (a new banner variant, a season's thumbnail badge, a social crop) is Creative Director authority (Governance Manual Section 7), consistent with how Brand Bible Section 15 already splits Locked vs. Living approval.

**Approval states:** this Guide does not invent a new status vocabulary. It inherits Production Bible Section 6's existing asset-status system (Draft → In Review → Approved → Superseded/Retired) in full, with one addition specific to brand assets:

```
DRAFT
  ↓
IN REVIEW        (Stage 4 checklist applied)
  ↓
REVISION         (only if the checklist fails — returns to DRAFT)
  ↓
APPROVED         (Production Bible Section 6's existing "Approved" state —
                  passed review, current canonical version)
  ↓
LOCKED           (brand-specific designation — see below)
```

**What "Locked" means here:** "Locked" is not a seventh competing lifecycle state alongside Production Bible Section 6's five — it is a designation applied to an Approved asset that embodies a Locked identity element (Brand Bible Section 3's Primary Logo master file, for example). A Locked asset can only be superseded through the same Founder Authority process that would change the Brand Bible's own Locked sections (Governance Manual Section 6) — never through a routine Creative Director revision. An Approved asset that embodies a Living element (a social template, a merchandise mockup) remains Approved without ever needing the Locked designation, and may be revised under normal Creative Director discretion.

**Revision handling:** any requested change to an Approved or Locked asset is a new version, reviewed and approved the same way as the original (Production Bible Section 7) — never a silent overwrite of an existing file.

---

### Stage 6 — Release & Storage

**Where approved files live:** Brand Bible Section 14's `/brand/assets/` (general brand assets) or YouTube Brand Kit Section 14's `/brand/assets/youtube/` subtree (YouTube-specific assets) — this Guide does not define a third location; it only enforces that nothing is released outside these two, already-documented folders.

**Folder structure:** unchanged from Brand Bible Section 14 and YouTube Brand Kit Section 14 — both remain not-yet-created until a first real asset exists (Studio Wiki Section 15's rule against speculative scaffolding); this Guide's Section 8 defines which asset creates them first.

**Versioning rules:** standard studio-wide `v{major}.{minor}` (Production Bible Section 6; Brand Bible Section 14; YouTube Brand Kit Section 13) — Section 6 below restates this only to give brand-specific examples, not to redefine it.

**Archive rules:** unchanged from Production Bible Section 14 — a Superseded or Retired brand asset moves to Archive with a one-line reason, retrievable, never deleted.

---

## 4. AI-Assisted Brand Asset Workflow **[LOCKED]**

Mythic Forge Studios is an AI-assisted production studio (Studio OS Section 5) — this applies to brand assets exactly as it applies to show assets, with the same guardrail: **AI assists execution; it does not replace creative authority.**

**Allowed:**
- Concept exploration — generating multiple candidate executions of an *already-approved* idea (e.g., rendering the anvil-and-fracture mark at different weights to test legibility)
- Variations — producing size/format/color-mode variants of an approved asset (e.g., generating every required export size from an approved master)
- Reference generation — producing comparison material to evaluate execution quality (Stage 2)
- Moodboards — assembling existing approved brand material for internal review
- Early experimentation — fast iteration during Stage 2, before anything enters Stage 3 as a real draft

**Restricted — AI tools may not decide:**
- The final logo design, color, or typography — these are Brand Bible-Locked facts (Section 3); AI may render candidates, but a candidate becomes real only through the human approval chain in Stage 5
- Any brand direction change — a "the AI suggested a better color" outcome is never a valid path to a palette change; only a Founder Override (Governance Manual Section 6) changes a Locked brand element
- Any canon decision — brand assets never introduce story canon (front matter, this document and both companions); an AI-generated brand asset that accidentally depicts or implies a story fact is rejected at Stage 4, not shipped with a note

**Guiding rule (inherited from Studio OS Section 5's Originality Decision Framework):** any AI-generated concept is a first draft, not a final approval — this applies to brand assets with zero exception. The same Originality Check Studio OS Section 5 requires of any studio asset applies to AI-assisted brand illustration (Brand Bible Section 7 already states this; this Guide operationalizes it as a mandatory Stage 3/4 gate rather than a general principle).

---

## 5. Brand Asset Quality Control Checklist **[LOCKED]**

Every asset passes this checklist at Stage 4 before advancing to Stage 5. This is the reusable, complete version of the review gate introduced in Section 3.

**Brand Check**
- [ ] Correct colors (Brand Bible Section 4 — exact hex values, correct role usage)
- [ ] Correct typography (Brand Bible Section 5 — correct typeface, weight, and hierarchy)
- [ ] Correct logo usage (Brand Bible Section 3; YouTube Brand Kit Section 2 for channel-specific placement) — correct variant for context, clear-space and minimum-size rules observed
- [ ] Correct tone (Brand Bible Section 12, Brand Voice) — applies to any text the asset carries

**Technical Check**
- [ ] Correct resolution and dimensions for the asset's specified use (Brand Bible Section 14; YouTube Brand Kit Section 12)
- [ ] Correct file format (per the same sections)
- [ ] Correct naming convention (Section 6 below)

**Platform Check**
- [ ] Works correctly on its intended platform (renders as expected in the actual destination — channel page, app icon slot, merchandise print file, etc.)
- [ ] Mobile readability — legible at the smallest realistic render size for its type (YouTube Brand Kit Sections 2, 4, 6 give concrete minimums for channel assets)
- [ ] Dark/light background testing — legible and correctly composed against both, where the asset's context could show either (YouTube Brand Kit Section 2's UI-chrome-compatibility rule)

**Future Check**
- [ ] Can scale for future Mythic Forge Studios projects — does not encode anything specific to a single episode, season, or moment that would make it obsolete outside the context it was made for, consistent with Brand Bible Section 16 (Future Expansion)

An asset that fails any single item returns to Stage 3 (Draft Creation) as a Revision — it does not proceed with a noted exception.

---

## 6. Brand Asset Naming & Version Control **[LOCKED]**

This Guide does not invent a new naming philosophy — it extends the pattern already established in Brand Bible Section 14 (`mfs-logo-{variant}-{color-mode}_v{X.X}.{ext}`) and YouTube Brand Kit Section 13 (`mfs-youtube-{asset-type}-{descriptor}_v{X.X}.{ext}`) to a single general form covering every brand asset type:

**General convention:** `mfs-{asset-type}-{descriptor}_v{X.X}.{ext}`

| Category | Example |
|---|---|
| Logo | `mfs-logo-primary-dark_v1.0.svg` |
| YouTube | `mfs-youtube-banner-main_v1.0.png` |
| Motion | `mfs-motion-intro_v1.0.mp4` |
| Audio | `mfs-audio-logo_v1.0.wav` |

**Major version changes:** a locked-element revision, a structural change to the asset, or anything requiring Founder sign-off beyond a routine pass (Production Bible Section 6) — e.g., a new Primary Logo master file.

**Minor version changes:** an additive or corrective change within the existing structure and already-approved design — e.g., a corrected export, an added size variant, a fixed compression artifact.

**Locked versions:** the current Approved-and-Locked file for a Locked identity element (Section 3, Stage 5) — exactly one Locked version of any given Locked asset is "current" at a time, mirroring Brand Bible Section 3's Logo Consistency Rule that only one Primary Logo file per color mode is ever current.

**Archived versions:** every Superseded or Retired version remains retrievable in Archive (Production Bible Section 14) — never deleted, never overwritten in place.

---

## 7. Asset Registry Integration **[LOCKED]**

**Resolving the audit's open question:** brand assets are logged in the **same** Asset Registry the Production Bible already establishes (Production Bible Section 7) — this Guide does not create a second, competing registry. They are logged under a new category value, alongside whatever categories already track show production assets.

**Recommended category:** `BRAND_ASSET`

**Fields (extending Production Bible Section 7's existing name/type/version/status/location/originality-check fields with two brand-specific additions — Creator and Approval Date — needed because brand assets, unlike most show assets, are frequently produced or iterated by a single non-departmental owner):**

| Field | Description |
|---|---|
| Asset ID | Stable identifier for this asset across all its versions |
| Asset Name | Human-readable name (e.g., "Primary Logo — Dark Version") |
| Category | `BRAND_ASSET` |
| Version | Current `v{major}.{minor}` |
| Status | Draft / In Review / Approved / Locked / Superseded / Retired (Section 3, Stage 5) |
| Creator | Who produced this version (person, or "AI-assisted, reviewed by {name}" per Section 4) |
| Approval Date | Date this version was marked Approved or Locked |
| Storage Location | File path under `/brand/assets/` or `/brand/assets/youtube/` |

No brand asset is "real" until it is logged here — an asset that exists only as a file with no registry entry is treated as unapproved, exactly as Production Bible Section 7 already states for any other asset type.

---

## 8. First Production Pipeline: MFS Brand Launch Assets **[LOCKED]**

**Recommended order for producing the first official set of brand assets:**

1. **Primary Logo Master SVG**
2. **Logo Variants** (Secondary, Horizontal, Vertical, Icon-only, Monochrome, Dark, Light — Brand Bible Section 3)
3. **Channel Avatar** (YouTube Brand Kit Section 2)
4. **YouTube Banner** (YouTube Brand Kit Section 3)
5. **Thumbnail Branding System** (icon-bug and episode-number badge — YouTube Brand Kit Section 6)
6. **Watermark / Icon Bug** (YouTube Brand Kit Section 2)
7. **Motion Intro** (YouTube Brand Kit Section 7)
8. **Audio Logo** (Brand Bible Section 9)

**Why this order matters:** every asset after the first depends on something the first establishes. The Primary Logo Master SVG is the single source every other variant, crop, and application is derived from (Brand Bible Section 3's rule against redrawing) — producing anything downstream of it first would mean redoing that work once the master exists. Logo Variants must exist before the Channel Avatar and Banner, since both are explicitly defined as applications of specific variants (Icon Version; Horizontal Logo), not independent designs. The Thumbnail Branding System and Watermark both depend on the Icon Version passing its small-size legibility test (YouTube Brand Kit Section 2) — that test can't be run until the Icon Version itself is final. The Motion Intro depends on the settled-glow logo animation state (Brand Bible Section 8) already being defined against a final logo, and the Audio Logo is timed to land against that same visual settle point (YouTube Brand Kit Section 7) — so audio is sequenced last, once the visual timing it synchronizes to is locked.

---

## 9. Future Maintenance Rules **[LIVING]**

**When assets can be updated:** a Living-element asset (Section 3, Stage 5) may be updated under normal Creative Director discretion when it no longer serves its purpose well (e.g., a social crop that doesn't read correctly on a platform's redesigned UI) — this is a minor or major version bump per Section 6, not a redesign.

**When redesigns are allowed:** a redesign — meaning a change to a Locked identity element itself (the logo concept, the palette, the typefaces, the studio name/tagline) — requires the same Founder Override bar as any other Locked-section change to the Brand Bible (Governance Manual Section 6; Brand Bible Section 15). This Guide's workflow does not gate that decision; it only ensures that once such a decision is made, every downstream asset is rebuilt through the same six stages, not patched piecemeal.

**How legacy assets are archived:** per Production Bible Section 14 — retained, never deleted, retrievable at every prior version.

**How consistency is protected over years:** by the same principle Brand Bible Section 1 states directly — growth in brand surface area should never outpace the studio's actual capacity to maintain consistency across all of it. This Guide protects that principle mechanically: every new asset, however small, passes through the same six stages and the same registry, so "one identity, every surface" remains true by process, not by memory.

---

## 10. Final Production Checklist

Before any brand asset becomes official:

- [ ] Created using the approved workflow (Section 3, Stages 1–6)
- [ ] Passed brand review (Section 5, Brand Check)
- [ ] Passed technical review (Section 5, Technical Check, Platform Check)
- [ ] Correctly named (Section 6)
- [ ] Added to the Asset Registry (Section 7)
- [ ] Approved version — and, if it embodies a Locked identity element, Locked — recorded (Section 3, Stage 5)

---

## Final Validation

- **No brand identity was redesigned, reinterpreted, or modified.** The studio name, abbreviation, tagline, "the brand echoes the fiction; it never explains it" principle, logo concept, color palette, typography, motion identity, audio identity, naming conventions, and the Brand Bible/YouTube Brand Kit relationship are all unchanged and are cited, never restated as new fact.
- **No story canon was introduced.** No character, faction, location, technology, power mechanic, or world fact appears anywhere in this document.
- **No competing status vocabulary was created.** This Guide's approval states inherit Production Bible Section 6's existing five-state asset lifecycle in full, adding only "Locked" as a designation on top of "Approved" for identity-Locked assets — not a sixth competing system.
- **No competing Asset Registry was created.** Brand assets are logged in the same registry Production Bible Section 7 already establishes, under a new `BRAND_ASSET` category — resolving the audit's open question directly.
- **Compatible with every existing document.** Checked against Brand Bible Sections 1, 3–5, 7, 9, 12, 14–16; YouTube Brand Kit Sections 2–4, 6–7, 12–14; Production Bible Sections 6–7, 14; Studio Governance Manual Sections 5–7; Studio OS Sections 5, 29. No contradictions found.
- **This document is strictly a workflow layer.** Every section defines a process, a checklist, or a registry integration — never a design decision.
- **Ready to move from documentation into production**, pending Founder review of this Guide itself (front matter, Status).

---

**Version:** 1.0
**Status:** Draft — ready for Founder review; structure and workflow fully defined, not yet exercised against a real production cycle
**Authority:** Subordinate to the Master System Prompt and the Brand Bible; governed operationally by the Studio Governance Manual (Section 1); instantiates Production Bible Section 7 for brand assets specifically, rather than replacing it
**Scope:** The production workflow for brand assets only — request, concept development, drafting, review, approval, release, AI-assistance boundaries, quality control, naming/versioning, registry integration, first-pipeline sequencing, and long-term maintenance. Explicitly excludes all story canon, lore, and any redefinition of the identity elements the Brand Bible and YouTube Brand Kit already establish.

---

### Changelog
`[v1.0 — 2026-07-07] Initial Brand Asset Production Guide established: 10 sections (Document Purpose & Authority through Final Production Checklist) plus Final Validation, closing the workflow gap identified by the Brand System Audit. Defines a six-stage asset creation workflow (Request → Concept Development → Draft Creation → Internal Review → Approval → Release & Storage), AI-assistance boundaries (allowed vs. restricted uses), a reusable Brand/Technical/Platform/Future quality checklist, naming and version-control rules extending the existing Brand Bible/YouTube Brand Kit convention, Asset Registry integration via a new BRAND_ASSET category within the existing Production Bible registry (rather than a competing one), the recommended first-production order for the studio's initial brand asset set, future maintenance rules, and a final pre-release checklist. Introduces zero story canon and redesigns no existing brand element; every identity fact (name, tagline, logo concept, palette, typography, motion/audio identity, naming pattern) is cited from the Brand Bible or YouTube Brand Kit, never restated as new. Reconciles the "Locked" approval state requested for this workflow with Production Bible Section 6's existing asset-status vocabulary as a designation on Approved, not a competing sixth state.`
