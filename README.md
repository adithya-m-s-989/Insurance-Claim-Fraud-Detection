# Project: Detecting Fraudulent Insurance Claims

## Overview

This project is dedicated to identifying fraudulent insurance claims by applying machine learning techniques to the `insurance_claims.csv` dataset. The core task is a supervised classification problem, where the model learns to predict whether a claim is fraudulent based on a variety of features associated with the claim and the claimant. The ultimate aim is to improve the efficiency and accuracy of fraud detection systems for insurance providers.

## Dataset: `insurance_claims.csv`

The `insurance_claims.csv` dataset provides a rich collection of insurance claim records. Each row corresponds to an individual claim, while columns represent diverse features related to that claim.

**Data Source & Composition:**
* Data was aggregated from multiple insurance providers.
* Includes a diverse range of insurance types such as vehicular, property, and personal injury.
* Each record offers insights into the claimant's background, specifics of the claim, associated documentation, and feedback from insurance professionals.
* Contains specific indicators and parameters considered during the claim's original assessment.

**Key Features (examples):**
* `months_as_customer`: Duration the claimant has been a customer.
* `age`: Age of the claimant.
* `policy_state`: The state where the insurance policy was issued (e.g., 'OH', 'IN', 'IL').
* `insured_sex`: The gender of the insured person (e.g., 'MALE', 'FEMALE').

**Target Variable:**
* `fraud_reported`: A binary variable indicating whether the claim was ultimately determined to be fraudulent ('Y') or legitimate ('N'). This is the variable our model aims to predict.

**Data Privacy & Anonymization:**
In adherence to privacy standards and agreements with data providers, specific personal details and direct identifiers within the dataset have been anonymized. Each claim is associated with a unique ID to ensure data privacy while preserving data integrity for analysis.

**Fraud Assessment:**
The claims in this dataset underwent rigorous examination, including both manual assessments and automated checks, to determine their legitimacy. The `fraud_reported` variable reflects the outcome of this thorough investigation.

## Project Objectives
1.  **Data Preprocessing:** Clean and prepare the `insurance_claims.csv` dataset for modeling (handling missing values, encoding categorical features, etc.).
2.  **Exploratory Data Analysis (EDA):** Uncover patterns, relationships, and insights within the data.
3.  **Feature Engineering & Selection:** Create new relevant features and select the most impactful features for fraud prediction.
4.  **Model Development:** Implement and train various supervised classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, etc.).
5.  **Model Evaluation:** Assess model performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score, AUC-ROC) and techniques like cross-validation.
6.  **Interpretation & Insights:** Understand the factors driving fraudulent claims based on the model.
