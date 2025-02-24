# Online Payment Fraud Detection using Machine Learning

# Overview
Online payment fraud has become a significant concern with the rise of digital transactions. This project focuses on detecting fraudulent transactions using machine learning techniques. The dataset contains transaction details, and we apply various preprocessing techniques, machine learning models, and evaluation metrics to identify fraud effectively.

# Dataset

The dataset contains multiple features related to online payment transactions. Some of the key attributes include:

* step – Represents the unit of time within the dataset.
* type – Type of transaction (e.g., CASH_OUT, TRANSFER, PAYMENT).
* amount – The amount of money transferred.
* nameOrig – ID of the sender.
* oldbalanceOrg – Initial balance of the sender before transaction.
* newbalanceOrig – New balance of the sender after transaction.
* nameDest – ID of the recipient.
* oldbalanceDest – Initial balance of the recipient before transaction.
* newbalanceDest – New balance of the recipient after transaction.
* isFraud – A binary indicator (1 = fraudulent, 0 = legitimate).
* isFlaggedFraud – Indicates if the transaction was flagged as fraudulent.

# Data Preprocessing

* Identifying and handling missing values.
* Encoding categorical variables using techniques such as One-Hot Encoding.
* Standardizing and normalizing numerical features.
* Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

# Model Training

* Several machine learning models were trained and evaluated to identify fraudulent transactions:
* Logistic Regression – A simple yet effective linear model.
* XGBoost Classifier – A powerful gradient boosting model.
* Random Forest Classifier – An ensemble learning method for improved accuracy.

# Evaluation Metrics
To evaluate the models effectively, the following performance metrics were used:

* Confusion Matrix – To visualize false positives and false negatives.
* ROC-AUC Score – To measure the model’s ability to distinguish between fraud and non-fraud transactions.

# Technologies Used

* Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
* Machine Learning (Logistic Regression, Random Forest, XGBoost)
* Data Preprocessing (One-Hot Encoding, Feature Scaling, SMOTE)
* Model Evaluation (ROC-AUC, Confusion Matrix, Precision-Recall)

# Future Improvements
Possible future improvements include:

* Implementing Deep Learning models for fraud detection.
* Using Anomaly Detection techniques to enhance fraud identification.
* Incorporating Real-Time Fraud Detection using streaming data.
