# Iris-classifier

Classifying Iris flower species using Machine Learning

Check out [iris_classifier.ipyb](iris_classifier.ipyb) for the code

[app](app) contains files for the web app which is under development


## Table of contents

1. [Intro](#What-is-machine-learning?)
2. [Problem](#Our-Problem)
3. [Solution](#Solution)
4. [Naive Bayes Algorithim](##Why-we-used-Naive-Bayes-Algorithm)
5. [About us and the project](#About-us-and-the-project)


## What is machine learning?

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it to learn for themselves.

Machine learning is used in internet search engines, email filters to sort out spam, websites to make personalised recommendations, banking software to detect unusual transactions, and lots of apps on our phones such as voice recognition.


## Our Problem

Iris Classification is perhaps the best-known example in the field of machine learning.The aim is to classify iris flowers among three species (setosa, versicolor, or virginica) from measurements of sepals and petals' length and width.The iris data set contains 3 classes of 150 instances each, where each class refers to a type of iris plant.

The central goal here is to design a model that makes useful classifications for new flowers or, in other words, one which exhibits good generalization.

## Solution

### 1.Create the dataset.

Inorder to classify the different species of the Iris, we should prepare the datasets with features and labels.But sklearn comes with the inbuilt datasets for the iris classification problem.The data set consists of 150 samples, 3 labels: species of Iris (Iris setosa, Iris virginica and Iris versicolor) and 4 features: Sepal length, Sepal width, Petal length, Petal Width in cm.

Scikit learn only works if data is stored as numeric data, irrespective of it being a regression or a classification problem. It also requires the arrays to be stored at numpy arrays for optimization. Since, this dataset is loaded from scikit learn, everything is appropriately formatted.

Since our process involve training and testing, we should split our dataset. x_train contains the training features x_test contains the testing features y_train contains the training label y_test contains the testing labels

### 2.Build the model.

We can use any classification algorithm to solve the problem. First create an empty model. Inorder to provide the operations to the model we should train them. If our model has to predict the flower, we have to train the model with the Features and the Labels.

### 3.Train the model.

We can train the model with fit function and then the model will be ready to make predictions.

### 4.Make predictions.

Predictions can be done with predict function. The predictions can be matched with the expected output to measure the accuracy value.

## Why we used Naive Bayes Algorithm

So in this project we are using Naive Bayes Algorithm. Naive Bayes algorithm is a supervised learning algorithm, which is based on Bayes theorem and used for solving classification problems. It is mainly used in text classification that includes a high-dimensional training dataset. Naive Bayes Classifier is one of the simple and most effective Classification algorithms which helps in building the fast machine learning models that can make quick predictions. It is a probabilistic classifier, which means it predicts on the basis of the probability of an object. Some popular examples of Naïve Bayes Algorithm are spam filtration, Sentimental analysis, and classifying articles.

Naive Bayes is one of the fast and easy ML algorithms to predict a class of datasets. It can be used for Binary as well as Multi-class Classifications. It performs well in Multi-class predictions as compared to the other Algorithms. It is the most popular choice for text classification problems.

Here we are using Gaussian model Naive Bayes model. The Gaussian model assumes that features follow a normal distribution. This means if predictors take continuous values instead of discrete, then the model assumes that these values are sampled from the Gaussian distribution.

## About us and the project

Tech Analogy broght us to a 14 days Workshop on Cognitive Application using ML/AI. It was a great opportunity as we were able to study an industry oriented skill. We Learned through interactive sessions and stay connected with the like minded people throughout the session. Our guest speaker Aditya Jyoti Paul's sessions were excellent as he had a stunning ability to explain complicated topics in simple terms.

The Iris Classification project was done by Lenin and Sandra Victor. We both discussed and created the classifier and Lenin made the web application and Sandra wrote the descriptions in the web app. Overall the doing this project was a great experience for us.

Thank You Tech Analogy for this wonderful opportunity
