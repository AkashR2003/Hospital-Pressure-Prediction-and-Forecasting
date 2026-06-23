# Hospital Pressure Prediction & Forecasting using Machine Learning
## Project Overview
This project focuses on predicting hospital pressure levels and forecasting future hospital pressure scores using Machine Learning and XGBoost.
A custom healthcare dataset was designed and created by simulating real-world hospital operational factors such as patient volume, emergency cases, bed occupancy, staff availability, medicine usage, weather conditions, and seasonal trends.

## Objectives
* Predict Hospital Pressure Levels (Low, Medium, High)
* Compare multiple Machine Learning models
* Optimize model performance using Hyperparameter Tuning
* Forecast Hospital Pressure Scores for the next 7 days
* Support hospital resource planning and decision-making

## Dataset

Custom-built Hospital Pressure Score Dataset containing:

* Patient Count
* Emergency Cases
* Available Beds
* Occupied Beds
* Doctors Available
* Nurses Available
* Medicine Usage
* Weather Conditions
* Festival Information
* Seasonal Trends
* Hospital Pressure Score
* Pressure Level

## Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 93.20%   |
| Random Forest       | 93.20%   |
| Gradient Boosting   | 92.52%   |
| XGBoost             | 92.52%   |
| Decision Tree       | 86.39%   |

### Tuned XGBoost

* Accuracy: 93.88%
* Hyperparameter Tuning: GridSearchCV

## Forecasting Results

XGBoost Regressor was used to forecast hospital pressure scores for the next 7 days.

Performance Metrics:

* MAE: 2.15
* RMSE: 2.67
* R² Score: 0.961

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Jupyter Notebook

## Key Features

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Comparison
* Hyperparameter Tuning
* Classification & Forecasting
* Confusion Matrix Analysis
* Future Pressure Prediction

## Conclusion

The Tuned XGBoost model achieved the highest performance with 93.88% accuracy and successfully forecasted future hospital pressure scores. The project demonstrates how Machine Learning can assist healthcare organizations in resource allocation, staffing decisions, and hospital workload management.
