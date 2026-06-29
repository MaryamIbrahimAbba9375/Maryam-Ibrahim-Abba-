# Adult Income Prediction Classification 📊

## Project Overview
This repository contains the code and analysis for predicting whether an individual's income exceeds $50K/yr based on census data. This project was built to design an end-to-end machine learning workflow, from data preprocessing to model evaluation.

## Dataset
The data is sourced from the **Adult Income Dataset** (extracted from the 1994 Census bureau database).
* **Target Variable:** `Salary` (Binary: `<=50K` or `>50K`)
* **Key Features:** Age, Workclass, Education, Marital Status, Occupation, Relationship, Race, Gender, Capital Gain/Loss, Hours per week, and Native Country.

## Project Objectives
1. **Predictive Modeling:** Build a robust machine learning classification model to predict the income bracket.
2. **Model Evaluation:** Rigorously evaluate the model's performance using at least three distinct performance metrics.

## Tech Stack
* **Language:** Python
* **Libraries:** pandas, NumPy, scikit-learn
* **Environment:** Jupyter Notebook

## Methodology
* **Data Preprocessing:** Handled missing values, mapped the target variable to binary integers, and applied One-Hot Encoding to transform categorical text data into a machine-readable format.
* **Feature Scaling:** Standardized continuous features using `StandardScaler` to ensure uniform feature weighting.
* **Modeling:** Trained a `RandomForestClassifier` utilizing balanced class weights to effectively handle natural class imbalances in the dataset.

## Results & Evaluation
The model was tested on a 20% unseen holdout set. The performance was evaluated using the following classification metrics:
* **Accuracy:** [Insert your accuracy score here, e.g., 0.85]
* **Precision:** [Insert your precision score here]
* **Recall:** [Insert your recall score here]
* **F1-Score:** [Insert your F1-score here]

## How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn
