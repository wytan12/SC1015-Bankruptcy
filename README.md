# SC1015-Company Bankruptcy Prediction
# Introduction
Lab: B128 
Group: 7
Members: Ng Yuen Herng, Tan Wei Yin, Pearlina Tan Qinlin

With the collapse of large companies such as FTX and Silicon-Valley Bank, our group began to wonder what causes a company to go bankrupt. This gave us inspiration for our project on predicting whether a company would go bankrupt. The dataset we use is from Kaggle, and is sourced from the Taiwan Economic Journal from 1999 to 2009. In the case of the dataset, bankruptcy was based on the business regulations of the Taiwan Stock Exchange.

Source: https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction?resource=download

## Problem Statement
What are the factors that causes a company to go bankrupt and what's the best model to predict whether a company will go bankrupt.

## Models Building
1. K-Nearest Neighbors
2. Random Forest
3. SVM 
4. XGBoost

## Models Evaluation
1. ROC-AUC curve
2. SHAP

# Conclusion
1. Random Forest is the best model to predict whether a company will go bankrupt or not, according to both ROC and F1 score metrics.
2. The Top 3 determinants of whether a company will go bankrupt is a high borrowing dependency, low EPS and low Net Income to Total Assets
## What did we learn
1. Handling imbalanced datasets using SMOTE
2. K-Nearest Neighbors, Random Forest Classifier, SVM, XGBoost
3. Concepts on ROC & AUC, and F1 Score

## Individual Contributions

Ng Yuen Herng:
1. XGboost
2. SVM
3. SHAP Analysis

Tan Wei Yin:
1. Random Forest
2. KNN 
3. ROC Curve Analysis

Pearlina Tan Qinlin:
1. Data Extraction
2. Data Analysis
3. Data Transformation

## References
https://www.google.com/amp/s/www.geeksforgeeks.org/data-science-tutorial/amp/ <br>
https://towardsdatascience.com/smote-fdce2f605729
