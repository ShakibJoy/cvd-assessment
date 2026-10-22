# cvd-assessment

Continuous Cardiovascular Risk Estimation via Interpretable Regression


**Summary.** We frame cardiovascular-disease (CVD) risk estimation as **regression** on a
continuous risk score rather than binary classification. Using 1,529 patient records from
Jamalpur Medical College Hospital, Bangladesh (CAIR-CVD-2025), we add four clinically derived
features (TC/HDL ratio, non-HDL cholesterol, pulse pressure, mean arterial pressure), compare
six regression models, and interpret the final model with coefficients and SHAP.

## Dataset
CAIR-CVD-2025 (Nirob et al., 2025), Mendeley Data:
https://data.mendeley.com/datasets/d9scg7j8fp/1 — download it there; the data are not
redistributed in this repository.

## Repository contents
- `[notebook name].ipynb` — full pipeline: preprocessing, feature engineering, models, SHAP
- `figures/` — correlation heatmap, predicted-vs-true and residual plots, SHAP plots
