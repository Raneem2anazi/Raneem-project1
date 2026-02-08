# Project 1: Loan Default Prediction

## Overview
This project aims to predict whether a loan will default (Charged Off) or be fully paid using historical Lending Club loan data.

The project focuses on building an interpretable machine learning model that supports decision-making for financial institutions.

## Dataset
- Source: Lending Club (Kaggle)
- Size: Approximately 710,000 loan records
- Target variable: loan_status (Fully Paid / Charged Off)

## Project Structure
- project1.ipynb: Data loading, EDA, data preprocessing, model training, and evaluation
- problem_statement.md: Business problem, users, decisions, and success metrics
- evaluation_report.md: Model evaluation, comparison, and explainability
- README.md: Project overview and instructions

## Models Used
- Logistic Regression
- Decision Tree Classifier

## Evaluation Metrics
- Accuracy

## Key Findings
- Both models achieved similar accuracy
- Logistic Regression was selected due to better interpretability and stability
- Interest rate and loan term were among the most influential features

## How to Run
Open the notebook `project1.ipynb` and run all cells sequentially.

## Notes
This project prioritizes model interpretability to support risk-based decisions for banks and credit institutions.
