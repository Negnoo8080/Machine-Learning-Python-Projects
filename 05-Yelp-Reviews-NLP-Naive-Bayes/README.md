# Project 5: Yelp Review Sentiment Classification using Naïve Bayes

## What this project does
This exercise focuses on basic Natural Language Processing (NLP) and Text Classification. We used a dataset of Yelp reviews to predict the number of stars a user gave based on their text comment.

## What I did:
* Used Scikit-Learn's `CountVectorizer` to convert text reviews into numbers (word counts) that a model can understand.
* Split the data into training and testing sets.
* Trained a **Multinomial Naïve Bayes** model to classify star ratings.
* Filtered the dataset to compare extreme classes (only 1-star and 5-star reviews) and saw how the model's accuracy improved.
* Used Python's `pickle` library to save the trained model and the vectorizer into a `.pkl` file for future use.

## Libraries used:
* Scikit-Learn
* Pandas & NumPy
* Pickle
