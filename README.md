# Credit_Risk_Analysis
## Background and Objectives:
* Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
* Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results Observations and :
### Balanced Random Forest Classifier

The Balanced Random Forest Classifier is an ensemble method in which each tree of the forest will be provided a balanced bootstrap sample of the training data. No oversampling or undersampling techniques is performed prior to training, after the train/test split.

Results:

* Accuracy: 78.78%
* High-Risk Precision: 0.04
* Low-Risk Precision: 1.00
* High-Risk Recall: 0.67
* Low-Risk Recall: 0.91
* High-Risk F1 Score: 0.07
* Low-Risk F1 Score: 0.9

Confusion Matrix:

![](https://github.com/Spandanson/Credit_Risk_Analysis/blob/master/Resources/confusion%20matrix%20ramdom%20forest%20classifier.png)

Classification Report:

![](https://github.com/Spandanson/Credit_Risk_Analysis/blob/master/Resources/classification%20report%20radom%20forest%20classifier.png)

Important Features:

![](https://github.com/Spandanson/Credit_Risk_Analysis/blob/master/Resources/Important%20Features.png)
