# Heart Disease Prediction

## Problem Statement
Predicting heart disease severity (0-4) using patient clinical data
from the UCI Heart Disease dataset.

## Dataset
- Source: UCI Heart Disease Dataset
- 920 patients across 4 hospitals
- 15 features including age, cholesterol, ECG results

## Approach
- Multiclass Classification (0-4 severity)
- Logistic Regression

## Preprocessing Steps
- Missing value analysis (MCAR/MAR/MNAR)
- KNN imputation for MAR numerical columns
- OHE for nominal columns
- Ordinal encoding for slope
- StandardScaler for numerical features
- SMOTE for class imbalance

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 49% |
| Macro F1 | 0.40 |
| Macro Recall | 0.45 |


