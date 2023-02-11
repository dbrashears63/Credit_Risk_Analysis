# Credit_Risk_Analysis

## Overview of the analysis:
Machine learning was applied to solve a real-world challenge. Our primary focus will be credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were employed to train and evaluate models with unbalanced classes. The Python imbalanced-learn and scikit-learn libraries were used to build and evaluate models using resampling. Within these libraries the following techniques were employed Naïve Random Oversampling, SMOTE Oversampling, Undersampling, Combination (Over and Under) Sampling. In order to reduce bias BalancedRandomForestClassifier and EasyEnsembleClassifier techniques were used.

## Results:
The results for the machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/113568268/218285841-381d3be9-ffbb-4bf8-a03e-bff682e1b0c7.png)

1.	Balanced Accuracy: 0.6839
2.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3.	Recall: High/Low risk = .66/.68


### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/113568268/218285866-f81e08bd-f58a-4387-abac-c7cfe9f82d24.png)

1.	Balanced Accuracy: 0.6691
2.	Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3.	Recall: High/Low risk = .69/.68

### Undersampling
![image](https://user-images.githubusercontent.com/113568268/218285899-b001a9be-f56a-4f6e-a792-27579c5c0c34.png)

1.	Balanced Accuracy: 0.6839
2.	Precision: Precision is low for high-risk loans and high for Low-risk loans.
3.	Recall: High/Low risk = .69/.68


### Combination Under-Over Sampling
![image](https://user-images.githubusercontent.com/113568268/218285910-e464d36b-7724-43dd-b56a-1209d478256d.png)
1.	Balanced Accuracy: 6839
2.	Precision: Precision is low for High-risk loans and high for Low-risk loans.
3.	Recall: High/Low risk = .69/.68

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/113568268/218285940-5cb84dc4-7a68-4196-a6a1-94c9f9d7e758.png)

1.	Balanced Accuracy: 0.7882
2.	Precision: Precision is low for high-risk loans and high for Low-risk loans.
3.	Recall: High/Low risk = .90/68

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/113568268/218285984-29f2f60a-7fac-426b-8bcf-f7f870f43391.png)
1.	Balanced Accuracy: 0.9298
2.	Precision: Precision is low for high-risk loans and high for Low-risk loans.
3.	Recall: High/Low risk = .91/.94

## Summary:
The compared accuracies were measured between 0 and 1. The closer to 1, the better the score. The Easy Ensemble AdaBoost Classifier is the strongest model with .9298 accuracy. The other data models were less accurate. The precision fell within a similar range of each other. 
























