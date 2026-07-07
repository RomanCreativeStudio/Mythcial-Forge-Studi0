# THE FRACTURE PROTOCOL
## Story Timeline Bible
### Version 1.0

**Classification:** Internal — Production/Governance Document
**Status:** Framework only. Introduces zero characters, locations, events, wars, discoveries, organizations, technology, lore, history, dates, years, eras, or episodes. Every field, category, and example below is a placeholder — this document defines the *container* chronology will eventually live inside, not any chronology itself.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` — this document is subordinate to it in all cases and carries no canon authority of its own.
**Companion documents:** `bible/Fracture_Protocol_World_Bible_v1.1.md` (World Rule 5, history persists; Section 2, the deliberately-unresolved founding event this framework must never pressure toward resolution), `series/01-the-fracture-protocol/Series_Bible_v1.1.md` (Running Mysteries, Section 15), `registries/Fracture_Protocol_Canon_Reference_System_v1.0.md` (Section 4, Timeline — that system's pointer category now points here for framework, not content), `bible/Fracture_Protocol_Proposal_Vault_v1.0.md` (where a missing chronology answer goes).
**Standing constraint this document must never violate:** World Bible Section 2 states that what caused the founding Fracture is "deliberately unconfirmed" and that "this ambiguity is permanent scaffolding, not an oversight — do not resolve it without founder sign-off." Nothing in this framework — not its structure, not its examples, not its eventual use — may be read as resolving that, or any other deliberately-unresolved mystery (Series Bible Section 15), by implication. A framework that could store a date for the Fracture is not the same as a framework that asserts one exists yet.

---

### How to use this document

This is not a history of anything. It is the filing system a history would use, if and when the founder approves populating it. Every section below defines a rule, a field, a category, or a process — never a fact. If you find an actual date, year, named event, or character biography anywhere below, that is a defect in this document, not a feature — flag it the same way any other canon leak in a process document would be flagged (Repository Health Guide Section 2).

Tags: **[LOCKED]** — founder/Creative Director sign-off required to change. **[LIVING SECTION]** — the framework may gain new categories or fields without a full sign-off, as long as no actual chronology content is added without going through Section 9.

---

## 1. Purpose **[LOCKED]**

This document defines how official chronology is stored, organized, updated, and referenced, once the franchise has one. It does not create history — it creates the system history will eventually live inside. Every rule here answers a structural question ("how is a timeline entry identified," "how does a script synchronize with it," "what happens when something needs to be corrected") and none of them answers a narrative question ("what happened," "when," "to whom"). Those remain exclusively the World Bible's, Series Bible's, and (upon approval) this framework's populated content's business — never this document's.

---

## 2. Authority **[LOCKED]**

The Master System Prompt remains the highest authority over this document, exactly as it does over every other document in this repository (Master System Prompt Section 2, Source of Truth Rule). This Timeline Bible **stores** canon once it exists — it never **creates** canon. Populating a single entry with real content (Section 6) is itself a canon action and requires the same authority as any other: explicit creator approval via the Founder Override Protocol (Master System Prompt Section 13), following Drift Detection (Section 12, Rule 3) exactly as a new character or faction would.

This document is Documentation/Process in the Studio Governance Manual's three-way classification (Section 4, Canon vs. Process vs. Documentation) — it is never itself Canon, no matter how much canon it eventually indexes.

---

## 3. Timeline Philosophy **[LOCKED]**

Three permanent principles govern this framework, all already established elsewhere and restated here only as they apply to chronology specifically:

1. **History persists forever.** Once a timeline entry is approved as canon, it remains true — consequences from past entries remain valid (World Bible Section 15, Rule 5). This framework has no mechanism for simply deleting an inconvenient past entry.
2. **Nothing is forgotten.** An entry that stops being narratively relevant is not removed — it is retained per Section 13 (Maintenance), the same way a retired document is retained rather than deleted (Studio Governance Manual Section 18).
3. **No retcons without Founder Override.** Changing what a previously-approved entry says happened is not a routine edit — it is a Major Canon Update (Master System Prompt Section 13, Change Classification) and follows Section 9 (Retcon Rules) without exception.

---

## 4. Chronology Rules **[LOCKED framework, LIVING detail]**

Every timeline entry is classified along a temporal-position axis. These are structural labels only — no actual event is classified below.

| Classification | Meaning |
|---|---|
| **Past** | Occurs before the current point of active story focus |
| **Present** | Occurs at or concurrent with the current point of active story focus |
| **Future** | Planned or reserved to occur after the current point of active story focus (e.g., a Running Mystery reserved for a later season — Series Bible Section 15) |
| **Unknown** | Deliberately unresolved — the entry's existence may be implied, but its placement is intentionally withheld (this is the classification the founding Fracture event itself would carry, per World Bible Section 2, if it were ever entered here — which it has not been) |
| **Parallel** | Concurrent with another specific entry — i.e., two things happening at the same point in **the same single chronology**, from different character or location perspectives. This classification does **not** imply alternate timelines, alternate universes, or a multiverse — Master System Prompt Section 3 and World Bible Section 1 are explicit that this is one controlled megacity, not a scattered multiverse, and this framework must never be read as introducing one. "Parallel" here means "simultaneous," never "alternate." |

---

## 5. Timeline Structure **[LOCKED spine, LIVING labels]**

The framework's organizing hierarchy, using placeholders only — this shape does not assert that "Era" or "Year" are confirmed, real, in-world units. Whether an eventual populated timeline actually uses years, or some other unit entirely, is itself an open question deferred to founder approval when real content is proposed (Section 9). This is a container shape, not a claim about what's inside it.

```
{Era}
   │
   ▼
{Year}
   │
   ▼
{Season}
   │
   ▼
{Episode}
   │
   ▼
{Scene}
   │
   ▼
{Event}
```

Each level is optional in practice — not every entry needs a Scene-level placement, and some entries (a slow-building world-state change, for instance) may only ever resolve to an Era- or Year-level placement. The hierarchy exists to let an entry be as precise or as deliberately vague as its own canon status requires — an "Unknown" classification (Section 4) is fully compatible with leaving every level below `{Era}` blank.

---

## 6. Timeline Entry Format **[LOCKED]**

Every timeline entry, once approved, uses this exact structure. All values below are placeholders — no entry currently exists using this template.

```
### TML-{NNNN} — [Entry Title Placeholder]

| Field | Value |
|---|---|
| **ID** | TML-{NNNN} |
| **Title** | [Placeholder] |
| **Source** | [Which approved document/section established this — e.g., "World Bible §{N}" or "Series Bible S{season}E{episode}"] |
| **Status** | `Active` / `Superseded` / `Retconned` / `Under Review` (Section 8) |
| **Chronology Classification** | Past / Present / Future / Unknown / Parallel (Section 4) |
| **Structural Placement** | {Era} / {Year} / {Season} / {Episode} / {Scene} (Section 5) — any level may be blank |
| **Affected Characters** | [Placeholder list] |
| **Affected Locations** | [Placeholder list] |
| **Dependencies** | [Other TML-{NNNN} entries this one requires to already be true] |
| **Canon Level** | `LOCKED CANON` / `PROPOSED` / `APPROVED CANON` (Master System Prompt Section 12, Rule 2 — reused here, not redefined) |
| **Founder Approval** | [Exact Founder Override Command, or "Pending"] |
| **Last Updated** | [Date] |
```

**ID Convention:** `TML-{NNNN}`, four-digit zero-padded, sequential, never reused or renumbered — same convention and same reasoning as the Studio Decision Log's `DEC-{NNNN}` (Decision Log Section 3).

---

## 7. Timeline Categories **[LIVING SECTION]**

Every entry, once it exists, is tagged with one or more categories below. These are classification labels only — no entry currently exists in any of them.

| Category | Scope |
|---|---|
| Character Events | Placeholder — individual character-level occurrences |
| World Events | Placeholder — occurrences affecting the setting broadly |
| Political | Placeholder — Authority/institutional-level occurrences |
| Scientific | Placeholder — Signal/system-mechanic-level occurrences |
| Environmental | Placeholder — Zone/megacity-structure-level occurrences |
| Personal | Placeholder — private, non-public-record occurrences |
| Cultural | Placeholder — Mid Zone/civilian-life-level occurrences |
| Mystery | Placeholder — occurrences tied to a Running Mystery (Series Bible Section 15) |
| Artifact | Placeholder — Root Artifact-related occurrences (World Bible Section 11) |
| Technology | Placeholder — Cipher-work/system-related occurrences (World Bible Section 7) |

A new category may be added the same way a new Studio Wiki index section is added (Studio Wiki Section 24) — appended, never restructuring the existing list.

---

## 8. Continuity Rules **[LOCKED]**

- **Nothing disappears.** An entry that becomes less narratively central does not lose its place in the chronology — it is marked accordingly (Section 13) but never removed.
- **Everything has consequences.** An approved entry that would logically affect a later point in the chronology must be checked against that later point before the later point is itself approved — this is the timeline-specific instance of World Bible Section 15, Rule 6 ("the world continues existing off-page").
- **No silent contradiction.** If a proposed entry would contradict an existing `Active` entry, this is Drift Detection (Master System Prompt Section 12, Rule 3) — the proposal is not approved until the contradiction is resolved, either by revising the proposal or by initiating a Retcon (Section 9) on the existing entry.

---

## 9. Retcon Rules **[LOCKED]**

Changing what an already-approved timeline entry says is never a routine edit. It requires the full Founder Override Protocol (Master System Prompt Section 13), classified as a Major Canon Update (Change Classification) without exception, regardless of how small the change looks:

1. A Change Impact Report is produced (Master System Prompt Section 13) specifically naming every downstream entry (Section 8, Dependencies) that could be affected.
2. An explicit Founder Override Command is given for the retcon specifically — approval of the original entry does not carry forward as approval of a change to it.
3. The original entry's Status (Section 6) is updated to `Retconned`, not deleted — it remains visible, cross-referencing the entry that replaced it.
4. A new entry is created for the corrected chronology, with its own `TML-{NNNN}` ID (Section 6) — a retcon is a new entry, not an overwrite of the old one.
5. The retcon is logged in the Studio Decision Log (`governance/Fracture_Protocol_Studio_Decision_Log_v1.0.md`), since a retcon is definitionally a significant decision with real alternatives (keep vs. change) — see that document's own Section 2 for the scope rule.

---

## 10. Episode Synchronization **[LIVING SECTION]**

How a script updates the timeline, once scripts exist:

1. During Scripting (Production Bible Section 3, stage 2), any chronology-relevant beat the script introduces is flagged, not silently written into the script as if already canon.
2. Before the script passes its canon check (Production Bible Section 3, gate condition), each flagged beat is checked against Section 8 (Continuity Rules) for contradiction with any existing `Active` entry.
3. On script approval, each flagged beat becomes a timeline entry proposal, following the same Proposal Vault → Founder Override path as any other canon addition (Section 2) — script approval alone does not create a timeline entry.
4. Once approved, the entry is logged using the Section 6 format the same day, per the Studio Wiki's same-day update rule (Studio Wiki Section 24).

---

## 11. Cross-References **[LOCKED]**

| Document | Relationship |
|---|---|
| World Bible | Source of world-level chronology facts (Section 2, Section 15); this framework never resolves World Bible's deliberately-unresolved items by implication |
| Series Bible | Source of story/episode-level chronology facts (Section 11, Section 15 — Running Mysteries) |
| Canon Reference System | Its Timeline category (Section 4) points here for framework; this document never duplicates that system's other categories |
| Art Bible | Visual continuity for a given timeline entry (e.g., a character's appearance at a given structural placement) is Art Bible's domain, referenced from an entry, never restated here |
| Proposal Vault | Where a chronology question with no existing answer goes (Section 2) — never answered here by inference |
| Production Bible | Governs the pipeline stage (Scripting) that generates timeline entry proposals (Section 10) |

---

## 12. Future Scaling **[LIVING SECTION]**

This framework is built to support one master chronology across every future format, not a separate timeline per format:

- **Multiple seasons:** each new season's approved entries extend the same chronology; a new season never starts its own parallel timeline.
- **Spin-offs:** a spin-off series (a second Series Bible, Studio Wiki Section 5) contributes to the same master chronology unless the founder explicitly establishes it as a separate continuity — a decision that would itself be a Founder Override-level call, not a default.
- **Films, games, books:** any future format (Studio OS Section 28, Phased Roadmap) that touches story content synchronizes against this same framework via the same Section 10 process, regardless of medium.
- **Still one master chronology.** The Master System Prompt's Universe Identity (Section 3) names exactly one valid universe; this framework structurally enforces that there is exactly one chronology to match it, no matter how many formats eventually reference it.

---

## 13. Maintenance **[LIVING SECTION]**

- **Version control:** this document follows the studio-wide `v{major}.{minor}` convention (Production Bible Section 6) — a new field, category, or structural level is a minor bump; a change to the ID convention, entry format, or retcon process is a major bump.
- **Archive:** an entry marked `Retconned` or otherwise no longer active is never deleted — it is retained in place with its Status field updated, per Section 9 and the Studio Governance Manual's Retirement Policy (Section 18).
- **Retired entries:** follow the same tombstone pattern already used elsewhere in this repository (e.g., Production OS's retired sections, Decision Log `DEC-0001`) — the entry stays, its content is marked superseded, and it points to whatever replaced it.
- **Corrections:** a correction to this framework's structure (not to any populated content, since none exists yet) follows the Studio Governance Manual's Change Request Workflow (Section 11) like any other process document.

---

## 14. Validation

1. **No lore.** No character, faction, technology, or power mechanic is named as an example anywhere in this document beyond citing the section of an existing Bible where such things are already defined.
2. **No events.** No occurrence, discovery, conflict, or story beat is described, implied, or exampled — every category (Section 7) and structural level (Section 5) is an empty label.
3. **No dates.** No year, era name, or absolute chronological marker appears anywhere — Section 5's hierarchy uses bracketed placeholders (`{Era}`, `{Year}`) explicitly flagged as unconfirmed generic labels, not real in-world units.
4. **No history.** Every entry format field (Section 6) is populated with a placeholder or an instruction, never a value — there is no populated `TML-{NNNN}` entry anywhere in this document.
5. **Only framework.** Every section defines a rule, a field, a process, or a classification — never a fact. Verified by direct review against Section 2's standing constraint: nothing here resolves, narrows, or nudges the founding Fracture event (World Bible Section 2) or any Running Mystery (Series Bible Section 15) toward an answer.
6. **Compatible with all existing documents** — checked against World Bible Sections 2, 7, 11, 15; Series Bible Section 15; Master System Prompt Sections 2–3, 12–13; Studio Governance Manual Sections 4, 11, 18; Canon Reference System Section 4 (Timeline); Studio Decision Log Sections 2–3; Production Bible Section 3, 6. No contradictions found; the "Parallel" classification (Section 4) was specifically checked against the single-megacity/no-multiverse rule and rephrased to mean simultaneity, never alternate timelines.

---

*End of Story Timeline Bible v1.0. This document has no history in it and should never acquire one without an explicit Founder Override Command — the day it does, that's a canon event, not a framework update.*

---

### Changelog
`[v1.0 — 2026-07-07] Initial Story Timeline Bible established: 14 sections (Purpose through Validation) defining the storage, organization, update, and reference system for future chronology — Chronology Rules (Past/Present/Future/Unknown/Parallel), Timeline Structure (Era/Year/Season/Episode/Scene/Event, placeholders only), Timeline Entry Format (TML-{NNNN} convention, reusing Master System Prompt's Canon States for the Canon Level field), Timeline Categories, Continuity Rules, Retcon Rules (Founder Override Protocol only), Episode Synchronization, cross-references, future-format scaling, and maintenance. Introduces zero canon — no character, location, event, date, year, era, or episode is named anywhere. The "Parallel" classification was explicitly scoped to mean simultaneity within the single chronology, never alternate timelines, to avoid any implied conflict with the Master System Prompt's single-megacity/no-multiverse rule.`
