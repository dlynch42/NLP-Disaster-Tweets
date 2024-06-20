# NLP Disaster Tweets
This repository contains code and resources for analyzing and classifying disaster-related tweets using Natural Language Processing (NLP) techniques.

## Overview
In this project, we aim to build a machine learning model that can accurately classify tweets as either disaster-related or non-disaster-related. By leveraging NLP techniques, we can extract meaningful features from the text data and train a classifier to make predictions.

## Dataset
The dataset used for this project is the [Disaster Tweets Dataset](https://www.kaggle.com/c/nlp-getting-started) from Kaggle. It consists of a collection of tweets that are labeled as either disaster-related or not. The dataset provides a valuable resource for training and evaluating our models.

## Project Structure
The repository is organized as follows:

- [`disaster_tweets.ipynb`](disaster_tweets.ipynb): This directory contains Jupyter notebooks with the code for data preprocessing, feature extraction, model training, and evaluation.
- `data/`: This is a created directory contains the dataset files after unzipping

## Notebook Content

- **Data Preprocessing**: This section covers the preprocessing steps required for the disaster tweets dataset, including data loading, data augmentation, and data splitting.
- **Model Architecture**: This section defines the architecture of the tweet classification model using the Keras Sequential API. It includes the layers, activation functions, and regularization techniques used in the model. It also covers the training process of the tweet classification model, including compiling the model, defining the loss function and optimizer, and fitting the model to the training data.
- **Results & Analysis**: This section evaluates the performance of the trained model on the training and validation data, including calculating accuracy, loss, and recall.
- **Test Model**: This section runs the model on test data and creates a submission.
- **Conclusion**: This section offers insight to how the submission held up and what could be done to improve the accuracy of the model.

## Usage

To run the notebook, open it in Jupyter and execute all cells.

## Requirements

Run the installs within the notebook.