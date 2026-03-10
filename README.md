# metabolic-syndrome-prediction
Machine learning project that predicts metabolic syndrome using clinical and demographic health data. The analysis includes data preprocessing, Random Forest classification, permutation feature importance, and stakeholder-friendly visualizations highlighting key metabolic risk factors.

Project Overview

This project develops a machine learning model to predict metabolic syndrome using demographic and clinical health indicators. The analysis includes data preprocessing, exploratory analysis, model training using a Random Forest classifier, and feature importance analysis using permutation importance.

Metabolic syndrome is a cluster of metabolic abnormalities including obesity, dyslipidemia, hypertension, and impaired glucose metabolism. Identifying important predictors can help better understand the factors associated with metabolic risk.

⸻

Dataset

The dataset contains demographic and clinical health measurements for individuals.

Each row represents one patient and includes several health indicators related to metabolic risk.

Features include
	•	Age
	•	Sex
	•	Race
	•	Marital status
	•	Income
	•	BMI
	•	Waist circumference
	•	Blood glucose
	•	HDL cholesterol
	•	Triglycerides
	•	Uric acid
	•	Urinary albumin/creatinine ratio

Target variable

MetabolicSyndrome
	•	0 → No Metabolic Syndrome
	•	1 → Metabolic Syndrome

⸻

Data Preprocessing

The following preprocessing steps were applied:
	•	Converted categorical variables to numerical values
	•	Handled missing values using SimpleImputer
	•	Exploratory data analysis using correlation matrices and visualizations
	•	Train/test split (80% training, 20% testing)

⸻

Model

A Random Forest Classifier was used to predict metabolic syndrome.

Reasons for choosing this model:
	•	Performs well on tabular health data
	•	Handles nonlinear relationships
	•	Allows analysis of feature importance

⸻

Model Evaluation

The model was evaluated using classification metrics including:
	•	Accuracy
	•	Precision
	•	Recall
	•	F1-score
	•	Confusion matrix

These metrics measure how well the model predicts metabolic syndrome status.

⸻

Feature Importance

Permutation importance was used to identify the features that most influence the model’s predictions.

Top predictors included
	•	Blood Glucose
	•	Triglycerides
	•	Waist Circumference
	•	HDL Cholesterol
	•	BMI
	•	Age
	•	Sex

These variables are known clinical indicators related to metabolic syndrome and metabolic health.

⸻

Key Insights

Two explanatory visualizations were created to highlight trends for stakeholders.

Blood Glucose

Higher blood glucose levels are associated with an increased probability of metabolic syndrome.

Waist Circumference

Individuals with larger waist circumference show a higher rate of metabolic syndrome, reflecting the strong relationship between central obesity and metabolic risk.

⸻

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn
