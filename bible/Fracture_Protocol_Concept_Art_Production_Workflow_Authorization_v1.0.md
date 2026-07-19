# THE FRACTURE PROTOCOL — CONCEPT ART PRODUCTION WORKFLOW AUTHORIZATION

**Classification:** Internal — Governance Document (**Approved**)
**Status:** Compiled 2026-07-18 per "Founder Directive — Concept Art Production Workflow Authorization," continuing from Phase 6K.0 v2.1, the Concept Art Technical Standards Authorization, the Concept Art Capability Audit, and the FPP-CHAR-001 Kael Concept Art Exploration. Establishes the approved production path and validation checkpoints only. No artwork created, no asset (including FPP-CHAR-001) approved, no visual standard lowered, no canon modified.
**Absolute authority:** subordinate to Master System Prompt → Locked Canon → `Fracture_Protocol_Phase6K0_Concept_Art_Governance_v1.0.md` (v2.1) → `Fracture_Protocol_Concept_Art_Production_Capability_Audit_v1.0.md` → `Fracture_Protocol_Concept_Art_Technical_Standard_Decision_v1.0.md` → `mythic-forge-art-bible/prompt-library.md` → the BRA-0001A external-ingestion precedent (`documentation/Asset_Registry.md`, BRA-0001A entries) → this authorization.

---

## Option Evaluation

**Option A — Internal AI-assisted workflow: not currently viable.** The Concept Art Production Capability Audit directly confirmed, by tool search, that no image-generation capability exists in this environment. Selecting an "internal" workflow would authorize a process this environment cannot execute — it would not serve the directive's own purpose of establishing an *approved, working* production path.

**Option B — External production and controlled ingestion: selected.** This is not a new invention — it is the same pattern already proven in this repository: the Brand Asset line's Signature Cinematic Presentation images (BRA-0001A) were produced externally and delivered by direct upload to the branch (outside this session's chat, since this environment cannot export chat-submitted images to disk), then verified for integrity, moved via `git mv` without re-encoding, and registered only after passing verification. This is the only currently executable path capable of satisfying the Locked "semi-realistic anime cinematic hybrid" register, which no internal capability can produce.

**Option C:** no distinct third method is identified. A "hybrid" of internal exploratory work (silhouette/proportion references, which do not attempt the sanctioned register and were already produced for FPP-CHAR-001) alongside externally-produced finished art is not a separate option — it is incorporated into Option B's own workflow below as the supporting pre-visualization tier, not a substitute for it.

---

## Verification

- **Compliance with Phase 6K standards:** externally-produced art does not bypass Phase 6K.0's governance — it changes only where the pixels originate. Every asset, regardless of production source, must still trace to Concept Art Authority (§2), respect Visual Design Constraint Authority (§3), and pass Approval Authority (§4) in full.
- **Compliance with Art Bible rendering authority:** Option B is the mechanism that *enables* compliance rather than working around it — it is currently the only path capable of producing the Locked sanctioned register at all, given the confirmed absence of internal capability.
- **Asset validation process:** defined below (Validation Checkpoints).
- **Version-control process:** unchanged from the standing discipline (Phase 6A.5 Version Standard, Phase 6K.0 §6 Revision Rules) — `v{major}.{minor}`, reopen-and-append, Asset Lifecycle progression, full changelog preservation.
- **Approval workflow:** unchanged — Phase 6K.0 §4 in full (Technical Review, Alignment Audit, Founder Review, Founder Approval, Asset Registry update), applied identically regardless of internal or external origin.

---

## Documented Production Path

1. **Scope directive.** A Founder Directive (or delegated instruction) names the exact subject and specific deliverable (e.g., "Kael, Primary Outfit Turnaround, Calm state"), citing Phase 6K.0 Concept Art Authority (§2) and the relevant Production Package.
2. **Prompt assembly.** A prompt is assembled using only Locked `prompt-library.md` templates (e.g., the Kael Base Prompt Template plus the appropriate Emotion Modifier) — no invented prompt language beyond what is Locked. Any element the templates don't cover (e.g., a costume detail not present in the base template) is flagged, not improvised into the prompt.
3. **External generation.** Image generation occurs outside this session, using the assembled Locked prompt, via an external AI image-generation tool, external illustrator, or Founder-supplied source.
4. **Direct delivery.** The resulting file is delivered by direct upload to the repository branch (outside this session's chat), consistent with the BRA-0001A precedent and this environment's own confirmed inability to export chat-submitted images to disk.
5. **Ingestion pass.** A dedicated verification pass follows before any registration: confirm file validity and integrity; move into the correct Folder Structure location (`series/01-the-fracture-protocol/concept-art/<category>/`) via `git mv`, no re-encoding; run the file through every Validation Checkpoint below.
6. **Approval chain.** Full Phase 6K.0 §4 progression: Technical Review → Alignment Audit → Founder Review → Founder Approval → Asset Lifecycle status update → Asset Registry entry → Commit → Push.

---

## Validation Checkpoints

1. **File integrity.** Valid, uncorrupted image file; actual format/dimensions measured directly from the file, never assumed from a filename or request.
2. **Canon compliance.** Direct visual cross-check against every Locked citation governing the subject (Physical Production Profile, Costume Canon, Color Language/eye-glow specification, the specific Emotion Modifier used) — any deviation flagged explicitly, never silently accepted, exactly as the BRA-0001A banner's aspect-ratio mismatch was caught and disclosed rather than passed through.
3. **Forbidden Elements compliance.** Direct check against the full `forbidden-elements.md` blacklist — no flat cel-shaded/TV-anime-signature rendering, no fantasy-magic signifiers, no reskinned existing IP, no costless/infinite system effects, no forbidden real-world intrusions, no gratuitous content.
4. **Rendering register compliance.** Direct visual confirmation of "semi-realistic anime cinematic hybrid: detailed, cinematically lit, high-detail facial focus" — not assumed from the prompt text alone, since generation models can drift (per `prompt-library.md`'s own documented failure modes).
5. **Technical standard compliance.** Resolution and color space checked against the category-specific values in `Fracture_Protocol_Concept_Art_Technical_Standard_Decision_v1.0.md` (e.g., 4000×4000px sRGB for Character).
6. **No duplicate or orphaned asset.** Confirm the file does not already exist under a different name, and does not silently supersede an existing Registry entry without a proper Revision under Phase 6K.0 §6.

Failure at any checkpoint stops registration and Approval; the specific failure is flagged for Founder decision, per Phase 6K.0's own Production Conflict Resolution (§7) — never silently corrected or waved through.

---

## Founder Review & Alignment Audit

| Audit type | Result |
|---|---|
| Founder Review | PASS — Option A confirmed non-viable by direct citation to the Capability Audit; Option B confirmed viable by direct citation to an already-proven precedent (BRA-0001A) in this same repository; no unsupported third option invented. |
| Alignment Audit | PASS — no artwork created; no asset (including FPP-CHAR-001) approved; no visual standard lowered; no canon modified. Every validation checkpoint traces to an already-Locked source. |
| Regression Verification | PASS — no existing document modified. |

**Determination: PASS.** No canon contradiction, repository corruption, or governance conflict found.

---

## Founder Approval

**Approved 2026-07-18** following a clean PASS Founder Review & Alignment Audit. No blocking condition found. **Option B — External Concept Art production and controlled asset ingestion — is the authorized workflow**, with the production path and six validation checkpoints above as its binding process. FPP-CHAR-001 is not approved by this document; no actual production has begun under this workflow.

---

### Changelog
`[v1.0 — 2026-07-18] Compiled per "Founder Directive — Concept Art Production Workflow Authorization," continuing from Phase 6K.0 v2.1, the Concept Art Technical Standards Authorization, the Concept Art Capability Audit, and the FPP-CHAR-001 Kael Concept Art Exploration. Evaluated three options: Option A (internal AI-assisted) rejected as currently non-viable, per the Capability Audit's own confirmed absence of an internal image-generation tool; Option B (external production, controlled ingestion) selected, directly modeled on the already-proven BRA-0001A precedent in this repository; no distinct Option C identified, with internal silhouette/proportion exploration work folded into Option B's own supporting pre-visualization tier rather than treated as a separate path. Documented a six-step production path (scope directive, Locked-prompt assembly, external generation, direct delivery, ingestion pass, full Phase 6K.0 §4 approval chain) and six validation checkpoints (file integrity, canon compliance, Forbidden Elements compliance, rendering-register compliance, technical-standard compliance, duplicate/orphan check). No artwork created; no asset approved; no visual standard lowered; no canon modified. Status: "Approved."`
