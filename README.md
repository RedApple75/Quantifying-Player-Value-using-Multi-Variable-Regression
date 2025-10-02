# Multi-Variable Regression for NBA Player Performance Analysis

## Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- NBA API

## Problem Statement
The goal of this project was to develop a multiple linear regression model to quantify an NBA player's individual contribution to their team's success. The primary objective was to create an interpretable metric, or 'Win Impact', based on player performance statistics and validate its correlation with team wins.

## Solution Approach
The solution uses a multiple linear regression model built on a dataset collected from the official NBA API. The key components are:

### Data Collection & Processing
A dataset of over **1,000 individual player records** was collected using the official **NBA API**. This raw data was then cleaned, processed, and structured using Pandas to prepare it for feature engineering and modeling.

### Feature Engineering
**Five distinct feature sets** were designed and tested, experimenting with various combinations of player statistics (e.g., points, rebounds, assists, efficiency metrics) to identify the most predictive variables for a team's success.

### Regression Model
A multiple linear regression model was built using **Scikit-learn**. The model was trained to predict a team's win total based on the aggregated, engineered features of the players on its roster.

### Player Ranking System
The coefficients from the trained regression model were used to generate a 'Win Impact' score for each player. This produced a final, interpretable ranking for **over 500 players** across the league.

## Results
The final model achieved a high degree of accuracy in predicting team success, demonstrating a strong and statistically significant correlation between the selected player metrics and wins.

- **R-squared:** 0.977 (97.7%)

The generated player rankings provided an interpretable metric that correlated strongly with a team's actual performance, successfully quantifying individual player contributions beyond simple box-score stats.
