# Project 6: Machine Learning Model Deployment as a Web Service via Flask API

## Overview
This project demonstrates the production-grade deployment of a trained machine learning pipeline into a functional web service. By wrapping a K-Nearest Neighbors (KNN) classification model within a **Flask** microframework layer, the application exposes endpoints that ingest raw text/numerical data via JSON payloads, dynamically reconstruct dataframes, and return real-time analytical predictions.

## Key Features & Implementations
* **Model Pipeline Implementation:** Integrated a supervised K-Nearest Neighbors (KNN) classification algorithm tailored to classify diamond carat profiles based on feature extractions.
* **RESTful API Development:** Formulated a local backend service using **Flask** to handle stateful request-response cycles:
  * **GET Endpoint (`/diamond/sample`):** Extracts and streams a single, un-indexed feature snapshot translated directly to a structured JSON format.
  * **POST Endpoint (`/diamond/evaluate`):** Accepts custom JSON records, pipes the parsed dictionaries dynamically into a Pandas DataFrame structure, aligns targeted column headers, and queries the operational model to retrieve discrete string classifications.
* **Production Error Handling:** Implemented defensive validations checking explicit request formats, ensuring an integrated JSON content type before invoking predictive evaluation routines.

## Technologies Used
* **Language:** Python
* **Framework:** Flask (Micro Web Framework)
* **Libraries:** Scikit-Learn, Pandas, NumPy
