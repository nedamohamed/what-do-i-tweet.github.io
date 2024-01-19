# CS 210 Fall 2023-24 Project: Tweeting Patterns

## Table of Contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)

## Getting Started

The notebooks included in this project can be applied to any twitter archive, especially the data extraction and cleaning. The onky excpetion is for textual data. If your textual data includes a mixture of language including Arabic, Romanized Arabic and English, it will work fine. Please note that it's still not complete. The text sentiment analysis parts of the textual data analysis and lematization were removed from this project due to the time constraints. I will add them later for my own.

You can apply this code to the archive you get from X (formerly Twitter) and get your own analysis.

Under the *Figures* file, you can find the HTML content for the figures. This will be easier to browse than the websites.

Under the *data* file, you can find the extracted clean data. Anything that could breach the privacy of my followers or following was removed. It is mostly numerical.

Here's a brief explanation for what each file includes:

1. "ad_target_df_cleaned.csv": This .csv file conttains the targeting type, taregting value pair and the number of times they occurred together. This means it incldues the number of times this pair was used with taregted ads.
2. "correlation_matrix.csv": This file is a matrix showing the correlation between likes and retweets.
3. "emoji_tweets.csv": This csv file shows how often each emoji was used. A more interesting analysis would be the use of emojis over time.
4. "likes_per_day.csv": This csv file shows the number of likes gained for tweets and retweets over time since 2019.
5. "mode_hour.csv": This files shows the most active hour for each day in the dataset.
6. "mode_language.csv": This file shows which language was used most in tweets and retweets for every day in the dataset.
7. "retweets_per_day.csv": This shows the retweet pattern over time similar to "likes_per_day.csv".
8. "target_date_df": This shows the taregting type and value pairs and dates, which makes it feasible to track interests and targeting over timne.
9. "taregting_freq_df.csv": This shows the targeting type and how often it was used for every taregt data in the dataset.
10. "tweet_counts.csv": This shows the distribution of posts between original tweets, replies, quotes, circle tweets, circle quotes and retweets.
11. "tweets by datetime.csv": This shows the tweets by date-time pairs. It shows all activity.
12. "tweets_by_date.csv": This shows the number of tweets per day.
13. "tweets_by_hour.csv": This shows the cumulative sum of tweets produced at every hour of the day.
14. "tweets_languages.csv": This shows the language distribution.
15. "tweets_versus_retweets.csv": For each day in the dataset, this contains the number of tweets and number of retweets.
16. "value_freq_df.csv": This shows the frequency of each targeting value regardless of the taregting type.

## Prerequisites

All the prerequisites are in the first cell of every ipynb under "imports".

