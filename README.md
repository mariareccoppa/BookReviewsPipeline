# Text Classification and Transformation of Book Reviews
This project utilizes a machine learning pipeline for sentiment analysis on book reviews. It is designed to classify the sentiment of textual reviews into positive or negative categories using logistic regression.

## Project Overview
The pipeline is built using Python and incorporates several key libraries:
* Pandas and NumPy for data manipulation
* Matplotlib and Seaborn for data visualization
* Scikit-learn for machine learning tasks

It includes the following steps:
* Loading and preprocessing the data using Pandas
* Splitting the data into training and test sets
* Extracting features from the text data using TF-IDF
* Building and evaluating a logistic regression model


## Data
The dataset used in this project is bookReviewsData.csv, which contains book reviews to be classified. The data is split into 80% for training and 20% for testing.

## Model Evaluation
The logistic regression model's performance is assessed using an ROC curve, with an aim to maximize the area under the curve (AUC) for the best classifier performance.
