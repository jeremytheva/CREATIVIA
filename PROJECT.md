# CREATIVIA Landing Site

Last materially reviewed: 2026-09-28

## Purpose

Static CREATIVIA landing/waitlist site describing the broader creative platform concept, workspaces, blueprints, monetisation and community positioning.

## Current implementation

The default branch is `master`. `main` currently points to the same baseline commit. PR #1 contains interactive modal/theme/waitlist enhancements and is the only pre-existing implementation PR.

This repository is a static HTML site; no package-managed application runtime, database, authenticated backend or provider schema is represented.

## Continuity

- `AGENTS.md` — repository operating contract.
- `PROJECT.md` — scope and project-specific master-standard application.
- `STATUS.md` — durable current state.

## Validation

No canonical scripted validator exists today. Static/browser validation must be recorded explicitly rather than inferred. If a repeatable build/test stack is introduced later, add a canonical repository validation entry point.

## Data/providers

Database/schema/migration governance and provider certification are currently `NOT_APPLICABLE`.

If the waitlist becomes backed by a real external service/database, add a domain/data contract, provider representation, certification evidence and controlled migration process before treating that service as production authority.

## Productive-work boundary

The existing open PR #1 is valid unfinished integration work and should be validated/reconciled before new landing-page feature work is created.
