
# Airline Passenger Referral Prediction

This data comprises airline reviews for well-known airlines worldwide from 2006 to 2019. One of the most significant business difficulties is predicting the referral of airline passengers.
Determining passenger outcomes will result from analysing airline reviews from well-known airline sectors.

## Goal of the Project

* EDA is the first step in the process since it will help you comprehend the situation from a business standpoint. Our study has led us to the conclusion that one of our main objectives is to create a model that can predict whether or not a passenger will enthusiastically recommend their vacation to family, friends, and the general public.
* Once the primary goal has been achieved. Now they can prepare for any passenger feedback, execute the task, analyse the results, and grow their business requirements.
* Now the Aviation Industry results in increasing their growth.

## Steps Involved

❖Null values Treatment and Outliers

❖ Exploratory Data Analysis

❖ Fitting different models and Tuning the hyperparameters for better accuracy

❖ Model Interpretation
## Null value Removal

From Analysis we found that Our datasets consists of Null values. To build a better model its necessary to remove those null values.
We used below mention techniques to remove null values

* Quantile-1 value
* Median Imputation 
* Column removal

The below image show the box plot after removal of outliers


## Exploratory Data Analysis

To learn more about the datasets and to obtain insights into business understanding, we undertook exploratory data analysis.

giflink




## Fitting different models and Tuning the hyperparameters 

To build an Airline Passenger Reffereal Prediction System and improve Accuracy Score, we used various classifier models they are


| Models        |
| ------------- |
| Logistic Regression Model|
| Decision Tree Model  | 
| Random Forest Model| 
| Gradient Boosting Model|

-*-*--*-*--*-*-Logistic Regression Model-*-*--*-*--*-*--*-*-

| Metrics | Train_Score | Test_Score |
| ------------- | ------------- | ------------- |
|  Accuracy_Score   |  0.894204 |   0.895950
|  Precsion_Score   |  0.895205  |  0.892142
|    Recall_Score   |  0.880908  |  0.883372
|   Roc_Auc_Score   |  0.893597  |  0.895142

-*-*--*-*--*-*-Decision Tree Model After Hyperparameter Tuning-*-*--*-*--*-*--*-*-

|Metrics | Train_Score  |Test_Score|
| ------------- | ------------- | ------------- |
 | Accuracy_Score   |  0.898937  |  0.899209|
 | Precsion_Score  |   0.920707 |   0.915827|
  | Recall_Score   |  0.861962  |  0.862879|
  | Roc_Auc_Score  |   0.897250  |  0.896877|

-*-*--*-*--*-*-Random Forest Model After Hyperparameter Tuning-*-*--*-*--*-*--*-*-

|  Metrics|  Train_Score | Test_Score|
| ------------- | ------------- | ------------- |
 | Accuracy_Score   |  0.900081 |    0.900993|
 |Precsion_Score |    0.922929|    0.922568|
 |Recall_Score  |   0.862125  |  0.859547|
 |  Roc_Auc_Score  |   0.898350 |   0.898333|

-*-*--*-*--*-*-Gradient Boosting Model After Hyperparameter Tuning-*-*--*-*--*-*--*-*-

|  Metrics  |Train_Score|  Test_Score|
| ------------- | ------------- | ------------- |
 |Accuracy_Score |    0.906522 |   0.904718|
 |Precsion_Score |    0.919235 |   0.914986|
  | Recall_Score |    0.881071 |   0.876874|
 |Roc_Auc_Score |    0.905361  |  0.902930|

## Model Interpretation

* It's also crucial to interpret the model. The majority of machine learning models
    are **blackbox-based**.To understand what happens within the blackbox and why the model predicts
    certain outcomes.
* This is where **LIME** (Local Model Interpretability Model Agnostic) and **SHAP**
    Values comes in handy for interpretation.

**Lime and Shap values Interpretation Images shown below**


**Shap values summary plot**

## Technical Skills

* Data Cleaning 

* Data Visualization

* Outlier Removal

* Encoding Techinques

* Classifier Model Building 

* Hyperparamter Tuning

* Model Interpretation



