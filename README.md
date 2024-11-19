## **Title**
**Credit Card Fraud Detection using Machine Learning**

---

## **Description**
Provide a brief overview of the project:  
"This project aims to detect fraudulent transactions using machine learning techniques. It includes preprocessing, feature engineering, addressing multicollinearity, handling class imbalance, and evaluating various models such as Logistic Regression, XGBoost, and SMOTE-enhanced models."

---

## **Features**
- Correlation matrix to explore relationships between variables.
- Multicollinearity handling using PCA.
- Addressing class imbalance with weighted classes and SMOTE.
- Implementation of classification models:
  - Logistic Regression
  - XGBoost
- Hyperparameter optimization with GridSearchCV.
- ROC Curve and feature importance analysis.

---

## **Dataset**
Describe the dataset briefly:
- Columns used: `amount`, `oldbalanceOrg`, `newbalanceOrig`, etc.
- Target variable: `isFraud` (binary classification).
- Data cleaning steps: Dropped irrelevant columns and handled missing values.

---

## **Project Workflow**
1. Data Preprocessing:
   - Dropping irrelevant columns.
   - Scaling numerical values.
2. Exploratory Data Analysis:
   - Visualizing correlations using heatmaps.
   - Calculating Variance Inflation Factor (VIF).
3. Model Training and Evaluation:
   - Logistic Regression (Baseline).
   - SMOTE for class imbalance.
   - XGBoost for high accuracy.
   - Hyperparameter tuning with GridSearchCV.
4. Feature Importance Analysis:
   - Analyzing coefficients and interpreting model predictions.

---

## **Results**
Include highlights of your model performance:
- XGBoost Accuracy: **99.95%** (overfitted).
- Logistic Regression Accuracy after SMOTE: **76.12%**.
- Optimized Logistic Regression Accuracy: **80.30%**.

---

## **Future Work**
- Experiment with other algorithms like Random Forest or Deep Learning models.
- Explore real-time fraud detection using streaming datasets.
- Incorporate additional features or external data sources for improved accuracy.
