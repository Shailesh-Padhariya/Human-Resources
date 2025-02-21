HR Analytics and Employee Attrition Prediction:
Libraries used: pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost

Accuracy per Model:

Logistic Regression: 89.13%

Random Forest Classifier: 87.5%

XGboost Classifier: 87.5%

Note: Every Model used to classify and predict gave the accuracy with difference of 3%
we can say that:

Feature Importance is Well-Captured – The dataset's features are consistently informative across models.
No Major Model Superiority – Since XGBoost and Random Forest didn’t significantly outperform Logistic Regression, complex models might not be necessary.
Potential for Further Tuning – Hyperparameter tuning or feature engineering could help improve performance beyond the current ceiling (~89%).

Project Overview:

This project analyzes HR data to uncover insights about employee demographics, salary distribution, job satisfaction, and attrition trends. It also builds predictive machine learning models to understand the key factors influencing employee turnover.

The dataset consists of various employee attributes, including:

Personal details (Age, Gender, Marital Status, Education Level, etc.)

Job-related features (Job Role, Job Level, Department, Business Travel, etc.)

Compensation and Benefits (Monthly Income, Stock Option Level, Salary Hike, etc.)

Work Experience (Years at Company, Years in Current Role, Performance Rating, etc.)

Attrition Status (whether the employee has left or stayed)

Project Structure:

The project is divided into multiple components:

Data Processing

Data cleaning and transformation

Label encoding categorical variables

Exploratory Data Analysis

Employee demographics insights

Attrition trends by various factors

Visualization of correlations between different attributes

Machine Learning Models (Python)

Feature engineering & one-hot encoding

Normalization using MinMaxScaler

Model training & evaluation

Comparison of classification models:

Machine Learning Models Used:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Key Insights from EDA:

Younger and less experienced employees are more likely to leave.

Sales representatives have the highest attrition rate compared to other job roles.

Employees with lower job satisfaction and work-life balance tend to leave more often.

Higher salary and stock option levels are correlated with employee retention.

Distance from home impacts attrition; employees living far from work have a higher chance of leaving.

