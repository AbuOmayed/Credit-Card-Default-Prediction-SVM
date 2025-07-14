# Credit Card Default Payment Prediction using SVM

## Project Overview
This project uses **Support Vector Machine (SVM)** algorithms to predict whether credit card clients in Taiwan will default on their payments the following month. The model is trained on a comprehensive dataset from April to September 2005, containing demographic information, credit limits, payment history, and bill statements.

## Dataset Description
The dataset includes 30,000 clients and 25 features such as:

- Demographic variables: Age, Gender, Education, Marital status  
- Credit information: Credit limit (`LIMIT_BAL`), payment history (`PAY_0` to `PAY_6`), bill amounts (`BILL_AMT1` to `BILL_AMT6`), previous payments (`PAY_AMT1` to `PAY_AMT6`)  
- Target variable: `default.payment.next.month` indicating default status (1 = default, 0 = no default)

## Objectives
- Preprocess and analyze demographic and payment data  
- Build and train an SVM classifier for binary classification of default status  
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score  
- Identify key predictors influencing default risk

## Dataset Source
The dataset is publicly available at the UCI Machine Learning Repository:  
[Credit Card Default Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

## Usage
Clone the repo, install dependencies from `requirements.txt`, and run the Jupyter Notebook for detailed exploratory data analysis, model building, and evaluation.

---

Feel free to open issues or submit pull requests for improvements and feedback!
