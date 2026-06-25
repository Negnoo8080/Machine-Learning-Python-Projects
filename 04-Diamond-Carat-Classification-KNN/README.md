# Project 4: Diamond Carat Range Classification using K-Nearest Neighbors (KNN)

## Overview
This project implements a supervised machine learning pipeline using the K-Nearest Neighbors (KNN) algorithm to classify diamonds into specific weight (carat) ranges based on their physical measurements and quality characteristics. It showcases data transformation, categorical encoding, and feature optimization.

## Key Features & Implementations
* **Data Transformation & Feature Engineering:** Cleaned the feature space by dropping non-contributing dimensions and engineered a continuous target variable (`carat`) into distinct, discrete categorical ranges ('0-1', '1-2', '2-3', etc.).
* **Categorical Data Encoding:** Converted categorical diamond characteristics like `cut` attributes into optimized integer structures for machine learning compatibility.
* **Supervised KNN Pipeline:** Implemented a **K-Nearest Neighbors Classifier** using Scikit-Learn, splitting the multi-feature space to optimize localized classification performance.
* **Hyperparameter Tuning & Diagnostics:** Constructed an error-rate analysis across different values of $K$ to mathematically determine the optimal neighbor threshold for maximum testing accuracy.

## Technologies Used
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib
* **Dataset:** Diamonds Dataset
