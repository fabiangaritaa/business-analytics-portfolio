# Business Analytics Portfolio — Fabian Garita

A public portfolio for demonstrating Power BI, R, KNIME, and Tableau skills.

## Root Cause & Defect Analysis — Public Demo
This is a **synthetic demonstration**, not Amazon data. It does not reproduce any confidential operational records, exact performance figures, internal categories, or proprietary workflows.

### Goal
Explore fictional weekly workload and defect trends; identify the largest fictional defect categories and visualize defect rates.

### Suggested dashboard
- Cards: total jobs, total defects, defect rate
- Weekly trend: defect rate by week
- Bar chart: defects by root-cause category
- Filters: week and category

### DAX examples
```dax
Total Jobs = SUM('Demo'[Job Count])
Total Defects = SUM('Demo'[Defects])
Defect Rate = DIVIDE([Total Defects], [Total Jobs], 0)
```

### Publishing guidance
Create a new Power BI file using only `synthetic_defects.csv`. Do not upload internal Amazon PBIX files, screenshots, reports, datasets, or confidential process descriptions without authorization.

## Other projects
Add separate folders for R, KNIME, and Tableau coursework once reviewed for publication.
