# Task 2 – End-to-End ML Pipeline (Customer Churn Prediction)

## Objective
Build an end-to-end ML pipeline using scikit-learn to predict customer churn.

## Dataset
- Telco Customer Churn dataset (CSV)
- Target column: `Churn` (Yes = 1, No = 0)

## Steps
1. Data Cleaning (drop ID, handle missing values)
2. Feature Encoding (one-hot encoding for categorical features)
3. Train/Test Split
4. Model Training:
   - Logistic Regression
   - Random Forest
5. Evaluation (accuracy, classification report, confusion matrix)
6. Feature Importance Analysis
7. Final ML Pipeline with `Pipeline`

## Results
- Logistic Regression Accuracy: ~80-82%
- Random Forest Accuracy: ~84-87%
- Key churn drivers: Contract type, Tenure, Monthly Charges, Internet Service

## Tools
Python, pandas, scikit-learn, seaborn, matplotlib, Jupyter Notebook

## Conclusion
The ML pipeline successfully predicts customer churn and highlights key features affecting retention. Random Forest performed better than Logistic Regression.
