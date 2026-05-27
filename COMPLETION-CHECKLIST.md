# Ax4 WHS/SHEQ Documentation Completion Checklist

This checklist is the live orientation board for the controlled Ax4 WHS/SHEQ documentation suite.

Agents must update this checklist when they select a document to work on, not only when the document is completed. This prevents duplicate work and gives all live agents a clear view of what is unclaimed, claimed, in progress, complete or awaiting review.

---

## Status Options

- `Not started` — no agent has claimed the document and no controlled draft exists.
- `Selected / claimed` — an agent has selected the document and intends to work on it.
- `In progress` — drafting, research, review or revision work has started.
- `Draft complete` — controlled draft exists and is ready for human review.
- `In review` — assigned for Director, technical, legal or operational review.
- `Needs revision` — draft exists but requires correction before use.
- `Approved` — approved for operational use.
- `Later` — not required for the first controlled release but retained for maturity.

---

## Agent Selection and Completion Process

Before drafting begins, each agent must:

1. read `README.md`, `MASTER-ROADMAP.md`, `DOCUMENT-REGISTER.md`, this checklist, `AGENT-OPERATING-RULES.md`, `RESEARCH-BRIEF-TEMPLATE.md` and `changelog/CHANGELOG.md`;
2. identify the single document code they are selecting;
3. update this checklist immediately by changing that document status to `Selected / claimed`;
4. add the agent name or identifier in the `Claimed By / Notes` column where known;
5. only then begin research, drafting or editing work.

When drafting or revision work starts, update the status to `In progress`.

Before handoff, each agent must:

1. create or update the assigned controlled document;
2. update this checklist status and file path;
3. update `DOCUMENT-REGISTER.md` where document status changes;
4. add a dated entry to `changelog/CHANGELOG.md`;
5. report assumptions, linked documents, references used and open questions.

A document marked `Draft complete` is ready for human review but is not approved for operational use until signed off by the nominated approver.

---

## Phase 1 — Corporate Policy Layer

| # | Code | Document Name | Status | File | Claimed By / Notes |
|---:|---|---|---|---|---|
| 1 | POL-WHS-001 | Work Health and Safety Policy | In progress | `docs/01-corporate-policy/` | Claimed by ChatGPT policy drafting agent; controlled draft in preparation |
| 2 | POL-ENV-001 | Environmental Policy | Draft complete | `docs/01-corporate-policy/POL-ENV-001-environmental-policy.md` | Draft completed by ChatGPT policy drafting agent; pending Director review |
| 3 | POL-QUA-001 | Quality Policy | In progress | `docs/01-corporate-policy/` | Claimed by ChatGPT policy drafting agent; preparing controlled draft |
| 4 | POL-SHEQ-001 | Integrated SHEQ Policy Statement | Not started | `docs/01-corporate-policy/` |  |

## Phase 2 — System Governance Layer

| # | Code | Document Name | Status | File | Claimed By / Notes |
|---:|---|---|---|---|---|
| 5 | MAN-SHEQ-001 | SHEQ Management Manual | Not started | `docs/02-system-governance/` |  |
| 6 | PRO-DOC-001 | Document Control Procedure | Not started | `docs/02-system-governance/` |  |
| 7 | PRO-INC-001 | Incident, Hazard and Near Miss Reporting Procedure | Not started | `docs/02-system-governance/` |  |
| 8 | PRO-CON-001 | Contractor and Partner Management Procedure | Not started | `docs/02-system-governance/` |  |
| 9 | REG-TRN-001 | Training and Competency Register | Not started | `docs/02-system-governance/` |  |

## Phase 3 — Field Control Layer

| # | Code | Document Name | Status | File | Claimed By / Notes |
|---:|---|---|---|---|---|
| 10 | TMP-SHEP-001 | Site Safety, Health and Environment Plan | Source exists — needs modernisation | `docs/03-field-control/` |  |
| 11 | TMP-JSA-001 | Job Safety Analysis Template | Source exists inside SHEP — needs extraction | `docs/03-field-control/` |  |
| 12 | TMP-SWMS-001 | Safe Work Method Statement Template | Not started | `docs/03-field-control/` |  |
| 13 | FRM-EMR-001 | Emergency Response Form | Not started | `docs/03-field-control/` |  |
| 14 | FRM-IND-001 | Site Induction Record | Not started | `docs/03-field-control/` |  |

## Phase 4 — Technical Asbestos Layer

| # | Code | Document Name | Status | File | Claimed By / Notes |
|---:|---|---|---|---|---|
| 15 | SOP-ASM-001 | Asbestos Inspection, Survey and Sampling Procedure | Source exists — needs modernisation | `docs/04-technical-asbestos/` |  |
| 16 | SOP-ASM-002 | Intrusive Investigation Procedure | Not started | `docs/04-technical-asbestos/` |  |
| 17 | SOP-ASM-003 | Asbestos Register and Risk Assessment Reporting Procedure | Not started | `docs/04-technical-asbestos/` |  |
| 18 | LIB-LIM-001 | Report Limitations Library | Not started | `docs/06-libraries/` |  |
| 19 | LIB-RAS-001 | Recommended Action System | Concept exists — needs formalisation | `docs/06-libraries/` |  |

## Optional Mature Build Additions

| # | Code | Document Name | Status | File | Claimed By / Notes |
|---:|---|---|---|---|---|
| 20 | SWMS-ASM-001 | Asbestos Inspection and Sampling SWMS | Later | `docs/03-field-control/` |  |
| 21 | SWMS-HTS-001 | Working at Heights / Ladder Access SWMS | Later | `docs/03-field-control/` |  |
| 22 | SWMS-ELEC-001 | Working Near Electrical Services SWMS | Later | `docs/03-field-control/` |  |
| 23 | SWMS-CON-001 | Confined Space / Restricted Access SWMS | Later | `docs/03-field-control/` |  |
| 24 | SWMS-RESP-001 | Respiratory Protection and PPE SWMS | Later | `docs/03-field-control/` |  |
| 25 | FRM-SAMP-001 | Sample Log / Chain of Custody Form | Later | `docs/05-forms-registers/` |  |
