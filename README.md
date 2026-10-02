# The gTLD Report

A static, responsive 22-category report for monthly new gTLD registration snapshots.

## Data status

The category taxonomy is implemented. Monthly tables should be populated from `stats2026.xlsx` after validating the complete workbook and the authoritative TLD-to-category mapping. Do not treat placeholder values as measured data.

## Monthly update workflow

1. Add the new workbook to `data/incoming/`.
2. Maintain the TLD mapping in `data/tld-categories.json`.
3. Aggregate each TLD's Domains value by month and category.
4. Update the monthly rows in the category templates.
5. Run a link and HTML validation check.
6. Commit and allow GitHub Pages to deploy.

Figures represent end-of-month registration snapshots, not daily registrations.

## SEO

The site uses descriptive page titles, canonical URLs, semantic headings, responsive HTML tables, and a generated sitemap. Add Dataset and BreadcrumbList JSON-LD when production data is populated.
