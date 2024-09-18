# Kaggle-Competitions-and-Other-Exercises
Code for some projects I worked on during my Master's program.

1. Ames Housing Data Regression. This code is for a linear regression model to predict house prices.
   Based on the Kaggle Ames Housing Dataset (https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
   Final score achieved was within the top 15% of submissions at the time of posting.
2. Kingston Temperature Prediction. This code is for a time series (ARIMA) model to predict the temperature for the next 100 years in Kingston, Ontario.
3. Document Classification. This was code I wrote for a spam email classification problem. Features text processing with a simple Multinomial NB as the champion algorithm in the pipeline.
4. Sentiment Analysis via Machine Learning Based Approach. This code uses machine learning to predict document sentiment using a pre-scored training dataset.
5. Tweet Scraping. A python-based web scraper designed to scrape tweet information (handle, time, content, etc.) off Twitter. Used in the sentiment analysis of Tweets containing the word "Tesla" or "Elon Musk" on Tesla's stock price.
6. Tweet Preprocessing. Simple ETL/cleaning script for scraped tweet data from the above code.
7. Tesla Tweets & Descriptive Model. R code analysis on the effect of the above Tweets (sentiment) on Tesla's closing price each day. Interestingly, an R-squared of 0.04 (significant, 95% CI does not cross 0) was found between sentiment and closing price.
