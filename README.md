Sentiment Analysis on Airline Customer Tweets
Overview
This project focuses on performing sentiment analysis using customer-generated tweets related to North American airline companies. The goal is to analyze and predict sentiment based on the text content of the tweets. Two different approaches are employed for sentiment prediction: Naive Bayes and Long Short-Term Memory (LSTM) models.

Project Structure
The repository is organized as follows:

data/: Contains the dataset used for training and testing the sentiment analysis models.
notebooks/: Jupyter notebooks used for data exploration, preprocessing, and model training.
src/: Source code for implementing the sentiment analysis models, including Naive Bayes and LSTM implementations.
results/: Stores the results obtained from model evaluations, including accuracy metrics and visualizations.
Sentiment Analysis Models
Naive Bayes Model
The Naive Bayes model is implemented to classify the sentiment of customer tweets. This probabilistic model assumes independence between features and is suitable for text classification tasks.

LSTM Model
Long Short-Term Memory (LSTM) neural network architecture is employed for sentiment analysis. LSTMs are well-suited for capturing sequential dependencies in data, making them effective for analyzing text data with context.
