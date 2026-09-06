# CreditWise_Loan_System
# Loan Approval Prediction

## Project Overview

This project predicts whether a loan application will be **approved or rejected** using Machine Learning.

The project includes data preprocessing, exploratory data analysis (EDA), categorical data encoding, feature scaling, feature engineering, and training multiple classification models.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses a dataset named:

`loan_approval_data.csv`

The dataset contains information about loan applicants, such as:

* Gender
* Education Level
* Employment Status
* Marital Status
* Property Area
* Loan Purpose
* Applicant Income
* Credit Score
* DTI Ratio
* Savings
* Loan Amount
* Loan Term
* Collateral Value
* Loan Approval status

## Project Workflow

1. Load the dataset
2. Check and handle missing values
3. Perform Exploratory Data Analysis (EDA)
4. Encode categorical variables
5. Analyze feature correlations
6. Split data into training and testing sets
7. Apply feature scaling using StandardScaler
8. Perform feature engineering
9. Train Machine Learning models
10. Evaluate the models

## Machine Learning Models

The following classification algorithms are used:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

## Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook
```

Then open the `.ipynb` file and run the cells.

## Objective

The main objective of this project is to understand how Machine Learning can be used to analyze loan applications and predict loan approval based on applicant information.
