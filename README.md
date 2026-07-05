# Project Overview

## Credit Card Fraud Detection Using Machine Learning

The **Credit Card Fraud Detection** project is designed to identify fraudulent credit card transactions using Machine Learning techniques. With the rapid growth of online banking and digital payment systems, credit card fraud has become a significant challenge for financial institutions. Detecting fraudulent transactions quickly and accurately helps reduce financial losses and improves customer security.

This project uses historical transaction data from the **fraudTrain.csv** and **fraudTest.csv** datasets. The data is preprocessed by handling missing values, extracting useful features such as transaction hour, day, and month, and selecting relevant attributes for model training. The processed data is then used to train multiple Machine Learning algorithms, including **Logistic Regression**, **Decision Tree**, and **Random Forest**.

The performance of each model is evaluated using metrics such as **Accuracy, Precision, Recall, F1-Score, Classification Report, and Confusion Matrix**. A comparison of these models helps identify the most effective algorithm for detecting fraudulent transactions. In this project, the best-performing model is saved using the Joblib library, allowing it to be reused for predicting new transactions.

The project demonstrates the complete Machine Learning workflow, including data loading, preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, comparison, and deployment readiness. It provides a practical solution for detecting fraudulent credit card transactions and serves as an excellent learning project for understanding real-world applications of Machine Learning in the financial sector.
