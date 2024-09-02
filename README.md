# SMS Spam Predictor


## Project Overview:
The SMS Spam Predictor is a machine learning project designed to classify SMS messages as either spam or ham (non-spam). This project utilizes natural language processing (NLP) techniques to preprocess text data and machine learning algorithms to predict whether a given message is spam.

## Features
1)Data Cleaning: Handling missing values and removing duplicates.
2)Text Preprocessing: Tokenization, lowercasing, stop words removal, and TF-IDF vectorization.
3)Model Training: Building and training a classifier to detect spam messages.
4)Model Evaluation: Assessing the model's performance using standard metrics.


## Requirements
To run this project, you need the following Python libraries:

1)pandas
2)numpy
3)nltk
4)matplotlib
5)seaborn
6)scikit-learn

## Project Structure
The project is structured as follows:

1) Importing Libraries: Essential libraries are imported for data manipulation, visualization, and model building.

2) Loading the Dataset: The dataset is loaded using pandas and cleaned by dropping unnecessary columns and handling missing data.

3) Data Preprocessing: The text data is preprocessed, including:
    * Removing duplicates.
    * Converting labels (ham, spam) to numerical values (0, 1).
    * Tokenization and feature extraction using TF-IDF vectorization.
      
4) Exploratory Data Analysis (EDA): Visualizing the distribution of spam vs. ham messages and understanding the data's structure.

5) Model Training: The preprocessed data is split into training and testing sets. A machine learning model (likely Naive Bayes) is trained on the training data.

6) Model Evaluation: The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

7) Predictions: The model is used to predict the class labels of unseen messages.

## Results:
The trained model is evaluated on the test set, and the performance metrics are displayed in the notebook. The model can be used to classify new SMS messages as spam or ham.

   
