Diabetes Prediction using SVM

This project predicts whether a person is diabetic or not based on their medical attributes using the Pima Indians Diabetes Dataset. The model is built with Support Vector Machine (SVM) and achieves good accuracy on both training and testing datasets.

📌 Project Overview

Dataset: Pima Indians Diabetes Database

Features include:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Target Variable: Outcome (0 = Non-diabetic, 1 = Diabetic)

The dataset is preprocessed, standardized, and split into training and testing sets. An SVM classifier with a linear kernel is trained and evaluated.

⚙️ Tech Stack

Python

NumPy

Pandas

Scikit-learn

🚀 Steps in the Project

Load Dataset → Import CSV file into Pandas DataFrame.

Data Exploration → View shape, summary statistics, and class distribution.

Feature Scaling → Standardize features using StandardScaler.

Train-Test Split → 80% training and 20% testing.

Model Training → Support Vector Machine (SVM) with linear kernel.

Evaluation → Accuracy on training and test data.

Prediction System → Accepts input values and predicts diabetes status.

📊 Results

Training Accuracy: ~78.7%

Testing Accuracy: ~77.2%

The model generalizes well without major overfitting.
