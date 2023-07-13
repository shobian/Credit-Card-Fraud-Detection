# Credit-Card-Fraud-Detection

Introduction:

This repository contains a credit card fraud detection model developed using logistic regression. The goal of the project was to create a binary solution for detecting fraudulent credit card transactions. The dataset used for training and evaluation consisted of anonymized transaction features derived from real credit card transactions.

Dataset:

The dataset used for this project contains 284,807 credit card transactions, out of which 492 transactions are labeled as fraudulent (class 1), while the remaining transactions are legitimate (class 0). To address the class imbalance issue, undersampling techniques were applied to balance the dataset, resulting in an equal number of legitimate and fraudulent transactions (492 each).

The "Credit Card Fraud Detection" dataset available on Kaggle is a collection of credit card transactions aimed at detecting fraudulent activities. It contains a total of 284,807 transactions, of which 492 are labeled as fraudulent (0.172% of the total). The dataset is highly imbalanced, with the majority of transactions being legitimate.

Each transaction in the dataset is represented by 31 columns, including the "Time" column representing the time elapsed in seconds between the current transaction and the first transaction in the dataset. The "Amount" column indicates the transaction amount, while the "Class" column denotes the class label, where 1 indicates a fraudulent transaction and 0 represents a legitimate transaction.

To protect user privacy, most of the features in the dataset have been transformed through a Principal Component Analysis (PCA) transformation. As a result, the original features are not available, and instead, the transformed features (V1, V2, ..., V28) are provided. Additionally, there are two additional non-transformed features: "Time" and "Amount."

The dataset was created using real credit card transactions from European cardholders, which span a two-day period in September 2013. Due to privacy concerns, the original features have been transformed to maintain the confidentiality of sensitive information.

The purpose of this dataset is to develop and evaluate machine learning models that can effectively identify fraudulent credit card transactions based on the provided features. Researchers and data scientists can utilize this dataset to explore and develop various fraud detection algorithms, including supervised learning, anomaly detection, or fraud pattern analysis.

By analyzing this dataset, researchers can investigate different strategies for detecting fraudulent transactions, such as feature engineering, ensemble methods, or anomaly detection techniques. The dataset serves as a valuable resource for developing and testing credit card fraud detection systems and enhancing security in financial transactions.


Model Approach:

A logistic regression model was chosen as the primary approach for fraud detection. Logistic regression is a widely used classification algorithm that works well for binary classification tasks. The model was trained on the balanced dataset, leveraging the transformed features (V1 to V28), time, and amount columns provided in the dataset.
