# Credit Card Default Payment Prediction Using SVM

## Description
This project uses a Support Vector Machine (SVM) classifier to predict whether credit card clients will default on their payments the following month. It leverages a dataset containing demographic details, credit limits, repayment histories, and billing information. The project includes data preprocessing, model training, evaluation, and interpretation to provide insights into credit risk.

---

## Dataset Information

The dataset captures credit card client data in Taiwan from April 2005 to September 2005, containing 25 variables:

- **ID:** Client identifier  
- **LIMIT_BAL:** Credit limit in NT dollars (individual and family/supplementary credit)  
- **SEX:** Gender (1 = male, 2 = female)  
- **EDUCATION:** Education level (1 = graduate school, 2 = university, 3 = high school, 4 = others, 5 & 6 = unknown)  
- **MARRIAGE:** Marital status (1 = married, 2 = single, 3 = others)  
- **AGE:** Age in years  
- **PAY_0** to **PAY_6:** Repayment status from September 2005 to April 2005, coded as:  
  - -1 = pay duly  
  - 1 = payment delay for one month  
  - 2 = payment delay for two months  
  - …  
  - 8 = payment delay for eight months  
  - 9 = payment delay for nine months or more  
- **BILL_AMT1** to **BILL_AMT6:** Amount of bill statements from September 2005 to April 2005 (in NT dollars)  
- **PAY_AMT1** to **PAY_AMT6:** Amount of previous payments from September 2005 to April 2005 (in NT dollars)  
- **default.payment.next.month:** Target variable indicating default status next month (1 = yes, 0 = no)

---

## Methodology
- Data preprocessing including encoding and feature scaling  
- Splitting data into training and testing sets  
- Training an SVM classifier to predict default payment risk  
- Evaluating the model with accuracy and confusion matrix  
- Hyperparameter tuning for optimized performance

---

## Results
The SVM classifier demonstrates robust predictive capability in identifying clients at risk of defaulting, providing valuable insights for financial decision-making.

---

## Usage

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/credit-card-default-prediction-svm.git
cd credit-card-default-prediction-svm
pip install -r requirements.txt
jupyter notebook notebooks/credit_card_default_svm.ipynb
