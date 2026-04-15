# Context Engineering Governance Reference Scaffold

Public reference scaffold for Context Engineering governance.

## Authority Boundary

This repository is a public, non-authoritative reference scaffold.
The authoritative governance source for the Josh-Phillips-LLC org lives in:

- `Josh-Phillips-LLC/context-engineering-governance`

## Purpose

This repository preserves a public reference copy of policy, process, and architecture-governance artifacts that describe how downstream implementation and role repositories operate.

Normative split direction:

- governance -> implementation -> role repositories

## Initial Bootstrap Scope

This scaffold preserves governance artifacts migrated from `Josh-Phillips-LLC/Context-Engineering` to establish a reviewable public reference baseline:

- `governance.md`
- `context-flow.md`
- `00-os/adr/`
- `00-os/role-charters/`
- governance review/checklist templates and PR policy contract artifacts

See `MIGRATION_PROVENANCE.md` for source commit references.

## Boundary Gates

Boundary drift is enforced by CI in:

- `BOUNDARY_GATES.md`
- `.github/workflows/validate-boundary-governance.yml`

## Change Management

- Issue-first workflow
- Split issue intake/routing policy (`00-os/intake-routing.md`)
- PR review required
- Executive Sponsor approval required for protected-path governance changes

See `governance.md` and `00-os/workflow.md` for the public reference copy of the operating model. The authoritative operating model lives in the LLC governance repo.
