# Heart-Stroke-Prediction
This project analyzes a stroke dataset to build predictive models for identifying individuals at risk of stroke based on health and demographic attributes. The goal is to compare the performance of multiple machine learning algorithms, evaluate their accuracy, and identify the best-performing model.

Steps Involved
Data Preprocessing:
Removed irrelevant columns.
Handled missing values.
Converted categorical variables into numerical values using label encoding and replacements.

Exploratory Data Analysis (EDA):
Visualized feature distributions and their relationship to stroke occurrence using histograms.
Identified correlations between features using a heatmap.

Feature Selection:
Selected key attributes (age, hypertension, heart_disease, etc.) for predicting stroke.

Model Training and Evaluation:
Built and evaluated four classification models: Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN).
Used accuracy_score, confusion_matrix, F1 score, and error metrics (MAE, MSE) for performance evaluation.

Comparison of Models:
Visualized accuracy scores for all models using a bar plot.
Identified the best-performing model based on accuracy and F1 score.
