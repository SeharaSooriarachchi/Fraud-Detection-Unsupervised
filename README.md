# Unsupervised Fraud Transaction Detection
# Project Overview
This project applies unsupervised machine learning techniques to detect potentially fraudulent transactions in a financial dataset without the need for labeled data. Fraud detection is crucial in the financial sector, where rapid identification of anomalous behavior can prevent financial loss and fraud escalation.
# Techniques Used

Exploratory Data Analysis (EDA)

K Prototypes

Classification Models

Feature Engineering

SHAP plot

# Dataset
Publicly available Kaggle Dataset:

https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection/data

#Results
After applying unsupervised learning techniques to detect anomalies in transaction data, a set of potential fraud cases was identified based on their deviation from normal transaction patterns. These anomalies were visualized and analyzed using PCA, which showed clear separation from the majority of transactions.

To further validate and refine the detection process, the identified anomalies were labeled as fraudulent, and the remaining transactions were labeled as non-fraudulent. This allowed the use of supervised classification models to learn patterns from these newly labeled instances and improve detection accuracy.

# Future Work

Add semi-supervised learning layer with some labeled samples.

Real-time streaming detection.

Better visualization of detected anomalies.

Deploy the model via a simple Streamlit app or Flask API.



