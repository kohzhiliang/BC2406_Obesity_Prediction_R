# Obesity Prediction (R)

**Analytics I (BC2406) — NTU Business Analytics · group project**

## Overview
Predict obesity level from lifestyle and dietary features using multiple
classification models, comparing their performance on a held-out test set.

## Problem
Classify individuals into obesity categories from self-reported diet/activity data —
a classic supervised-learning problem for understanding behavioural health drivers.

## Data
- `ObesityDataSet_raw_and_data_sinthetic.csv` — lifestyle/diet features
  (gender, food frequency, physical activity, transport mode, etc.).

## Method (R)
- Data cleaning & column renaming for readability (e.g. `FAVC` →
  `high_caloric_food_frequenctly`).
- Missing-value checks.
- Modelling with `caret`:
  - **Random Forest**
  - **Neural Network** (`nnet`)
  - **CART** (`rpart`)
  - Logistic regression
- Evaluation with **ROC** (`pROC`), train/test split via `caTools`.

## Tools & Techniques
R · `randomForest` · `nnet` · `rpart` · `caret` · `pROC` · `ggplot2` ·
`data.table` · `dplyr` · classification · model evaluation

## Repository Structure
- `Code.R` — full analysis script
- `ObesityDataSet_raw_and_data_sinthetic.csv` — dataset
- `Report.docx` — group report

## How to Run
```r
# set working directory to the folder containing the CSV, then:
source("Code.R")
```
Requires the packages listed above.

*Group project — NTU Business Analytics (BC2406). This repo overlaps with the
Healthcare_LoS_Prediction ML story; kept as a supplementary R classification example.*
