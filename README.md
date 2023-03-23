# Credit_Risk_Analysis


# Overview

The purpose of the analysis was to predict credit risk using supervised learning algorithms with six machine learning models

# Results

The analysis used six machine learning algorithms including:

* Naive RandomOverSampler: Oversampling
* Balanced Accuracy Score: 0.6533977140416822
<img width="684" alt="Screen Shot 2023-03-23 at 11 31 05 AM" src="https://user-images.githubusercontent.com/107570913/227253997-4a807d03-a148-4a27-8273-2f3151b6db58.png">

* SMOTE (Synthetic Minority Oversampling Technique): Oversampling
* Balanced Accuracy Score: 0.6512291961274883
<img width="684" alt="Screen Shot 2023-03-23 at 11 32 22 AM" src="https://user-images.githubusercontent.com/107570913/227254312-6f671944-ee2d-4e88-b664-367177c38118.png">


* Cluster Centroids: Undersampling
* Balanced Accuracy Score: 0.5160196365189295
<img width="684" alt="Screen Shot 2023-03-23 at 11 33 09 AM" src="https://user-images.githubusercontent.com/107570913/227254410-3d2dd9ad-b797-47ac-a3b0-33278ae00a10.png">

* Balanced Random Forest Classifier: Reduction bias
* Balanced Accuracy Score: 0.8731182795698925
<img width="684" alt="Screen Shot 2023-03-23 at 11 29 57 AM" src="https://user-images.githubusercontent.com/107570913/227253576-5c434960-984c-4a67-aa6d-5a4d37a45d9e.png">


* Easy Ensemble AdaBoost Classifier: Reduction bias
* Balanced Accuracy Score: 0.9316600714093861
<img width="684" alt="Screen Shot 2023-03-23 at 11 27 44 AM" src="https://user-images.githubusercontent.com/107570913/227253020-cd8fef4b-0bae-4017-9506-911fc88dab21.png">


* SMOTEENN Combination Sampling
* Balanced Accuracy Score: 0.6375241226214794
<img width="684" alt="Screen Shot 2023-03-23 at 11 40 14 AM" src="https://user-images.githubusercontent.com/107570913/227256495-d907688d-5146-4e54-9f45-6b46412cd949.png">



# Summarry

When compared to other models in the analysis, ensemble models such as the Balanced Random Forest Classifier and Easy Ensemble Classifier showed better recall performance in high risk credit decisions. Nevertheless, these models had low precision, which means they may not be suitable for real-life situations. Therefore, I do not recommend using these models to predict credit risk as they may not perform as expected.
