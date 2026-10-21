# quarto-epi-report

An automated, reproducible epidemiological report pipeline built with Quarto, survey-weighted baseline tables (`gtsummary`), and design-adjusted regression modeling (`svyglm`).

## Overview
This repository provides a reproducible Quarto (`.qmd`) document designed to:
- Generate survey-weighted baseline demographic summaries (`tbl_svysummary`).
- Fit design-adjusted logistic regression models (`svyglm`).
- Plot adjusted Odds Ratios (aOR) using `ggplot2`.

## File Structure
- `epi_survey_report.qmd`: Complete reproducible Quarto document.
