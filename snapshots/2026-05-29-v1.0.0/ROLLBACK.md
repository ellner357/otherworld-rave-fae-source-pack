# Rollback Notes

This file records how to back out each recovery milestone without deleting source history.

## Current Branch

- Recovery branch: `home-resume-2026-05-29-2007`
- Base commit from `main`: `a1df9ab7eb73822ecd658c5f43033591604ffb44`
- Recovery audit commit: `3d16c4de155a693eed7034f925a5bfe6191a22e2`

## Milestone Rollback Log

| Version | Commit | What changed | Rollback path |
|---|---|---|---|
| 1.0.0 | final v1.0.0 commit on branch | Final report, validation, version bump, v1.0.0 snapshot | Revert the final v1.0.0 commit to return to v0.5.0 package state |
| 0.5.0 | 30491e5 | Gemini, NotebookLM, Google Docs export package and mirror links | Revert `30491e5` to return to character-pack state; manually archive/delete created Google Docs mirrors only if Matt approves |
| 0.4.0 | dafd18b | Character bible, voice guide, archetypes, diagnostics, safety, motifs, examples | Revert `dafd18b` to return to canon-spine state |
| 0.3.0 | 17b258c | Start-here guide, canon index, event lore, threshold mechanics, continuity rules | Revert `17b258c` to return to source-audit state |
| 0.2.0 | 1330747 | Source audit, source indexes, canon policy, privacy filter, quarantine notes | Revert `1330747` to return to scaffold state |
| 0.1.0 | 5d0bff9 | Required scaffold and tracking files | Revert `5d0bff9`, leaving the recovery audit intact |

## Safety Notes

- Do not use `git reset --hard` or destructive checkout for rollback unless Matt explicitly approves it.
- Prefer `git revert <commit>` on the recovery branch.
- Preserve `RECOVERY_AUDIT.md` unless Matt asks for a clean rebuild from `main`.
- Google Docs mirrors created during v0.5.0 are external artifacts. Do not delete them without explicit approval.
