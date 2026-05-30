# Future Change Workflow

Version: 1.0.1

Use this whenever adding, revising, or retiring lore in the source pack.

## 1. Start With Source Status

Before writing new lore, identify the source tier:

- `Confirmed`: directly supported by verified Otherworld source material.
- `Likely`: supported by multiple safe source patterns but not directly stated.
- `Interpretive`: character framing built from safe patterns.
- `Outside inspiration`: useful parallel from official outside sources, not Otherworld canon.
- `Off-limits`: private, identifying, unsafe, or not suitable for character-facing docs.

If a claim is beautiful but unsupported, label it interpretive or leave it out.

## 2. Apply Privacy Filtering

Read `PRIVACY_FILTER.md` before adding anything from source material.

Never put these into character-facing docs:

- names from private sources
- emails or phone numbers
- medical notes
- personal packing details
- volunteer or crew schedules
- exact logistics
- private URLs, forms, credentials, tokens, or claim codes
- substance dosing, sourcing, combinations, procurement, or instructions

Turn private/logistics material into broad patterns only.

## 3. Make The Smallest Useful Change

Prefer small edits:

- one lore correction
- one new example
- one source-rule clarification
- one setup-guide update
- one snapshot/version milestone

Do not rewrite completed docs unless they are clearly wrong, stale, empty, or unsafe.

## 4. Update CHANGELOG.md

For each version or meaningful change, add a new section near the top:

```markdown
## [1.0.2] - YYYY-MM-DD

### Added

- New thing.

### Changed

- Updated thing.

### Fixed

- Corrected thing.
```

Use only the subsections that apply.

## 5. Update ROLLBACK.md

Add a row with:

- version
- commit hash after commit exists
- what changed
- how to roll it back

Preferred rollback is `git revert <commit>`. Do not use destructive reset unless Matt explicitly asks.

## 6. Create A Snapshot For Milestones

For meaningful milestones, create:

```text
snapshots/YYYY-MM-DD-vX.Y.Z/
```

Copy the current source-pack files needed to understand that version. Keep snapshots as review/rollback aids, not a replacement for Git history.

Tiny bookkeeping-only changes may not need a full snapshot unless Matt asks.

## 7. Label Generated Lore vs Canon

When adding generated lore, make its status explicit:

- Confirmed source fact
- Source-compatible interpretation
- Character voice example
- Outside inspiration only
- Off-limits/private pattern

Do not let confident voice make uncertain material sound sourced.

## 8. Keep Commits Reversible

Before committing:

1. Run `git status`.
2. Review `git diff`.
3. Confirm only intended files changed.
4. Confirm no private/logistics material leaked.
5. Commit with a specific message.
6. Push only after verification.

Good commit message examples:

- `v1.0.2 clarify canon labels`
- `v1.0.3 add voice examples`
- `v1.1.0 expand source-safe lore`

