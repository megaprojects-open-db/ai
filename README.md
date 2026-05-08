# Mega Projects Open Database

A community-maintained, transparent database of large infrastructure, energy,
and industrial projects — tracking how much they were planned to cost, how much
they actually cost, when they were planned to finish, and when they actually
finished.

The goal: **make schedule and cost performance of mega projects easy to look
up, compare, and reason about** — for researchers, journalists, policymakers,
and the curious public.

## What's in here

| Path | What |
|---|---|
| [`data/master.csv`](data/master.csv) | Canonical project list. One row per project, 38 columns covering scope, dates, and costs. |
| [`data/snapshots/`](data/snapshots/) | Quarter-end frozen snapshots so we can show movement quarter-over-quarter. |
| [`docs/index.html`](docs/index.html) | Live dashboard. When GitHub Pages is enabled on `/docs`, this becomes the public viewer. |
| [`reports/`](reports/) | Quarterly written reports (Markdown / PDF). |

## Project scope

- **Sectors:** Infrastructure (transport, water, civic), Energy & power, Industrial & manufacturing
- **Geography (initial focus):** US, Canada, UK, EU, Australia, New Zealand
- **Threshold:** ~$1B (USD or CAD) total project cost
- **Time:** projects from any era, but active research focuses on what's been completed in the last few years and what's currently under construction

## How to contribute

Got a correction, a missing project, or a better source for an existing row?

1. Fork the repo, edit `data/master.csv`, and open a Pull Request.
2. In your commit message and PR description, **include a link to a primary
   source** (regulator filing, audit report, project owner press release).
3. We'll review and merge.

For larger changes (new columns, schema changes), please open an issue first.

## Data quality flags

This is an open project that grows with research. Some rows are more complete
than others. Confidence levels are tracked in the maintenance log
(`data/changelog.md`, coming soon). Notable known issues are listed in
`docs/observations.md`.

## License

Data: CC BY 4.0 (attribute as "Mega Projects Open Database").
Code: MIT.

## Maintainers

This project is co-maintained by Yi (research lead) with assistance from Claude
for research, data entry, and dashboard development.
