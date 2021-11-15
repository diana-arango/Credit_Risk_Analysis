# Credit_Risk_Analysis
Supervised Machine Learning and Credit risk 
## Overview
By applying the skills learnt thru the module regarding data preparation, statistical reasoning and machine learning it is expected on this analysis to use imbalance-learn and scikit-learn libraries to evaluate the performance of six machine learning models: RandomOverSample, ClusterCentroids, BalancedRandomForestClassifier  and EasyEnsembleClassifier when predicting credit risk for a lending services company named LendingClub.

## Results
###	Credit_risk_resampling
#### Random oversampling 
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit_risk_resampling/Random%20oversampling.png

#### Oversampling
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit_risk_resampling/Oversampling.png

#### SMOTE Oversampling
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit_risk_resampling/SMOTE%20Oversampling.png

#### Balanced Random Forest Classifier 
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit_risk_resampling/o%20Balanced%20Random%20Forest%20Classifier%20.png

#### Easy Emsemble AdaBoost Classifier
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit_risk_resampling/o%20Easy%20Emsemble%20AdaBoost%20Classifier.png

*Learning modules used to predict credit risk: 
Random oversampling 
Oversampling
Smote Oversampling
Balanced Random Forest Classifier 
Easy Emsemble AdaBoost Classifier

1.	The performance of most of the modules, was imbalanced to determine the accuracy of the risk of a loan. 
a.	Their precision ranked between 0.01 to 0.04% to predict high risk loans
b.	Their rec for predicting high risk loans was over 50% of probability however their prediction was imbalance in comparison to predict low risk loans which were between 70 to 80 % 
c.	On the other hand, Module: Easy Emsemble AdaBoost Classifier precision was closer to a perfect deviation .09. Its rec were close enough between 0.89 for high risk and 0.94 for low_ risk. Nevertheless the distance between high risk and low risk on the F1 column were substantially distant

### Credit risk ensemble

#### Balanced Random Forest Classifier
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit%20risk%20ensemble/Balanced%20Random%20Forest%20Classifier.png

#### Easy Ensemble AdaBoost Classifier 
https://github.com/diana-arango/Credit_Risk_Analysis/blob/main/Pictures/Credit%20risk%20ensemble/Easy%20Ensemble%20AdaBoost%20Classifier%20.png

*Learning modules used to predict credit risk: 
Balanced Random Forest Classifier
Easy Ensemble AdaBoost Classifier

1.	On the Easy Ensemble AdaBoost Classifier the precision to predict high risk load was 0.09, close to predict low risk loans with 1 points of precision. Rec values for both risks options were close predicted with .89 and .94 respectively. F1, On the other hand, didn’t predicted a balance percentage high risk were just 0.16 points while low risk loans were 0.97 
2.	On the Balanced Random Forest Classifier Precision was .04 points for high risk loans in comparison to 1 for low risks, rec was imbalance for the model as the high risk prediction loans were far from be closer to low risk loans which has .89 points 



## Summary 
Summarize the results  of the machine learning models 
Recommedation on the model to use 
