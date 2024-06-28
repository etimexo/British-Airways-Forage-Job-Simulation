# British-Airways-Forage-Job-Simulation
# British-Airways-Forage-Job-Simulation
# British Airways Job Simulation on Forage

This repository contains the code and resources used for the British Airways job simulation on Forage. The project involves web scraping customer reviews from Skytrax, performing sentiment analysis on the gathered data, and creating a model to predict whether a customer will complete their booking based on certain features in a provided dataset.

## Table of Contents
- [Overview](#overview)
- [Setup and Installation](#setup-and-installation)
- [Web Scraping](#web-scraping)
- [Sentiment Analysis](#sentiment-analysis)
- [Predictive Modeling](#predictive-modeling)
- [Conclusion](#conclusion)

## Overview
In this project, I worked on three main tasks:
1. Web scraping customer reviews on British Airways' services from Skytrax.
2. Performing sentiment analysis on the scraped reviews to understand customer satisfaction.
3. Building a predictive model to determine the likelihood of a customer completing their booking based on features in the provided dataset.

## Setup and Installation
To run this project, you'll need to have Python installed on your system. You can install the required packages (pandas, numpy, matplotlib, seaborn, textblob, scikit-learn)

## Web Scraping
The web scraping script collects customer reviews from Skytrax. The script is located in src/web_scraping.py.

Libraries for scraping: requests, BeautifulSoup, pandas
Output: A CSV file containing the scraped reviews and their metadata.
Sentiment Analysis
The sentiment analysis is performed on the collected reviews to gauge customer satisfaction. This is done using a Jupyter notebook located in task1.ipynb file.

## Sentiment Analysis
Libraries Used: TextBlob, pandas, matplotlib
Output: Sentiment scores and visualizations of the results.
Predictive Modeling
A predictive model is built to determine if a customer will complete their booking based on certain features in the dataset. The code for this is in task2.ipynb.

## Predictive Modeling
Libraries used for prediction: pandas, numpy, scikit-learn, matplotlib, seaborn
Model Used: Random Forest (other models can also be explored)
Evaluation Metrics: Cross-validation Accuracy, Precision, Recall, F1 Score

## Conclusion
The project successfully demonstrates the use of web scraping, sentiment analysis, and predictive modeling in the context of analyzing customer reviews and predicting booking completions. The results provide valuable insights into customer satisfaction and the factors influencing booking decisions.