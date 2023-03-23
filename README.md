# Credit_Risk_Analysis


# Overview

The purpose of the analysis was to predict credit risk using supervised learning algorithms with six machine learning models

# Results

The analysis used six machine learning algorithms including:

* Naive RandomOverSampler: Oversampling
<img width="684" alt="Screen Shot 2023-03-23 at 11 31 05 AM" src="https://user-images.githubusercontent.com/107570913/227253997-4a807d03-a148-4a27-8273-2f3151b6db58.png">


Balanced Accuracy Score: 0.6533977140416822

* SMOTE (Synthetic Minority Oversampling Technique): Oversampling
<img width="684" alt="Screen Shot 2023-03-23 at 11 32 22 AM" src="https://user-images.githubusercontent.com/107570913/227254312-6f671944-ee2d-4e88-b664-367177c38118.png">


Balanced Accuracy Score: 0.6512291961274883

* Cluster Centroids: Undersampling
<img width="684" alt="Screen Shot 2023-03-23 at 11 33 09 AM" src="https://user-images.githubusercontent.com/107570913/227254410-3d2dd9ad-b797-47ac-a3b0-33278ae00a10.png">

Balanced Accuracy Score: 0.5160196365189295

* Balanced Random Forest Classifier: Reduction bias

<img width="684" alt="Screen Shot 2023-03-23 at 11 29 57 AM" src="https://user-images.githubusercontent.com/107570913/227253576-5c434960-984c-4a67-aa6d-5a4d37a45d9e.png">

Balanced Accuracy Score: 0.8731182795698925


* Easy Ensemble AdaBoost Classifier: Reduction bias
<img width="684" alt="Screen Shot 2023-03-23 at 11 27 44 AM" src="https://user-images.githubusercontent.com/107570913/227253020-cd8fef4b-0bae-4017-9506-911fc88dab21.png">


Balanced Accuracy Score: 0.9316600714093861


# Summarry

When compared to other models in the analysis, ensemble models such as the Balanced Random Forest Classifier and Easy Ensemble Classifier showed better recall performance in high risk credit decisions. Nevertheless, these models had low precision, which means they may not be suitable for real-life situations. Therefore, I do not recommend using these models to predict credit risk as they may not perform as expected.
