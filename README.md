# Credit-Card-Fraud-Detection
It is important that credit card companies are able to recognize fraudulent credit card transactions so that 
customers are not charged for items that they did not purchase.

![App Screenshot](https://www.xenonstack.com/hubfs/xenonstack-credit-card-fraud-detection.png)

# Dataset(Taken from Kaggle)
The dataset contains transactions made by credit cards in September 2013 by European cardholders. 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data.
# Algorithms Used
1. Isolation Forest Algorithm 
2. Local Outlier Factor(LOF) Algorithm
# Results
1. Isolation forest detected 71 erros , while Local Outlier detection detected 97 errors.
2. Isolation forest has accuracy of 99.75%, while Local Outlier detection has accuracy of 99.65%.
3. Overall Isolation forest performed much better if we take the precison scores also into the account.

