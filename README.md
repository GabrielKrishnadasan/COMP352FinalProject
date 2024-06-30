# COMP352FinalProject

# NBA Salary Predictor

### Authors: Scott Schnieders, Dillon Timmer, Kaelan Anderson, Gabriel Krishnadasan

## Project Overview

This project aims to predict NBA player salaries based on various performance statistics. By leveraging player data, we analyze and preprocess datasets to create a robust model that can accurately estimate player salaries.

## Data Importing and Pre-processing

We collected salary data from the 2022-2023 NBA season, referencing a dataset from Kaggle: https://www.kaggle.com/datasets/jamiewelsh2/nba-player-salaries-2022-23-season. Our pre-processing steps include:

- **Handling Missing Data**: Ensuring completeness of our dataset.
- **Outlier Removal**: Removing players with fewer than 20 games played to eliminate anomalies, such as season-ending injuries or short-term contracts.
- **Normalization**: Scaling data for better model performance.

## Data Analysis and Visualization

### Target Variable Visualizations

We explored relationships between salary and various performance metrics, such as VORP (Value Over Replacement Player), to identify key predictors. Our visualizations can be seen in the folder labeled 'charts'

## Model Development

We utilized multiple machine learning models, including:

- **Linear Regression**
- **Decision Trees**
- **Random Forests**
- **Elastic Net**
- **XG Boost**

We also performed hyperparameter tuning for XGBoost using Bayesian search.

K-fold cross-validation was implemented for better performance on our training data.

### Meta Models

In addition to individual models, we experimented with meta-models:

- **Stacking Regressors**: Combining predictions from multiple models to improve overall performance.
- **Voting Regressors**: Using an ensemble approach to aggregate predictions from several base models for more accurate results.

Each model was evaluated based on their RMSE and StDev.

## Results

The project concludes with a comparison of model performances, highlighting the best-performing model for salary prediction based on our analysis. Random Forest became our best-performing model, with XGBoost following as a close second. 

In our variable importance analysis for our top 2 performing models, we found that features like Age and TotalMinutes were highly valued when predicting salary. This is mostly because someone who has played in the NBA for an extended period of time is likely to receive a higher salary. 

## Conclusion

This analysis provides insights into which factors most significantly impact NBA player salaries and offers a predictive framework for future salary estimations.

