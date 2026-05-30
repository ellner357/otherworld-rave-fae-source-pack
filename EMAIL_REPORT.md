# Otherworld Rave-Fae Source Pack Recovery / Build Report

Report date: 2026-05-29

## Repo

- Repo URL: https://github.com/ellner357/otherworld-rave-fae-source-pack
- Branch used: `home-resume-2026-05-29-2007`
- Branch type: recovery branch created from `main`
- Default branch: `main`
- Main branch seed commit: `a1df9ab7eb73822ecd658c5f43033591604ffb44`
- Recovery audit commit: `3d16c4de155a693eed7034f925a5bfe6191a22e2`
- v1.0.0 build commit: `88b6c1fc016e35766e4308af63ef64348c2681c5`
- Note: this fallback-report update is committed after the v1.0.0 build commit; the exact final branch head can be checked with `git log -1`.

## What The Shop Codex Completed

- Created the GitHub repo.
- Added a seed `README.md`.
- Appears to have created one abandoned Google Docs capability preflight test.
- Did not complete the source pack scaffold, audit, snapshots, tool files, or final docs.

## What Home Codex Completed

- Created `RECOVERY_AUDIT.md` first and committed it before the build.
- Created and used recovery branch `home-resume-2026-05-29-2007`.
- Built the required repository structure.
- Completed source audit, privacy filter, canon policy, source indexes, and private quarantine notes.
- Completed the character-facing documentation set.
- Completed Gemini and NotebookLM setup package.
- Created and read-verified six Google Docs mirrors.
- Added rollback notes, changelog entries, snapshots, access notes, and this report.

## Version Reached

Version reached: 1.0.0 first usable source pack.

## Files Created / Updated Summary

- Top-level: README, changelog, rollback, access issues, email report, source audit, canon policy, privacy filter, recovery audit.
- Sources: Drive index, outside research index, reliability notes.
- Docs: start-here, canon rules, event lore, threshold mechanics, character bible, voice guide, continuity, archetypes, diagnostics, safety ethos, altered-state boundary, motifs, location fragments, examples.
- Tooling: Gemini instructions/file list/setup notes; NotebookLM source list/usage guide/canon questions.
- Google Docs export: mirror plan, creation list, copy order, mirror links.
- Private quarantine: README, redacted notes, do-not-use list, candidate review.
- Snapshots: dated version snapshots from v0.1.0 through v1.0.0.

## Snapshot / Rollback Status

- Snapshots exist for v0.1.0, v0.2.0, v0.3.0, v0.4.0, v0.5.0, and v1.0.0.
- Rollback notes are in `ROLLBACK.md`.
- Preferred rollback method is `git revert`, not destructive reset.

## Google Docs Mirror Links

- Start Here: https://docs.google.com/document/d/1yo_idZntWKc507rLxbkb2mCzo5BJc9sSJssEMK9HSNY
- Canon Index and Source Rules: https://docs.google.com/document/d/1fQKfy1cNfz9JMoTCKrmulZjD6MkLwnjDqxhlS8rl50E
- Rave-Fae Character Bible: https://docs.google.com/document/d/1N5xKJyQbV4ZPvHX4iNY2W-aLMkArpk4EUkfaxH0_ieg
- Voice Tone and Examples: https://docs.google.com/document/d/1HiNa18wGYklzWSUgWeUgaxk681kmn6VrN_XQp-AtVzM
- Gemini Gem Instructions: https://docs.google.com/document/d/1cHpNZlbuYseYDzcvucHkNy4XJpoMrSk3jH_GkgzpoZ8
- NotebookLM Source List: https://docs.google.com/document/d/1_EI8WgooViUOiMbUqlT3vrHnfqEVK_mTtjkergfpG9g

## Access Issues

- GitHub, Drive, and Google Docs were available.
- Gmail send and draft tools were present, but both returned `401: Reauthentication required` during final reporting.
- Because Gmail requires reauthentication, this `EMAIL_REPORT.md` file is the fallback final report.
- The prompt-listed `Time Line for OW 2022` ID with capital `Z` failed.
- The exact-title Drive search found the working lowercase-z spreadsheet ID.
- No access issue blocked the build.

## Private / Quarantine Summary

- Some sources contain personal, medical, schedule, or logistics material.
- Those details were not copied into character-facing docs.
- Private material was reduced to broad patterns only: care, preparation, volunteer labor, thresholds, and safety.

## Next Recommended Action

Review the recovery branch, then merge or open a PR when satisfied. After merge, set up the Gemini Gem using `gemini/gem-instructions.md` and upload the priority files from `gemini/gem-knowledge-file-list.md`.
