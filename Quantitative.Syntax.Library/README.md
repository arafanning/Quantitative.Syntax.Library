# Quantitative.Syntax.Library

A curated library of R syntax, reproducible workflows, and annotated examples for quantitative psychological research.

This repository is intended as a personal learning and reference resource. It organizes useful syntax by method while preserving links, citations, and notes about the original source.

## Repository structure

- `01_data-management/` — importing, cleaning, reshaping, coding, and documenting data
- `02_regression-and-robust-inference/` — linear and generalized linear models, robust standard errors, contrasts, and marginal means
- `03_multilevel-models/` — mixed-effects and hierarchical models
- `04_structural-equation-modeling/` — path analysis, CFA, SEM, and latent-variable models
- `05_longitudinal-models/` — growth models, repeated-measures approaches, and intensive longitudinal data
- `06_missing-data/` — missing-data diagnostics, multiple imputation, and full-information maximum likelihood
- `07_psychometrics-and-measurement/` — reliability, factor analysis, score construction, and measurement evaluation
- `08_visualization-and-reporting/` — publication-ready figures, tables, and reproducible reporting
- `09_reproducible-workflows/` — project organization, `renv`, Quarto/R Markdown, and version control
- `templates/` — reusable note and script templates
- `references/` — reading lists and source indexes

## How to use this library

Each example should include:

1. The original source or repository link.
2. A citation when one is available.
3. A brief explanation of what the syntax does.
4. Notes about assumptions, limitations, and when the method is appropriate.
5. Any modifications made to the original syntax.

The goal is not to collect isolated code fragments. The goal is to preserve enough context to understand what the code estimates and why the analytic choice is defensible.

## Attribution and responsible reuse

Do not copy another researcher’s code into this repository without attribution. When possible, link to the original file rather than reproducing it in full.

Before adapting code:

- review the repository license;
- identify the original author;
- cite the source in the file header or companion note;
- distinguish copied syntax from your own modifications;
- avoid reposting restricted data, credentials, or proprietary materials.

## Suggested naming convention

Use descriptive file names such as:

```text
robust-standard-errors-hc3.md
planned-contrasts-emmeans.md
latent-growth-model-lavaan.md
multiple-imputation-mice.md
```

For executable examples, keep the note and syntax together:

```text
planned-contrasts-emmeans/
    README.md
    example.R
```

## Contact

Ashley R. Adams, M.S.  
Clinical Science Ph.D. Candidate  
Florida International University  
asadams@fiu.edu
