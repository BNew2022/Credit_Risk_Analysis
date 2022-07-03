# Credit_Risk_Analysis

## Overview of the Analysis:

The purpose of this analysis is to test and compare 6 different machine learning models and compare the results to determine the most accurate model at predicting credit risk.  We will use two types of models for this analysis; Resampling models and Ensemble models, and try several methods of each model type.

## Results:
### Naive Oversampling:

  - Balanced Accuracy Score: 64.9%
  - 3rd place
  
![This is an image](https://github.com/BNew2022/Credit_Risk_Analysis/blob/main/Images/Naive_Random_Oversampling.png)

### SMOTE Oversampling:

  - Balanced Accuracy Score: 62.0%
  - 5th place

![This is an image](https://github.com/BNew2022/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png)

### Undersampling:

  - Balanced Accuracy Score: 51.4% 
  - Last place

![This is an image](https://github.com/BNew2022/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

### Combination:

  - Balanced Accuracy Score: 64.3%
  - 4th place

![This is an image](https://github.com/BNew2022/Credit_Risk_Analysis/blob/main/Images/Combination.png)

### Balanced Random Forest Classifier:

  - Balanced Accuracy Score: 78.9%
  - 2nd place

![This is an image](https://github.com/BNew2022/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest_Classifier.png)

### Easy Ensemble AdaBoost Classifier

  - Balanced Accuracy Score: 93.2%
  - 1st place

![This is an image](https://github.com/BNew2022/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble_AdaBoost_Classifier.png)


## Summary:

As we can see by the results of the Balanced Accuracy Scores, Ensemble learning models are stronger are better at predicting credit risk than resampling models, with the strongest model being the Easy Ensemble AdaBoost Classifier at 93.2%.  The weakest model at predicting credit risk was the Undersampling method with a Balanced Accuracy Score of 51.4%.
