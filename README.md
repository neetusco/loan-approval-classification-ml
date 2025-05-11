# Loan Approval Classification – Machine Learning Project

This project applies various **machine learning classification algorithms** to predict loan approval outcomes based on a dataset with 13 input features. Developed as part of the **Business Intelligence and Systems Infrastructure (BISI)** program at **Algonquin College**, this project demonstrates foundational knowledge of classification workflows in financial decision-making contexts.

## Project Overview

- **Goal**: Predict whether a loan application will be approved using historical applicant data.
- **Algorithms Used**:  
  - Linear Regression  
  - Logistic Regression  
  - Decision Trees  
  - Random Forest  
  - Neural Networks
- **Tools & Libraries**:  
  - Python  
  - scikit-learn  
  - pandas  
  - matplotlib / seaborn (for optional visualization)
- **Accuracy Achieved**: 72%

## Dataset

The dataset contains anonymized loan application records with 13 features such as applicant income, credit history, loan amount, and employment status.

> *Note: For academic use only. Dataset was cleaned and preprocessed before model training.*

## Key Steps

1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Standardized/normalized numerical features

2. **Model Building**
   - Trained and evaluated five classification models
   - Used confusion matrix, accuracy, and precision for model comparison

3. **Evaluation & Results**
   - Random Forest performed best with ~72% accuracy
   - Visualized feature importance and classification outcomes

## Sample Output

Include accuracy metrics, confusion matrix screenshots, or plots here (optional).

## Learning Outcomes

- Developed practical understanding of classification algorithms  
- Explored ML model evaluation techniques  
- Demonstrated application of ML to financial approval use cases

## How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/loan-approval-classification-ml

# Open the Jupyter notebook
Loan_Eligibility_Model_Solution.ipynb
