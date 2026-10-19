# Customer Churn Prediction and Retention Strategy

## Project Overview

This project applies machine learning techniques to customer churn prediction and retention strategy optimization using the IBM Telco Customer Churn dataset available on Kaggle.

The objective is to demonstrate how data-driven methods can help businesses identify customers at risk of leaving, understand customer segments, and explore potential retention interventions.

## Objectives

- Predict customer churn using supervised learning.
- Segment customers using unsupervised learning.
- Explore retention action selection using a simulated reinforcement learning environment.
- Translate analytical findings into business recommendations.

## Machine Learning Techniques

### 1. Supervised Learning
Classification algorithms evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Evaluation metrics include Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

### 2. Unsupervised Learning
K-Means clustering is used to identify customer segments based on tenure, monthly charges, total charges, and customer lifetime value.

### 3. Reinforcement Learning
A Q-Learning simulation evaluates alternative retention actions under explicitly stated assumptions about retention effects and incentive costs.

**Note:** Reinforcement learning results are illustrative and have not been validated using real retention campaign outcomes.

## Dataset

Source: [Telco Customer Churn — IBM Dataset on Kaggle](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)

The notebook uses the Kaggle API to download the dataset. A Kaggle API credential file must be supplied securely when running the notebook.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Google Colab
- Kaggle API

## How to Run

1. Open the notebook in Google Colab.
2. Obtain Kaggle API credentials from your Kaggle account.
3. Upload the credentials when prompted by the notebook.
4. Run the notebook cells in order.
5. Review the model evaluation, customer segments, and simulated retention policy.

Never commit Kaggle credentials or other secrets to the repository.

## Limitations

Predictive results depend on the dataset and preprocessing approach. Cluster selection involves a trade-off between statistical separation and business interpretability. Reinforcement learning outcomes depend on simulated assumptions and should not be interpreted as proven financial gains.

## Business Application

The project demonstrates how machine learning can support churn-risk assessment, customer segmentation, and the design of targeted retention experiments.

Retention recommendations should be validated with real campaign data before operational use.
