# Next-Day-Rain-Prediction


This is the Australian Weather dataset, been used to predict the next day rain. Three different classifier used in a hard voting system to predict.
Multi Layer Perceptron
Random Forest Classifier
SVM Classifier
These three algorithms used to predict the label and then the predictions are used in a hard voting system to classify.

The goal of this project is to predict next day rain depending on different parameters. The dataset (https://www.kaggle.com/skmuhammadasif/australian-rainfall-prediction/data ) has been collected from kaggle. This dataset contains about 10 years of daily weather observations from numerous Australian weather stations. There were 23 different features about the location, minimum and maximum temperature, rainfall, sunshine, wind pressure/ directions/ speed/ humidity of different time periods, rain report of the next day and previous days as well as the monthly rainfall data. The dataset size was 142193 & data has been split into the ratio of 75:25 for further procedure and training. Has been implemented different machine learning models for training and few of them(SVC, RF & MLP) reached highest 89% accuracy. 

Preprocessing & Model Implementation steps : 
Multicollinearity has been checked for feature selection procedure
Dropped the unnecessary columns
Nan values has been handled by filling with common/ frequent values for categorical data
Correlation among the features has been observed 
As a feature scaling/ data normalization procedure, Standardization has been implemented
Data spitting done into the ratio of 75:25
Models implemented: MLP Classifier(89.36%), Random Forest Classifier(89.51%), Support Vector Machine Classifier(89.18%) & Voting Classifier(89.52 %) 
 
