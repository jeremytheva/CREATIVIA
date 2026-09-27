# AI Agent Operating Contract

This repository follows the current master AI-first platform-development standards. Repository and GitHub state are authoritative for execution.

## Entry and continuation

Read `AGENTS.md`, `PROJECT.md`, `STATUS.md`, current PRs/issues and relevant code before working. Correct stale durable status when repository evidence disagrees.

For `Continue`, `Continue implementation`, `Continue automatic tasks`, `Proceed` or `Next`, choose the highest-priority dependency-correct task and continue autonomously. If one workstream is blocked, continue independent valid work.

Do not invent work to remain active. New work must be supported by a roadmap/accepted requirement, issue, defect, failed validation, review finding, security/data need, technical debt or release dependency.

## Owner intervention

Escalate only when tooling cannot safely resolve unavailable secrets/credentials, external accounts/billing, destructive or irreversible operations, third-party approvals, unavailable manual verification, genuine unresolved product decisions, material security/privacy/provider/cost choices, or irreversible production migrations.

Routine implementation, testing, documentation, PR progression and dependency sequencing are autonomous.

## PR lifecycle and WIP

Normal PRs are the default; Draft is exceptional.

Use `IMPLEMENTING → VALIDATING → READY FOR REVIEW → MERGE READY → MERGED`, with `BLOCKED` as an optional overlay.

Default limits:
- dependent PR stack: maximum 2;
- ordinary open implementation PRs: maximum 3.

If exceeded, stop new overlapping implementation and prioritize validation/reconciliation/merge.

Close without merge only when abandoned, duplicate, superseded, cancelled or rejected.

## Validation

This static-site repository currently has no canonical scripted validator. Use the hierarchy:
A. documented repository validator when one exists;
B. trusted alternate static/browser validation;
C. exact-commit deployment/browser verification;
D. `VALIDATION_WAITING`.

Never mark an unexecuted check PASS. Empty/zero-step CI jobs are `NOT_RUN`, not application failures. GitHub Actions is supporting infrastructure, not a separate acceptance system.

## Evidence provenance

Track current/candidate/validated/deployed/runtime/browser evidence in `STATUS.md` when available. Build/deployment/runtime/browser evidence are distinct.

## Templates, data and providers

Reuse patterns/templates before sharing runtime implementation.

This repository is a static landing-page implementation. No application database/provider schema or migration authority exists. Do not create fictional SQL/provider certification. If persistence or backend capabilities are later added, define domain semantics first, provider schema second, controlled migrations third, and provider certification evidence before production reliance.

## Reporting

Routine owner responses use:

Done
- <1–3 material outcomes>

Next
- <single best next action>

You
- Nothing required.

`You` always appears. Replace its value with the exact owner action when necessary. Add `Blocked`, `Problem`, or `Decision needed` only when materially required. Keep detailed evidence in repository/GitHub records.
