# ALIGN-006 — Policy and Wording Anchor

Date: 2026-07-08
Status: Source-material alignment note / not an approved controlled document
Primary alignment source: `ax4consultants-lab/ax4-systems-orchestration/docs/workblocks/ALIGN-006-platform-gap-alignment-solution.md`

## Purpose

Anchor the platform gap solution to the controlled policy/documentation source material.

Apps may consume approved policy, procedure, limitations and standard wording. Apps must not invent technical asbestos methodology, limitations language, recommendation wording or compliance claims independently.

## Policy Repository Owns

```text
WHS/SHEQ policy source material
field control procedures
asbestos technical procedures
limitations wording
standard report wording
Recommended Action System / RAS source concepts
SHEP / SWMS / JSA source material
forms and register templates
review and approval metadata for controlled documents
```

## Policy Repository Does Not Own

```text
app runtime
Supabase schema mutation
field capture UI
Hub runtime
Document Generator runtime execution
QR token creation or resolution
client delivery
invoice / closeout automation
Echo / MCP write authority
```

## Wording Authority Direction

Future apps should treat approved wording libraries as upstream authority for:

```text
limitations
survey methodology statements
no-access language
sample/lab-result wording
recommended action expansions
permit-to-work statements
Safe Work Instruction base wording
management-plan control wording
client-facing compliance disclaimers
```

## RAS Alignment

Recommended Action System concepts should resolve from controlled codes to controlled wording.

Pattern:

```text
recommendation_code = stable controlled code
recommendation_text = controlled expansion from approved library
report_note_override = assessor-approved override where required
```

Example code families:

```text
L-GEN / M-GEN / H-GEN
L-ELEC / M-ELEC / H-ELEC
DUST
PTW
ACC / no-access
REM / removed item
```

This note does not approve any individual code set. Final RAS tables must be controlled separately.

## Compliance Claim Guardrails

Approved public/commercial wording should avoid overstated claims.

Preferred examples:

```text
NATA lab pathways
samples analysed by a NATA-accredited laboratory
SafeWork SA-aligned documentation
WHS-compliant asbestos registers and management plans
DIT-aligned capability where prequalification is not yet confirmed
```

Avoid unless formally verified:

```text
AX4 is NATA-accredited
DIT prequalified
WorkCover SA approved
fully automated compliance without human review
asbestos-free / cleared / no contamination exists everywhere
```

## System Interface Rule

Applications may reference this repo for approved source material, but this repo does not execute workflows.

Expected future path:

```text
approved wording library
→ Document Generator rendering context
→ draft document
→ human review
→ issued controlled document
```

## Hard Stop

If a controlled wording library is required for runtime use, create a separate controlled document/workblock and update the document register, completion checklist and changelog according to this repository's operating rules.