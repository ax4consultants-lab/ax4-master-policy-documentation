# Ax4 Master Policy Documentation

Controlled documentation workspace for **Ax4 Consulting Pty Ltd**, trading as **Ax4**, **Ax4 Asbestos Consultants** and **Ax4 WHS Consultants**.

This repository is the source of truth for Ax4 policy, WHS/SHEQ governance, field controls, asbestos technical procedures, forms, registers, limitations libraries and standard wording systems.

It is **not** the Atom/Ax4 agentic runtime repository. Atom, EchoForge and other agents may ingest or reference this repository, but this repository owns the policy/documentation source material.

---

## Primary Mission

Build and maintain a controlled WHS/SHEQ documentation suite suitable for South Australian WHS compliance, asbestos and hazardous materials consulting, tender submissions, field safety control, technical report defensibility, repeatable document production and future automation through Atom/EchoForge workflows.

---

## Core Rule

Policy sets commitment. The SHEQ Manual explains the system. Procedures define how work is done. SHEP, SWMS and JSA documents control site execution. Forms and registers prove it happened. Libraries standardise wording and automation logic.

---

## Repository Orientation

Every agent must start by reading:

1. `README.md`
2. `MASTER-ROADMAP.md`
3. `DOCUMENT-REGISTER.md`
4. `COMPLETION-CHECKLIST.md`
5. `AGENT-OPERATING-RULES.md`
6. `RESEARCH-BRIEF-TEMPLATE.md`
7. `changelog/CHANGELOG.md`

Then work only on the assigned document code.

---

## Completion Tracking Rule

Every document workblock must update completion tracking before handoff.

Before an agent finishes, it must:

1. create or update the assigned controlled document;
2. update `COMPLETION-CHECKLIST.md` with the current status and file path;
3. update `DOCUMENT-REGISTER.md` if the document status changes;
4. add a dated entry to `changelog/CHANGELOG.md`;
5. report assumptions, linked documents, compliance references used and open questions.

A document marked `Draft complete` is ready for human review but is not approved for operational use until signed off by the nominated approver.

---

## Repository Structure

```text
ax4-master-policy-documentation/
├── README.md
├── MASTER-ROADMAP.md
├── DOCUMENT-REGISTER.md
├── COMPLETION-CHECKLIST.md
├── AGENT-OPERATING-RULES.md
├── RESEARCH-BRIEF-TEMPLATE.md
├── docs/
│   ├── 01-corporate-policy/
│   ├── 02-system-governance/
│   ├── 03-field-control/
│   ├── 04-technical-asbestos/
│   ├── 05-forms-registers/
│   └── 06-libraries/
├── source-material/
│   ├── legacy-policy/
│   ├── shep/
│   ├── sop/
│   └── limitation-wording/
├── changelog/
└── archive/
```

---

## Core Build Count

- **Core suite:** 19 controlled documents
- **Mature suite:** 25 controlled documents

The current build target is the 19-document core suite, then expansion to the mature suite where useful.

---

## Jurisdiction

Default jurisdiction: **South Australia**.

Key references for drafting include the Work Health and Safety Act 2012 (SA), Work Health and Safety Regulations 2012 (SA), Safe Work Australia asbestos Codes of Practice, SafeWork SA guidance and relevant Australian Standards.

---

## Document Control Standard

All controlled documents must include title, document code, category, version, status, owner, approver, effective date and review date.

---

## Agent Rules Summary

Agents must work only on the assigned document code, preserve document separation, avoid overstatement, use Australian English, align with SA WHS requirements, include assumptions and open questions, update the completion checklist, update the document register where status changes and log significant document creation or updates in `changelog/CHANGELOG.md`.

---

## Source Material

Existing Ax4 source documents include the legacy Ax4 SHE Policy, SHEP, SOP1, quote/report limitation wording and Recommended Action System concepts.

These are source materials only. They are not automatically approved final documents.

---

## Current Status

Status: **controlled workspace established**.

Current document progress is tracked in:

> `COMPLETION-CHECKLIST.md`

Next build target remains:

> `POL-WHS-001 — Work Health and Safety Policy`
