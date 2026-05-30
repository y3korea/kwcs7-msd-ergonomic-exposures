# Physical/ergonomic exposures and work-related musculoskeletal pain (KWCS 2023)

Analysis code for a study of **physical and ergonomic work exposures and site-specific
work-related musculoskeletal pain** (low-back, upper-limb, lower-limb) among Korean workers,
using the **7th Korean Working Conditions Survey (KWCS, 2023)**, for targeted physical therapy.

## Notebook
`KWCS7_physical_exposures_MSD.ipynb` — runs in Google Colab or Jupyter. It performs:
data preparation, survey-weighted logistic regression (adjusted ORs), population
attributable fractions (PAF), and interpretable machine learning (LightGBM + SHAP).

## Data availability
The KWCS is a publicly available national survey of the Occupational Safety and Health
Research Institute (OSHRI), KOSHA. **The dataset is not redistributed here** in accordance
with its data-use terms. Download the 2023 (7th) KWCS from the KOSHA portal
(https://portal.kosha.or.kr) and place the CSV in `input/`.

## Reproduce
1. Open the notebook in Google Colab (mount Drive) or Jupyter.
2. Put the KWCS 2023 CSV in `input/`.
3. Run all cells. Tables and figures are written to `output/run_<timestamp>/`.

## Environment
Python 3.10+ — see `requirements.txt`.
