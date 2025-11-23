# Overview

This project explores historical stock price data for four major companies:

*Apple (AAPL)

*Microsoft (MSFT)

*Netflix (NFLX)

*Google (GOOG)

 The dataset covers 3 months of stock activity, and the goal is to analyze patterns in price movements, volatility, and correlations across these companies.


# What’s Included

-stock market.ipynb → Full analysis & visualizations

-stocks.csv → Dataset containing daily OHLC values

-Visualizations exploring:

*Closing price distribution

*Volume trends

*Volume vs. price relationship

*Correlation matrix

*Pandas Profiling report


# Exploratory Data Analysis (EDA)
✔ 1. Closing Price Distribution

A histogram was created to understand how closing prices are spread. Shows strong clustering for each company.

✔ 2. Total Trading Volume By Company

The bar chart shows AAPL has the highest trading volume, followed by GOOG and MSFT.

✔ 3. Volume vs. Closing Price

A scatterplot  helps visualize whether higher volume relates to price shifts.

✔ 4. Boxplot of Closing Prices

The boxplot displays the distribution, median, quartiles, and outliers for all companies.

✔ 5. Correlation Heatmap

The correlation matrix indicates that OHLC values are highly correlated (r> 0.99), while volume exhibits a negative correlation (r ~ –0.54).


# Key Insights

Some of the important findings:

*OHLC prices across companies move strongly together (high correlations).

*AAPL had the highest trading volume, showing heavy market activity.

*Volume does not directly predict price (weak negative correlation).

*Stock price clusters show stable behavior within each ticker.

*Closing prices for most stocks fall into clear price ranges with occasional outliers.
