# Credit_Risk_Analysis

## Overview of the analysis: 
During our analysis, we will be exploring which supervised Machine Learning Model that will satisfy the prediction of credit risk. we will be covering 
RandomOverSampler, SMOTE and OverSampling algorithms; other algorithm that we will user are Undersampling, ClusterCentroids and SMOTEENN. 
we will train our models using credit card dataset from LendingClub, the models are BalancedRandomClassifier and EasyEnsembleClassifier to help us reduce bias.


## Results: 

### Random OverSampling 
- Balanced accuracy score
    the model scores with the balanced Accuracy score of 62.49%, there is a decline in the performance comparing to innital traing and testing scores
    it maybe due to oversampling the model.

![Balanced_accuracy_score](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Balanced_accuracy_score_RandomOverS.PNG)

- Confusion Matrix: 
    as shown below there is an  significant increase in false Positive(FP) number, there is more accuracy in predicting low credit risk. 

![Confusion_Matrix](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Confusion_Matrix_RandomOverS.PNG)

- Imbalanced Classification Report
    the average total of predicting low credit risk is 65% as shown below, and 60% for high risk

![Imbalanced_Classification_Report](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Imbalanced_Classification_Report_RandomOverS.PNG)

### SMOTE
- Balanced accuracy score is 65.12%, there is an improvement of accuracy comparing to our model of RandomOverSampling.

- Confusion Matrix : as shown below the prediction of low credit risk is high and for high credisk risk is very low

![Confusion_Matrix](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Confusion_Matrix_SMOTE.PNG)

- Imbalanced Classification Report : the classification report is showing an improvement for average total prediction of low risk to 66% while for high credit 
risk is 64%

![Imbalanced_Classification_Report](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Imbalanced_Classification_Report_SMOTE.PNG)

### ClusterCentroids

- Balanced accuracy score : the balance accuracy score is 62.49%

- Confusion Matrix 

![Confusion_Matrix](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Confusion_Matrix_ClusterCentroids.PNG)

- Imbalanced Classification Report

![Imbalanced_Classification_Report](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Imbalanced_Classification_Report_ClusterCentroids.PNG)

### SMOTEENN

- Balanced accuracy score : the balance accuracy score is 61.63%

- Confusion Matrix

![Confusion_Matrix](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Confusion_Matrix_SMOTEENN.PNG)

- Imbalanced Classification Report : the combination method of SMOTEEN has improved high credit recall up to 69% while the low credit risk is 54%

![Imbalanced_Classification_Report](https://github.com/elzmanzi/Credit_Risk_Analysis/blob/main/Resource/Imbalanced_Classification_Report_SMOTEENN.PNG)

### Balanced Random Forest Classifier 
- Balanced accuracy score using BalancedRandomClassifier is almost 79%

- Confusion Matrix

![Confusion_Matrix]()

- Imbalanced Classification Report

![Imbalanced_Classification_Report]()

### Easy Ensemble Classifier 

- Balanced accuracy score using easy ensemble classifier is 93% which is more that 13% from Balanced Random classifier

- Confusion Matrix

![Confusion_Matrix]()

- Imbalanced Classification Report

![Imbalanced_Classification_Report]()

## Summary: 
By seeing the result ahead we can conclude that the best suitable models are BalancedRandomClassifier and EasyEnsembleClassifier. But EasyEnsembleClassifier is the best suited for our analysis among the rest.
