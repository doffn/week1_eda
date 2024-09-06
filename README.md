# Financial News and Stock Analysis Project

## Overview

This project consists of two main components:
1. News Headline Analysis (Task 1)
2. Financial Stock Analysis (Task 2)

The project aims to provide insights into financial news headlines and perform quantitative analysis on stock market data.

## Task 1: News Headline Analysis

### Features

- Descriptive statistics of news headlines dataset
- Analysis of headline lengths
- Publisher analysis
- Publication date trends
- Sentiment analysis using NLTK's VADER
- Topic modeling using CountVectorizer
- Time series analysis of publication patterns

### Key Components

1. **Data Loading and Preprocessing**
   - Loads data from CSV file
   - Converts date strings to datetime objects

2. **Descriptive Statistics**
   - Basic statistics of the dataset
   - Identification of columns with NaN values

3. **Text Analysis**
   - Headline length analysis
   - Sentiment analysis
   - Topic modeling and top words extraction

4. **Time-based Analysis**
   - Publication trends by hour, day, month, and year
   - Publisher frequency analysis

5. **Visualizations**
   - Headline length distribution
   - Top publishers
   - Publication date trends
   - Sentiment distribution
   - Top words in headlines
   - Hourly publication frequency

## Usage

```python
# Import necessary libraries
python pip install requirements.txt ```

## Libraries Used

### pandas
- **Purpose**: Data manipulation and analysis
- **Usage**: Loading CSV files, data preprocessing, and handling time series data
- **Key features**: DataFrame operations, date range functions, data aggregation


### matplotlib
- **Purpose**: Data visualization
- **Usage**: Creating static, animated, and interactive visualizations
- **Key features**: Line plots, scatter plots, histograms, customizable chart elements

### seaborn
- **Purpose**: Statistical data visualization
- **Usage**: Enhanced data visualization based on matplotlib
- **Key features**: Attractive default styles, built-in themes, complex statistical plots

### nltk (Natural Language Toolkit)
- **Purpose**: Natural language processing
- **Usage**: Sentiment analysis of news headlines
- **Key features**: VADER sentiment analyzer, tokenization, text processing utilities

### scikit-learn
- **Purpose**: Machine learning and data mining
- **Usage**: Text feature extraction for topic modeling
- **Key features**: CountVectorizer for text feature extraction

### ta (Technical Analysis Library)
- **Purpose**: Technical analysis of financial markets
- **Usage**: Calculation of various technical indicators for stock analysis
- **Key features**: Trend indicators (e.g., SMA, EMA), momentum indicators (e.g., RSI, MACD), volatility indicators (e.g., Bollinger Bands), volume indicators (e.g., OBV, CMF)



## Task 2: Financial Stock Analysis

### Features

- Data loading and preprocessing from CSV files
- Calculation of various technical indicators
- Visualization of stock prices and technical indicators
- Comprehensive analysis of a given stock

### Key Components

1. **StockAnalyzer Class**
   - Initializes with stock data from CSV
   - Calculates technical indicators
   - Plots various indicators

2. **Technical Indicators**
   - Simple Moving Averages (SMA)
   - Exponential Moving Averages (EMA)
   - Moving Average Convergence Divergence (MACD)
   - Average Directional Index (ADX)
   - Relative Strength Index (RSI)
   - Stochastic Oscillator
   - Commodity Channel Index (CCI)
   - Bollinger Bands
   - Average True Range (ATR)
   - On-Balance Volume (OBV)
   - Chaikin Money Flow (CMF)

3. **Visualization Methods**
   - Individual indicator plots
   - Comprehensive analysis plot


## This project was made by Dawit Neri for WEEK 1 EDA final