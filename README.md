# Predictive-Analytics-of-Stock-Market-Data

### Overview
This repository contains an in-depth analysis of Tata Consultancy Services (TCS) stock market data over a period of 10 years, from 2013 to 2024. The objective of this analysis is to extract key performance metrics, understand stock price trends, and build predictive models for generating trading signals. This project utilizes various data analysis techniques and machine learning models to provide insights and potential trading strategies.

### File Structure
<br>TCS_Stock_Analysis.ipynb: The primary Jupyter Notebook containing the complete code for data analysis, visualization, and model building.
<br>TCS_Stock_Data_2013_to_2024.csv: A CSV file containing the cleaned and pre-processed TCS stock data used in the analysis.
<br>README.md: This file, providing an overview and details of the analysis.

### Key Components of the Analysis
#### Data Collection and Cleaning:
The analysis begins with the collection and aggregation of TCS stock data from multiple CSV files.
<br>The data is cleaned by handling missing values, converting data types, and filtering relevant records.

#### Descriptive Statistics:

<br>Summary statistics are calculated to understand the overall distribution of key stock metrics such as Open Price, Close Price, High Price, Low Price, and Volume.
<br>The analysis includes computation of price statistics over various time periods to gauge the stock's historical performance.

#### Trend Analysis:
<br>The dataset is enriched with additional features such as daily percentage changes and categorized trends to capture market sentiments.
<br>Various trends (e.g., "Bull Run," "Bear Drop") are analyzed to understand their impact on trading volume.

### Visualizations:
#### Several visualizations are created to understand the stock's behavior over time, including:
<br>Line plot of TCS's close price over time.
<br>Stem plot of daily percentage changes.
<br>Pie chart of stock trend distribution.
<br>Bar charts showing median and mean traded quantities by trend.
<br>Histogram of daily percentage change distribution.
<br>Overlay plots of Bollinger Bands, Simple Moving Averages, and trade signals.

#### Moving Averages and Bollinger Bands:
<br>Calculation and visualization of moving averages (21-day SMA, 34-day LMA) and Bollinger Bands (14-day SMA) to identify trading opportunities.
<br>The crossover strategy using these indicators helps in generating buy/sell signals.

### Predictive Modeling:
Various machine learning models (Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Decision Tree, Random Forest, Gaussian Naive Bayes, Neural Networks) are trained to predict trading signals based on the derived features.
<br>Model performance is evaluated using accuracy, confusion matrices, and classification reports.
