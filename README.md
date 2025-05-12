## INTRODUCTION
The business problem centers on leveraging data from the 2009 H1N1 Flu Survey conducted during and after the H1N1 flu pandemic.This analysis aims to leverage the 
survey responses on vaccination status, emographic and socio-economic information to identify the factors that influenced vaccine adoption. The resulting insights will be critical for developing more effective public health strategies to promote higher vaccination rates during future pandemics

### Main Objective
The goal of this project is to create models that can predict H1N1 and seasonal flu vaccine uptake(independently) based on a person's demographic, socio-economic factors and behavioral patterns

### DATA DESCRIPTION
The datasets used for this project [H1N1 AND Seasonal Flu](https://www.drivendata.org/competitions/66/flu-shot-learning/data/). It contains the social, economic and demographic backgrounds of the respondents as well as their opinions on the H1N1 and seasonal flu vaccines. The datasets have been divided into the training set features and the training set labels.

### DATA PREPARATION AND MODELLING
The data preparation:
       * The train_test split 
       * Replacing missing values with SimpleImputer
       * Dropped 'irrelevant' columns 
       * One-Hot encoded categorical columns
       * Scaled numerical columns

Logistic Regression and Decision Tree classifier were used for my analysis

### EVALUATION
The Logistic Model for the H1N1 flu had an overall accuracy of 82% and AUC of 0.84

The Logistic Regression Model for the seasonal flu had and accuracy of 78% and AUC of 0.86

Important Features for H1N1 Flu vaccine prediction:
![Alt text](attachments\h1n1_features.png)

Important Features for Seasonal Flu vaccine prediction:
![Alt text](attachments\seasonal_features.png)

### CONCLUSION
Public awareness campaigns to effectively communicate the safety and risks of the vaccines to build public trust. Recognizing the observed higher uptake among older individuals, targeted outreach and communication strategies should be specifically developed and implemented to engage younger demographics and increase their understanding of the benefits and safety of both flu vaccinations.
