# fake_news_detection
Fake News Detection using ML and NLP

# Fake News Detection

This project aims to build a machine learning model to identify unreliable news articles. The model uses Logistic Regression and Natural Language Processing (NLP) techniques to classify news as fake or real.

## Project Overview

The goal is to create a reliable system to automatically detect fake news articles using text data. The project includes data preprocessing, model training, evaluation, and result visualization.

## Dataset

The dataset used in this project consists of news articles with the following attributes:

- `id`: Unique identifier for each news article.
- `title`: Title of the news article.
- `author`: Author of the news article.
- `text`: Main text content of the news article, which could be incomplete.
- `label`: Binary label indicating the reliability of the article (1: Fake, 0: Real).

The dataset file is `train.csv`.



## Preprocessing

The preprocessing steps include:

- **Filling Missing Values**: Handling missing data in the dataset.
- **Removing Stop Words**: Removing common words that do not contribute to the meaning.
- **Stemming**: Reducing words to their root form using the Porter Stemmer.
- **TF-IDF Vectorization**: Converting text data into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).

## Model

The model used for classification is Logistic Regression. It is trained on the processed text data and evaluated on the test set. 

### Evaluation Metrics

- **Confusion Matrix**: Visual representation of the classification performance.
- **Classification Report**: Detailed report showing precision, recall, f1-score, and support for each class.
- **Accuracy Score**: Overall accuracy of the model.

## Results

The model achieves an accuracy of 98% on the test set.

## How to Use

### Cloning the Repository

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
