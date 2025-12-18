# ***AI-Powered Inflation Forecasting System***

This repository contains the source code, data analysis, and documentation for the "AI-Powered Inflation Forecasting and Economic Decision Support System" project. This study investigates the effectiveness of machine learning models compared to traditional econometric methods for forecasting US inflation, culminating in a conceptual Decision Support System (DSS) for business stakeholders.

## Project Overview

**Aim**: To develop a robust, data-driven inflation forecasting framework for the US economy (2000-2024) and evaluate whether advanced Machine Learning (ML) models outperform traditional statistical benchmarks.

## Key Features:

***Data Integration***: Merges 6 monthly macroeconomic indicators: CPI, Fed Funds Rate, M2, Oil (WTI), PPI, and Unemployment.

***Modeling***: Implements and compares three distinct forecasting paradigms:

***SARIMA** (Classical Statistical)

***Prophet*** (Modern Component-Based)

***Random Forest*** (Machine Learning with Lag Features)

***Validation***: Rigorous evaluation on a hold-out test set (2022-2024) using RMSE and MAE metrics.

***Decision Support***: Includes output data formatted for a Tableau dashboard to enable scenario analysis.





### Prerequisites

### To run this project, you will need Python 3.x and the following libraries:

***pandas***
***numpy***
***matplotlib & seaborn***
***statsmodels***
***pmdarima (for Auto-ARIMA)***
***prophet (Facebook Prophet)***
***scikit-learn***
***Installation***

### Clone the repository:

git clone [https://github.com/rozi2300/inflation-forecasting.git](https://github.com/your-username/inflation-forecasting.git)


pip install -r requirements.txt
