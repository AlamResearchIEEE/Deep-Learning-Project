# Diabetes Prediction Using Deep Learning Algorithms
## This project was done as a part of deep learning course 10 percent mark. 
## Abstract:
Nowadays, Diabetes is the most common disease in humans. People having diabetes have a high risk of other diseases such as heart disease, kidney disease, stroke, etc. Therefore, Early-stage prediction of diabetes has significant importance in the health sector.  This study aims to create a clinical support system that will help to diagnose diabetes disease at the primary stage. In this study, We have proposed a model to predict diabetes disease more accurately using Build the RNN Model (LSTM with Dropout).

## Dataset
We have collected datasets from Kaggle. The diabetes dataset contains 768 instances. Each instance has 9 features.
https://www.kaggle.com/datasets/kandij/diabetes-dataset

## Methodology
After the collection of the dataset, I applied the following steps to build deep learning models and predict accuracy.  
![alt text](https://github.com/AlamResearchIEEE/Deep-Learning-Project/blob/main/Flow%20diagram.jpg)


We have evaluated several machine learning models trained with algorithms such as Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, Multinomial Naïve Bayes, K Neighrest Neighbors, and Stochastic Gradient Descent algorithm to predict diabetes and heart diseases.  
The outcomes of the experiment are shown in the result section. 

## Results
We have applied multiple machine learning algorithms to predict diabetes and heart disease. For evaluation of the model, we have considered cross validation result, test score, precision, recall and F1 score. According to these parameters, we have found that Logistic regression model is the winner. It provides highest accuracy (best cv score and test score)  for both diabetes and heart disease prediction. 
For diabetes prediction, Logistic Regression model gives 78% accuracy in cross validation (10-Fold CV)   and 77% accuracy in test result. 
For heart disease prediction, same model gives 82% and 87% accuracy respectively. 

## Conclusions:
In this study, various machine learning algorithms are applied to the datasets and the classification has been done using various algorithms of which Logistic Regression gives the highest accuracy of 77% and 87% respectively for diabetes and heart disease prediction. 
Clearly, our machine-learning models can predict diabetes and heart disease at the primary stage. It will definitely help in the diagnosis of diseases early and will increase the chance of recovery. Further, this study can be extended to find how likely non-diabetic and people with no heart disease at present can have the risk of diabetes and heart disease in the next few years. 



## Contributors: 
1. Abu Kowcher (2016-13-08)
2. Md. Nurul Alam (2016-13-51)
3. Rezaul Karim (2016-13-06) 

## Instructor:
Md. Mynoddin, Lecturer, Dept. of CSE, RMSTU. 

