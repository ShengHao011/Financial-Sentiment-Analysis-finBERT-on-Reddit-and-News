# Financial Sentiment Analysis, applied on reddit posts about the market and daily news
This project provides a market sentiment analysis pipeline using FinBERT on real-time reddit/subreddit posts and financial news. FinBERT is a specialized Natural Language Processing (NLP) model. It is build on top of the BERT architecture and pretrained specifically on financial text, making it particularly effective for finance-related language task such as sentiment analysis.

The code takes in data from different subreddits using the Reddit API PRAW, as well as news articles using News API. After collecting the data, the project applies the finBERT model to determine whether the overall sentiment is positive, neutral, or negative, producing a sentiment score.

