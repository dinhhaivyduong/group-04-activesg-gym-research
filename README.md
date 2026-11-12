# Motivations, Barriers and ActiveSG Gym Use by Age and Sex, 2022–2025

**NMC5344 — Coding for Communicators | National University of Singapore**

## Research Overview

This project examines how motivations and barriers to exercise relate to changing ActiveSG gym attendance across age and sex groups in Singapore between 2022 and 2025.

## Research Question

How do motivations and barriers to exercise relate to changing ActiveSG gym attendance across age and sex between 2022 and 2025?

## Data and Methodology

We integrate three public data sources covering exercise motivations, participation barriers, and ActiveSG gym attendance, supplemented by Singapore resident population data.

The final analytical dataset contains 32 age-sex-year observations.

Methods include:

- Data cleaning and integration using R
- Descriptive statistics and data visualization
- Construction of four motivation and barrier indices
- Multiple linear regression with age-sex group and year controls
- Interaction regression
- Model comparison and sensitivity analysis
- Examination of Simpson's paradox

## Key Findings

- Female gym visits increased by approximately 103% between 2022 and 2025, compared with 59% for males.
- Adults aged 60+ experienced the fastest growth in visits.
- Enjoyment motivation was positively associated with gym visits per resident.
- The association between enjoyment motivation and gym use may be stronger among women.
- Aggregated associations can be misleading when age-sex group differences are not considered.

These findings are exploratory, group-level associations and should not be interpreted as causal effects.

## Research Files

- [Full Research Report](NMC5344_Final_Report_v8.pdf)
- [R Markdown Source Code](NMC5344_Final_Report_v8.Rmd)

## Authors

- Duong Dinh Hai Vy
- Adelle Lim Xen Wei
- Chen Anqi
- Nguyen Le Uyen
- Chiam Soon Lin Ezra

## Tools

R, R Markdown, tidyverse, ggplot2, knitr, broom

## Reproducibility

The R Markdown analysis requires the original public datasets and the prepared population data file. Data sources are documented in the research report.

## Acknowledgment

Group project completed for NMC5344 at the National University of Singapore.
