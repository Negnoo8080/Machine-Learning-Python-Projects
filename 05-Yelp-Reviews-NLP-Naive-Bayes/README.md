# Project 5: Text Classification and Sentiment Analysis on Yelp Reviews using Naïve Bayes

## Overview
This project implements an end-to-end Natural Language Processing (NLP) and supervised machine learning pipeline to analyze and predict user ratings (star counts) from Yelp review texts. It showcases advanced text vectorization, binary vs. multi-class classification evaluation, and model deployment serialization.

## Key Features & Implementations
* **Text Vectorization & Feature Extraction:** Utilized `CountVectorizer` from Scikit-Learn to perform textual tokenization and structured a feature matrix ($X$) from raw review strings using `fit_transform`.
* **Supervised Learning Pipeline:** Implemented and trained a **Multinomial Naïve Bayes (MultinomialNB)** classifier, specialized for discrete word-count feature frequencies.
* **Comparative Classification Analysis:** 
  * Evaluated baseline classification performance across all multi-class star ratings (1 to 5 stars).
  * Filtered the dataset to focus strictly on extreme sentiment profiles (1-star vs. 5-star reviews), significantly improving classification metrics by training on highly separated classes.
* **Model Serialization (Deployment Ready):** Implemented Python's `pickle` library to serialize and bundle the pipeline components (both the fitted vectorizer and trained model structures) into a production-ready `.pkl` package for downstream integration.

## Technologies Used
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn, Pickle
* **Dataset:** Yelp Reviews Dataset
