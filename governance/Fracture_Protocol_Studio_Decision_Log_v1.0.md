# THE FRACTURE PROTOCOL — STUDIO DECISION LOG
### Version 1.0

**Classification:** Internal — Living Historical Record
**Status:** Structure and guidance only. **No entries have been logged yet** — this document does not invent, backfill, or reconstruct any past decision. The founder or a delegated Continuity Editor populates it going forward, and may choose to backfill historical entries separately if desired; that is a founder decision, not one made by creating this template.
**Absolute authority:** `bible/Fracture_Protocol_Master_System_Prompt_v1.2.md` for anything canon-related; `governance/Fracture_Protocol_Studio_Governance_Manual_v1.0.md` for anything process-related. This Log records decisions — it does not make them, approve them, or grant anyone authority they don't already have under those two documents.
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

*No entries yet. Add new entries below this line, in chronological order, using the Section 4 format.*

---

## Final Validation

1. **No canon introduced.** This document defines no character, faction, location, technology, power mechanic, or world fact.
2. **No decisions invented.** The log (Section 8) is empty by design — nothing here fabricates or reconstructs history that wasn't explicitly logged by the founder or a delegated party.
3. **No duplication.** This Log doesn't restate what changelogs already record (the "what") or what the Governance Manual already defines (the "how decisions get made") — it adds the one layer neither of those covers: the "why," alternatives, impact, and review cadence for decisions significant enough to warrant it.
4. **Compatible with all existing documents.** Explicitly subordinate to the Master System Prompt and Governance Manual; distinguishes itself from the Proposal Vault (pre-decision) in Section 2.
5. **Recommendation for future consideration (not implemented):** the founder may want to backfill this Log with the project's major decisions to date (the fantasy-to-sci-fi pivot, the Canon Governance System, the Founder Override Protocol, the Production Bible, the Studio Wiki rework, the Governance Manual and Index) — each already has a detailed record in its originating document's changelog and could be distilled into a Decision Log entry. Not done here per the explicit instruction not to invent past decisions; flagged as an option for the founder to trigger deliberately (Section 7).

---

*End of Studio Decision Log v1.0. This is where the studio's "why" lives — update it the same day a qualifying decision is approved (Section 6).*

---

### Changelog
`[v1.0 — 2026-07-07] Initial Studio Decision Log established: structure, Decision ID convention, entry format, status values, logging workflow, and maintenance guidance. No entries logged — the log (Section 8) starts empty by explicit instruction; backfilling historical decisions is flagged as an available future option, not performed automatically.`
