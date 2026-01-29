📊 Task 4: Feature Encoding & Scaling
🧠 AI & ML Internship
📌 Objective

The objective of this task is to understand and implement feature engineering techniques, specifically categorical feature encoding and numerical feature scaling, to prepare a dataset for Machine Learning models.

📁 Dataset

Name: Adult Income Dataset

Description:
The dataset contains demographic and employment-related information used to predict whether a person earns more than 50K per year.

🛠 Tools & Technologies Used

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook

🔍 Task Overview

In this task, the following steps were performed:

Loaded the Adult Income dataset

Identified categorical and numerical features

Applied Label Encoding for ordered categorical data

Applied One-Hot Encoding for non-ordered categorical data

Scaled numerical features using StandardScaler

Combined encoding and scaling using ColumnTransformer

Saved the preprocessed dataset for model usage

⚙️ Feature Engineering Techniques Used
🔹 Label Encoding

Used for categorical features where order exists

Example:
income → <=50K = 0, >50K = 1

🔹 One-Hot Encoding

Used for categorical features without order

Converts categories into binary columns

🔹 Feature Scaling

Applied StandardScaler

Ensures all numerical features have:

Mean = 0

Standard Deviation = 1

📈 Why Feature Scaling is Important

Prevents bias due to different feature ranges

Improves performance of distance-based algorithms

Essential for:

Logistic Regression

KNN

SVM

K-Means

Neural Networks

📂 Project Structure
Task-4-Feature-Encoding-Scaling/
│
├── adult.csv
├── adult_preprocessed.csv
├── task4_feature_encoding_scaling.ipynb
├── README.md

📤 Deliverables

✅ Preprocessed Dataset (adult_preprocessed.csv)

✅ Jupyter Notebook

✅ GitHub Repository

✅ README Documentation

🧪 Learning Outcome

Understood feature engineering basics

Learned when to use Label vs One-Hot Encoding

Gained practical knowledge of feature scaling

Prepared data for Machine Learning models
