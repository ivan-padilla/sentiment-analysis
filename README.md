# DU30's ICC Arrest: A Sentiment Analysis on FB Comments using Machine Learning

## Overview
This repository contains a sentiment analysis project focused on Facebook comments surrounding the arrest of former President Rodrigo Duterte by the International Criminal Court (ICC). The main component is a Python notebook that cleans, processes, and analyzes Facebook comments related to the event. A labeled dataset of comments is included, and the results of the sentiment classification are visualized for better insight into public reaction.

## Contents
- sentimentAnalysis.ipynb – Jupyter Notebook for preprocessing, training a sentiment model, and visualizing results.
- trainingClean.xlsx – Dataset containing Facebook comments and their sentiment labels.
- newCommentsClean.xlsx - New comments dataset (not used in training the model).

## Dependencies
Ensure you have the following Python libraries installed before running the notebook:
- pandas – For data manipulation and preprocessing.
- nltk – Natural Language Toolkit for text processing.
- scikit-learn – For machine learning model training and evaluation.
- plotly – For creating visualizations.
- deep translator – For translating the comments.

## Usage
- Open sentimentAnalysis.ipynb in Jupyter Notebook or Google Colab.
- Load the dataset using pandas.
- Clean and preprocess the text data.
- Split the data into training and testing sets.
- Train a machine learning classifier on the labeled data.
- Evaluate the model’s performance using accuracy, precision, recall, and confusion matrix.
- Use the trained model to to analyze sentiments of new Facebook comments.
