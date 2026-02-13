SMS Spam Classification (Machine Learning Project)

This project builds a machine learning model that can classify SMS messages as Spam or Ham (Not Spam).
It uses basic Natural Language Processing (NLP) techniques along with Logistic Regression.

About the Project

This is a beginner-level machine learning project where I:

Loaded and explored the SMS Spam dataset

Cleaned and prepared the text data

Converted text into numerical features using TF-IDF

Trained a Logistic Regression model

Evaluated the model using accuracy, precision, recall, F1-score and confusion matrix

Tested the model with custom input messages

The project is implemented in Google Colab.

Dataset

SMS Spam Collection Dataset
Total messages: 5572

Spam: 747

Ham: 4825

The dataset contains short text messages labeled as spam or not spam.

Technologies Used

Python

Pandas

Scikit-learn

NumPy

TF-IDF Vectorizer

Google Colab

Model Performance

The Logistic Regression model reaches around 95% accuracy on the test set.
It performs reasonably well for a simple model trained on a basic dataset.

How to Run This Project

Download the .ipynb notebook from this repository.

Open it in Google Colab (recommended).

Upload the dataset if required.

Run all cells from top to bottom.

At the end, you can test the model with your own message.

Example Usage

You can test your own text message by editing the following in the notebook:

test_message = ["Your message here"]


The model will output whether it is spam or not.

Purpose

This project is created as part of my learning journey in machine learning and text classification.
It is intended for practice and demonstration
