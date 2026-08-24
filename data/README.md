# Data

This project uses publicly released processed clinicoradiomic data from the
Children's Brain Tumor Network (CBTN) pediatric low-grade glioma cohort.

The analysis uses two processed datasets:

- `X_clinical.pkl` — processed clinical variables
- `X_radiomic.pkl` — processed MRI radiomic features

The data were originally released with the pLGG immune clinicoradiomics study
by the D3b Center / Children's Brain Tumor Network.

## Data availability

The original processed data should be obtained from the official
`d3b-center/pLGG-immune-clinicoradiomics` repository or its associated
Zenodo record.

The patient-level data files are intentionally not redistributed in this
repository.

## Local setup

After obtaining the original files, place them locally as:

data/X_clinical.pkl
data/X_radiomic.pkl

These files are excluded from Git version control through `.gitignore`.
