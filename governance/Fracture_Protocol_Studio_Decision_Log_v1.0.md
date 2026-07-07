# THE FRACTURE PROTOCOL — STUDIO DECISION LOG
### Version 1.0

**Classification:** Internal — Living Historical Record
**Status:** Living — 2 entries logged (`DEC-0001`, `DEC-0002`), both dated 2026-07-07. This document does not invent, backfill, or reconstruct any past decision — every entry corresponds to a decision actually made and approved. The founder or a delegated Continuity Editor populates it going forward, and may choose to backfill earlier historical decisions (predating this Log's creation) separately if desired; that remains a founder decision, not one made automatically.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` for anything canon-related; `governance/Fracture_Protocol_Studio_Governance_Manual_v1.1.md` for anything process-related. This Log records decisions — it does not make them, approve them, or grant anyone authority they don't already have under those two documents.
**Companion documents:** `bible/Fracture_Protocol_Proposal_Vault_v1.0.md` (pre-decision ideas — see Section 2 for the distinction), every document's own in-file changelog (routine, line-level change history — see Section 2), `governance/Fracture_Protocol_Studio_Governance_Index_v1.0.md` (this Log will get a one-line pointer there once it has entries worth summarizing).

---

## 1. Purpose

Individual documents already record *what changed* in their own changelogs. What's missing is a single place recording *why* the studio's significant decisions were made — the reasoning, the alternatives that were considered and rejected, the actual impact, and when the decision should be revisited. This Log is that place. It exists so that two years from now, nobody has to reconstruct "why did we decide that?" from memory or from a terse one-line changelog entry.

This is a **historical record, not a governance document** — it doesn't define process (that's the Governance Manual's job) and it doesn't hold pending ideas (that's the Proposal Vault's job). It only records decisions that have already been made and approved.

---

## 2. Scope — What Belongs Here vs. Elsewhere

| Type of change | Where it's recorded |
|---|---|
| A significant creative, technical, or production decision — especially one with real alternatives that were seriously considered, or lasting structural impact | **This Log**, in full (Section 4 format) |
| A routine edit, correction, or version bump with an obvious single right answer (typo fix, cross-reference sync, stale-term correction) | The affected document's own changelog only — does not need a Decision Log entry |
| An idea that hasn't been decided on yet | `Proposal Vault` — moves here only once approved, and only if it clears the bar in the row above |
| A process/jurisdiction rule (how decisions get made, who approves what) | `Studio Governance Manual` — this Log assumes that structure, it doesn't restate it |

**Rule of thumb:** if a future contributor would reasonably ask "wait, why did we do it that way instead of the obvious alternative?", it belongs here. If the answer is self-evident from the change itself, a changelog line is enough.

---

## 3. Decision ID Convention **[LOCKED]**

- Format: `DEC-{NNNN}`, four-digit zero-padded, sequential, starting at `DEC-0001`.
- IDs are **never reused and never renumbered**, even if a decision is later reversed or superseded — the ID identifies the historical event of deciding, not the current state of the thing decided.
- A decision that later gets reversed or replaced gets a **new** Decision ID for the reversal/replacement; the original entry's Status field is updated to `Superseded` or `Reversed` and cross-references the new ID (Section 5).

---

## 4. Entry Format **[LOCKED]**

Every entry uses this exact structure:

```
### DEC-{NNNN} — [Short Decision Title]

| Field | Value |
|---|---|
| **Decision ID** | DEC-{NNNN} |
| **Date** | YYYY-MM-DD |
| **Decision Summary** | One or two sentences stating what was decided. |
| **Reason** | Why this decision was made — the problem or opportunity it addressed. |
| **Alternatives Considered** | What else was on the table, and why it wasn't chosen. Write "None seriously considered — single clear path" if genuinely true; don't pad this field. |
| **Impact** | What actually changed as a result — which documents, systems, or processes were affected. |
| **Related Documents** | Specific documents/sections affected or referenced (e.g., "Master System Prompt §12, World Bible §16"). |
| **Founder Approval** | How approval was given — an exact Founder Override Command (Master System Prompt §13) for canon decisions, or Creative Director sign-off for process decisions (Governance Manual §5). Write "Pending" if not yet confirmed. |
| **Future Review Date** | A specific date, "N/A — permanent," or a cadence (e.g., "Next Quarterly Review," Governance Manual §17). |
| **Status** | `Active` / `Superseded` / `Reversed` / `Under Review` (Section 5) |
```

---

## 5. Status Values **[LOCKED]**

| Status | Meaning |
|---|---|
| **Active** | Currently in effect; the decision stands as recorded. |
| **Superseded** | Replaced by a later decision that changed the outcome without reversing the original reasoning — cross-reference the newer Decision ID. |
| **Reversed** | Explicitly undone; no longer in effect. Cross-reference the Decision ID that reversed it, if the reversal itself was significant enough to log. |
| **Under Review** | Flagged for reconsideration (e.g., at a Monthly or Quarterly Review, Governance Manual §17) but not yet resolved either way. |

A `Superseded` or `Reversed` entry is **never deleted** — it stays in place with its Status updated, exactly like the Proposal Vault's own non-deletion rule for its entries.

---

## 6. Logging Workflow **[LOCKED]**

1. A qualifying decision (Section 2) is made and approved per the Governance Manual's Approval Responsibilities (§5).
2. The same day, an entry is added using the format in Section 4, appended to the end of Section 8 (the log itself) — never inserted out of chronological order.
3. The affected document's own changelog still gets its normal one-line entry — this Log doesn't replace that, it adds the "why" layer on top.
4. If the decision affects the Studio Wiki's indices (a new document, a jurisdiction change, a status change), those are updated the same day per the Wiki's own Maintenance Rules (§24).

---

## 7. Maintenance **[LIVING SECTION]**

- This Log is append-only going forward — new entries go at the bottom of Section 8, in chronological order by Date.
- Reviewed at every Monthly Review (Studio OS §26) for any entry whose Future Review Date has arrived — each is either reaffirmed (Status stays `Active`, a note added) or resolved into a new decision (new entry, old one marked `Superseded`/`Reversed`).
- If the founder chooses to backfill historical decisions (the sci-fi pivot, the Canon Governance System's creation, etc.), that backfill is itself a deliberate, explicit choice — not something this template performs on its own — and should be done in one clearly-dated pass so entries aren't quietly trickling in out of order.

---

## 8. Decision Log

### DEC-0001 — Resolve the Production Bible / Production OS jurisdiction overlap

| Field | Value |
|---|---|
| **Decision ID** | DEC-0001 |
| **Date** | 2026-07-07 |
| **Decision Summary** | Resolved the standing overlap between Production Bible and Production OS via Option 2, Delineate: Production Bible retains sole jurisdiction over production philosophy, studio organization, pipeline sequence/gates, folder structure, file naming, version control, asset management, risk management, and review workflow. Production OS was narrowed to department-level SOP execution detail only. |
| **Reason** | The overlap had been flagged across three separate audits (at the Production Bible's creation, in the Phase 2 continuity audit pass, and again in the Studio Architecture Audit) without resolution. The Studio Architecture Audit's Overall Score and Production Readiness Status explicitly conditioned "APPROVED WITH MINOR REVISIONS" on resolving it, and the founder approved this correction directly. |
| **Alternatives Considered** | (1) Consolidate — retire Production OS entirely and treat Production Bible as its sole successor. Rejected: Production OS's department-level SOPs (Sections 6–27, 33–48) are genuinely non-duplicative and valuable; full retirement would destroy real content to solve a problem Delineate solves without loss. (2) Leave as-is — accept the duplication indefinitely. Rejected: already flagged three times without action; a fourth flag was judged worse than a modest, low-risk structural fix. |
| **Impact** | Production OS bumped v1.0 → v2.0 (six sections retired as tombstones: Production Philosophy, Asset Management SOP, File Naming Standards, Folder Structure, Backup Strategy, Version Control — each now points to its Production Bible equivalent). Production Bible bumped v1.0 → v1.1 (Section 15 updated to record the resolution). Studio Governance Manual bumped v1.0 → v1.1 (Section 3's interim assignment marked resolved; Section 8 and Final Validation updated). Studio Wiki, Studio Governance Index, and Repository Health Guide cross-references updated accordingly. All three renamed files' cross-references were propagated repository-wide. |
| **Related Documents** | Production Bible §15, Production OS front matter and §2/28–32, Studio Governance Manual §3/§8/Final Validation, Studio Wiki §2/§6/§17/§18 |
| **Founder Approval** | Direct instruction: "Apply the two approved architecture corrections from the Studio Architecture Audit" (2026-07-07) |
| **Future Review Date** | Next Quarterly Review (Repository Health Guide §9) — confirm the delineated split is holding once Season One scripts actually exercise the pipeline |
| **Status** | Active |

### DEC-0002 — Reconcile the Studio Wiki and Studio Governance Manual status vocabularies

| Field | Value |
|---|---|
| **Decision ID** | DEC-0002 |
| **Date** | 2026-07-07 |
| **Decision Summary** | Explicitly mapped the Studio Governance Manual's Document Lifecycle states (Draft/In Review/Active/Superseded/Retired) to the Studio Wiki's completion-progress legend (✅/🔄/📋/⬬) as two complementary axes — one tracks lifecycle currency, the other tracks completion progress — rather than leaving them as two unreconciled "status" systems. |
| **Reason** | The Studio Architecture Audit identified this as a previously-unflagged finding: two different vocabularies both called "status" had coexisted since the Governance Manual's creation with no stated relationship between them. |
| **Alternatives Considered** | Retiring one vocabulary in favor of the other. Rejected: they genuinely answer different questions (is this document in force? vs. how much of it is built?) and collapsing them into one axis would lose information, not simplify anything. |
| **Impact** | Studio Governance Manual §10 gained an explicit reconciliation note and mapping table. No document's actual status field was changed — this was a clarification of meaning, not a re-classification. |
| **Related Documents** | Studio Governance Manual §10, Studio Wiki status legend (top of document) |
| **Founder Approval** | Direct instruction: "Apply the two approved architecture corrections from the Studio Architecture Audit" (2026-07-07) |
| **Future Review Date** | N/A — permanent, unless a future document introduces a third status-like vocabulary |
| **Status** | Active |

---

## Final Validation

1. **No canon introduced.** This document defines no character, faction, location, technology, power mechanic, or world fact.
2. **No decisions invented.** `DEC-0001` and `DEC-0002` correspond to decisions actually made this session in direct response to an explicit founder instruction — nothing is backfilled or reconstructed.
3. **No duplication.** This Log doesn't restate what changelogs already record (the "what") or what the Governance Manual already defines (the "how decisions get made") — it adds the one layer neither of those covers: the "why," alternatives, impact, and review cadence for decisions significant enough to warrant it.
4. **Compatible with all existing documents.** Explicitly subordinate to the Master System Prompt and Governance Manual; distinguishes itself from the Proposal Vault (pre-decision) in Section 2.
5. **Recommendation for future consideration (not implemented):** the founder may still want to backfill this Log with earlier major decisions (the fantasy-to-sci-fi pivot, the Canon Governance System, the Founder Override Protocol, the Production Bible, the Studio Wiki rework, the Governance Manual and Index) — each already has a detailed record in its originating document's changelog and could be distilled into a Decision Log entry. Not done here; flagged as an option for the founder to trigger deliberately (Section 7).

---

*End of Studio Decision Log v1.0. This is where the studio's "why" lives — update it the same day a qualifying decision is approved (Section 6).*

---

### Changelog
`[v1.0 — 2026-07-07] Initial Studio Decision Log established: structure, Decision ID convention, entry format, status values, logging workflow, and maintenance guidance. No entries logged — the log (Section 8) starts empty by explicit instruction; backfilling historical decisions is flagged as an available future option, not performed automatically.`
`[v1.0 — 2026-07-07] Logged the first two entries: DEC-0001 (resolving the Production Bible/Production OS jurisdiction overlap) and DEC-0002 (reconciling the Studio Wiki/Governance Manual status vocabularies), both approved via direct founder instruction applying the Studio Architecture Audit's two approved corrections. Structure version stays 1.0 — only the log's content (Section 8) changed, per this document's own append-only convention.`
