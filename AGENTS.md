# Repository AI Operating Contract

This repository remains authoritative for CREATIVIA-specific scope, implementation and evidence. `jeremytheva/project-master` supplies reusable standards/templates only.

## Autonomous continuation
On Continue / Proceed / Next, inspect repository and GitHub state, choose the highest-priority dependency-correct task, prefer validation/integration when WIP limits are reached, bypass only non-critical blockers with independent work, update durable status, and stop rather than invent speculative work without an accepted requirement, defect, failed validation, review finding, security/data need, technical debt item or release requirement.

## PR and WIP controls
Normal non-draft PRs are the default. Lifecycle metadata is `IMPLEMENTING → VALIDATING → READY FOR REVIEW → MERGE READY → MERGED`, with `BLOCKED` as an overlay.

Default limits: dependent PR stack <= 2; ordinary open implementation PRs <= 3. If exceeded, stop overlapping implementation and validate/reconcile/merge first.

## Validation
Prefer the repository's canonical validation executor when defined. Fallback: canonical executor → trusted alternate → exact-commit equivalent deployment/build → `VALIDATION WAITING`. Never mark an unexecuted check PASS. Empty/zero-step CI is infrastructure evidence only.

## Status, templates, data and providers
`STATUS.md` is the continuity source. Keep validation, deployment, runtime and browser evidence separate. Reuse Project Master patterns before sharing runtime implementation and record adoption in `.project-master/manifest.yaml`.

Application/domain semantics remain separate from physical/provider schema. Do not invent provider authority or fictional SQL. Provider claims distinguish `IMPLEMENTED`, `PROVIDER VERIFIED` and `APPLICATION VERIFIED`. Irreversible production data/provider changes require a migration approval package including backup/restore and post-change verification.

## Owner boundary and reporting
Escalate only for inaccessible credentials/secrets, external account/billing configuration, destructive/irreversible production actions, third-party approvals, unavailable manual verification, genuinely unresolved product decisions, or material security/privacy/provider/cost choices not already governed.

Routine response:
```text
Done
- <1–3 material outcomes>
Next
- <single best next action>
You
- Nothing required.
```
Add `Blocked`, `Problem` or `Decision needed` only when materially necessary. Detailed evidence stays in repository/GitHub.
