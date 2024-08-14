# Stock Market Predictor - Exploratory Analysis

Welcome to the **Stock Market Predictor** Project! This project hosts repositories dedicated to predicting stock market trends using, Long Short-Term Memory (LSTM) networks. Below is an overview of the repositories contained within this organization and their respective roles in the overall project.

## Repositories

### 1. **Stock_Market_Predictor_Web_App**
- **Description**: This repository hosts the web application that serves as the user interface for our stock market prediction model. The web app allows users to perform an exploratory analysis of various stock market trends. Users can input stock symbols, select time ranges, and visualize predictions alongside historical data.
- **Key Features**:
  - User-friendly interface for inputting stock data.
  - Visualization tools for historical data and predictions.
  - Integration with LSTM model for real-time predictions.
- **Technologies**: Django, Javascript, HTML/CSS, Python, Redis, Celery, Nginx, Supervisor, Gunicorn, Pytorch, Selenium

### 2. **stock-market-predictor-lstm**
- **Description**: This repository contains the core LSTM model that powers the stock market predictions in the web app. The LSTM model is trained on historical stock data to forecast future stock prices. This repository provides detailed documentation on the model architecture, training process, and how to customize the model for different stock datasets.
- **Key Features**:
  - Implementation of LSTM for time series forecasting.
  - Training scripts and datasets.
  - Model evaluation and tuning guidelines.
- **Technologies**: Python, Pytorch

### 3. **Entity-Sentiment-Analysis-and-Stock-Headline-Scraper**
- **Description**: This repository focuses on the entity sentiment analysis model and the stock headline scraper. The entity sentiment analysis is used to gauge market sentiment based on news headlines, which can be a crucial factor in predicting stock market movements. The headline scraper gathers relevant news articles for analysis.
- **Key Features**:
  - Entity sentiment analysis model to evaluate market sentiment.
  - Web scraper to collect stock-related news headlines.
- **Technologies**: Python, Selenium, Pytorch

## Getting Started

To get started with any of these repositories, navigate to the respective repository and follow the instructions provided in the README.md files. Each repository is self-contained with detailed setup guides, usage instructions, and contribution guidelines.

## Contact

For any questions, issues, or suggestions, please open an issue in the respective repository or contact me.

---

I hope you find this project useful and informative. 
