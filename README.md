# HackaTUM 2023 Optiver Challenge: Trading Bot with Sentiment Analysis

## Overview

This repository contains the work I developed for the Optiver Challenge at HackaTUM 2023, where participants were tasked with creating a trading bot to operate in a simulated market environment. The objective was to compete against other participants to achieve the highest profits within a 30-minute trading session. A unique aspect of this challenge was the requirement to analyze incoming tweets, which influenced the share prices in the simulated market. This repository showcases the methodology I employed to train a sentiment analysis model using DistilBERT, along with the fine-tuning processes I undertook to optimize its performance for this specific application.

## Project Structure

- `data/`: Contains sample datasets, including tweets and market data used for training and testing the model.
- `models/`: Includes the pre-trained DistilBERT model and any fine-tuned models along with their configurations.
- `requirements.txt`: Lists all the necessary Python packages needed to run the code in this repository.

## Setup

To set up your environment to run the code, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/TimMachTUM/sentiment-analysis-for-financial-tweets.git
   cd sentiment-analysis-for-financial-tweets
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## How It Works

The core of this project is the sentiment analysis model powered by DistilBERT, fine-tuned to interpret the sentiment of tweets and predict their impact on share prices. The process involves:

- **Data Preparation**: Cleaning and preprocessing tweet data for model training.
- **Model Training and Fine-tuning**: Leveraging DistilBERT's pre-trained model, further fine-tuned on our specific dataset to capture the nuances of market-related tweets.
- **Evaluation**: Testing the bot in a simulated environment to measure its performance against historical data and during the competition.

## Results

The sentiment analysis model achieved an overall accuracy of 82.47% on the test set and our team reached 13th place in the whole competition.

---