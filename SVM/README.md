# Credit Card Default Prediction

This repository demonstrates the analysis and modeling of credit card default data using **binary classification** techniques. The project includes data exploration, feature analysis, model building, evaluation, and visualization.  

---

## Objective

The primary goal of this project is to **predict whether a customer will default on their credit card payment in the following month**, based on historical credit and payment behavior. This is a **binary classification problem**, where customers are classified as:

- `1` → Default  
- `0` → No default  

The project aims to apply machine learning techniques to provide insights into factors that contribute to default risk and support decision-making for credit risk management.  

---

## Dataset Presentation

The **UCI Credit Card dataset** is provided by the University of California, Irvine (UCI) Machine Learning Repository. It contains **30,000 instances** and **25 attributes**, representing credit information and payment behavior of customers from a Taiwanese bank.  

---

## Variable Description

**Explanatory Variables:**

1. **ID**: Unique identification number assigned to each client.  
2. **LIMIT_BAL**: Credit limit in NT dollars (includes individual and family/supplementary credit).  
3. **SEX**: Client gender (1 = male, 2 = female).  
4. **EDUCATION**: Client education level (1 = graduate school, 2 = university, 3 = high school, 4 = others).  
5. **MARRIAGE**: Client marital status (1 = married, 2 = single, 3 = others).  
6. **AGE**: Client age in years.  
7. **PAY_0 to PAY_6**: Repayment status from September to April.  
   - Scale: -1 = paid duly, 1 = delayed 1 month, 2 = delayed 2 months … up to 8 = delayed 8 months, 9 = delayed 9 months or more.  
8. **BILL_AMT1 to BILL_AMT6**: Statement bill amounts from September to April (in NT dollars).  
9. **PAY_AMT1 to PAY_AMT6**: Previous payment amounts from September to April (in NT dollars).  

---

## Expected Results

The project expects to:  

- Identify the **key factors influencing credit default**, such as credit limit, repayment history, and demographics.  
- Build a **predictive model** capable of classifying customers into default vs. non-default categories with high accuracy.  
- Evaluate the model using metrics such as **Accuracy, Precision, Recall, F1-Score, and ROC-AUC** to ensure performance and reliability.  
- Provide actionable insights for **credit risk assessment and management**.  
