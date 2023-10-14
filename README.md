# Cyberbullying-Detection-Using-ML
This repository contains a machine learning project with a primary focus on predicting instances of cyberbullying using a Twitter dataset.

## Dataset

• The dataset used here is taken from Kaggele.
• It contains 20,000+ tweets.
• The values 0 and 1 were used to label non- offensive and offensive tweets respectively in the training set. 

## Data Preprocessing

Analyzed Twitter dataset using NLP techniques such as tokenization, stop words removal, stemming and vectorization to understand the sentiment of 20,000+ tweets
identifying and addressing negative sentiment. 

## Model Building

The dataset was split into train and test after preprocessing it and then applied Multinomial Naive Bayes, Decision Tree, Logistic 
Regression and SVM on the dataset. 

To evaluate the classifiers, accuracy, recall, precision, and f-score are used as performance indicators.

## Results 

Classifier           &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;> Precision &nbsp;      > Recall  &nbsp;     > F1-score

Multinomial NB      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 80.42                           &nbsp;&nbsp; 52.22        &nbsp;&nbsp;63.32

Decision Tree        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;77.33         &nbsp;&nbsp;93.02         &nbsp;&nbsp;&nbsp;85.45

Logistic Regression    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;60.14         &nbsp;&nbsp;75.70        &nbsp;&nbsp; 67.03

SVM   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;88.57         &nbsp;&nbsp;98.43         &nbsp;&nbsp;&nbsp;93.2

Achieved highest accuracy of 95.01% using SVM with an f1-score 93.24%.
