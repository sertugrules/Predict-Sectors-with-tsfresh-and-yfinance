# Ertuğrul Sert Data-Intensive Application Project

## Project Overview
This project, addresses a time series classification problem with a focus on financial data analysis.
The primary goal is to develop a classification model that distinguishes the behavior of specific stocks across different sectors based on time-series data. By analyzing monthly returns and applying feature engineering on momentum series, the project seeks to identify which sector a given stock resembles the most, offering insights into potential market movements.

## Features
- **Sector Data Collection:** Utilizes web scraping to gather a comprehensive list of sectors and their respective stock data.
- **Time Series Analysis:** Constructs time series of monthly returns from 2005 onwards, analyzing sector-based performance.
- **Feature Engineering:** Applies tsfresh for extensive feature engineering, including imputing, encoding, and transformation of the time series data.
- **Model Building:** Develops a classification model to determine sector resemblances based on the engineered features.
- **Similarity Analysis:** Evaluates other sectors to determine resemblance and potential sector classification for given stocks.

## Technologies Used
- Python
- yfinance
- pandas
- BeautifulSoup
- tsfresh

## Installation
To run this project, you'll need to install the required Python libraries. You can install them using pip:
```bash
pip install yfinance pandas requests bs4 tsfresh
