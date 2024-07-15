## Project Overview:

The goal of this project is to develop a predictive model that estimates future flight prices based on historical data and various influencing factors.


## Objectives/Buisness Goals:


- Predict flight prices for specific routes.
- Analyze factors influencing flight price fluctuations.
- Provide actionable insights for travelers.

## Data Preprocessing:

- Data Cleaning: Handle missing values, outliers, and inconsistencies.
- Feature Engineering: Create features such as:
   
      1. Day of the week.

      2. Time of booking (lead time).

      3. Airline Preffered.

      4. Number of stops.


## Exploratory Data Analysis (EDA):

- Visualize price trends With number of stops.
 - Analyze correlation between features and price.
- Identify seasonal patterns and price volatility.     
- Identify Price variation with Source and Destination.

## Model Selection:
- Regression Models
     
       1. Extratree Regression
       2. Random Forest.
       3. Catboost Regression

Gradient Boosting (XGBoost, LightGBM).

## Model Evaluation:
- Split data into training and test sets (e.g., 80/20).
- Use metrics like RMSE, MAE, and R² to evaluate model performance.

## Accuracy:


| Model Name             |Accuracy                                                               |
| ----------------- | ------------------------------------------------------------------ |
| Random Forest Regression | 0.8532074703106208 |
| Extratree Regressor | 0.7890353681268577|
|Catboost Regressor | 0.8596289688357996 |



## Deployment:
- Create a web application Flask serve predictions.

## Future Work:
- Incorporate real-time data for ongoing price updates.
- Explore deep learning models for improved accuracy.
- Develop a user interface for travelers to input parameters and get price predictions.
## Tools and Technologies:
 - Programming Languages: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- Database: SQL for storing historical data.
- Web Framework: Flask, Django for the application.

## Conclusion:
This project aims to empower travelers with predictive insights, helping them make informed decisions and potentially save on flight costs.
