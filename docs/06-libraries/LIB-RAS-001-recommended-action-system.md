# LIB-RAS-001 — Recommended Action System

## Document Control

| Field | Detail |
|---|---|
| Document Code | LIB-RAS-001 |
| Document Title | Recommended Action System |
| Category | Technical Library |
| Version | 1.0 |
| Status | Draft complete — pending Director review |
| Owner | Ax4 Consulting Pty Ltd |
| Approver | Director |
| Effective Date | To be inserted on approval |
| Review Date | To be inserted on approval |

## Document History

| Version | Date | Description | Author / Reviewer |
|---|---|---|---|
| 1.0 | 2026-05-27 | Initial controlled draft prepared for review | ChatGPT policy drafting agent |

---

## 1. Purpose

This Recommended Action System provides controlled standard wording for asbestos register entries, asbestos management plans and related Ax4 reporting outputs.

The purpose of this library is to:

- improve consistency across Ax4 asbestos and hazardous materials reports;
- support legally defensible and practical recommendations;
- reduce variation between consultants and reviewers;
- provide controlled wording for common material, condition, access and work-context scenarios;
- support future report automation through Ax4, Atom and EchoForge workflows.

This library is a wording and decision-support tool. It does not replace consultant judgement, agreed scope, site-specific risk assessment, legislative requirements, client duty-holder obligations or specialist advice where required.

---

## 2. Scope

This library applies to recommended action wording used in:

- asbestos registers;
- asbestos register reviews;
- asbestos management plans;
- asbestos register and risk assessment reports;
- pre-refurbishment and pre-demolition advice where register-style recommendations are required;
- automation-ready report generation systems controlled by Ax4.

This library may also be adapted for hazardous materials reporting, but asbestos-specific wording must not be used for non-asbestos hazards without review.

---

## 3. Use Rules

The action code selected must reflect the actual inspection evidence, agreed scope and risk context.

Users must consider:

- material type;
- confirmed, presumed or suspected status;
- condition;
- friability;
- accessibility;
- likelihood of disturbance;
- current occupancy or use;
- planned maintenance, refurbishment or demolition works;
- whether sampling was undertaken;
- whether removal, repair, isolation, signage or further investigation is required.

Where the action code does not adequately describe the site condition, the consultant must add a site-specific note or escalate for technical review.

Ax4 must not use standard wording in a way that implies:

- a site is asbestos-free;
- all asbestos has been identified;
- concealed materials have been inspected where they have not;
- sampling was undertaken where it was not;
- removal or remediation has occurred without evidence;
- Ax4 has assumed the client or workplace duty holder's legal responsibilities.

---

## 4. Code Structure

Recommended action codes use the following format:

```text
[RISK]-[CATEGORY]-[ACTION]
```

Example:

```text
M-GEN-01
```

This means:

- `M` = Medium risk / planned action;
- `GEN` = General asbestos-containing material category;
- `01` = standard action wording number.

---

## 5. Risk Levels

| Code | Risk Level | General Meaning | Typical Priority |
|---|---|---|---|
| L | Low | Manage in place under existing controls where material is stable and unlikely to be disturbed | Long-term / routine review |
| M | Medium | Manage in place with planned action, further investigation or removal during maintenance/refurbishment | Planned action |
| H | High | Immediate restriction, make-safe, removal, decontamination or specialist action required | Immediate or urgent action |
| R | Record / Administrative | Item removed, action completed, removal to be confirmed or register to be updated | Administrative close-out or verification |

Risk level must be based on the specific report's risk assessment method and evidence. The code does not replace the formal risk rating in the register.

---

## 6. Categories

| Category | Meaning | Typical Use |
|---|---|---|
| GEN | General ACM | Bonded sheet, board, tiles, lining, general confirmed or presumed ACM |
| ELEC | Electrical | Switchboards, electrical backing panels, meter panels, electrical risers or electrical plant areas |
| MAINT | Maintenance | Materials requiring planned maintenance replacement or repair |
| PLANT | Plant / Equipment | Boilers, plant rooms, mechanical equipment, gaskets, rope seals, flanges and machinery |
| DUST | Dust / Debris | Asbestos-containing or suspected contaminated dust/debris |
| GASK | Gaskets / Rope Seals | Flange gaskets, boiler seals, plant gaskets, rope seals |
| SEAL | Sealants / Mastics | Sealants, mastics, adhesives and similar materials |
| ACC | Access / No Access | No access, limited access, restricted areas or verification required |
| PTW | Permit to Work | Work cannot proceed without permit, isolation, removal or clearance control |
| REM | Removal / Completed | Removed items, completed action, removal to be verified or register updated |

---

## 7. Priority Layer

Where helpful for client communication, action codes may be mapped to a priority layer.

| Priority | Meaning | Typical Timing |
|---|---|---|
| P1 | Immediate / urgent | Restrict access, make safe, remove, decontaminate or obtain specialist control before access or work proceeds |
| P2 | Planned action | Manage in place until scheduled works, maintenance cycle, shutdown or planned removal |
| P3 | Routine management | Manage in place, label, inspect during routine review and avoid disturbance |
| P4 | Administrative verification | Confirm removal, update register or obtain supporting records |

The priority layer is optional unless required by a report template or client scope.

---

## 8. Standard Output Format

Where a code expands into report text, the preferred structure is:

```text
Recommended Action:
[Primary action sentence]

Management:
[Control / monitoring requirement]

Trigger:
[Event that requires escalation or action]

Notes:
[Optional site-specific context]
```

For register tables with limited space, the short action text may be used. For management plans or detailed reports, the full expanded wording should be used.

---

## 9. Low-Risk Action Codes

### L-GEN-01 — Manage in Place

**Short action:** Maintain in situ under the asbestos management plan. Label where practicable. Avoid disturbance. Inspect during routine review.

**Recommended Action:**

Maintain the material in situ under the asbestos management plan.

**Management:**

The material should remain labelled where practicable, protected from disturbance and inspected during routine register review.

**Trigger:**

Review before maintenance, refurbishment, demolition, intrusive access or any work that may disturb the material.

---

### L-GEN-02 — Sample Required / Treat as Presumed

**Short action:** Sample to confirm where required. Treat as presumed asbestos-containing material until confirmed otherwise.

**Recommended Action:**

Arrange sampling and laboratory analysis if confirmation is required for management, maintenance, refurbishment or demolition planning.

**Management:**

Until analytical confirmation is available, treat the material as presumed asbestos-containing material and avoid disturbance.

**Trigger:**

Confirmation is required before disturbance or where the client requires material status to be verified.

---

### L-ACC-01 — Confirm Presence Prior to Works

**Short action:** Confirm presence and extent before works. Treat as asbestos-containing material if not confirmed.

**Recommended Action:**

Confirm the presence, extent and condition of the material before relevant works proceed.

**Management:**

Where confirmation cannot be obtained, manage the material as presumed asbestos-containing material.

**Trigger:**

Further investigation is required before disturbance, access opening, refurbishment, demolition or service works in the relevant area.

---

### L-ELEC-01 — Electrical Item, Do Not Disturb

**Short action:** Do not disturb during normal operation. Remove or make safe before electrical upgrade works.

**Recommended Action:**

Manage the material in situ and do not disturb it during normal operation.

**Management:**

Access to electrical equipment should be controlled and works should be undertaken only by competent persons using suitable controls.

**Trigger:**

Removal, isolation or further assessment is required before electrical upgrade, replacement, drilling, cutting or disturbance.

---

## 10. Medium-Risk Action Codes

### M-GEN-01 — Planned Removal During Works

**Short action:** Manage in place and label. Remove during planned maintenance, refurbishment or demolition works.

**Recommended Action:**

Manage the material in situ until planned works provide an appropriate opportunity for removal or replacement.

**Management:**

Maintain labelling where practicable, prevent disturbance and include the material in maintenance or refurbishment planning.

**Trigger:**

Remove before or during works that may disturb the material.

---

### M-MAINT-01 — Programmed Removal / Replacement

**Short action:** Remove and replace during the next suitable maintenance cycle.

**Recommended Action:**

Program removal or replacement during the next suitable maintenance cycle.

**Management:**

The material may remain in place if stable and not subject to disturbance, provided it is managed under the asbestos management plan.

**Trigger:**

Action is required when the item is accessed, repaired, upgraded, replaced or otherwise disturbed.

---

### M-GASK-01 — Gasket / Rope Seal, Treat as ACM

**Short action:** Treat as asbestos-containing unless confirmed otherwise. Replace during maintenance or shutdown.

**Recommended Action:**

Treat the gasket, rope seal or similar plant material as asbestos-containing unless confirmed otherwise by suitable evidence.

**Management:**

Avoid disturbance during normal operation and include the item in plant maintenance planning.

**Trigger:**

Remove or replace during maintenance, shutdown, dismantling, repair or equipment upgrade.

---

### M-SEAL-01 — Sealant / Mastic, Programmed Replacement

**Short action:** Maintain in place. Replace during programmed works if disturbance is likely.

**Recommended Action:**

Maintain the sealant or mastic in place where stable and unlikely to be disturbed.

**Management:**

Do not sand, grind, scrape, cut or disturb the material without suitable assessment and controls.

**Trigger:**

Further assessment or removal is required before works that may disturb the material.

---

### M-PLANT-01 — No Access to Plant / Internal Area

**Short action:** No access gained. Inspect during next shutdown or access opportunity. Treat as asbestos-containing until confirmed.

**Recommended Action:**

Inspect the inaccessible plant, equipment or internal area during the next shutdown or suitable access opportunity.

**Management:**

Until inspected or confirmed otherwise, treat relevant hidden materials as presumed asbestos-containing material.

**Trigger:**

Further investigation is required before dismantling, maintenance, service works, refurbishment or demolition.

---

### M-ELEC-01 — Electrical Upgrade Trigger

**Short action:** Manage in situ. Remove or make safe during electrical upgrade or replacement.

**Recommended Action:**

Manage the electrical-associated material in situ until electrical upgrade, replacement or disturbance is planned.

**Management:**

Access and disturbance should be controlled. Electrical works must be planned with asbestos risk considered before work begins.

**Trigger:**

Removal, isolation or specialist assessment is required before drilling, cutting, upgrade, replacement or disturbance.

---

## 11. High-Risk Action Codes

### H-GEN-01 — Restrict Access and Remove ASAP

**Short action:** Restrict access. Arrange licensed removal as soon as reasonably practicable.

**Recommended Action:**

Restrict access to the affected material or area and arrange removal or remediation by a competent licensed asbestos removalist where required.

**Management:**

Do not disturb the material. Implement interim controls to prevent access, contact, damage or fibre release.

**Trigger:**

Urgent action is required where the material is damaged, deteriorated, friable, unstable or likely to be disturbed.

---

### H-DUST-01 — Dust / Debris, Restrict and Decontaminate

**Short action:** Restrict access immediately. Do not disturb. Licensed removal and decontamination required.

**Recommended Action:**

Restrict access immediately and do not disturb asbestos-containing or suspected asbestos-contaminated dust or debris.

**Management:**

Arrange assessment, removal and decontamination using suitably competent persons and licensed asbestos removal controls where required.

**Trigger:**

Access or works must not proceed until the area has been made safe and clearance or verification has been completed where required.

---

### H-PTW-01 — Permit / Isolation Required Before Works

**Short action:** Permit to work required. Isolate, remove or make safe before works proceed.

**Recommended Action:**

Do not commence works that may disturb the material until a suitable permit, isolation, removal or make-safe process has been completed.

**Management:**

Coordinate the work with the client, relevant duty holder, contractors and licensed or competent specialists as required.

**Trigger:**

Action is required before maintenance, service, refurbishment, demolition, intrusive access or contractor works.

---

### H-PTW-02 — Decontamination and Clearance Required

**Short action:** Restrict access. Decontaminate before works. Clearance or verification required before re-entry.

**Recommended Action:**

Restrict access and arrange decontamination before any further works or uncontrolled access.

**Management:**

Use appropriate specialist controls and obtain clearance or verification documentation where required by the scope, risk or legal requirements.

**Trigger:**

No access or works should proceed until the area is confirmed suitable for re-entry or further work.

---

### H-ELEC-01 — Electrical Item, High-Risk Disturbance

**Short action:** Restrict access. Remove or make safe before any electrical works.

**Recommended Action:**

Restrict access to the affected electrical item or area until asbestos risk has been controlled.

**Management:**

Electrical works must not disturb the material unless planned and controlled by competent persons using suitable asbestos and electrical safety controls.

**Trigger:**

Removal, isolation, make-safe or specialist assessment is required before electrical access, upgrade, replacement, drilling, cutting or disturbance.

---

## 12. Removal / Administrative Codes

### R-REM-01 — Item Removed, Update Register

**Short action:** Item removed. Update register with removal details and supporting documentation.

**Recommended Action:**

Update the asbestos register to record the item as removed where suitable supporting evidence is available.

**Management:**

Retain removal documentation, clearance documentation, contractor details, dates and any relevant licence or certificate information in the project file.

**Trigger:**

Register update should occur after verified removal or receipt of suitable records.

**Suggested register note:**

```text
Item removed ([Month Year]) by [Contractor], Licence No. [insert where applicable]. Supporting removal / clearance documentation retained where provided.
```

---

### R-REM-02 — Confirm Removal or Locate Item

**Short action:** Confirm removal or locate item. Update register accordingly.

**Recommended Action:**

Confirm whether the item has been removed, remains in place or was unable to be located.

**Management:**

Review previous register information, client records, removal documents, site observations and photographs where available.

**Trigger:**

Register update is required once the item status has been confirmed.

---

## 13. Review Timing Guidance

Recommended review timing must align with the asbestos management plan, applicable legal requirements, risk rating and client circumstances.

General guidance:

| Risk / Priority | Review or Action Timing |
|---|---|
| High / P1 | Immediate restriction, make-safe, removal, decontamination or specialist action as soon as reasonably practicable |
| Medium / P2 | Planned action before disturbance, during maintenance, shutdown, refurbishment or programmed works |
| Low / P3 | Routine review as part of asbestos register / management plan review cycle |
| Record / P4 | Update register after verification, removal documentation or status confirmation |

Where material condition deteriorates or site use changes, the action timing must be reviewed.

---

## 14. Removal and Remediation Wording Rules

Removal and remediation wording must be controlled and must not overstate Ax4's role.

Use wording such as:

- arrange removal by a licensed asbestos removalist where required;
- remove before disturbance;
- decontaminate using competent persons and appropriate controls;
- obtain clearance or verification documentation where required;
- update the register after verified removal.

Avoid wording that implies:

- Ax4 will perform licensed removal unless specifically engaged and authorised to do so;
- removal has occurred without evidence;
- clearance has occurred without clearance documentation;
- the client has no further duty once a report is issued.

---

## 15. Automation Mapping Logic

The following decision logic may be used to support report automation. It must be treated as decision support only and must allow consultant override.

### 15.1 Input Variables

Recommended minimum input variables:

- material type;
- ACM status: confirmed, presumed, suspected, no access or removed;
- condition: good, fair, poor, damaged or debris;
- friability: bonded, friable, unknown;
- accessibility: accessible, limited access, no access;
- disturbance risk: low, medium, high;
- work context: normal management, maintenance, refurbishment, demolition, shutdown or emergency;
- sampling status: sampled, not sampled, sample not practicable, sample declined or not required by scope;
- location type: general, electrical, plant/equipment, dust/debris, sealant, gasket/rope seal, access limitation.

### 15.2 Suggested Rule Order

Automation should apply rules in the following precedence order:

1. Removed / administrative status;
2. Dust, debris or contamination;
3. Friable or poor-condition material;
4. Planned works or disturbance context;
5. No access / unknown status;
6. Electrical or plant-specific risks;
7. Bonded material in good condition with low disturbance risk;
8. Default to technical review where no rule fits.

### 15.3 Example Rules

| Rule | Suggested Code |
|---|---|
| Item confirmed removed with supporting documentation | R-REM-01 |
| Item not located or removal uncertain | R-REM-02 |
| Asbestos-containing or suspected contaminated dust/debris | H-DUST-01 |
| Friable ACM in poor condition or unstable material | H-GEN-01 |
| Any ACM likely to be disturbed by imminent works | H-PTW-01 or H-PTW-02 |
| Bonded ACM in good condition with low disturbance risk | L-GEN-01 |
| Unknown/suspected material requiring confirmation | L-GEN-02 |
| No access to plant or internal equipment | M-PLANT-01 |
| Electrical board or electrical-associated ACM, stable/no works | L-ELEC-01 |
| Electrical board or electrical-associated ACM with planned works | M-ELEC-01 or H-ELEC-01 |
| Gasket, rope seal or plant seal to be replaced during maintenance | M-GASK-01 |
| Sealant or mastic to be disturbed during works | M-SEAL-01 |

### 15.4 JSON-Ready Example

```json
{
  "action_code": "H-DUST-01",
  "risk_level": "H",
  "category": "DUST",
  "priority": "P1",
  "short_action": "Restrict access immediately. Do not disturb. Licensed removal and decontamination required.",
  "recommended_action": "Restrict access immediately and do not disturb asbestos-containing or suspected asbestos-contaminated dust or debris.",
  "management": "Arrange assessment, removal and decontamination using suitably competent persons and licensed asbestos removal controls where required.",
  "trigger": "Access or works must not proceed until the area has been made safe and clearance or verification has been completed where required."
}
```

---

## 16. Quality Control Rules

Before a recommended action is issued, the report preparer or reviewer should confirm:

- the code matches the risk rating and material condition;
- confirmed ACM is distinguished from suspected or presumed ACM;
- no-access items are clearly identified;
- removal recommendations are supported by scope and risk;
- sampling language matches what occurred;
- client duty-holder responsibilities are not transferred to Ax4;
- action wording is consistent across the register and management plan;
- urgent risks are clearly escalated;
- limitations are included where relevant.

---

## 17. Approval and Change Control

This library is controlled wording.

Changes to codes, wording, risk logic or automation mapping must be reviewed before use because changes may affect report consistency, legal defensibility and automated output.

New codes may be added where recurring site conditions are not adequately covered by this version. New codes should follow the same format, include short and expanded wording, and be recorded in the document history.

---

## Assumptions

- This library supports asbestos register and management plan wording and does not replace site-specific risk assessment or consultant judgement.
- The listed codes are a controlled starting set and may need expansion after field testing.
- Removal, remediation, air monitoring and clearance wording may require review by licensed or competent specialists depending on scope.
- Automation rules must allow consultant override.

## Required Linked Documents / Forms

- SOP-ASM-003 — Asbestos Register and Risk Assessment Reporting Procedure
- LIB-LIM-001 — Report Limitations Library
- PRO-DOC-001 — Document Control Procedure
- MAN-SHEQ-001 — SHEQ Management Manual
- TMP-SHEP-001 — Site Safety, Health and Environment Plan
- TMP-JSA-001 — Job Safety Analysis Template
- FRM-SAMP-001 — Sample Log / Chain of Custody Form, when developed

## Compliance References Used

- Work Health and Safety Act 2012 (SA)
- Work Health and Safety Regulations 2012 (SA), including asbestos management requirements where applicable
- SafeWork SA guidance
- Safe Work Australia asbestos Codes of Practice and guidance material
- Relevant Australian Standards where applicable to the scope, signage, respiratory protection, sampling or demolition context

## Open Questions / Unresolved Fields

- Confirm whether Ax4 wants priority labels P1–P4 displayed in client-facing register tables.
- Confirm whether the action codes should be embedded into the AMPR template dropdowns.
- Confirm whether hazardous-material-specific action codes should be added later for lead, silica, mould and synthetic mineral fibre.
- Confirm whether review timing should be hard-coded or left as guidance for the consultant and management plan.
