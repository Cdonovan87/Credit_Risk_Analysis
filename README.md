# Credit_Risk_Analysis
## Overview
For this challeneg I was tasked with running algorithms on credit risk. I was to train and test 6 different algorithms and then to evaluate  these different models and then write a report on a recommendation on if these models should be used to predict potential credit risk.
## Results
* RandomOverSampler
   * Balanced Accuracy : 63%
   * High Risk
      * Precision : 1%
      * Sensitivity : 62%
      * f1 : 2%
   * Low Risk
      * Precision : 100%
      * Sensitivity : 65%
      * f1 : 79%
* Smote
   * Balanced Accuracy : 63%
   * High Risk
      * Precision : 1%
      * Sensitivity : 62%
      * f1 : 2%
   * Low Risk
      * Precision : 100%
      * Sensitivity : 64%
      * f1 : 78%
* ClusterCentroids
   * Balanced Accuracy : 51%
   * High Risk
      * Precision : 1%
      * Sensitivity : 60%
      * f1 : 1%
   * Low Risk
      * Precision : 100%
      * Sensitivity : 43%
      * f1 : 60%
* SMOTEEN
   * Balanced Accuracy : 62%
   * High Risk
      * Precision : 1%
      * Sensitivity : 71%
      * f1 : 2%
   * Low Risk
      * Precision : 100%
      * Sensitivity : 54%
      * f1 : 70%
* BalancedRandomForestClassifier
   * Balanced Accuracy : 79%
   * High Risk
      * Precision : 4%
      * Sensitivity : 67%
      * f1 : 7%
   * Low Risk
      * Precision : 100%
      * Sensitivity : 91%
      * f1 : 95%
* EasyEnsembleClassifier
   * Balanced Accuracy : 92%
   * High Risk
      * Precision : 7%
      * Sensitivity : 91%
      * f1 : 14%
   * Low Risk
      * Precision : 100%
      * Sensitivity : 94%
      * f1 : 97%

## Summary
Based on the above results I would reccomend the EasyEnsembleClassifier model to be used. Looking at its results we see that it has the highest balanced accuracy score at 92% whereas all the other models came in a range of 50% to around 70%. It also the highest f1 scores for both high and low risk compared to all the other models. The BalancedRandomForestClassifier model could also be potentially used as it has a accuracy score of 79%  but its precision, sensitivity and f1 scores for both low and high risk are a little to low for this model to be reliable like the one mentioned before.
