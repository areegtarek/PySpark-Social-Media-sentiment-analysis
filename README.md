# PySpark-Social-Media-sentiment-analysis

### 1. Problem specification:
Sentiment Analysis model by using PySpark to analyze social media data for
gaining insights into user sentiment. We analyze the collected data to find out
which tweets are positive and negative.

### 2. Data Collection
This is the sentiment140 dataset from Kaggle. It contains 1,600,000 tweets
extracted using the Twitter API. The tweets have been annotated (0=negative,
1=positive) and they can be used to detect sentiment.

#####It contains the following 6 fields:
      1. target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
      2. ids: The id of the tweet ( 2087)
      3. date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
      4. flag: The query (lyx). If there is no query, then this value is NO_QUERY.
      5. user: the user that tweeted (robotickilldozr)
      6. text: the text of the tweet (Lyx is cool)
      
