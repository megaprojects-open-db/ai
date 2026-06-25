# Project Reports

This folder contains detailed PDF reports for individual projects in the Mega Projects Open Database.

## Naming convention

Use the project number and a short slug, all lowercase with hyphens:

```
{project-no}_{short-name}.pdf
```

Examples:
- `01_hornsea-2.pdf`
- `52_dart-silver-line.pdf`
- `07_hs2.pdf`

## Public URL pattern

Once uploaded, each PDF is accessible at:

```
https://megaprojects-open-db.github.io/ai/reports/{filename}.pdf
```

## Linking to the dashboard

Add the full URL to the `Report URL` column in `master.csv` (column to be added).
The dashboard will show a "Full report ↗" link on the Project Details card when a value is present.

## How to upload a new PDF

**Option A — via GitHub website (easiest):**
1. Go to https://github.com/megaprojects-open-db/ai/tree/main/docs/reports
2. Click "Add file" → "Upload files"
3. Drag in the PDF, use the naming convention above
4. Commit directly to main

**Option B — via Claude in a Cowork session:**
1. Place the PDF in your `MegaProjectResearch` folder
2. Tell Claude: "Upload `{filename}.pdf` to docs/reports/ and add the Report URL to master.csv for project {name}"
