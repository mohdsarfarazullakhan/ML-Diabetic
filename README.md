# ML-Diabetic
**Diabetes Readmission Prediction**

**Machine Learning Project | Healthcare Analytics**

This project builds a machine learning pipeline to analyze the diabetic_data.csv dataset and predict patient readmission. The notebook performs complete data handling, exploration, preprocessing, model building, and evaluation.



**Features of This Project**

✔ Load and clean the diabetic dataset
✔ Handle missing values & inconsistent entries
✔ Encode categorical variables
✔ Perform exploratory data analysis (EDA)
✔ Feature engineering
✔ Train ML models (Logistic Regression / Random Forest / etc.)
✔ Evaluate models using accuracy, precision, recall, F1
✔ Visualize insights

**Machine Learning Pipeline**
1. Data Loading

Uses:

import pandas as pd
import numpy as np


Loads the diabetic_data.csv dataset and inspects columns, data types, and missing values.

2. Data Cleaning

Replace “?” with NaN

Remove invalid/outlier entries

Drop columns with too many unknown values

Basic transformations (mapping, type casting)

3. Exploratory Data Analysis (EDA)

Check distributions

Study correlations

Detect skewed data

Generate summary statistics

View sample rows (df.head())

4. Preprocessing

Handle categorical data using Label Encoding / One-Hot Encoding

Standardize numeric features

Train-test split

5. Model Training

Typical models:

Logistic Regression

Random Forest

Decision Tree

XGBoost (if installed)

6. Evaluation

Includes metrics like:

Accuracy

Precision

Recall

F1-Score

Also supports:

Confusion Matrix

Classification Report

**Requirements**

Create a requirements.txt:

pandas
numpy
scikit-learn
seaborn
matplotlib


**Results & Insights**

Identifies key predictors of hospital readmission

Models provide insights for reducing re-admission risk

Useful for healthcare decision-making
