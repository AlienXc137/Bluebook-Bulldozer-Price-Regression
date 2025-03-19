# Bulldozer Price Prediction

## Overview
This project predicts the price of bulldozers using machine learning techniques. The dataset is sourced from Kaggle's **Blue Book for Bulldozers** competition, which provides historical data on bulldozer sales.

## Dataset
The dataset includes various features such as:
- Year of sale
- Machine hours usage
- Machine type
- Model ID
- Other categorical and numerical features

The dataset can be accessed from [Kaggle's Blue Book for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers).

## Approach
1. **Data Preprocessing:**
   - Handle missing values
   - Convert categorical variables
   - Feature engineering
2. **Model Selection:**
   - Used regression models: Random Forest
3. **Model Training & Evaluation:**
   - Train-test split
   - Hyperparameter tuning
   - Performance evaluation using RMS

## Results
- The best model achieved an RMSLE of 0.2443 on the test set.
- Feature importance analysis showed that `YearMade` and `MachineHours` were key predictors.


