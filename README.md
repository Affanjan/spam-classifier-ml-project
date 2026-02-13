# Spam Classifier – Machine Learning Project

This project is a simple machine learning model that classifies messages as **spam** or **not spam**.  
It uses Natural Language Processing (NLP) techniques along with a classification algorithm to make predictions.

## Project Structure

- **spam_classifier_ml_project.ipynb** – Main Google Colab notebook  
- **spam.csv** – Dataset used for training and testing  
- **README.md** – Project explanation and documentation

## How It Works

1. The dataset is loaded and cleaned.
2. Text messages are preprocessed (removing punctuation, converting to lowercase, etc.).
3. TF-IDF vectorization converts text into numerical form.
4. A machine learning model is trained to detect spam patterns.
5. The model predicts whether a new message is spam or not.

## How to Use This Project

1. Open the notebook (`.ipynb` file) in Google Colab.  
2. Run the cells in order.  
3. At the bottom of the notebook, enter a message into the text box.  
4. The model will output whether it's **spam** or **not spam**.

## Dataset

This project uses a public SMS spam dataset that contains labeled text messages.  
Each message is marked as:

- `ham` → not spam  
- `spam` → spam message  

## Requirements

To run the project:

- Python 3  
- Scikit-learn  
- Pandas  
- NumPy  
- Google Colab (recommended)

All required libraries are installed automatically in Colab.

## Goal of the Project

The aim is to understand:

- How text preprocessing works  
- How machine learning models classify text  
- How to build a simple NLP pipeline  

## License

This project is for educational purposes only.  
Feel free to use or modify it.
