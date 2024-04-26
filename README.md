# Reddit Sentiment Analysis

This project involves collecting headlines from Reddit, processing the text data, and performing sentiment analysis to classify sentiments as positive, negative, or neutral. The project uses machine learning models and natural language processing tools to predict the sentiment of headlines from various subreddits related to economy, finance, business, and investing.

## Project Structure

- **Data Collection**: Uses the `praw` library to fetch headlines from specific subreddits.
- **Data Cleaning**: Involves converting to lowercase, removing special characters, and other preprocessing steps.
- **Sentiment Analysis**: Uses `nltk`'s SentimentIntensityAnalyzer for initial sentiment annotation.
- **Feature Extraction**: Applies TF-IDF, Word2Vec, and GloVe for feature extraction.
- **Model Training**: Trains Naive Bayes, SVM, and Neural Network models to classify sentiment.
- **Deployment**: A simple GUI using `tkinter` to predict sentiment from user input.

## Setup Instructions

1. **Clone the Repository**
git clone https://github.com/yourusername/reddit-sentiment-analysis.git
cd reddit-sentiment-analysis

2. **Install Dependencies**
pip install -r requirements.txt


3. **Configuration**
- Update the `praw` configuration in the script with your Reddit API credentials:
  ```python
  reddit = praw.Reddit(client_id='your_client_id',
                       client_secret='your_client_secret',
                       user_agent='your_user_agent')
  ```

4. **Running the Code**
Select a virtual environment or a python environment to run for and execute the jupyter notebook file. 
  ```

## Features

- **Data Collection from Reddit**: Fetches headlines from multiple subreddits.
- **Comprehensive Text Processing**: Includes tokenization, stop word removal, and lemmatization.
- **Multiple Feature Extraction Techniques**: Uses TF-IDF, Word2Vec, and GloVe.
- **Multiple Machine Learning Models**: Evaluates different models to find the best performer.
- **Interactive GUI**: Allows users to enter text and receive sentiment predictions.

