# Twitter Sentiment Analysis

This project performs sentiment analysis on tweets to classify them as positive or negative. The analysis uses text processing techniques and machine learning algorithms to determine the sentiment of each tweet.

## Project Overview

- **Objective**: To classify tweets as positive or negative based on their content.
- **Tools & Libraries**: Python, Pandas, scikit-learn, NLTK, CountVectorizer, Multinomial Naive Bayes
- **Data**: Tweets with sentiment labels (positive, negative, neutral)

## Features

- Text preprocessing (tokenization, stopword removal, stemming)
- Feature extraction using CountVectorizer
- Sentiment classification using Multinomial Naive Bayes

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   
## Usage

Prepare the Data: Place your tweet dataset (CSV file) in the project directory. Ensure it has columns for 'Heading' and 'Sentiment'.


## This script will perform the following steps:

Load and preprocess the tweet data

Split the data into training and testing sets

Vectorize the text data using CountVectorizer

Train a Multinomial Naive Bayes model

Evaluate the model and print results

## Predict Sentiment:

To predict the sentiment of new tweets, modify the predict_sentiment function in sentiment_analysis.py with your new tweet data.
