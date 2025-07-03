# Credit-Card-Fraud-Detection 

# Project Overview
This project focuses on detecting fraudulent credit card transactions using data analysis and machine learning. Since fraud is rare and the dataset is highly imbalanced, special techniques such as under-sampling and over-sampling are applied to improve model performance and ensure fair evaluation.

# Objective
To build a reliable classifier that distinguishes between legitimate and fraudulent transactions, with proper handling of data imbalance.

# Key Steps

### 1. Data Preprocessing
- Removed duplicate records and dropped irrelevant features.
- Scaled numerical features using `StandardScaler` for model compatibility.
- Checked for null values and ensured data integrity.

### 2. Class Imbalance Handling
- Used **under-sampling** to balance the majority and minority classes.
- Applied **over-sampling (SMOTE)** to synthetically balance the dataset.

### 3. Exploratory Data Analysis (EDA)
- Visualized the distribution of fraudulent vs. non-fraudulent transactions.
- Analyzed patterns in transaction amount and time.

### 4. Model Building
- Built and evaluated a **Logistic Regression** classifier.
- Compared model performance across original, under-sampled, and over-sampled datasets.

# Results
- The model performed significantly better on balanced datasets.
- Using SMOTE (over-sampling) yielded improved recall for fraud detection, which is crucial in real-world applications.
