# Project 7: Unsupervised Clustering on Iris Dataset using K-Means

## Overview
This project implements an unsupervised machine learning workflow utilizing the **K-Means Clustering** algorithm on the classic Iris dataset. The primary objective is to partition unlabeled multidimensional biological data into distinct structural groupings and evaluate the mathematical mapping against real categorical classifications.

## Key Features & Implementations
* **Optimal Cluster Determination (The Elbow Method):** Implemented a Within-Cluster Sum of Squares (WCSS) inertia loop across multiple cluster counts ($K$) to graphically identify the "elbow" point, mathematically justifying the selection of 3 optimal clusters.
* **Unsupervised Clustering Pipeline:** Structured and deployed a `KMeans` estimator via Scikit-Learn to compute multi-feature cluster centers and assign discrete spatial labels to unstructured continuous features.
* **Clustering Evaluation & Alignment:** Built a customized cross-tabulation and confusion matrix structure to align unsupervised cluster index outputs with the dataset's ground-truth target features, assessing clustering purity and spatial segregation.

## Technologies Used
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
* **Dataset:** Iris Flower Dataset
