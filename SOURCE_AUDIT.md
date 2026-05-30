# Source Audit

Version: 1.0.0
Last updated: 2026-05-29

This audit summarizes source access, reliability, privacy handling, and canon-use decisions. It intentionally avoids raw private source content.

## Source Classes

| Class | Definition | Character-facing use |
|---|---|---|
| Primary public-style Otherworld source | Event guides, public-facing pages, theme copy, values, safety language | Strong canon after paraphrase and attribution |
| Private/logistics Otherworld source | Packing notes, schedules, work plans, volunteer logistics, personal notes | Do not copy raw; transform only high-level non-private patterns |
| Official outside inspiration | Gemini, NotebookLM, Burning Man official help/culture/survival pages | Not Otherworld canon; use for tool setup or broad cultural parallels |
| Unrelated Drive result | Search hit not clearly tied to Otherworld/Rave-Fae/allowed scope | Do not use |

## Verified Drive Sources

| Source | Status | Reliability | Privacy risk | Canon decision |
|---|---|---|---|---|
| `Otherworld2022-SurvivalGuide-v3 (1).pdf` | Readable | High for Otherworld 2022 public-style event ethos, safety, theme, terms | Medium; includes logistics and operational details | Use as primary canon, paraphrased and filtered |
| `Otherworld` Google Doc | Readable | Low to medium; personal checklist/logistics source | High | Quarantine. Use only tiny, abstracted, non-private vibes if needed |
| `2024 Otherworld` Google Doc | Readable | Low for character canon; personal care/logistics source | High | Quarantine. Do not use character-facing details |
| `Level Up+ Otherworld` spreadsheet | Metadata readable | Medium for camp/planning patterns | High | Quarantine; maybe extract generic collaboration patterns only |
| `Otherworld logo materials 2022` folder | Metadata readable | Medium for visual/aesthetic reference | Low to medium | Use for visual notes if assets are inspected later |
| `Time Line for OW 2022` spreadsheet | Metadata readable via corrected lowercase-z ID | Medium for planning/history structure | Medium to high | Use only redacted, non-personal timing/role patterns |
| `DPW - April 26th Work Party Schedule 2026` spreadsheet | Metadata readable | Medium for work-party structure | High | Quarantine; do not expose schedules |
| `DPW Crew Schedule (2026)` spreadsheet | Metadata readable | Medium for operational archetypes | High | Quarantine; do not expose schedules or names |

## Case-Sensitive Link Correction

Google Drive IDs are case-sensitive. The prompt-listed `Time Line for OW 2022` ID using capital `Z` failed with 404:

```text
11K2ygKL4t56yUFJ58X1i3_1cSBZREbIaNUAPG59VTnE
```

The exact-title Drive search found the working lowercase-z ID:

```text
11K2ygKL4t56yUFJ58X1i3_1cSBzREbIaNUAPG59VTnE
```

Use the lowercase-z ID only.

## Verified Outside Inspiration

| Source | Status | Use |
|---|---|---|
| Gemini custom Gems help | Opened official Google support page | Gem setup guidance |
| NotebookLM source/discovery help | Opened official Google support page | NotebookLM source behavior guidance |
| NotebookLM in Gemini Apps help | Opened official Google support page | Grounding and tool-boundary guidance |
| Burning Man 10 Principles | Opened official page via redirect | Outside cultural parallel only |
| Burning Man culture | Opened official page via redirect | Outside cultural parallel only |
| Burning Man Survival Guide 2025 | Opened official guide | Outside safety/preparation inspiration only |

## Privacy Findings

- Several Drive sources contain personal, medical, schedule, packing, contact, or exact logistics content.
- That material is useful for understanding risk and tone, but not for public or character-facing docs.
- Character-facing files must use redacted, generalized, non-identifying transformations.
- Any logistics-specific material belongs in `private-quarantine/` summaries only, and even there raw details should not be copied.

## Canon Findings

- The 2022 Survival Guide is the strongest source for Otherworld ethos: participation, gifting, decommodification, consent, accountability, self-reliance, Leave No Trace, safety, and the idea that the event is not a passive consumer festival.
- The source pack should distinguish event canon from Rave-Fae character interpretation.
- The helper can know how temporary cities, thresholds, dance floors, rituals, volunteer culture, and safety systems work, but she should not reveal operational/private specifics.
- The principle for uncertain lore is: gorgeous does not automatically mean canon.

## Access Findings

- GitHub, Drive, Google Docs, and Gmail tooling are available.
- No useful Google Docs mirrors existed in the repo at audit time.
- One abandoned preflight Google Doc exists and should not be treated as a mirror.

## Build Decision

Continue the project from v0.2.0 into v0.3.0 canon docs. Use the 2022 survival guide as the main canon spine, private sources only through the privacy filter, and official outside links only for tool guidance or inspiration.
