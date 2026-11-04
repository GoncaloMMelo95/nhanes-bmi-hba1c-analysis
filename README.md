# BMI and HbA1c Analysis in US Adults

## Project Overview

This project investigates the association between body mass index (BMI) and glycated haemoglobin (HbA1c) levels in US adults using publicly available data from the **2017–2018 National Health and Nutrition Examination Survey (NHANES)**, conducted by the US Centers for Disease Control and Prevention (CDC).

The project demonstrates a reproducible data analysis workflow, from data acquisition and validation to data cleaning, exploratory analysis, statistical modelling and visualisation.

## Research Question

Is body mass index (BMI) associated with HbA1c levels in US adults?

## Data Source

Data are obtained from the official CDC NHANES 2017–2018 public-use datasets.

The analysis uses the following components:

- `DEMO_J`: Demographic information and survey design variables.
- `BMX_J`: Body measurements, including BMI.
- `GHB_J`: Glycohemoglobin measurements, including HbA1c.
- `DIQ_J`: Diabetes questionnaire information.

**All data used in this project are publicly available. No personal research, laboratory or thesis data are included.**

## Methods

The planned workflow includes:

1. Downloading and validating the original NHANES datasets.
2. Merging datasets using the participant identifier (`SEQN`).
3. Assessing missing data and defining the analytical sample.
4. Performing exploratory data analysis.
5. Estimating the association between BMI and HbA1c while accounting for the complex NHANES survey design.
6. Producing clear visualisations and reporting results.

## Repository Structure

```text
nhanes-bmi-hba1c-analysis/
├── docs/
├── notebooks/
├── outputs/
│   ├── figures/
│   └── tables/
├── .gitignore
└── README.md
```

## Important Considerations

NHANES uses a complex multistage probability sampling design. Survey weights, strata and primary sampling units will therefore be considered in the statistical analysis.

This is an observational, cross-sectional analysis. Findings will be interpreted as associations rather than causal relationships.

## Project Status

**In progress** — data acquisition, validation and preparation.

## Author

Gonçalo Melo
