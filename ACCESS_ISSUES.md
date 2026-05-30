# Access Issues

## Confirmed Access

- GitHub repo read/write: available.
- GitHub branch creation: available.
- GitHub PR inspection: available.
- Google Drive read access: available for verified source links.
- Google Docs create/update tools: available.
- Gmail send and draft tools: available.

## Known Issues

- The prompt-listed `Time Line for OW 2022` spreadsheet ID with capital `Z` failed with 404.
- The same title was found by Drive search with lowercase `z` in the ID: `11K2ygKL4t56yUFJ58X1i3_1cSBzREbIaNUAPG59VTnE`.
- `google-docs-export/google-docs-mirror-links.md` did not exist during the audit.
- One loose Google Doc named `Otherworld Rave-Fae Source Pack - Capability Preflight Test` exists, but it is an abandoned test doc, not a useful mirror.
- Six useful Google Docs mirrors were later created during v0.5.0 and recorded in `google-docs-export/google-docs-mirror-links.md`.
- No source access issue blocked the v1.0.0 build.
- Gmail send and draft tools were present, but both final send and final draft creation returned `401: Reauthentication required`.
- Because Gmail reauthentication is required, `EMAIL_REPORT.md` is the final fallback report.

## Recovery Decision

Continue on `home-resume-2026-05-29-2007`. Do not write recovery build content directly to `main`.
