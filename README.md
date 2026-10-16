
# Air Quality Analysis and Health Impact Prediction Using Machine Learning

MSc Data Science research project — University of Ghana.

## Overview
This project develops an integrated framework for PM2.5 forecasting, Air Quality Index (AQI) classification, and population-level epidemiological health-burden estimation in Ghana.

## Key components
- Air-quality data preprocessing and missing-value imputation.
- Random Forest, XGBoost, CNN, LSTM, and hybrid-model evaluation.
- NowCast-based AQI categorisation using Support Vector Machine classification.
- Health-burden estimation using disease-specific exposure-response functions and Ghana-level mortality and DALY baselines.

## Reported forecasting results
| Metric | Random Forest |
|---|---:|
| MAE | 2.0058 µg/m³ |
| RMSE | 3.1339 µg/m³ |
| R² | 0.8041 |

Verify these reported results against the final evaluation outputs before publication.

## Reproducibility and limitations
Document the software environment, data provenance, preprocessing steps, model validation strategy, and limitations. Access to the original monitoring data may be subject to the data provider's conditions.

Health-burden estimates are model-based population-level estimates, not individual medical predictions or proof of causality.
