# Movie-Genre-Classification Web APP


This project is a machine learning-powered web application that predicts the genre of a movie based on its plot or description. It uses Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier trained on a dataset of movie descriptions.

Features
Clean and preprocess movie descriptions using regular expressions

Transform text using TF-IDF vectorization (with unigrams and bigrams)

Train a Multinomial Naive Bayes model

Save and load the trained model/vectorizer using pickle or joblib

Interactive web interface using Flask

Expose the app online using ngrok

Dataset
The dataset used is publicly available on Kaggle:
therohithanand/movie-genre-classification

Fields used:

Description: Plot or summary of the movie

Genre: Target label for classification
