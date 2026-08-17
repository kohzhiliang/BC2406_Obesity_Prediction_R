# Obesity Prediction (R)

**Analytics I (BC2406) group project — NTU Business Analytics**

## Problem
Predict obesity level from lifestyle and dietary features using classification modelling.

## Data
- `ObesityDataSet_raw_and_data_sinthetic.csv` — lifestyle/diet features (gender, food frequency, physical activity, transport, etc.)

## Method (R)
- Data cleaning & column renaming for readability
- Missing-value checks
- Modelling with `caret`: **Random Forest**, **Neural Network (nnet)**, **CART (rpart)**, logistic regression
- Evaluation with ROC / `pROC`, train/test split via `caTools`

## Tools
R · randomForest · nnet · rpart · caret · pROC · ggplot2 · data.table · dplyr

## Files in repo
- `Code.R` — full analysis script
- `ObesityDataSet_raw_and_data_sinthetic.csv` — dataset
- `Report.docx`

