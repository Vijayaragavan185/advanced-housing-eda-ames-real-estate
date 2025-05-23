# Advanced Housing Prices Data Cleaning & EDA

## Overview
This project demonstrates advanced data cleaning and exploratory data analysis techniques using the Ames Housing dataset.

## Dataset
The dataset contains 79 explanatory variables describing residential homes in Ames, Iowa, with the goal of predicting sale prices.

## Cleaning Steps
1. Conducted in-depth missing value analysis using visualizations
2. Applied different strategies for handling missing values based on their meaning
3. Used advanced outlier detection methods (Z-score, IQR)
4. Conducted feature engineering to create meaningful new variables
5. Applied transformations to handle skewed distributions

## EDA Highlights
1. Identified key price predictors through correlation analysis
2. Visualized relationships between features and sale price
3. Analyzed neighborhood impacts on housing prices
4. Examined effects of quality ratings on property values

## Key Findings
1. Overall quality, living area, and neighborhood are top price predictors
2. Several variables show strong positive skew requiring transformation
3. Identified outlier properties with large area but low price
4. The age of the house impacts price, especially for older homes

## Files
- advanced_cleaning_eda.ipynb: Jupyter notebook with code and analysis
- housing_cleaned.csv: Cleaned dataset ready for modeling
