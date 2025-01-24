# Customer-Account-Closure-Analysis
A project exploring factors influencing credit card account closures. Using exploratory data analysis (EDA), machine learning models (Logistic Regression, Decision Tree, KNN), and evaluation metrics, this project predicts account closure likelihood and provides insights into actionable policies to retain customers.

## Overview
This project investigates factors influencing credit card account closures using exploratory data analysis (EDA) and machine learning models. It aims to:
- Identify patterns in account closures based on customer behavior and demographics.
- Predict the likelihood of account closures with high accuracy.
- Provide actionable recommendations to reduce account closure rates.

## Dataset
- **Description**: The dataset contains customer information, including:
  - Card type (Blue, Silver, Gold)
  - Contact frequency
  - Account tenure
  - Utilization ratio
  - Number of dependents
  - Account status (closed or active)
- **Target Variable**: Account status (Closed = 1, Active = 0).

## Methodology
- **EDA**:
  - Distribution of card types among closed vs. active accounts.
  - Correlation of contact frequency, account tenure, and utilization ratio with account closures.
- **Predictive Modeling**:
  - Logistic Regression, Decision Tree, and KNN models.
  - Evaluation metrics: AUC-ROC, precision, recall, accuracy, and F1-score.
- **Key Questions**:
  1. What factors are associated with account closure?
  2. How accurately can we predict account closure?
  3. What policies can reduce account closure rates?

## Results
1. **Top Factors**:
   - Utilization ratio: Customers with lower utilization ratios are more likely to close accounts.
   - Contact frequency: Regular customer engagement correlates with fewer closures.
   - Card type: Blue cardholders show higher closure rates.
2. **Model Performance**:
   - Logistic Regression: AUC-ROC = 0.944, Accuracy = 86.1%.
   - Decision Tree: AUC-ROC = 0.912, Accuracy = 88.4%.
   - KNN: AUC-ROC = 0.912, Accuracy = 83.8%.

## Tools and Technologies
- **Python**: pandas, numpy, scikit-learn, matplotlib, seaborn.
- **R**: ggplot2, plotly (if applicable).


