# Machine Learning Portfolio: Decision Tree Analysis

This repository demonstrates the application of **Decision Tree algorithms** for both **classification** and **regression** problems using **R**. The projects illustrate end-to-end workflows including data exploration, feature selection, model development, evaluation, and visualization.

---

## Project Structure

* **Decision Tree Classification**  
  Predicting diabetes onset based on patient health metrics.

* **Decision Tree Regression**  
  Predicting employee salaries based on demographic and professional experience.

---

## Project 1: Diabetes Onset Prediction (Classification)

### Objective
Develop a predictive model to determine whether an individual has diabetes based on diagnostic measurements. A **pruned Decision Tree** was used to ensure a balance between predictive accuracy and interpretability, which is critical for medical decision support.

### Dataset and Variables
* **Dataset:** Pima Indians Diabetes Database (`Diabetes_data_1.csv`)  
* **Features:** `Glucose`, `Blood Pressure`, `Skin Thickness`, `BMI`, `Pregnancies`, `Age`, `Diabetes Pedigree Function`  
* **Target:** `Outcome` (Binary: 0 = Non-diabetic, 1 = Diabetic)

### Key Results
* **Most Important Predictor:** Glucose levels were identified as the most significant factor for predicting diabetes.  
* **Model Performance:**  
  - Accuracy: 75%  
  - F1-Score: 82.2%  
* The model emphasizes **recall** to correctly identify diabetic patients, enhancing clinical relevance.

---

## Project 2: Salary Prediction Analysis (Regression)

### Objective
Predict annual salaries of employees by analyzing the relationship between professional experience, education, and demographic factors. A **pruned Decision Tree Regression model** was applied to reduce overfitting and improve predictive performance.

### Dataset and Variables
* **Dataset:** Corporate Salary Data (`Salary_Data.csv`)  
* **Features:** `Age`, `Gender`, `Education Level` (Bachelor’s, Master’s, PhD), `Years of Experience`  
* **Target:** `Salary` (Continuous numerical value)

### Key Results
* **Most Influential Predictors:** Years of Experience and Age were the primary drivers of salary.  
* **Performance Metrics:**  
  - RMSE: 16,742  
* The model provides accurate predictions while maintaining interpretability through tree pruning.

---

## Tools and Libraries
* **R** – Data analysis and modeling  
* **rpart / rpart.plot** – Decision Tree modeling and visualization  
* **ggplot2** – Data visualization  
* **caret** – Model evaluation and cross-validation  
