
# Sample Superstore Sales — Portfolio Project

A data-analytics portfolio containing a Power BI report built on the Sample Superstore sales dataset, plus supporting SQL queries and a project report PDF. This repository is a deliverable (report + queries + write-up), not an application or codebase.

## Contents

- `Sample Superstore Sales Portfolio Project.pbix` — Power BI Desktop report (interactive visuals + data model).
- `SQL Queries for KPI analysis` — Word document (DOCX) containing the SQL used for KPI computations and data preparation.
- `project 2 result.pdf` — Project write-up and results summary.

## What this repo shows

The PBIX file contains visuals, measures (KPIs) and Power Query transformations built for analysis of Sample Superstore sales data. The Word document holds SQL queries used during analysis; the PDF contains the final narrative, findings, and screenshots.

## How to open / view

1. Clone or download the repository:
   - `git clone https://github.com/Priyankayadav1502/Sample-Superstore-Sales-Portfolio-Project.git`

2. Open the Power BI report:
   - Install Power BI Desktop (Windows).
   - Open `Sample Superstore Sales Portfolio Project.pbix` in Power BI Desktop.

3. Inspect supporting documents:
   - Open `SQL Queries for KPI analysis` in Microsoft Word (or another DOCX viewer).
   - Open `project 2 result.pdf` in any PDF reader.

Notes:
- PBIX is a binary file — GitHub will not render it. Use Power BI Desktop to inspect visuals, measures and queries.
- The PBIX may use embedded data or live/credentialed data sources. Power BI Desktop will prompt for credentials if a connection is external.

## Reproduce / extract analysis artifacts

- SQL: open the Word document, copy queries into `.sql` files, and run them against your local database or sample CSVs.
- DAX measures: in Power BI Desktop, select a visual or the Model view and copy measures.
- Power Query (M): in Power BI Desktop go to Transform data → Advanced Editor, then copy the M code.
- To document data sources and refresh behavior, check: Home → Transform data → Data source settings.

Optional extraction tools:
- Tabular Editor (for model metadata) — when connected to the model.
- External PBIX extractors exist but Power BI Desktop is the recommended way to inspect content.

## Suggested next steps (if you want me to help)

- I can extract the SQL queries from the DOCX and provide them as plain `.sql` files.
- I can inspect PBIX metadata for declared data sources and list key measures/visuals (requires the PBIX or exported metadata).
- I can add a LICENSE, CHANGELOG, or move SQL into a `sql/` folder and add short READMEs for each query.

## License & attribution

No explicit license file is included. Contact the repository owner for reuse permissions.

Author: Priyankayadav1502 — https://github.com/Priyankayadav1502

---
If you want the README added to the repository and you can grant write access (or provide a fork), I can commit it for you. Otherwise copy-paste this `README.md` into the repository root.
```
