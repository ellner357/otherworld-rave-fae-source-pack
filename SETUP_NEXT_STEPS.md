# Setup Next Steps

Version: 1.0.1

Use this when Matt is ready to set up the Gemini Gem or NotebookLM from the v1.0.0 source pack.

## Open First

1. `README.md` for the repository map.
2. `CANON_POLICY.md` for source authority rules.
3. `PRIVACY_FILTER.md` for what must stay out of character-facing tools.
4. `gemini/gem-instructions.md` for the Gemini Gem instruction text.
5. `gemini/gem-knowledge-file-list.md` for upload priority.
6. `notebooklm/notebooklm-source-list.md` for strict-source research setup.

## Existing Google Docs Mirrors

Use these mirrors if working from Google Docs is easier. Do not create duplicates unless one of these is actually broken.

| Source file | Mirror |
|---|---|
| `docs/00-start-here.md` | https://docs.google.com/document/d/1yo_idZntWKc507rLxbkb2mCzo5BJc9sSJssEMK9HSNY |
| `docs/01-canon-index-and-source-rules.md` | https://docs.google.com/document/d/1fQKfy1cNfz9JMoTCKrmulZjD6MkLwnjDqxhlS8rl50E |
| `docs/04-rave-fae-character-bible.md` | https://docs.google.com/document/d/1N5xKJyQbV4ZPvHX4iNY2W-aLMkArpk4EUkfaxH0_ieg |
| `docs/05-voice-tone-and-examples.md` | https://docs.google.com/document/d/1HiNa18wGYklzWSUgWeUgaxk681kmn6VrN_XQp-AtVzM |
| `gemini/gem-instructions.md` | https://docs.google.com/document/d/1cHpNZlbuYseYDzcvucHkNy4XJpoMrSk3jH_GkgzpoZ8 |
| `notebooklm/notebooklm-source-list.md` | https://docs.google.com/document/d/1_EI8WgooViUOiMbUqlT3vrHnfqEVK_mTtjkergfpG9g |

## Create The Gemini Gem

1. Open Gemini and create a custom Gem.
2. Name it `Otherworld Rave-Fae Guide`.
3. Open `gemini/gem-instructions.md`.
4. Paste the full contents of `gemini/gem-instructions.md` into the Gem instructions field.
5. Upload knowledge files from `GEMINI_UPLOAD_PACK.md` in order.
6. Start with the minimum upload set if Gemini has file or size limits.
7. Test with questions that force canon sorting, privacy refusal, and voice.

## Attach These First If Gemini Has Limits

Minimum first upload set:

1. `CANON_POLICY.md`
2. `PRIVACY_FILTER.md`
3. `SOURCE_AUDIT.md`
4. `docs/00-start-here.md`
5. `docs/01-canon-index-and-source-rules.md`
6. `docs/04-rave-fae-character-bible.md`
7. `docs/05-voice-tone-and-examples.md`
8. `docs/09-in-world-safety-ethos.md`
9. `docs/10-altered-state-worldview-not-drug-guide.md`
10. `docs/13-example-scenes-and-micro-monologues.md`

Keep `CANON_POLICY.md` and `PRIVACY_FILTER.md` high priority. They are guardrails, not optional flavor.

## Set Up NotebookLM

Use NotebookLM as the strict-source research library, not as the character voice.

1. Create a new NotebookLM notebook for the source pack.
2. Add the generated source-pack docs from `NOTEBOOKLM_SETUP_PACK.md`.
3. Add original source docs only when Matt wants source checking, not character performance.
4. Ask canon-checking questions from `notebooklm/notebooklm-canon-questions.md`.
5. If NotebookLM surfaces private detail, keep it in source-checking context only and do not copy it into character-facing docs.

## Do Not Upload

Do not upload raw private source material to the Gemini Gem:

- private names
- emails or phone numbers
- medical notes
- personal packing notes
- volunteer schedules
- crew schedules
- exact logistics
- private URLs, forms, credentials, tokens, or claim codes

The repo's `private-quarantine/` files are safe category-level notes. They are not the same thing as raw private Drive content.

## Update The Repo Later

For future changes:

1. Read `CANON_POLICY.md` and `PRIVACY_FILTER.md` before adding lore.
2. Put new character-facing content in `docs/`.
3. Label new material as confirmed, likely, interpretive, outside inspiration, or off-limits.
4. Update `CHANGELOG.md` with a new version section.
5. Update `ROLLBACK.md` with the commit and rollback path.
6. Create a snapshot folder after meaningful milestones.
7. Keep commits small and reversible.

