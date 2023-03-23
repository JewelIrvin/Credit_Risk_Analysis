# Credit_Risk_Analysis


# Overview

The purpose of the analysis was to predict credit risk using supervised learning algorithms with six machine learning models

# Results

The analysis used six machine learning algorithms including:

* RandomOverSampler: Oversampling
Screenshot (167)

Balanced Accuracy Score: 0.6293939430565123

* SMOTE (Synthetic Minority Oversampling Technique): Oversampling
Screenshot (169)

Balanced Accuracy Score: 0.6277008271188627

* Cluster Centroids: Undersampling
Screenshot (171)

Balanced Accuracy Score: 0.5103893461611291

* Balanced Random Forest Classifier: Reduction bias
Screenshot (164)

Balanced Accuracy Score: 0.8731182795698925


* Easy Ensemble AdaBoost Classifier: Reduction bias
Screenshot (165)

Balanced Accuracy Score: 0.9316600714093861


# Summarry

When compared to other models in the analysis, ensemble models such as the Balanced Random Forest Classifier and Easy Ensemble Classifier showed better recall performance in high risk credit decisions. Nevertheless, these models had low precision, which means they may not be suitable for real-life situations. Therefore, I do not recommend using these models to predict credit risk as they may not perform as expected.
