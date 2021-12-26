# Credit_Risk_Analysis

## Overview of the analysis: 
_________________________________________________________________________
 
Working as a data analyst for a peer-to-peer lending services company, I have provided my expertise in machine learning to predict credit risk and offer a more accurate loan experience for customers and my company. In my time with lending company, I have developed my skills in data preparation, statistical reasoning, and machine learning. Leadership have approached me with a real-world problem where we will perform an analysis on a credit card dataset to predict credit risk. Using Machine Learning I will oversample the data using the RandomOverSampler and SMOTE algorithms and under sample the data using the Cluster Centroids algorithm. I will use a combinatorial approach of over- and under sampling using the SMOTEENN algorithm. I will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once I am done, I will evaluate the performance of the models and provide a written recommendation on whether they should be used to predict credit risk.

### Results:
_____________________________________________________________________

* I begin my analysis of the data by reading in the creadit card dataset CSV and cleaning the data to split my independent and dependent variables to be loaded as the Test and Training sets to perform our Machine Learning Analysis. 

![image](https://user-images.githubusercontent.com/88467263/147421160-2d9c8d1a-d8d8-4991-8da7-a677ad2a76f7.png)


## Use Resampling Models to Predict Credit Risk

![image](https://user-images.githubusercontent.com/88467263/147421270-3e29dbb3-abec-4862-a24e-1710231f6747.png)



## Use the SMOTEENN Oversampling RandomOverSampler algorithm to Predict Credit Risk 

![image](https://user-images.githubusercontent.com/88467263/147421302-40f4bcab-ee83-4a8d-a8f5-7c513daf2cd4.png)

## Use the SMOTEENN Undersampling ClusterCentroids algorithm to Predict Credit Risk 

![image](https://user-images.githubusercontent.com/88467263/147421325-49f03e0f-9bac-4e45-b857-a65f2e20de6e.png)


## Perform logistic regression: Use Ensemble Classifiers to Predict Credit Risk 

* The BalancedRandomForestClassifier algorithm does the following:
o An accuracy score for the model is calculated (2.5 pt)
o A confusion matrix has been generated (2.5 pt)
o An imbalanced classification report has been generated (5 pt)
o The features are sorted in descending order by feature importance (5 pt)
* The EasyEnsembleClassifier algorithm does the following:
o An accuracy score of the model is calculated (2.5 pt)
o A confusion matrix has been generated (2.5 pt)
o An imbalanced classification report has been generated (5 pt)
* Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.





