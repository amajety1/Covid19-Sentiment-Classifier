
# COVID-19 Twitter Sentiment Analysis

This project involves analyzing the sentiment of tweets related to **COVID-19**. The goal is to classify the sentiment of tweets into positive, negative, or neutral categories using natural language processing (NLP) and machine learning techniques.

## Project Overview
The sentiment of COVID-19 related tweets is determined using **Logistic Regression**, a machine learning algorithm, and text preprocessing techniques like **CountVectorizer** and **TF-IDF**. The analysis provides insights into public sentiment regarding COVID-19 during different phases of the pandemic.

### Key Steps:
- **Data Collection**: Tweets related to COVID-19 are collected through the Twitter API.
- **Text Preprocessing**: The text of the tweets is cleaned by removing handles, URLs, and unnecessary characters.
- **Vectorization**: The text is transformed into numerical features using **CountVectorizer** and **TF-IDF Vectorizer**.
- **Model Training**: A **Logistic Regression** model is trained to classify the sentiment of the tweets.
- **Sentiment Prediction**: The trained model predicts the sentiment (positive, negative, or neutral) of new tweets.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/amajety1/Covid19-Sentiment-Classifier.git
   ```

2. Navigate into the project directory:
   ```bash
   cd Covid19-Sentiment-Classifier
   ```


## Usage

###  Data Collection
Tweets are available in CovidTweets.csv


## Model

The model used for sentiment classification is **Logistic Regression**, a widely used machine learning algorithm for binary and multiclass classification problems. It is trained on the preprocessed and vectorized text data to classify tweets as:

- **Positive Sentiment**
- **Negative Sentiment**
- **Neutral Sentiment**

### Hyperparameters:
- **Penalty**: `l1` (Lasso) and `l2` (Ridge) regularization
- **Regularization Strength (C)**: Values like `100`, `10`, `1.0`, `0.1`, `0.01`

## Evaluation

The performance of the model can be evaluated using standard metrics like **accuracy**, **precision**, **recall**, and **F1-score**. You can calculate these using the following:

```python
from sklearn.metrics import classification_report
print(classification_report(y_test, y_pred))
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

