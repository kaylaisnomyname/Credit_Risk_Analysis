# Credit_Risk_Analysis

## Overview  
The purpose of this challenge is to test and compare the performance of six machine learning models on predicting credit risk using a credit card dataset from LendingClub. The six models are RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifer. 

## Results
The following are the balanced accuracy scores, precision, and recall scores for each model:
- Random Over Sampling:              0.6346, 0.99, 0.53  
- SMOTE:                             0.6321, 0.99, 0.66  
- Cluster Centroids:                 0.5316, 0.99, 0.39  
- SMOTEENN:                          0.6471, 0.99, 0.58  
- Balanced Random Forest Classifier: 0.7665, 0.99, 0.89  
- Easy Ensemble Classifier:          0.9316, 0.99, 0.94   

Screenshots of the results are shown below:  
1. RandomOverSampling  
![link](https://github.com/kaylaisnomyname/Credit_Risk_Analysis/blob/main/results/randomOverSampling.png?raw=true)  

2. SMOTE  
![link](https://github.com/kaylaisnomyname/Credit_Risk_Analysis/blob/main/results/SMOTE.png?raw=true)  
3. ClusterCentroid  
![link](https://github.com/kaylaisnomyname/Credit_Risk_Analysis/blob/main/results/clusterCentroids.png?raw=true)
4. SMOTEEN  
![link](https://github.com/kaylaisnomyname/Credit_Risk_Analysis/blob/main/results/SMOTEENN.png?raw=true)
5. BalancedRandomForestClassifier
![link](https://github.com/kaylaisnomyname/Credit_Risk_Analysis/blob/main/results/BalancedRandomForestClassifier.png?raw=true)
6. EasyEnsembleClassifier  
![link](https://github.com/kaylaisnomyname/Credit_Risk_Analysis/blob/main/results/EasyEnsembleClassifier.png?raw=true)

## Summary
In summary, Easy Ensemble Classifier has the best performance among these six models, with a high balanced accuracy score of 0.93, precision of 0.99, recall of 0.94. For this dataset, a model recommendation will be Easy Ensemble Classifier as it out performs the rest of the testing models.  
