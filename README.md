# SONAR-Rock-vs-Mine-Prediction
📌 Project Overview

This project is an end-to-end Machine Learning classification system that predicts whether an underwater object detected by SONAR signals is a Rock (R) or a Mine (M).

The model is trained using real SONAR signal data and uses Logistic Regression for binary classification.

This project demonstrates the complete ML workflow, from data loading and preprocessing to model training, evaluation, and real-time prediction.

🎯 Problem Statement

SONAR systems send sound waves underwater.
Based on the returned signal frequencies, we want to classify the object as:

Mine (M) – dangerous object

Rock (R) – safe natural object

📂 Dataset Information

Dataset Name: Sonar Dataset (UCI Machine Learning Repository)

Total Rows: 208

Total Features: 60 (numerical)

Target Column:

M → Mine

R → Rock

Each feature represents the energy of sonar signals at different frequencies.

🛠️ Technologies & Libraries Used

Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook / Google Colab

🔁 Project Workflow

Import required libraries

Load SONAR dataset

Exploratory Data Analysis (EDA)

Statistical analysis using describe()

Label distribution analysis

Feature & target separation

Train–test split (stratified)

Model training using Logistic Regression

Model evaluation (accuracy score)

Build a predictive system for new data

📊 Exploratory Data Analysis

Used .head(), .shape(), .describe() to understand data

Checked class balance using value_counts()

Used groupby() to analyze class-wise feature differences

🤖 Machine Learning Model

Algorithm: Logistic Regression

Type: Supervised Learning

Problem Type: Binary Classification

📈 Model Performance

Training Accuracy: ~83%

Testing Accuracy: ~76%

The model generalizes well without overfitting.

🔮 Prediction System

The project includes a real-time prediction system that:

Accepts new SONAR signal values

Predicts whether the object is a Rock or a Mine

Example Output:

['M']
The object is a mine

🚀 How to Run the Project

Clone this repository

Open the notebook in Jupyter / Google Colab

Install dependencies:

pip install numpy pandas scikit-learn


Run all cells sequentially

📌 Use Cases

Naval defense systems

Underwater mine detection

Submarine navigation safety

Learning end-to-end ML pipelines

🧠 Skills Demonstrated

Data preprocessing

Exploratory Data Analysis

Logistic Regression

Model evaluation

Building ML prediction systems

Python & Scikit-learn

🧾 Conclusion

This project showcases how machine learning can be applied to real-world defense and safety problems using Python. It is a strong beginner-to-intermediate project for Data Science & Machine Learning interviews.

👤 Author

Fajlur Rahman
Machine Learning & Data Science Enthusiast
