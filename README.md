# Stock Prediction Using Twitter Sentiment Analysis

## Introduction
This project aims to predict stock prices using Twitter sentiment analysis. By analyzing tweets related to a particular stock, we attempt to gauge the sentiment of the market towards that stock and use this information to predict its future price movements.

## Setup Instructions
1. Clone the repository to your local machine.
2. Ensure you have Python 3.x installed.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Download the necessary datasets: `TSLA_tweets.csv` and `TSLA_prices.csv`.
5. Run the Jupyter notebook `stock_prediction.ipynb` to execute the code and generate predictions.

## Description
- The project utilizes the Natural Language Toolkit (NLTK) library for sentiment analysis, specifically the VADER (Valence Aware Dictionary and sEntiment Reasoner) model.
- Tweets related to the target stock (Tesla in this case) are collected and processed to extract sentiment scores.
- A Random Forest Regression model is trained using features such as the number of tweets and overall sentiment (positive, negative, neutral).
- The trained model is then used to predict future stock prices based on the extracted features.

## Files Included
- `stock_prediction.ipynb`: Jupyter notebook containing the Python code for data processing, sentiment analysis, model training, and evaluation.
- `TSLA_tweets.csv`: Dataset containing tweets related to Tesla stock.
- `TSLA_prices.csv`: Dataset containing historical stock prices of Tesla.
- `README.md`: Documentation file providing an overview of the project, setup instructions, and description of files.

## Results
- The notebook includes visualizations of sentiment distribution, overall sentiment trends, and actual vs. predicted stock prices.
- Evaluation metrics such as Root Mean Squared Error (RMSE) and R-squared (R^2) scores are provided to assess the performance of the prediction model.

## Contributors
- Supratim Banik: [supratimbanik](https://github.com/supratimbanik)


