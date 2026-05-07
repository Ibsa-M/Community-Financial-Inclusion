# Financial Inclusion Prediction

## Overview

This project predicts whether an individual has a bank account using demographic and socioeconomic information.

The solution uses:
- data preprocessing
- feature engineering
- LightGBM classification

The project was developed for a machine learning competition focused on financial inclusion prediction.

## Project Structure

```text
Financial_Inclusion_Project/
│
├── data/
│   ├── Train.csv
│   └── Test.csv
│
├── notebooks/
│   └── financial_inclusion.ipynb
│
├── submissions/
│
├── README.md
│
└── requirements.txt
```

## Libraries Used

- pandas
- numpy
- scikit-learn
- lightgbm

## Workflow

1. Import libraries
2. Load datasets
3. Clean data
4. Encode target variable
5. Combine train and test datasets
6. Feature engineering
7. Split datasets
8. Train LightGBM model
9. Evaluate model
10. Generate predictions
11. Create submission file

## Model Used

LightGBM Classifier

Key parameters:
- `n_estimators=800`
- `learning_rate=0.05`
- `num_leaves=31`

## Evaluation Metrics

- F1 Score
- Mean Absolute Error (MAE)

## Submission

Predictions are exported as:

```text
submission27.csv
```