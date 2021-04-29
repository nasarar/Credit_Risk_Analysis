# Credit_Risk_Analysis

## Project Overview
Since identifying credit risks is naturally an unbalanced classification problem, imbalanced-learn and scikit-learn libraries are used to build and evaluate the machine learning models. To get around the severely skewed class distribution, an oversampling and undersampling techniques are used with RandomOverSampler, SMOTE, and SMOTEENN algorithms. Following the sampling, BalancedRandomForestClassifier and EasyEnsembleClassifier machine learning models are compared in order to reduce any forms of bias. These models are also used to predict the credit risk.


## Resources
-Data Source: LoanStats_2019Q1.csv

-Software: Jupyter Notebook 6.2.0

## Results
- Naive Random Oversampling: The balanced accuracy score is 65% while the high risk precision is 1% and recall is 69%.  
- SMOTE: The balanced accuracy score is 65% while the high risk precision is 1% and recall is 69%.
- Undersampling: The balanced accuracy score is 65% while the high risk precision is 1% and recall is 69%.
- Combination: The balanced accuracy score is 64% while the high risk precision is 1% and recall is 78%.
- Balanced Random Forest Classifier: The balanced accuracy score is 75.9% while the high risk precision is 3% and recall is 63%.
- Easy Ensemble AdaBoost Classifier: The balanced accuracy score is 93.1% while the high risk precision is 9% and recall is 92%.

## Summary
The analysis of the machine learning models used is seen by inspecting the precision and recalls of each model. During the testing with all 6 models, there must be a good balance of precision and recall however the two are always in contention. Improving precision will reduce the recall and vice versa. During the credit risk analysis it is showing that the Easy Ensemble AdaBoost Classifier has the best balance of both including a high accuracy score of 93% as well. 
