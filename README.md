# Loan Approval Prediction using Logistic Regression

## Group Members
1. Basliel Selamu - ATE/6761/13
2. Bethel Wondwossen - ATE/8712/13
3. Diborah Dereje - ATE/1712/13

## Abstract
We have implemented a Logistic Regression model to predict loan approval status based on various applicant details. Our best model achieved an accuracy of 84.44%, with comprehensive evaluation metrics such as precision, recall, and F1-score. The model was trained on a processed dataset containing 614 observations with 12 variables related to applicants' financial and demographic characteristics. This data was sourced from the Loan Prediction Dataset available on Kaggle.

## Project Overview
This project aims to predict loan approval decisions based on different applicant attributes. By leveraging Logistic Regression, we've created a model that provides valuable insights into the factors influencing loan approvals.

## Dataset
The dataset used in this project includes information on:
- Applicant's income
- Co-applicant's income
- Loan amount
- Loan term
- Credit history
- Marital status
- Education
- Property area

## Methodology
1. **Data Preprocessing**
   - Handling missing values
   - One-hot encoding of categorical variables
   - Outlier removal and skewness treatment
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**
3. **Feature Selection**
4. **Model Development using Logistic Regression**
5. **Model Evaluation and Comparison**

## Results
Our best performing model achieved:
- **Accuracy:** 84.44%
- **Precision, Recall, and F1-score:** Evaluated using classification reports

Additionally, we compared various models and their performance:

| Model               | Accuracy   |
|--------------------|------------|
| Random Forest      | 93.33%      |
| K Neighbors        | 91.11%      |
| SVM                | 86.67%      |
| Decision Tree      | 86.67%      |
| Logistic Regression| 84.44%      |
| Gaussian NB        | 80.00%      |
| Gradient Boost     | 80.00%      |
| Categorical NB     | 77.78%      |

These results indicate that Logistic Regression is a reliable method, though other models such as Random Forest achieved higher accuracy.

## Future Work
- Explore other machine learning algorithms such as ensemble methods
- Incorporate feature engineering techniques
- Collect more data to enhance generalization
- Perform hyperparameter tuning for further model optimization# loan-approval-prediction-LR
