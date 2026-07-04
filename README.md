# Medical Insurance Cost Prediction

Linear Regression model to predict medical insurance charges based on 
age, BMI, smoking status, region, and other features.

## Dataset
1338 records with features: age, sex, bmi, children, smoker, region, charges

## Approach
- EDA (distributions, correlations, outliers)
- Feature engineering (age & BMI categories)
- Statistical feature selection (Pearson correlation, Chi-square test)
- Train-test split with proper scaling (no data leakage)
- Linear Regression model

## Results
- R² Score: 0.79
- Adjusted R²: 0.79
- MAE: $4,358.73
- RMSE: $6,043.51

## Key Insight
Smoking status is the strongest predictor of insurance charges 
(correlation: 0.79), followed by age and BMI.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
