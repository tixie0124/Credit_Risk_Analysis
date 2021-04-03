# Credit_Risk_Analysis
## Overview of Analysis
The purpose of this analysis is to analyze the precision, sensitivity and other matrix of the machine learning models, which implements various data sampling techniques in predicting credit risk for LendingClub, a peer-to-peer lending company. The performance of the models are analyzed and a recommendation of the most applicable model is made. The techniques were used in the model include: oversampling, undersampling, a combination of both, and the SMOTE algorithm.
<br />
<br />

## Results
- **Naive Oversampling**<br />
![alt text](https://github.com/tixie0124/Credit_Risk_Analysis/blob/main/resources/naive_oversampling.PNG)
<br />
<br />
<br />

- **SMOTE Oversampling**
![alt text](https://github.com/tixie0124/Credit_Risk_Analysis/blob/main/resources/SMOTE_oversampling.PNG)
<br />
<br />
<br />

- **Under Sampling**<br />
![alt text](https://github.com/tixie0124/Credit_Risk_Analysis/blob/main/resources/under_sampling.PNG)
<br />
<br />
<br />

- **Combination(Oversampling and Undersampling)**<br />
![alt text](https://github.com/tixie0124/Credit_Risk_Analysis/blob/main/resources/combination.PNG)
<br />
<br />
<br />

- **Balanced Random Forest Classifier**<br />
![alt text](https://github.com/tixie0124/Credit_Risk_Analysis/blob/main/resources/balanced_random_forest_classifier.PNG)
<br />
<br />
<br />

- **Adaptive Boosting**<br />
![alt text](https://github.com/tixie0124/Credit_Risk_Analysis/blob/main/resources/adaboost_classifier.PNG)
<br />
<br />
<br />

## Summary
The purpose of assessing the credit risk is to reduce the risk of missing payment or even default for the lendor. It is more important to eliminate false negatives than false positives because the loss of a default for a lender significantly exceeds the loss in profit in case of a false positive. We don't want a high-risk customer to slip into the low-risk bracket.  Therefore, sensitivity should be the most important matrix that we look at. The results indicate that the model with adaptive boosting has the highest sensitivity on both high-risk and low-risk. This should be the model that we pick in current situation.
