

# Covid19-Sentiment-Classifier

This repository contains the code for a sentiment analysis project based on tweets related to COVID-19. The goal of this project is to analyze public sentiment surrounding the pandemic using natural language processing (NLP) techniques.

## Overview

In this project, I utilized Python and popular machine learning libraries, such as Pandas, Matplotlib, Seaborn, and Scikit-learn, to clean, preprocess, and analyze Twitter data related to COVID-19. The data is analyzed to classify tweets into positive, negative, or neutral sentiments. The final model is deployed in a web application for real-time sentiment analysis.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project aims to explore public sentiment on Twitter related to COVID-19 by using various machine learning and NLP techniques. It includes:

- Collecting tweet data via Twitter API.
- Preprocessing the text (tokenization, stopword removal, etc.).
- Analyzing the data for insights using visualizations.
- Building a machine learning model to classify tweet sentiment.
- Deploying the model on a web application using Flask.

## Dataset

The dataset for this project consists of tweets related to COVID-19, sourced from the Twitter API. The tweets have been labeled with sentiment categories: positive, negative, and neutral.

### Sample of Dataset

| Tweet Text                                        | Sentiment |
| ------------------------------------------------ | --------- |
| "COVID-19 is really affecting our lives."        | Negative  |
| "Stay safe, everyone!"                           | Positive  |
| "The world will recover from this."              | Neutral   |

## Installation

To install the necessary dependencies, clone this repository and install the required libraries using `pip`.

1. Clone the repository:

   ```bash
   git clone https://github.com/amajety1/Covid19-Sentiment-Classifier.git
   cd Covid19-Sentiment-Classifier
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## How to Run

1. **Data Preprocessing**: The preprocessing steps are handled in the `preprocessing.py` file. This includes text cleaning, tokenization, and feature extraction.
   
2. **Model Training**: The `train_model.py` file trains the sentiment analysis model using Scikit-learn’s Naive Bayes classifier.

3. **Web Application**: Run the Flask web application with the following command:

   ```bash
   python app.py
   ```

   This will start the web application at `http://localhost:5000`, where you can input tweets for real-time sentiment analysis.

## Usage

- **Input Tweets**: Enter a tweet in the web application's input field.
- **Sentiment Prediction**: The model will classify the tweet as positive, negative, or neutral.
- **Visualizations**: Explore sentiment trends over time, word clouds, and sentiment distribution in the analysis section.

## Contributing

Feel free to contribute to this project! If you have suggestions or improvements, open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
