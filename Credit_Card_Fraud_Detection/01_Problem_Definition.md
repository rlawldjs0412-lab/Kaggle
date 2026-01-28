# 01 Problem Definition

## 1️⃣ Project Basic Information

- Project Title : Credit Card Fraud Detection
- Data Set Name : Credit Card Fraud Detection
- Data Source : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

## 2️⃣ Problem Definition

1. Prediction Target

   The goal is to protect whether a credit card transaction is fraudulent or not.

2. Target Valuable

   Class, which represents the transaction lable.

3. Target Value Meaning

- '0' indicates a normal(legitimate) transaction.
- '1' indicates a fraudulent transaction.

4. Problem Type

   This is a supervised learning problem and specifically a binary classification task.

## 3️⃣ Input Data Overview

1. Data Unit

   Each row of data means each credit transaction.

2. Input Features

   Input data is made up by numbered variable which indicates characteristic of transaction.

3. Feature Characteristic

   The variables from 'v1' to 'v28' are anonymizated which is adapted PCA conversion for protecting presonal information.

4. Interpreable Features

   'time' and 'Amount' is containing their original meaning and offer informations that transaction time and amount.

## 4️⃣ Data Characteristics

1. Class Imbalance

   This data set is class extremity unbalanced data which has very row percent of fraud transaction. Almost transactions are normal, fraud transactions are very few of all data.

2. Feature Structure

   Almost input variables are indicated in numbered variable which is already adapted PCA conversion. Due to this, deference of scale between variables is not big, it is hard to translate eaches meaning directly.

3. Data Quality

   A few of missing value and almost are arranged data. Distribution of data and understanding feature of class are more important than additional missing value proceeding.

## 5️⃣ Why This Problen Is Challenging

1. Severe Class Imbalance
