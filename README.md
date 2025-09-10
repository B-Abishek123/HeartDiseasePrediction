## HeartDiseasePrediction
This project builds a machine learning pipeline to predict the likelihood of heart disease based on patient health attributes such as age, cholesterol, blood pressure, chest pain type, and more.

Using the clean dataset, I performed:

1. Data cleaning & preprocessing (encoding categorical variables).

2. Exploratory Data Analysis (EDA) with Seaborn & Matplotlib for medical insights.

3. One-hot encoding for categorical variables.

4. Handling class imbalance with SMOTE & Random Oversampling.

5. Modeling using Decision Tree, Random Forest.

6. Cross-validation (StratifiedKFold) for robust evaluation.

The goal is not only prediction accuracy but also interpretability and recall (catching as many positive cases of heart disease as possible).

Both Decision Tree and Random Forest gave about 86% accuracy.
Surprisingly, *Decision Tree* has better Recall and Precision than Random Forest for this dataset.


