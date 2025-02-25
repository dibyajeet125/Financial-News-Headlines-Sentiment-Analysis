# Financial-News-Headlines-Sentiment-Analysis
Developed a sentiment analysis model using NLP techniques on a dataset of 35,463 financial news headlines, achieving an accuracy of up to 97.45% in predicting sentiment as positive, negative, or neutral.

This project involves the application of Natural Language Processing (NLP) techniques to classify financial news headlines as positive, negative, or neutral. The dataset used consists of 35,463 entries from CNBC and Reuters financial news headlines.

Key Features
Data Preprocessing: The project includes preprocessing steps such as tokenization, stopword removal, stemming, and lemmatization to clean and normalize the text data.

Sentiment Analysis: The VADER sentiment analysis tool is used to analyze the polarity scores of the descriptions and headlines.

Machine Learning Models: Several machine learning models, including Linear SVC, Logistic Regression, Naive Bayes, and others, are applied to predict sentiment from both descriptions and headlines.

Model Performance: The best model, Linear SVC, achieved an accuracy of 93.4% on descriptions and 97.45% on headlines.

Real-Time Application: The model is demonstrated to predict the sentiment of real-time financial news headlines.

Technologies Used
Python

NLTK for NLP tasks

Scikit-Learn for machine learning models

Pandas for data manipulation

Project Structure
Data: Contains the dataset used for the project.

Code: Includes Python scripts for data preprocessing, model training, and prediction.

Results: Displays the performance metrics of the models.
