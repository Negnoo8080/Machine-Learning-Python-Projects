# Project 4: Diamond Carat Range Classification using KNN

## What this project does
This project applies the K-Nearest Neighbors (KNN) algorithm to the `diamonds` dataset. Instead of predicting prices, the task is to classify diamonds into different carat ranges.

## What I did:
* Cleaned up the data by dropping columns that weren't needed (like Color and Clarity).
* Converted the `cut` feature values into integers.
* Grouped the continuous `carat` values into discrete bins/ranges (like '0-1', '1-2', etc.) to create our target labels.
* Trained a **K-Nearest Neighbors Classifier**.
* Plotted a diagram of error rates across different values of $K$ to see which neighbor setting gives the highest accuracy.

## Libraries used:
* Scikit-Learn
* Pandas & NumPy
* Matplotlib
