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

Classifier           Precision   Recall   F1-score

Multinomial NB         80.42       52.22     63.32

Decision Tree          77.33       93.02     85.45

Logistic Regression    60.14       75.70     67.03

SVM                    88.57       98.43     93.2

Achieved highest accuracy of 95.01% using SVM with an f1-score 93.24%.
