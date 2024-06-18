# Online Payment Fraud Detection

## Introduction
This project aims to detect fraudulent transactions in an online payment system. By leveraging machine learning models, we aim to identify transactions that are likely to be fraudulent, helping to prevent financial losses and protect users' data.

## Dataset
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection). It contains various features of online transactions including the amount, transaction type, and whether the transaction is fraudulent.

### Dataset Description
- **step**: Time step in hours.
- **type**: Type of transaction.
- **amount**: The amount of the transaction.
- **nameOrig**: Customer identifier.
- **oldbalanceOrg**: Initial balance before the transaction.
- **newbalanceOrig**: New balance after the transaction.
- **nameDest**: Merchant identifier.
- **oldbalanceDest**: Initial balance of the merchant before the transaction.
- **newbalanceDest**: New balance of the merchant after the transaction.
- **isFraud**: Whether the transaction is fraudulent (1) or not (0).

## Conclusion
This project demonstrates the application of machine learning models to detect fraudulent transactions in an online payment system. The XGBoost Classifier showed promising results, making it a viable option for deployment in real-world scenarios.

## References
- XGBoost Documentation
- Scikit-learn Documentation 