# Doctor's Helper - Disease Risk Prediction

## Overview
Doctor’s Helper is a data science project aimed at predicting disease risk based on biological and environmental factors. The project utilizes machine learning techniques to analyze patient data and provide actionable insights.

## Repository Contents
- **Jupyter Notebook**: Data preprocessing, EDA, model training, and evaluation.
- **Presentation**: A multimedia summary of the process, findings, and recommendations.

## Dataset
### Features:
- **Biological**: Pregnancies, Blood Chemistry (I, II, III), Blood Pressure, Skin Condition, BMI, Genetic Predisposition, Age
- **Environmental**: Air Quality Index, Geographic Location (State)

## Methodology
1. **Data Preprocessing:**
   - Handle missing values and outliers.
   - Feature engineering and transformations.

2. **Exploratory Data Analysis (EDA):**
   - Feature distributions, correlations, and key insights.

3. **Model Selection:**
   - Models tested: Logistic Regression, Random Forest, Decision Tree.
   - **DecisionTreeClassifier** selected for best trade-off between performance and interpretability.
   - Hyperparameter tuning via **GridSearchCV**, optimized for recall.

4. **Feature Importance Analysis:**
   - Identified key contributors to disease prediction.

## Results
- Decision Tree model with high interpretability and strong performance.
- Feature importance ranking to aid medical decision-making.
- Recommendations for identifying at-risk patients.
