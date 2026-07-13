# ALIGN-006 — Policy and Wording Anchor

**Original date:** 2026-07-08  
**Current status:** `HISTORICAL_AMENDED_BY_SPLIT_SPINE_V1`  
**Primary architecture authority:** `ax4consultants-lab/ax4-systems-orchestration/docs/ALIGN-OPSDB-SPINE.md`  
**Controlled-document status:** source-material alignment note only

## Purpose

Anchor AX4 applications to controlled policy, procedure, limitations and standard wording without granting this repository runtime authority.

## Current Architecture Context

```text
OpsDB = operational/commercial records and metadata
Supabase = Hub portal auth, membership, QR and delivery records
Z: / Shared Drive = controlled file bytes
Hub = staff/client interface
Survey Buddy = field capture
Document Generator = approved-context draft renderer
Policy repository = controlled wording and methodology source material
```

The policy repository does not own or select the database, portal or file plane.

## Policy Repository Owns

- WHS/SHEQ policy source material;
- field control procedures;
- asbestos technical procedures;
- limitations wording;
- standard report wording;
- Recommended Action System source concepts;
- SHEP, SWMS and JSA source material;
- forms and register templates;
- review/approval metadata for controlled policy documents.

## Policy Repository Does Not Own

- OpsDB or Supabase runtime/schema mutation;
- A1xxx Client ID allocation;
- field-capture UI;
- Hub or Gateway runtime;
- Document Generator execution;
- QR token/session/access-log operations;
- file storage or delivery;
- invoice/closeout automation;
- Echo/MCP operational authority.

## Wording Authority Direction

Approved libraries may supply:

- limitations;
- survey methodology statements;
- no-access language;
- sample/laboratory-result wording;
- controlled recommendation/action expansions;
- permit-to-work statements;
- Safe Work Instruction base wording;
- management-plan control wording;
- client-facing compliance disclaimers.

Applications must not invent technical asbestos methodology, limitations, recommendations or compliance claims independently.

## RAS Direction

```text
recommendation_code = stable controlled code
recommendation_text = controlled expansion from approved library
report_note_override = assessor-approved override where required
```

Example families may include L/M/H general and electrical controls, dust, permit-to-work, access/no-access and removed-item codes. This note does not approve a final code set.

## Interface Direction

```text
approved wording/version reference
→ approved document context
→ Document Generator draft
→ human review
→ issued controlled document
→ controlled file package and portal delivery
```

The context must preserve the wording-library version and any assessor-approved override. The renderer must not silently substitute an uncontrolled wording source.

## Compliance Claim Guardrails

Preferred wording includes:

- samples analysed by a NATA-accredited laboratory;
- NATA laboratory pathways;
- SafeWork SA-aligned documentation;
- WHS-compliant registers and management plans where accurate;
- DIT-aligned capability where formal prequalification is not confirmed;
- controlled digital workflows with human review.

Avoid unverified claims such as AX4 being NATA accredited, DIT prequalified, WorkCover SA approved, fully automated compliance, or universal asbestos-free/cleared conclusions.

## Hard Stop

This note authorises no runtime integration, database mutation, document generation, issue, QR publication, file delivery, invoice, Echo access or real-job operation.

A runtime wording-library service requires its own controlled document/workblock, version register, approval, security and rollback process.
