# Online_news_sentiment
## Scrape Forbes, CNN, and NYTimes for daily articles and score their mood sentiments

This Python code performs the following steps:

1. Scrape Google using Selenium for URLs of Forbes articles based on a user-defined date range. The code incorporates methods to bypass Google's automatic browsing limit detection.
2. Import the saved URL's and scrape and score their sentiments using Newspaper and NLTK.
3. Repeat steps 1-2 for CNN and NYTimes.

Sentiment is scored separately for positive, negative, and neutral mood, as well as a combined sentimet score.

