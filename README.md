# Tweet_Sentiment_Analysis
Sentiment analysis for US airline tweets

The purpose of this assignment is to compute the sentiment of text information - in our case, tweets posted in 2015 regarding US airlines - and answer the research question: “What can public opinion on Twitter tell us about the US airlines in 2015?” The goal is to essentially use sentiment analysis on Twitter data to get insight into the people’s opinions on US airlines.

Two sets of data are used for this assignment. The generic_tweets.txt file contains tweets that have had their sentiments already analyzed and recorded as binary values 0 (negative) and 4 (positive). Each line is a single tweet, which may contain multiple sentences despite their brevity. The comma-separated fields of each line are:
0 class the polarity of each tweet (0 = negative emotion, 4 = positive emotion)
*
1. id the id of the tweet (e.g. 2087)
2. date the date of the tweet (e.g. Sat May 16 23:58:44 UTC 2009)
3. query the query (e.g. lyx). If there is no query, then this value is NO_QUERY.
4. user the user that tweeted (e.g. robotickilldozr)
5. text the text of the tweet (e.g. Lyx is cool)

The second data set, US_airline_tweets.csv, contains a list of tweets regarding several US airlines. The comma-separated fields of each line are:
<br>

 0. id the id of the tweet
1. sentiment can be “positive” or “negative”
2. negative_reason reason for negative tweets. Left blank for positive tweets.
3. user the user that tweeted
4. retweet_count number of retweets
5. text the text of the tweet
Both datasets have been collected directly from the web, so they may contain html tags, hashtags, and user tags.
