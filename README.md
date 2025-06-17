# PRODIGY_DS_04-twitter-sentiment-analysis

This project performs sentiment analysis on Twitter data using the TextBlob library. It includes data cleaning, polarity-based classification, and export of sentiment predictions.
# Twitter Sentiment Analysis with TextBlob

---

##  Dataset

- **Name**: twitter_training.csv
- **Source**: [Kaggle – Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

---

## Features

- Removes URLs, mentions, hashtags, and punctuation
- Converts all text to lowercase
- Performs sentiment classification: Positive, Negative, Neutral
- Visualizes original sentiment distribution
- Exports final predictions to a CSV file

---

##  Steps to Run

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis

### 2.install dependencies
pip install -r requirements.txt

### 3.Place twitter_training.csv in the project folder
### 4.Run the notebook

