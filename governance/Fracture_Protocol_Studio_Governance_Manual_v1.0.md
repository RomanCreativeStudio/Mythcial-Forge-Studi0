# THE FRACTURE PROTOCOL
## Studio Governance Manual
### Version 1.0

**Classification:** Internal — Constitutional Document
**Status:** Process document. Introduces no lore, canon, characters, story content, or worldbuilding.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` — this Manual is subordinate to it in all cases and can never conflict with the Canon Governance System (Section 12) or the Founder Override Protocol (Section 13). Those remain the highest authority for canon, full stop; nothing below overrides them.
**Companion documents:** `studio-os/Studio_OS_v1.0.md` (company process), `production-os/Production_OS_v1.0.md` (department SOPs), `production-bible/Fracture_Protocol_Production_Bible_v1.0.md` (production philosophy/pipeline), `README.md` (Studio Wiki — navigation).

---

### How to use this document

Every other process document (Studio OS, Production OS, Production Bible, Studio Wiki) tells you *what to do*. This Manual tells you *which of them is right when they disagree, who gets to change any of them, and how a change actually happens*. It is deliberately thin — where a rule is already fully specified somewhere else, this Manual points to it rather than restating it. If you ever find this document repeating another document's content word-for-word, that repetition is a bug: the rule belongs in exactly one place, and this Manual should hold the pointer, not the copy.

This Manual governs **process documents only** — Studio OS, Production OS, Production Bible, and the Studio Wiki. It has no authority over canon (Master System Prompt, World Bible, Series Bible, Art Bible, Proposal Vault), which is governed exclusively by the Master System Prompt's Canon Governance System and Founder Override Protocol.

Tags used throughout: **[LOCKED]** — Founder sign-off required to change. **[LIVING SECTION]** — may evolve without a full sign-off, as long as nothing Locked is contradicted.

---

## 1. Purpose & Scope **[LOCKED]**

This Manual exists because the studio now has four process documents (Studio OS, Production OS, Production Bible, Studio Wiki) that can, and occasionally do, cover adjacent ground. Its purpose is narrow and specific:

1. Establish which process document has final say when two of them appear to overlap or disagree.
2. Define who is authorized to create, change, merge, or retire a process document — and what that authorization requires.
3. Standardize how versioning, change requests, conflicts, documentation quality, cross-references, repository practice, audits, maintenance, and retirement work identically across all four, instead of each document inventing its own variant.

**Out of scope:** anything about what the universe *is* or what happens in its story. That is exclusively the Master System Prompt's, World Bible's, Series Bible's, and Art Bible's domain, governed by Section 12 (Canon Governance System) and Section 13 (Founder Override Protocol) of the Master System Prompt. This Manual does not interpret, extend, or soften those sections in any way.

---

## 2. Governance Hierarchy **[LOCKED]**

```
Master System Prompt
  (absolute authority — Canon Governance System, Founder Override Protocol)
        │
        ▼
Studio Governance Manual  (this document)
  (constitutional authority over process documents only)
        │
        ▼
Studio OS ── Production OS ── Production Bible ── Studio Wiki
  (each authoritative within its own scope — Section 3 defines the boundaries)
        │
        ▼
Individual scripts, assets, prompts, and production output
  (implementation detail, subordinate to everything above)
```

No process document may grant itself authority over canon, and no process document may grant itself authority over another process document's scope without this Manual being updated to reflect that (Section 11, Change Request Workflow). A process document rewriting its own jurisdiction unilaterally is exactly the kind of drift this Manual exists to prevent.

---

## 3. Document Authority Hierarchy **[LOCKED spine, LIVING assignments]**

| Document | Scope of Authority |
|---|---|
| **Studio OS** | Company-level policy: vision, mission, values, brand, creative philosophy/originality framework, IP protection, studio roles, long-term roadmap. |
| **Production OS** | Department-level SOP granularity: the detailed step-by-step instructions for each pipeline stage, time estimates, troubleshooting, KPIs. |
| **Production Bible** | Production-level organization and governance integration: philosophy, studio organization/approval hierarchy, the pipeline's stage *sequence* and gates, risk management, creator review workflow, readiness/completion checklists, archiving policy. |
| **Studio Wiki** | Navigation only: where something is, who owns it, what depends on it. Authoritative on location and status; never on content. |

**Standing interim assignment (Production Bible vs. Production OS):** these two currently overlap in describing pipeline stages, folder structure, naming, version control, asset management, and QA. Until the founder resolves this (the three options remain open, tracked in Production Bible Section 15 and Studio Wiki Section 6), the interim jurisdiction is: **Production Bible governs the pipeline's stage sequence, organizational structure, risk management, and review workflow; Production OS governs the granular, department-by-department execution detail within each stage.** This is a documented default for reducing day-to-day ambiguity, not a final resolution — it does not preempt the founder's eventual choice among consolidate / delineate / leave-as-is.

A new process document added in the future gets a row here the same day it's created (Section 17, Future Expansion Rules) — it does not operate outside this table.

---

## 4. Canon vs. Process vs. Documentation **[LOCKED]**

Three, and only three, categories exist. Everything in the repository is exactly one of them:

| Category | Definition | Governed By |
|---|---|---|
| **Canon** | What the universe is and what happens in it — characters, factions, world structure, power systems, story, visual law | Master System Prompt Sections 12–13 exclusively |
| **Process** | How the studio and its production pipeline operate | This Manual, plus Studio OS / Production OS / Production Bible within their Section 3 scopes |
| **Documentation (navigation)** | Where things are and what state they're in | Studio Wiki exclusively |

**Rule:** a Process document may never contain Canon (Production Bible and Production OS both use neutral placeholders instead of named canon elements for exactly this reason). A Documentation (navigation) document may never contain Canon or restate Process rules in detail — it points to them. Confusing these categories in either direction is a Drift Detection-adjacent event and should be corrected the same way any other documentation bug is corrected: flagged and fixed, not left standing.

---

## 5. Approval Responsibilities **[LOCKED]**

| Decision Type | Who Approves |
|---|---|
| Canon (any kind, per Master System Prompt Section 12, Rule 4's Locked Categories) | Founder, via the Founder Override Protocol (Master System Prompt Section 13) — no exceptions |
| A new process document, or a change to an existing one's scope (Section 3) | Founder |
| A Locked section within an existing process document | Founder |
| A Living section within an existing process document | Creative Director (currently the Founder) or a delegated department lead once roles are filled (Production Bible Section 2) |
| Routine production sign-off (a stage-gate approval that doesn't touch canon or process scope) | Per Production Bible Section 11 (Creator Review Workflow) — does not require this Manual's involvement |

This table does not create any new approval authority — it collects, in one place, who already holds each kind of approval per the documents that actually define it, so a contributor never has to guess.

---

## 6. Founder Authority **[LOCKED]**

The Founder is the constitutional root of this entire governance structure. The Founder, and only the Founder:

- Holds ultimate authority over canon (Master System Prompt Section 12, Rule 1) — unaffected by anything in this Manual.
- May create, merge, retire, or reassign the scope of any process document (Section 3).
- May amend this Manual itself (Section 19, Future Expansion Rules — this document's own Locked sections require the same sign-off as any other).
- Is the only party who can resolve a standing interim assignment (Section 3) into a permanent one.

Founder authority is not delegable for canon decisions. It is delegable for process decisions once the studio roles map (Studio OS Section 29, Production Bible Section 2) is actually filled — Section 7 below defines what that delegation looks like once it happens.

---

## 7. Creative Director Authority **[LOCKED]**

The Creative Director is a role, not necessarily a person permanently synonymous with the Founder — today they are the same individual, but this Manual treats them as conceptually distinct so the studio can scale without a rewrite.

The Creative Director:
- Holds day-to-day creative and canon-facing approval, per Master System Prompt Section 12, Rule 1 and Production Bible Section 2.
- Reviews and approves Living-section process changes (Section 5 above) without requiring a Founder Override Command, since these are process, not canon, decisions.
- Cannot independently approve a canon change, a new process document, or a Locked-section process change — those remain Founder Authority (Section 6) regardless of who holds the Creative Director title.

If the Founder ever delegates the Creative Director role to someone else, that delegation is itself a Founder Authority decision and must be recorded in this Manual's changelog the same day it happens.

---

## 8. AI Authority Limits **[LOCKED]**

Any AI system (including this one) operating on this repository, regardless of which role it is framed as holding for a given task (Creative Director, Canon Guardian, Production Manager, Pipeline Architect, Continuity Editor — Master System Prompt Section 1), is bound by the same limits in every case:

- **No independent canon authority**, ever (Master System Prompt Section 12, Rule 1). An AI may draft, recommend, and log Proposals — it may never implement a structural canon change without an explicit Founder Override Command (Section 13).
- **No independent authority to retire, merge, or silently resolve overlapping process documents.** When two process documents overlap (Section 3's standing interim assignment is the current live example), an AI flags it as an open item and proposes options — it does not pick one unilaterally.
- **No authority to skip Drift Detection** (Master System Prompt Section 12, Rule 3) for the sake of production convenience, however minor the change seems.
- **No authority to modify this Manual's Locked sections**, or any other process document's Locked sections, without recorded Founder sign-off.
- **Full authority to perform housekeeping**: fixing broken cross-references, correcting stale terminology, syncing version numbers, and running audits (Section 16) — these are maintenance, not governance, decisions, and don't require a Founder Override Command.

An AI is a steward operating within this structure, never a party to it — it holds no vote in Section 3's document-authority table and cannot amend that table.

---

## 9. Version Control Policy **[LOCKED]**

All process documents use the studio-wide **v{major}.{minor}** convention (Studio OS Section 30; Production Bible Section 6 defines the full operational detail — this Manual states the policy, not the mechanics):

- **Major bump** — a Locked-section rewrite or a structural change, requiring Founder sign-off.
- **Minor bump** — an additive or corrective change within the existing structure.

Every version bump requires a same-day changelog entry on the changed document (never batched, never backfilled). This policy applies uniformly across Studio OS, Production OS, Production Bible, and Studio Wiki — no process document may adopt a different versioning scheme for itself.

---

## 10. Document Lifecycle **[LOCKED]**

Every process document (not individual assets — see Production Bible Section 6 for asset-level status, which this policy does not duplicate) moves through the same five states:

| Status | Meaning |
|---|---|
| Draft | Being written, not yet in force |
| In Review | Submitted for Founder review |
| Active | Approved and currently governing its scope |
| Superseded | Replaced by a newer version of itself; prior version retained per Section 18 (Retirement Policy) |
| Retired | No longer governs anything; retained, never deleted |

A process document cannot skip from Draft directly to Active — Review is mandatory, even for a document the Founder is confident about, so there is always a recorded checkpoint.

---

## 11. Change Request Workflow **[LOCKED]**

For a change to any process document's **content** (not canon — see Master System Prompt Section 13 for that): 

1. Identify what's changing and which document(s) it affects.
2. Classify it: Living-section update (Creative Director can approve, Section 5) or Locked-section/structural change (Founder approval required).
3. If the change affects another process document's stated scope (Section 3), that overlap must be named explicitly before proceeding — silently expanding one document's scope into another's is not permitted.
4. Make the change, version-bump it (Section 9), and log the changelog entry the same day.
5. Update any cross-references this change affects (Section 14).

This is deliberately the process-document mirror of the Master System Prompt's Canon Update Workflow (Section 13) — same shape, scoped to process instead of canon, so a contributor only has to learn one pattern for "how does a change actually happen here."

---

## 12. Conflict Resolution **[LOCKED]**

| Conflict | Resolution |
|---|---|
| Master System Prompt vs. anything | Master System Prompt always wins — this is not this Manual's call to make or unmake |
| This Manual vs. Studio OS / Production OS / Production Bible / Studio Wiki | This Manual wins on jurisdiction questions (Section 3); the other document wins on its own scoped content |
| Two process documents disagree within their respective scopes (Section 3) | Treat it as a documentation bug — flag it, do not guess which is "more right," and route it through Section 11 (Change Request Workflow) to fix the document that's actually wrong |
| A process document vs. a canon question | The process document has no standing here at all; defer entirely to the Master System Prompt |

---

## 13. Documentation Standards **[LOCKED]**

Every process document must:
- State its own scope and its subordination to this Manual and the Master System Prompt in its front matter (all four currently do).
- Tag every section `[LOCKED]` or `[LIVING SECTION]` — an untagged section is treated as Locked by default until tagged.
- Use neutral placeholders instead of named canon elements wherever an example is needed (Production Bible's existing convention) — a process document is never the place canon gets introduced, even accidentally, via example text.
- End with a changelog block, append-only, one line per change, past tense, naming the section(s) affected.

---

## 14. Cross-Reference Rules **[LOCKED]**

- Every cross-reference to another document names the document and the specific section (e.g., "Production Bible Section 7"), never just the document, so a reader doesn't have to search.
- When a document is renamed, retitled, or restructured (as happened when the Knowledge Base became the Studio Wiki), **every cross-reference to its old section numbers elsewhere in the repository must be updated the same day** — a rename or restructure is not complete until every inbound reference resolves correctly.
- A cross-reference is checked for validity as part of any audit (Section 16) — a citation to a section that no longer exists, or no longer means what it used to, is a defect with the same severity as a broken canon reference.

---

## 15. Repository Governance **[LOCKED]**

- `main` holds published, current documentation. Substantial revisions (new document versions, structural process changes, canon changes) are developed on a feature branch and merged via pull request so changes are reviewable before they take effect.
- Nothing in `/bible/` (canon) or the process-document folders (`studio-os/`, `production-os/`, `production-bible/`, `governance/`) is ever force-deleted; retirement follows Section 18.
- This repository's git history is the canonical audit trail for every document's authorship and change history — commit messages should be descriptive enough to serve as a secondary changelog on their own (Studio OS Section 30).

---

## 16. Audit Requirements **[LOCKED cadence, LIVING checklist]**

A **continuity audit** must be performed:
- Before any milestone is declared complete (as was done for Phase 2 and should be done again before any future phase-completion claim).
- After any structural rewrite of a process document (as happened with the Studio Wiki rework).
- At minimum once per quarter once the studio is in active production, even absent a specific trigger.

**Minimum audit checklist:**
- [ ] No Proposal Vault entry has leaked into any canon document.
- [ ] Every declared version number matches the document's own header.
- [ ] No Locked-rule contradiction or duplicate rule set exists across canon or process documents.
- [ ] Every cross-reference (Section 14) resolves to a section that actually exists and means what it's cited as meaning.
- [ ] No stale terminology from a retired canon era survives anywhere outside a changelog's historical context.
- [ ] Every open item previously flagged (Section 3's standing interim assignment, or any other) is still visible somewhere, not silently dropped.

An audit's findings are reported, not silently fixed for anything Locked or anything touching canon — cosmetic/process fixes (broken cross-references, stale counts) may be corrected directly as housekeeping (Section 8).

---

## 17. Maintenance Schedule **[LIVING SECTION]**

| Cadence | Activity | Owner |
|---|---|---|
| Same day as any process document change | Update Studio Wiki entries and any affected cross-references | Whoever makes the change |
| Weekly (once production is active) | Sprint check-in per Studio OS Section 25 | Production Manager |
| Monthly | Review process per Studio OS Section 26, including a check of this Manual's Section 3 assignments for drift | Founder |
| Quarterly | Full continuity audit (Section 16) | Founder or delegated Continuity Editor |
| Annually | Revisit Studio OS Section 1's Vision/Mission and this Manual's Document Authority Hierarchy (Section 3) for continued fit | Founder |

---

## 18. Retirement Policy **[LOCKED]**

A process document (or a section of one) is retired, never deleted, following the same principle as canon retirement (Studio Wiki Section 14, Archive Index):

1. Mark it Retired (Section 10) with a one-line reason and the date.
2. Preserve it in git history — it remains fully recoverable.
3. Update every cross-reference that pointed to it (Section 14) to point at its successor, or remove the reference if there is none.
4. Log the retirement in the retiring document's own changelog and in the Studio Wiki's Archive Index the same day.

Retiring a process document is a Founder Authority decision (Section 6) — an AI may recommend retirement (as has been done for the Production Bible/Production OS overlap) but may never execute it unilaterally (Section 8).

---

## 19. Future Expansion Rules **[LOCKED]**

- A new process document requires: a stated scope that doesn't already belong to an existing document (Section 3), Founder approval to create it, and same-day entries in this Manual's Section 3 table and the Studio Wiki's indices.
- This Manual itself may only be amended by the Founder; an AI may draft a proposed amendment but the amendment is not in force until Founder sign-off is recorded in the changelog.
- Growth in process documentation should never outpace this Manual's ability to state, in one table (Section 3), which document governs what — if a new document can't be cleanly slotted into that table, that's a signal to reconsider whether it should exist as written, not to add it and sort out jurisdiction later.

---

## 20. Final Validation

1. **No canon introduced.** This Manual defines no character, faction, location, technology, power mechanic, or world fact.
2. **No conflict with the Master System Prompt, Canon Governance System, or Founder Override Protocol.** Every section that touches canon authority (Sections 4–8) explicitly defers to Master System Prompt Sections 12–13 rather than restating or reinterpreting them; this Manual's own authority is scoped exclusively to process documents (Section 1).
3. **No duplicated content.** Where a rule already exists in full elsewhere (versioning mechanics in Production Bible Section 6, review stages in Production Bible Section 11, branching workflow in Studio Wiki Section 24), this Manual points to it rather than repeating it.
4. **Compatibility confirmed** with Studio OS v1.0, Production OS v1.0, Production Bible v1.0, and Studio Wiki v3.1 — each was checked against Section 3's scope assignments and none contradicts them.
5. **Standing open item surfaced, not resolved.** The Production Bible/Production OS overlap (Section 3) is formally documented with an interim jurisdiction split, explicitly marked as provisional — this Manual does not make the founder's consolidate/delineate/leave-as-is decision for them.
6. **Recommendation for future improvement (not implemented):** once studio roles beyond Founder are filled, revisit Sections 6–7 to define the actual delegation mechanics (how a non-Founder Creative Director is appointed, what if anything requires a Founder Override Command versus ordinary sign-off at that point) — today those sections assume a single individual and are simpler than they will eventually need to be.

---

*End of Studio Governance Manual v1.0. This is the constitution of the studio's operating system — every process document answers to it on jurisdiction, and it answers to the Master System Prompt on everything else.*

---

### Changelog
`[v1.0 — 2026-07-07] Initial Studio Governance Manual established: 20 sections covering purpose/scope, governance and document authority hierarchies, canon/process/documentation classification, approval responsibilities, Founder/Creative Director/AI authority limits, version control policy, document lifecycle, change request workflow, conflict resolution, documentation standards, cross-reference rules, repository governance, audit requirements, maintenance schedule, retirement policy, and future expansion rules. Introduces no canon. Formally documents (as a provisional interim assignment, not a resolution) the standing Production Bible/Production OS scope overlap first flagged at the Production Bible's creation — Founder decision remains open per Production Bible Section 15 and Studio Wiki Section 6.`
