# Credit_Risk_Analysis

Supervised Machine Learning


## Analysis Overview

Perform credit risk analysis using imbalanced-learn and scikit-learn libraries to build and evaluate Supervised Machine learning Models using resampling techniques where models with unbalanced classes are trained and evaluated, in order to write a recommendation on whether any of them should be used to predict credit risk.


Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, to oversample the data using the following machine learning models and their algoriths:
- Oversampling Model
    - RandomOverSampler Algorithm
    - SMOTE Algorithm
- Undersampling Model:
    - ClusterCentroids Algorithm
- Combination Over- and Undersampling Model
    - SMOTEEN Algorithm
- Reducing Bias Models:
    - BalancedRandomForestClassifier
    - EasyEnsembleClassifier




## Results

### Random Oversampling

![randomOverSampler_classification_report](./Resources/randomOverSampler_classification_report.png)

### SMOTE Oversampling

![SMOTE_over_sampling_classification_report](./Resources/SMOTE_over_sampling_classification_report.png)


### Cluster Centroids Undersampling

![undersampling_classification_report](./Resources/undersampling_classification_report.png)

### SMOTEENN Combination Under and Over Sampling

![smoteenn_classification_report](./Resources/smoteenn_classification_report.png)


### Balanced Random Forest Classifier - Ensemble Learner

![brfc_classification_report](./Resources/brfc_classification_report.png)

### Easy Ensemble AdaBoost Classifier

![eec_classification_report](./Resources/eec_classification_report.png)


### 2nd Test on Balanced Random Forest Classifier - Ensemble Learner



## Summary

### Model Accuracy

![model_accuracy_results](./Resources/model_accuracy_results.png)


![model_accuracy_results1](./Resources/model_accuracy_results1.png)



-------------------------------------------------------------------------------------------------------------------------------
For this deliverable, you’ll write a brief summary and analysis of the performance of all the machine learning models used in this Challenge.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

----------------------
Analysis (24 points)
The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)

Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)