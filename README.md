# Credit Risk Analysis


## Overview of the analysis: 
Using the LendingClub credit card dataset to predict credit card risk by evaluating the following models:
  a) Oversample: RandomOverSampler and SMOTE algorithms.
  b) Undersample: ClusterCentroids algorithm. 
  c) Combinatorial (over/undersampling): SMOTEENN algorithm.
  d) Machine learning models that reduce bias: BalancedRandomForestClassifier and EasyEnsembleClassifier.

# 
## Deliverables:
 - Deliverable 1: Use Resampling Models to Predict Credit Risk
 - Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
 - Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
 - Deliverable 4: A Written Report on the Credit Risk Analysis


#
## Tools:
  - Github
  - Gitbash
  - Jupyter Notebook
  - Anaconda
  - Python


# 

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

- Naive Random Oversampling:
The balanced accuracy for this method was 65.3%. The high-risk precision was 1% and recall was around 61%. For the low-risk, precision was 100% while recall was 70%.
![Naive Random Oversampling](/PNGs/NaiveRandom_Oversampling.png)

- SMOTE:
The balanced accuracy for this method was 62.64%. The high-risk precision was 1% and recall was  around 61%. For the low-risk, precision was 100% while recall was 64%.
![SMOTE](/PNGs/SMOTE_Oversampling.png)

- Cluster Centroid:
The balanced accuracy for this method was 52.93%. The high-risk precision was 1% and recall was around 61%. For the low-risk, precision was 100% while recall was 45%.
![Cluster Centroid](/PNGs/ClusterCentroid_undersampling.png)

- SMOTEEN:
The balanced accuracy for this method was 63.75%. The high-risk precision was 1% and recall was around 70%. For the low-risk, precision was 100% while recall was 57%.
![SMOTEEN](/PNGs/SMOTEENN_OverUnderSampling.png)

- Balance Random Forest Classifier:
The balanced accuracy for this method was 74.09%. The high-risk precision was 1% and recall was around 51%. For the low-risk, precision was 100% while recall was 98%.
![Balance Random Forest Classifier](/PNGs/BalancedRandomForestClassifier.png)

- Easy Ensemble Classifier:
The balanced accuracy for this method was 92.54%. The high-risk precision was 7% and recall was around 91%. For the low-risk, precision was 100% while recall was 94%.
![Easy Ensemble Classifier](/PNGs/EasyEnsembleClassifier.png)


#
## Summary: 
Oversampling, undersampling, and combinatorial methods were less accurate than the two ensemble models. The balance accuracy rates for those models ranged between 52.93% to 65.3%. The ensemble models ranged between 72.09% to 92.54%. High-risk precision was consistently at 1% for all methods except for the Easy Ensemble Classifier model at 7%. High-risk recall ranged between 51-70%, with the exception of the Easy Ensemble Classifier model at 91%. For low-risk precision, all models performed at 100%. For low-risk recall, the oversampling, undersampling, and combinatorial methods models were between 45-70%. Both classifier methods performed above 94%. All things considered, the Easy Ensemble Classifier seems to be the most efficient and accurate method, followed closely by the Balance Random Forest Classifier method.