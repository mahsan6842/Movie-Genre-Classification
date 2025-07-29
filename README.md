# Movie-Genre-Classification Web APP


This project is a machine learning-powered web application that predicts the genre of a movie based on its plot or description. It uses Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier trained on a dataset of movie descriptions.

Features:

Clean and preprocess movie descriptions using regular expressions

Transform text using TF-IDF vectorization (with unigrams and bigrams)

Train a Multinomial Naive Bayes model

Save and load the trained model/vectorizer using pickle or joblib

Interactive web interface using Flask

Expose the app online using ngrok

Dataset:

The dataset used is publicly available on Kaggle:
therohithanand/movie-genre-classification



Fields used:

Description: Plot or summary of the movie

Genre: Target label for classification


OUTPUT:

<img width="734" height="350" alt="image" src="https://github.com/user-attachments/assets/a1366d20-3d4c-47b4-899f-49cdaef645fe" />

<img width="614" height="322" alt="image" src="https://github.com/user-attachments/assets/e2360b59-869e-4424-b6cc-80901639a61d" />

<img width="549" height="314" alt="image" src="https://github.com/user-attachments/assets/d591ef4e-64dc-4eeb-b995-9916894973f4" />



Requirements for Movie Genre Classification Web App

scikit-learn (v1.3.0)

Used for machine learning tasks including model training (Multinomial Naive Bayes), vectorization, and evaluation.

pandas (v2.0.3)

For loading, manipulating, and preprocessing the movie dataset.

joblib (v1.3.2)

To save and load the trained model and TF-IDF vectorizer efficiently.

Flask (v2.3.2)

The lightweight web framework used to build the web interface for genre prediction.

pyngrok (v5.3.0)

Allows the Flask web application to be accessed publicly via a secure tunnel (used especially in development or demo environments like Google Colab).

kaggle (v1.6.6)
Used to download the movie genre dataset directly from Kaggle via API.

ipython (v8.14.0) (optional)
Enhances the development and interactive experience in notebooks or scripts. Useful during experimentation or testing.

