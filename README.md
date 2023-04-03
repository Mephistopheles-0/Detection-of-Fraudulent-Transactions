# Fraud Detection using Classification Models
This notebook explores the use of classification-based machine learning models to identify fraudulent transactions in financial datasets. The finance sector faces a significant problem of fraud, with organizations losing an estimated 5% of their annual revenue to fraud each year. This equates to potential global losses of up to $5.1 trillion.

Machine learning is well-suited for fraud detection tasks, as it can efficiently scan through large datasets of transactions, identify unusual patterns of behavior, and flag potentially fraudulent cases. In this notebook, we will explore several classification-based models that can distinguish between normal payments and fraudulent transactions.

## Data
The dataset used in this notebook contains information on credit card transactions and whether they are fraudulent or not. It consists of 284,807 transactions, with 492 of them being fraudulent. The dataset has 30 features, all of which are numerical and have been anonymized for privacy reasons.

## Models Explored
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting Classifier
- and more...

## Evaluation Metrics
Since the dataset is imbalanced, with only a small percentage of fraudulent transactions, accuracy is not an appropriate metric for evaluation. Instead, we will use the following evaluation metrics:

- Precision: The number of true positives divided by the total number of positive predictions (true positives + false positives)
- Recall: The number of true positives divided by the total number of actual positives (true positives + false negatives)

## Conclusion
Based on the evaluation metrics, the Random Forest Classifier and Gradient Boosting Classifier perform well in detecting fraudulent transactions, with AUPRC values of 0.77 and 0.80, respectively. These models can be used by financial institutions to
