# PyCity Schools — District Performance Analysis in pandas

A district-wide standardized-testing analysis: 15 schools, ~39k students, merged from school- and student-level CSVs into a single pandas pipeline (`Jupyter Notebook Pandas Challenge .ipynb`).

## What it computes
- **District summary** — total schools/students/budget, average math & reading scores, % passing each and both
- **Per-school summary** — spending per student, scores, passing rates by school
- **Rankings** — top and bottom five schools by overall passing rate
- **Drill-downs** — scores by grade level, by spending-per-student bands, by school size, and by school type

## Headline findings
- The **top five schools by overall passing rate are all charter schools**; the bottom five are all district schools
- Higher per-student spending does **not** track with better outcomes in this dataset — the highest-spending band underperforms the lowest
- Small and medium schools decisively outperform large schools on % passing both subjects

## Run it
`jupyter notebook "Jupyter Notebook Pandas Challenge .ipynb"` — written analysis also in `Panadas Analysis.docx`.

**Skills:** merges, groupby aggregation, binning with `pd.cut`, multi-level summaries, formatting.

---
*Built during the University of Texas Data Analysis Boot Camp (2023–24), with help from classmates, tutors, and AI tools — disclosed then, kept honest now.*
