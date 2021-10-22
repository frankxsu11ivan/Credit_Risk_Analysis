Using the imbalanced-learn and scikit-learn libraries, the goal is to evaluate three machine 
learning models by using resampling to determine which is better at predicting credit risk. 

Using the information provided in the code, the training and target  code variables are completed the following steps:

###Create the training variables by converting the string values into numerical ones using the get_dummies() method.
###Create the target variables.
###Check the balance of the target variables.
https://github.com/frankxsu11ivan/Credit_Risk_Analysis/blob/main/Mod17%20Picts%20as%20Resources/Line%206%20verification.png

Using these algorithms: 
###resample the dataset via Naive Random Oversampling,
###train a logistic regression classifier, 
###calculate the balanced accuracy score, 
###generate a confusion matrix, 
###and generate a classification report.
https://github.com/frankxsu11ivan/Credit_Risk_Analysis/blob/main/Mod17%20Picts%20as%20Resources/Line%2012%20verification.png
https://github.com/frankxsu11ivan/Credit_Risk_Analysis/blob/main/Mod17%20Picts%20as%20Resources/Line%2017%20verification.png

Deliverable 1
###Use the LogisticRegression classifier to make predictions and evaluate the model’s performance.
###Calculate the accuracy score of the model.
###Generate a confusion matrix.
###Print out the imbalanced classification report.
https://github.com/frankxsu11ivan/Credit_Risk_Analysis/blob/main/Mod17%20Picts%20as%20Resources/Line%2024%20verification.png

Deliverable 2
The combinatorial SMOTEENN algorithm does the following:
###An accuracy score for the model is calculated 
###A confusion matrix has been generated 
###An imbalanced classification report has been generated 
https://github.com/frankxsu11ivan/Credit_Risk_Analysis/blob/main/Mod17%20Picts%20as%20Resources/Line%2032%20verification.png

Deliverable 3
BalancedRandomForestClassifier algorithm
###An accuracy score for the model is calculated 
###A confusion matrix has been generated 
###An imbalanced classification report has been generated

EasyEnsembleClassifier algorithm
###An accuracy score for the model is calculated 
###A confusion matrix has been generated 
###An imbalanced classification report has been generated

Bulleted Result List of six machine learning models Accuracy Scores:
#SKLearn accuracy Score .99
#Balanced accuracy Score .60
#Smote Oversampling accuracy Score .69
#Smote Sklearn Score .66
#Undersampling Score .69
#Combination Score .58

Precision Score
#
#
#
#
#
#
Recall scores 
#
#
#
#
#
#
Summary:
The summary of the result of the SMOTE resample data using undersampling -or oversampling algorithm has a high accurace and while not the training percent accuracy - 
would be the correct model to use for the data in the model. From MOD 17 undersampling would be the algorithm recommended to drill down to get clarity to the variables and meaning of the data results.



