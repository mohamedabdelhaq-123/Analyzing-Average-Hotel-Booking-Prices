# Analyzing Average Hotel Booking Prices

## Overview
This project focuses on analyzing and predicting average hotel booking prices using regression models. The dataset includes various factors influencing hotel pricing, such as lead time, total number of guests, and other numerical attributes. The notebook applies both simple and multiple linear regression techniques to identify significant predictors of hotel prices.

## Methodology
1. **Data Preprocessing:**
   - Loading and cleaning the dataset.
   - Handling missing values and formatting numerical data.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing relationships between independent variables and hotel prices.
   - Identifying correlations using heatmaps and scatter plots.

3. **Regression Modeling:**
   - **Simple Linear Regression:** Analyzing the impact of individual features such as lead time and total guests on pricing.
   - **Multiple Linear Regression:** Using multiple numerical predictors to improve price estimations.
   
4. **Model Evaluation:**
   - Assessing model performance using R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
   - Comparing different models to determine the most effective predictor set.

## Dependencies
Ensure you have the following Python libraries installed:
pip install pandas numpy matplotlib seaborn scikit-learn

## Usage
1. Open the Jupyter Notebook (`Analyzing Average Hotel Booking Prices.ipynb`).
2. Run the preprocessing and EDA sections to explore the dataset.
3. Train and evaluate regression models to analyze pricing trends.
4. Interpret results and adjust features for improved predictions.

## Results
The regression models help understand key factors affecting hotel booking prices, providing insights for pricing strategies and revenue optimization.
