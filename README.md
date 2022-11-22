# Credit_Risk_Analysis

## Overview of the Analysis:

Managing credit risk is critical to health of any lender. Loans are made based on the ability of an applicant to make repayments and to stay current. Loan losses can drive down profitability and increased credit risk is also highly regulated. 
In the example, the analyst is using several criteria and modeling techniques in order to predict which applicants are at a higher risk of default. Specifically, applicants are being grouped into low-risk and high-risk categories. Because the data on high-risk customers occurs with less frequency, over sampling techniques may be useful. 
In addition to working through the example, the student is also exposed to supervised machine learning concepts and techniques, including:
-	Creating training and test groups from a given data set.
-	Implementing logistic regression, decision tree, random forest, and support vector machine algorithms.
-	Interpreting results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
-	Comparing advantages and disadvantages of each supervised learning algorithm.
-	Determining which supervised learning algorithm is best used for a given data set or scenario.
-	Using ensemble and resampling techniques to improve model performance.

## NAIVE RANDOM OVERSAMPLING:
![](https://github.com/vjtrom/Credit_Risk_Analysis/blob/main/images/Naive.png)

## SMOTE OVERSAMPLING:
![](https://github.com/vjtrom/Credit_Risk_Analysis/blob/main/images/SMOTE.png)

## UNDERSAMPLING:
![](https://github.com/vjtrom/Credit_Risk_Analysis/blob/main/images/Undersampling.png)

## COMBINATION (OVER/UNDER) SAMPLING:
![](https://github.com/vjtrom/Credit_Risk_Analysis/blob/main/images/Combination.png)

## RANDOM FOREST
![](https://github.com/vjtrom/Credit_Risk_Analysis/blob/main/images/Random%20Forest.png)

## ADABOOST CLASSIFIER
![](https://github.com/vjtrom/Credit_Risk_Analysis/blob/main/images/AdaptBoost.png)

# Recommendation:

Based on the results, Random Forests models seem to have the best predicitve power The Random Forest model had a balanced accuracy score of .68, and it also had very high recall and f1 scores. The Naive Random Oversampling model was also good with a balanced accurancy score of .67 which is the highest of all the models. It also has good precision and a recall rate of .66.

Conversely, the Undersampling model seems to have the worst performance, with a balanced accuracy score of .57 and lower scores for recall and f1. 
