# Rollback Notes

This file records how to back out each recovery milestone without deleting source history.

## Current Branch

- Recovery branch: `home-resume-2026-05-29-2007`
- Base commit from `main`: `a1df9ab7eb73822ecd658c5f43033591604ffb44`
- Recovery audit commit: `3d16c4de155a693eed7034f925a5bfe6191a22e2`

## Milestone Rollback Log

| Version | Commit | What changed | Rollback path |
|---|---|---|---|
| 0.1.0 | pending local commit | Required scaffold and tracking files | Revert the v0.1.0 commit, leaving the recovery audit intact |

## Safety Notes

- Do not use `git reset --hard` or destructive checkout for rollback unless Matt explicitly approves it.
- Prefer `git revert <commit>` on the recovery branch.
- Preserve `RECOVERY_AUDIT.md` unless Matt asks for a clean rebuild from `main`.
