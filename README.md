# Diabetes-Predictor-XGBoost-98.6-ROC-AUC-0.99-
This notebook presents a complete pipeline for predicting diabetes using the Healthcare Diabetes dataset. Built with the powerful XGBoost classifier and evaluated using a full suite of metrics and visualizations, the model is designed for both educational and practical use.

Notebook Overview
The notebook file DiabetesXGBOOST.ipynb contains:

Data exploration (distribution, correlation matrix, missing values)

Preprocessing (null handling, scaling, encoding)

Modeling with XGBoost (XGBClassifier from xgboost)

Evaluation metrics: accuracy, precision, recall, F1-score, AUC

Confusion matrix and ROC curve visualizations

Model export for deployment
 
Dataset Information
Source: Kaggle (Healthcare Diabetes dataset)
https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes
Size: 520 instances, 17 features

Target: Diabetic (0 = No, 1 = Yes)

Features include:

Age, BMI, Physical Activity, Sleep, Smoking History, Alcohol Consumption, Glucose, Blood Pressure, etc.

Key Highlights
Applied train-test split with stratification to preserve class balance

Model tuned for generalization and interpretability

AUC and classification metrics suggest robust performance on real-world patient data

Visual explanation of model performance included

How to Use
After downloading the notebook:

jupyter notebook diabetes-prediction-xgboost-98-6-roc-auc-0-99 .ipynb
To use the model in your own pipeline:

Preprocess your input data in the same way (scaling, feature selection).

Load or retrain the XGBoost model using the code provided.

Use model.predict() to classify new samples.

Author
Sifis Karalias
Computer Science Graduate - AI & Decision Support Systems (DSS) Enthusiast
 Focus: Ethical AI in Healthcare, Gamified Mental Health, Data Analysis

