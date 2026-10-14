# Advertisement Click Prediction Using Machine Learning

## Project Overview

This project aims to predict whether a user will click on an online advertisement using machine learning techniques.

The analysis explores demographic and behavioral factors associated with advertisement engagement and compares eight classification algorithms to identify an effective predictive model.

## Dataset

The dataset contains 1,000 observations, including user demographics, browsing behavior, advertisement information, and a binary target variable (`Clicked on Ad`).

## Methodology

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Chronological train/validation/test split
- Comparison of eight classification models
- Temporal feature evaluation
- Time-aware cross-validation
- Final model evaluation and interpretation

## Models Evaluated

Logistic Regression, Decision Tree, Random Forest, SVM, KNN, Gradient Boosting, XGBoost, and AdaBoost.

## Final Model

**Logistic Regression** was selected based on its predictive performance, stability, simplicity, and interpretability.

## Final Test Results

| Metric | Score |
|---|---|
| Accuracy | 97.50% |
| Precision | 99.03% |
| Recall | 96.23% |
| F1-score | 97.61% |
| ROC-AUC | 98.82% |

The model correctly classified **195 out of 200 test observations**.

## Key Insights

- Daily Time Spent on Site and Daily Internet Usage were strongly negatively associated with advertisement clicking.
- Age was positively associated with advertisement clicking.
- The tested temporal features did not improve validation performance.
- Logistic Regression achieved competitive results compared with more complex ensemble models.

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Joblib, and Jupyter Notebook.

## Limitations

The dataset is relatively small and covers a limited historical period. Results may not generalize to different advertising campaigns or populations without further validation.

## Future Improvements

Future experiments could investigate text-based advertisement features, larger datasets, probability calibration, and performance monitoring on new observations.