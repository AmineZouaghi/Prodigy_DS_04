# 🐦 Twitter Sentiment Analysis | Prodigy InfoTech Data Science Internship

## 📋 Project Overview
This project aims to analyze and visualize sentiment patterns in Twitter data to understand public opinion and attitudes toward specific topics or brands. The primary goal is to classify tweets into sentiment categories (positive, negative, and neutral) using Natural Language Processing (NLP) techniques and machine learning models.

## Dataset

The dataset used for this task is from the **Sentiment140** dataset available on Kaggle, which contains 1.6 million tweets categorized by sentiment.

- **Dataset Link**: [Sentiment140 Dataset on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
  
The dataset consists of the following columns:
- `target`: The polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
- `ids`: The unique ID of the tweet
- `date`: The date of the tweet
- `flag`: The query (if there is no query, this value is NO_QUERY)
- `user`: The Twitter username of the user who tweeted
- `text`: The actual text of the tweet

## Getting Started

### Prerequisites

To run this project, you'll need the following libraries installed:
- `pandas`
- `numpy`
- `nltk`
- `sklearn`
- `matplotlib`
- `seaborn`

## 📂 Repository Contents
- **Prodigy_DS_04_Twitter_Sentiment_Analysis.ipynb**: Jupyter notebook containing the sentiment analysis process, including data cleaning, sentiment classification, and visualization.
- **data/**: Folder containing the sentiment analysis dataset.

## 📊 Key Insights
1. **Sentiment Distribution**: Most tweets were classified as neutral, followed by positive and negative sentiments.
2. **Entity Sentiment**: Certain topics or brands received overwhelmingly positive sentiment, while others received more negative feedback.
3. **Sentiment Over Time**: Sentiment trends fluctuated during major events, showing spikes in both positive and negative reactions.

## Conclusion
This project demonstrates a basic sentiment analysis pipeline using machine learning on Twitter data. It can be extended or refined by using more advanced models or larger datasets.

## 🤝 Connect with Me
[LinkedIn: Mohamed Amine Zouaghi](https://www.linkedin.com/in/mohamed-amine-zouaghi-500210225/)
