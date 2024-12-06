# Loan Eligibility Prediction

This project aims to predict loan eligibility for customers applying to Dream Housing Finance Company. The solution involves preprocessing data, performing exploratory data analysis (EDA), and building various machine learning models to classify loan eligibility.

## Table of Contents
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Contributing](#contributing)

## Problem Statement
Dream Housing Finance Company deals with various home loans. The goal is to predict whether a loan applicant is eligible for a loan based on specific customer attributes.

## Dataset
- **Training Data:** `train.csv`
- **Testing Data:** `test.csv`
- Features include demographic details, loan amount, and credit history.

## Workflow
1. **Data Preprocessing**:
   - Handle missing values
   - Encode categorical variables
   - Create derived features like total income

2. **Exploratory Data Analysis (EDA)**:
   - Analyze income distributions, loan statuses, and other factors.
   - Visualize patterns like gender-wise loan approval rates.

3. **Model Building**:
   - Train multiple models:
     - Logistic Regression
     - K-Nearest Neighbors
     - Decision Tree
     - Random Forest
     - AdaBoost
     - Support Vector Machine (SVM)
   - Perform hyperparameter tuning for optimization.

4. **Model Evaluation**:
   - Compare models based on accuracy and confusion matrices.

## Machine Learning Models
The following algorithms are implemented with hyperparameter tuning:
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- AdaBoost
- Support Vector Machine (SVM)

## Results
The project evaluates the performance of all models and selects the best-performing one based on accuracy metrics.

## Technologies Used
- **Python**: Data manipulation and model training
- **Pandas, NumPy**: Data processing
- **Matplotlib, Seaborn**: Data visualization
- **Scikit-learn**: Machine learning

## How to Use
1. Clone this repository:
   ```bash
   git clone <repository_url>
