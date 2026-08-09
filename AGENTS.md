# AX4 Master Policy Documentation — Agent Instructions

**Alignment date:** 2026-08-09  
**Primary software/system governance:** `ax4consultants-lab/ax4-systems-orchestration`  
**Architecture:** `ACCEPT_SPLIT_SPINE_V1`

## Repository Purpose

This repository is the controlled WHS/SHEQ policy, procedure, template and knowledge-documentation surface for AX4. Its own document-control rules remain authoritative for SHEQ drafting within this repository.

It is **not** the authority for AX4 software architecture, runtime database ownership, portal migration, infrastructure or operational execution.

## Mandatory Current-State Read for Software/Automation References

Before drafting or changing material that describes AX4 software, automation, data ownership, portals, document generation, Echo or cross-system workflows, read current canonical system authority in this order:

1. `ax4-compliance-hub/AGENTS.md`
2. `ax4-systems-orchestration/docs/ALIGN-OPSDB-SPINE.md`
3. `ax4-systems-orchestration/state/authority-spine.json`
4. `ax4-systems-orchestration/state/assimilation-status.json`
5. the currently selected orchestration workblock

Canonical orchestration governance overrides historical software statements in this repository.

## AX4 Split-Spine Rule

```text
OpsDB              = operational/commercial authority
External Supabase  = current live Hub portal authority
Z:/ Shared Drive   = controlled file-byte authority
Compliance Hub     = staff/client interface
Survey Buddy       = field evidence capture
Document Generator = controlled renderer
Echo               = deny-by-default assistant/operator plane
```

There is no universal AX4 database.

## Portal Authority Localisation Guard

AX4 is developing a provider-neutral Portal Authority Plane with a logically separate `ax4-portal-db`. Current shadow-foundation work is isolated synthetic/nonproduction only. External Supabase remains the current live Hub portal-authority implementation until a separately approved migration/cutover.

Do not update policy, procedures, tender content, capability statements or controlled client-facing wording to present the synthetic shadow as a deployed system, completed migration or production control.

Where automation is described:

- Document Generator remains a controlled renderer, not issue authority or commercial source of truth;
- controlled file bytes remain authoritative on Z:/ Shared Drive;
- operational/commercial data belongs to OpsDB;
- portal identity/access/QR/delivery belongs to the live portal plane until approved cutover;
- Echo/Atom/AI capability never implies operational authority.

## Drafting and Execution Boundary

This repository may define controlled business procedures and standard wording. It does not itself authorise a database write, document issue, QR publication, client delivery, file migration, portal cutover, real-client onboarding or Echo action.

For SHEQ drafting rules, continue to follow `AGENT-OPERATING-RULES.md` and the controlled document roadmap. If a SHEQ document conflicts with canonical system authority on software/data ownership, stop and surface the conflict rather than silently reconciling it.
