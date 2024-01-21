# CS 210 Fall 2023-24 Project: Tweeting Patterns

## Table of Contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [What Is This?](#what-is-this?)
- [Next Steps](#next-steps)

## Getting Started

To view the project online, visit [https://nedamohamed.github.io/what-do-i-tweet.github.io/](https://nedamohamed.github.io/what-do-i-tweet.github.io/).


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

In order to see the project, all you need to do is visit the website linked above.

## What Is This?

The data I worked with consisted of over 12800 tweets and over 24000 instances of advertisements.

The analysis of this data aimed to discover patterns in my activvity and hopefully content and map them to what I already know about myself.

Pre-analysis, I had some ideas about the patterns I would find:

- I will be tweeting more over time.
- I will be most active during the evenings.
- Content analysis will show interest in history and Egyptian politics.

I conducted analysis on my activity by mapping my activity over the years and how often I tweet. Spikes in my activity was easily correlated with events happening at the time. For example, during the MeToo movement in Egypt starting July 2020, my activity saw its first spike. During the devaluation of the Egyptian pound, a spike can be seen, for every devaluation for that matter. Since the devaluation was usually gradual, the spike would last usually a week. This can be seen on the relevant graphs on the website.

Likes and retweets my tweets received are a good indication if how interactive my following is. Post COVID-19, a lot of my friends connected with me on Twitter, which explains the rise of interactions July 2020 onwards. It was also at this time that I started working in a popular magazine online, gaining more online traction.

So far, we can trace online patterns to changes and responses in my life.

The activity mapped to time shows my routine. How much time to do I have on my hand to tweet is exactly what this shows. When we look at the number of tweets I produced at each hour of the day, it's easy to spot that it's during the evenings that I'm most free.

However, this can be misleading. Tweeting does not necessarily equate free, but perhaps distracted. In order to get more out of this graph, it would be a good approach to compare it to my Google Calendar data and see whether or not I was free at the time.

## Next Steps

1. General content analysis and special analysis to the periods where there are spikes to see if the spikes are responses to the events happening.
2. Sentiment analysis to parallel it with events.
3. Cross-referencing data to Google Calendar.


