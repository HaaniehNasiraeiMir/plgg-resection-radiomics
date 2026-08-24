# Research Questions

## Study Title

Preoperative Prediction of Gross/Near-Total Resection in Pediatric Low-Grade Glioma Using Clinical and MRI Radiomic Features: A Machine-Learning Analysis of the CBTN Cohort

## Primary Research Question

Can preoperative clinical and MRI radiomic features predict achievement of gross/near-total resection in pediatric low-grade glioma?

## Primary Outcome

Binary extent-of-resection outcome:

- Gross/near-total resection
- Less-than-gross/near-total resection

The exact mapping of the processed CBTN extent-of-resection variable will be formally verified before model development.

## Candidate Preoperative Clinical Predictors

- Age at diagnosis
- Sex
- Tumor location
- NF1 status

Variables representing treatment after diagnosis or surgery will not be used as preoperative predictors.

## Radiomic Predictors

Processed preoperative MRI radiomic features derived from:

- T1-weighted MRI
- T1 post-contrast MRI
- T2-weighted MRI
- FLAIR MRI

## Planned Model Comparison

Three prediction strategies will be evaluated:

1. Clinical features only
2. Radiomic features only
3. Combined clinical + radiomic features

## Main Comparative Question

Do MRI radiomic features improve prediction of gross/near-total resection beyond clinical variables alone?

## Validation Strategy

The original CBTN cohort structure will be preserved:

- Discovery cohort: model development and internal cross-validation
- Replication cohort: final held-out evaluation

The replication cohort will not be used for feature selection, model tuning, or other model-development decisions.

## Key Methodological Principles

- Use only information available preoperatively as predictors.
- Prevent data leakage during preprocessing and feature selection.
- Perform feature selection within the model-development process.
- Avoid fitting unrestricted models using all radiomic variables because the number of radiomic features is large relative to the sample size.
- Report discrimination and clinically interpretable performance measures.
