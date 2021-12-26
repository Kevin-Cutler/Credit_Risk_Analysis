# Credit_Risk_Analysis

## Overview of the analysis: 
 
Working as a data analyst for a credit lending company a peer-to-peer lending services company, I have provided my expertise in machine learning to predict credit risk and offer a more accurate loan experience. In my time with lending company, I have developed my skills in data preparation, statistical reasoning, and machine learning. Leadership have approached me with a real-world problem where we will perform an analysis on a credit card credit dataset to predict credit risk. Using Machine Learning I will oversample the data using the RandomOverSampler and SMOTE algorithms, and under sample the data using the Cluster Centroids algorithm. I will use a combinatorial approach of over- and under sampling using the SMOTEENN algorithm. 
I will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once I am done, I will evaluate the performance of the models and provide a written recommendation on whether they should be used to predict credit risk.

1. Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Use Resampling Models to Predict Credit Risk

* Create the training variables by converting the string values into numerical ones using the get_dummies() method.
* Create the target variables.
* Check the balance of the target variables.


* For all three algorithms, the following have been completed:
o An accuracy score for the model is calculated (7.5 pt)
o A confusion matrix has been generated (7.5 pt)
o An imbalanced classification report has been generated (15 pt)

## Use the SMOTEENN algorithm to Predict Credit Risk 

* The combinatorial SMOTEENN algorithm does the following:
o An accuracy score for the model is calculated (5 pt)
o A confusion matrix has been generated (5 pt)
o An imbalanced classification report has been generated (5 pt)


## Use Ensemble Classifiers to Predict Credit Risk 

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





