# THE FRACTURE PROTOCOL — REPOSITORY HEALTH GUIDE
### Version 1.0

**Classification:** Internal — Maintenance Procedure
**Status:** Process document. Introduces no canon and no production workflow.
**Positioning:** This Guide is the detailed operational layer beneath `governance/Fracture_Protocol_Studio_Governance_Manual_v1.1.md` Sections 16–18 (Audit Requirements, Maintenance Schedule, Retirement Policy). Those sections state the *policy* — that audits happen, roughly what they check, and on what cadence. This Guide states the *exact procedure* — the concrete steps, checks, and heuristics used to actually perform them. Same relationship as Production Bible to Production OS, applied to repository/documentation health instead of episode production.
**Scope boundary:** This Guide governs the health of the **repository and its documentation** — folders, files, versions, cross-references, naming, duplication, archives, and backups of documentation. It does not define production pipeline stages or SOPs (that's Production Bible/Production OS's job — see those documents directly) and it does not touch canon content (that's the Master System Prompt's job) — it only cares whether canon *documents* are structurally healthy, never what they say.

---

### How to use this document

Every check in this Guide answers one question: **"is the repository still in the state every other document assumes it's in?"** A document can be perfectly well-written and still let the repository drift — a broken cross-reference, a stale version number, a duplicated section, an orphaned file. This Guide exists to catch that drift on a schedule, before it accumulates into the kind of multi-document inconsistency that a full continuity audit (Governance Manual §16) then has to untangle all at once.

Tags used throughout: **[LOCKED]** — Founder sign-off required to change. **[LIVING SECTION]** — may evolve as these procedures are actually run and refined in practice.

---

## 1. Folder Standards **[LOCKED spine, LIVING checklist]**

**Check, don't redefine:** the authoritative folder structure lives in Studio Wiki Section 15 and Production Bible Section 4. This section is the audit against that structure, not a second copy of it.

- [ ] Every top-level folder present on disk (`bible/`, `series/`, `mythic-forge-art-bible/`, `studio-os/`, `production-os/`, `production-bible/`, `governance/`) matches what Studio Wiki Section 15 says should exist — no undocumented folder, no documented folder missing.
- [ ] No canon content (character, faction, world, story detail) exists outside `bible/` or `series/`.
- [ ] No process content exists outside `studio-os/`, `production-os/`, `production-bible/`, or `governance/`.
- [ ] No folder was created speculatively — every folder on disk has real content in it (Studio Wiki §15's rule against scaffolding).

---

## 2. Duplicate Detection **[LIVING SECTION]**

The single most common health failure in this repository so far: two documents independently covering the same ground in comparable detail. The Production Bible/Production OS overlap is the worked example — flagged across three audits before it was actually resolved (Decision Log `DEC-0001`; Governance Manual §3), which is itself the lesson: flagging alone doesn't fix a duplication candidate, only an explicit resolution does.

**Procedure:**
1. When any new document is created, list its section headers and compare them against every existing document's section headers. A near-1:1 match in topic and depth (not just a shared cross-reference) is a duplication candidate.
2. Grep for distinctive phrases from a new or changed section across the rest of the repository — an exact or near-exact match elsewhere is a strong duplication signal, not a coincidence.
3. A duplication candidate is not automatically a defect — some overlap is a legitimate summary/detail relationship (e.g., Studio Governance Index summarizing the Governance Manual). The test: does the shorter document *cite* the fuller one, or does it *restate* the same facts as new authority? The former is fine; the latter is the defect.
4. Log any confirmed duplication as an open item (Governance Manual §3 style: name it, assign an interim default, mark it provisional) rather than resolving it unilaterally — resolution is a Founder Authority decision (Governance Manual §6).

---

## 3. Broken Link Checks **[LIVING SECTION]**

- [ ] Every `path/to/file.md` reference resolves to a file that actually exists at that path.
- [ ] Every `Document Section N` citation resolves to a section that still exists in that document, under that number, meaning what it's cited as meaning.
- [ ] When a document is renamed, retitled, restructured, or renumbered, every inbound reference to its old name/numbers is found (grep the whole repository for the old identifier) and updated the same day — a restructure is not complete until every inbound reference resolves correctly (Governance Manual §14).
- [ ] Version-numbered filenames (e.g., `_v1.2.md`) are checked for orphaned old-version references the same way — a bumped filename leaves the old name behind as a dangling reference if any cross-reference wasn't updated.

**Method:** grep the repository for the document's old title, filename, and every section number it used before the change; treat every hit outside a changelog's historical context as a defect to fix.

---

## 4. Version Audits **[LIVING SECTION]**

- [ ] Every document's declared version (in its own header) matches what the Studio Wiki's Version History Index (§18) says.
- [ ] Every *other* document's citation of a given document's version (e.g., "per World Bible v1.1") matches that document's actual current version — a citation naming a stale version is a defect even if the section reference itself still resolves.
- [ ] Every changelog ends with an entry matching the document's current header version — a document whose changelog's last entry doesn't match its own title version has an unlogged change somewhere.

---

## 5. Archive Rules **[LIVING SECTION]**

**Check, don't redefine:** archival policy lives in Production Bible Section 14 and Governance Manual Section 18. This section verifies compliance.

- [ ] Every retired document is still recoverable in git history (never force-deleted).
- [ ] Every retirement is logged in the Studio Wiki's Archive Index (§14) the same day it happens.
- [ ] No cross-reference in an active document still points to a retired document as if it were current.

---

## 6. File Naming Audits **[LIVING SECTION]**

**Check, don't redefine:** naming conventions live in Production Bible Section 5 and Studio Wiki Section 16. This section verifies compliance.

- [ ] Every document filename follows its type's convention (`{Document_Name}_v{X.X}.md` for Bibles/process documents; the per-asset-type conventions in Production Bible §5 once production assets exist).
- [ ] No filename was changed after being referenced elsewhere without every reference being updated (Section 3 above).
- [ ] No two different assets/documents share a slug or filename stem in a way that could be confused for one another.

---

## 7. Documentation Reviews **[LIVING SECTION]**

- [ ] Every `[LOCKED]` / `[LIVING SECTION]` tag still accurately reflects how that section is actually being treated in practice — a section marked Living that's never been touched without Founder sign-off might actually be de facto Locked, and vice versa.
- [ ] Every document's front-matter "Companion documents" / "Related Documents" list is still accurate given what's been created since.
- [ ] Every document still correctly states its own subordination (to the Master System Prompt, or to the Governance Manual) — this drifts silently if a document is edited piecemeal over time.

---

## 8. Monthly Maintenance **[LIVING SECTION]**

Run alongside Studio OS Section 26 (Monthly Review) and Governance Manual Section 17:

- [ ] Section 3 (Broken Link Checks) and Section 4 (Version Audits) in full.
- [ ] Any Decision Log entry (`governance/Fracture_Protocol_Studio_Decision_Log_v1.0.md`) with a Future Review Date in the past window is reaffirmed or resolved.
- [ ] Any open item tracked in the Studio Wiki (§6, §24) or Governance Manual (§3) is confirmed still visible and accurately described — not silently stale.

---

## 9. Quarterly Reviews **[LIVING SECTION]**

Run alongside Governance Manual Section 16's full continuity audit cadence:

- [ ] Every section of this Guide, in full (Sections 1–7).
- [ ] A repository-wide duplicate-content sweep (Section 2), not just for newly added documents but across the whole set — drift can accumulate gradually, not just at creation time.
- [ ] Confirm the interim jurisdiction split (Governance Manual §3, Production Bible vs. Production OS) is still the founder's intended state, or escalate for a decision.

---

## 10. Annual Reviews **[LIVING SECTION]**

Run alongside Studio OS Section 1 (Vision/Mission annual revisit):

- [ ] Re-confirm the Governance Manual's Document Authority Hierarchy (§3) still fits the studio's actual document set — by this point new document types will likely exist and may need their own row.
- [ ] Re-confirm this Guide's own procedures still match how the repository has actually grown (e.g., once `/production/`, `/scripts/`, `/publishing/` folders exist for real, Section 1 above needs to expand to cover them).
- [ ] Full backup verification (Section 11) at the annual cadence at minimum, regardless of what's found at Monthly/Quarterly cadence.

---

## 11. Backup Verification **[LOCKED principle, LIVING procedure]**

Scoped to **repository and documentation** backup only — binary production-asset backup (renders, audio, source art) is Production Bible Section 14's domain; this section does not duplicate it.

- [ ] This repository's git history is intact and the remote is reachable — the canonical audit trail (Governance Manual §15) depends on both.
- [ ] No document exists only as an uncommitted working-tree change for longer than a single working session.
- [ ] Once binary production assets begin to exist, confirm (don't perform) that Production Bible Section 14's "at least two locations" rule is actually being followed — this Guide checks compliance, Production Bible owns the policy.

---

## 12. Repository Cleanup **[LIVING SECTION]**

- [ ] No orphaned file exists outside the documented folder structure (Section 1).
- [ ] No empty, speculatively-created folder exists (Studio Wiki §15's anti-scaffolding rule).
- [ ] No stale branch lingers past the merge of its pull request, absent a stated reason.
- [ ] No scratch/temporary content was accidentally committed (draft fragments, tool output, anything not meant to be a permanent part of the documentation set).

---

## 13. Automation Opportunities **[LIVING SECTION]**

Scoped to repository/documentation health checks only — production pipeline automation is Production OS Section 37's domain.

| Opportunity | Value | Status |
|---|---|---|
| Scripted cross-reference validator (Section 3) | Removes manual grepping for every rename/restructure | 📋 Candidate — not yet built |
| Scripted version-consistency checker (Section 4) | Catches stale version citations automatically | 📋 Candidate |
| CI check blocking merges that introduce a broken cross-reference | Prevents drift from ever reaching `main` | 📋 Candidate |
| Duplicate-content similarity scan across documents (Section 2) | Surfaces overlap candidates without a manual section-by-section comparison | 📋 Candidate |

**Rule:** no automation is built before its manual procedure (this Guide) has been run successfully at least once — automate a working check, not a hypothetical one (mirrors Production OS §37's identical rule).

---

## 14. Final Validation

1. **No canon introduced.** This Guide contains no character, faction, location, technology, power mechanic, or world fact.
2. **No production workflow duplication.** Every section that touches production assets (Backup Verification, Automation Opportunities) explicitly scopes itself to repository/documentation health and points to Production Bible/Production OS for the production-specific policy, rather than restating pipeline stages or SOPs.
3. **No duplication of the Governance Manual.** Sections 16–18 of that document remain the policy layer; this Guide is cited throughout as their operational detail, not a replacement.
4. **Compatible with all existing documents** — checked against Studio Wiki §14–16, §18, Production Bible §14, §5, and Production OS §31, §37; no contradictions found.
5. **Recommendation for future improvement (not implemented):** the Automation Opportunities in Section 13 are genuinely buildable once the manual procedures here have been run a few times — revisit at the first Quarterly Review after this Guide has actually been used, per its own Section 13 rule.

---

*End of Repository Health Guide v1.0. Run its checklists on the cadences in Sections 8–10 — a maintenance guide nobody runs is not actually maintaining anything.*

---

### Changelog
`[v1.0 — 2026-07-07] Initial Repository Health Guide established: 14 sections covering folder standards, duplicate detection, broken link checks, version audits, archive rules, file naming audits, documentation reviews, and monthly/quarterly/annual review cadences, plus backup verification, repository cleanup, and automation opportunities. Positioned explicitly as the operational detail layer beneath Studio Governance Manual Sections 16-18, not a competing policy. Introduces no canon and no production-workflow content — Backup Verification and Automation Opportunities both explicitly scope out production-asset concerns in favor of Production Bible/Production OS.`
`[v1.0 — 2026-07-07] Updated Section 2's Production Bible/Production OS example to reflect resolution (Decision Log DEC-0001) rather than an open item — reframed as the lesson that flagging alone doesn't resolve a duplication candidate.`
