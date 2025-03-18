Stock Price Prediction using Lasso and OLS Regression

Project Overview

This project analyzes Tesla's historical stock data and builds predictive models using Lasso Regression and Ordinary Least Squares (OLS). The primary objective is to forecast stock prices and evaluate the effectiveness of different regression techniques in financial data analysis.

Objectives

Retrieve and process historical stock price data for Tesla (TSLA).

Implement and compare two regression models:

Ordinary Least Squares (OLS)

Lasso Regression

Evaluate model performance and derive insights into stock price behavior.

Data Source

Yahoo Finance: The stock data was collected using the yfinance library for the date range November 1, 2022, to November 30, 2024.

Features include:

Open, Close, High, Low prices

Adjusted Close

Trading Volume

Project Workflow

1. Data Collection

Downloaded Tesla’s historical stock prices using yfinance.

2. Data Preprocessing

Handled missing values with imputers.

Standardized features using StandardScaler for consistent scaling.

3. Model Implementation

OLS Regression:

Established a baseline model to analyze relationships between predictors and the target variable.

Lasso Regression:

Applied regularization to reduce overfitting and identify important predictors by penalizing insignificant coefficients.

4. Model Evaluation

Compared OLS and Lasso models using the R² metric.

Identified the strengths and limitations of each approach in predicting stock prices.

Tools and Libraries

Python Libraries:

pandas and numpy: Data manipulation and numerical computations.

yfinance: Data retrieval from Yahoo Finance.

scikit-learn: Machine learning pipeline, regression models, and evaluation metrics.

Techniques:

Feature scaling

Regularization via Lasso

Results and Insights

OLS Regression: Provided a straightforward baseline for prediction but lacked robustness in handling irrelevant features.

Lasso Regression: Enhanced prediction accuracy by penalizing less significant predictors, making it suitable for high-dimensional data.

Insights:

Demonstrated the impact of regularization on model performance.

Highlighted the value of regression analysis in stock price forecasting.

Conclusion

This project showcases the application of machine learning techniques in financial data analysis. By leveraging historical data, it emphasizes the utility of regression models in uncovering patterns and predicting stock behavior. The insights derived can inform investment strategies and decision-making.

How to Use This Project

Clone the repository to your local machine:

git clone <(https://github.com/FinanceG/Lasso-and-OLS-Regression-for-Investment-Strategy-Modeling/blob/main/FM%20by%20Python.ipynb)>

Acknowledgments

Special thanks to Yahoo Finance for providing the data and to the open-source Python community for tools and libraries used in this project.

