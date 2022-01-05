# HeartDisease
Heart Disease Prediction Model

The data set is comprised of 11 predictor features and a binary target (heart disease) with 918 observations. The objective of this analysis is to classify individuals into a group that is expected to suffer from heart failure or those that are not.  Each observation is a cross section of medical records belonging to a unique individual.

We developed three unique classification models, which were each peer reviewed for methodological soundness and performance. Classification methods were chosen by G2QC as the preferred technique since the target variable (heart disease) is binary. The three models employed for review were Decision Tree, Naïve Bayes, and Logistic Regression. 

Prior to model implementation, the data set was split into training and test sets. Of most importance is how the model(s) perform against the test set, as this will provide the closest comparison to real life circumstances. The performance metrics of interest are Accuracy, Precision, and Recall.

The Decision Tree model rank ordered the highest in terms of precision when predicting those that will not suffer from heart failure, but only by .7 percentage points and was the strongest of performers predicting recall of those with heart failure. The logistic regression was the strongest performer in terms of precision of those expected to suffer from heart disease (8.1 percentage points greater than the decision tree) as well as the recall of those expected to not suffer heart failure, and overall accuracy. The Naïve Bayes model did not score as the preeminent model in any performance metrics. 

Within the logistic regression model, the features that most contributed to the accuracy of the predictions are: Old peak, chest pain type (ATA and NAP),  and ST slope. 

