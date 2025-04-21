# Diabetes Prediction Model

## Project Overview
This project implements a machine learning model to predict diabetes in patients based on various health indicators. The model uses logistic regression to classify whether a patient has diabetes or not.

## Key Features
- Data analysis and visualization of diabetes dataset
- Feature selection and preprocessing
- Logistic Regression model implementation
- Model evaluation with multiple metrics
- Interactive prediction system

## Technologies Used
- Python 3.x
- Pandas for data manipulation
- NumPy for numerical computations
- Scikit-learn for machine learning
- Matplotlib and Seaborn for visualization

## Model Performance
- Accuracy: ~80%
- Precision: ~75%
- Recall: ~65%
- F1 Score: ~70%

## Features Used for Prediction
- Pregnancies
- Glucose Level
- Insulin Level
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

## Getting Started
1. Clone this repository
2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run the notebook:
   ```bash
   jupyter notebook converted_notebook.py
   ```

## Usage
The model can be used interactively through the `deploy()` function, which takes user input for various health indicators and provides:
- Diabetes prediction (Positive/Negative)
- Probability of prediction
- Model accuracy metrics 