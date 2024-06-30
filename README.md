# COMP352FinalProject

# NBA Salary Predictor

### Authors: Scott Schnieders, Dillon Timmer, Kaelan Anderson, Gabriel Krishnadasan

## Project Overview

This project aims to predict NBA player salaries based on various performance statistics. By leveraging historical data, we analyze and preprocess datasets to create a robust model that can accurately estimate player salaries.

## Data Importing and Pre-processing

We collected salary data from the past five seasons, excluding the most recent season to avoid high correlation with the target salary data. Our pre-processing steps include:

- **Handling Missing Data**: Ensuring completeness of our dataset.
- **Outlier Removal**: Removing players with fewer than 20 games played to eliminate anomalies, such as season-ending injuries or short-term contracts.
- **Normalization**: Scaling data for better model performance.

## Data Analysis and Visualization

### Target Variable Visualizations

We explored relationships between salary and various performance metrics, such as VORP (Value Over Replacement Player), to identify key predictors.

## Model Development

We utilized multiple machine learning models, including:

- **Linear Regression**
- **Decision Trees**
- **Random Forests**
- **Neural Networks**

### Meta Models

In addition to individual models, we experimented with meta models:

- **Stacking Models**: Combining predictions from multiple models to improve overall performance.
- **Voting Regressors**: Using an ensemble approach to aggregate predictions from several base models for more accurate results.

Each model was evaluated based on accuracy, precision, and other relevant metrics.

## Results

The project concludes with a comparison of model performances, highlighting the best-performing model for salary prediction based on our analysis.

## Conclusion

This analysis provides insights into which factors most significantly impact NBA player salaries and offers a predictive framework for future salary estimations.

