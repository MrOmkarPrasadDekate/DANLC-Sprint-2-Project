# DANLC-Sprint-2-Project

Credit Card Fraud Detection
This project focuses on detecting fraudulent credit card transactions using machine learning. The data is initially transferred from a CSV file to a MySQL database to ensure robust data storage and efficient querying. The project is implemented in Python and includes data preprocessing, exploratory data analysis, and model training to identify fraudulent transactions.

Project Overview
The goal is to predict fraudulent credit card transactions by analyzing transaction data. The workflow includes loading and processing data from a MySQL database, training classification models, and evaluating their performance.
In this project we have used "Logistic Regression algorithm" for making predictions and "Accuracy Score" for model evaluation.

Dataset
The dataset used for this project, creditcard.csv, contains anonymized credit card transactions with class labels:

0: Genuine transactions

1: Fraudulent transactions

Note: 
  1. The dataset is highly imbalanced.
  2. Dataset is obtained from Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Data Source
The data is initially imported from creditcard.csv into a MySQL database for efficient access and manipulation. The CreditCardFraudDetection.ipynb notebook then connects to the database to fetch data and proceed with analysis.
