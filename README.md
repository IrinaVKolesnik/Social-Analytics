#  Social Analytics:  Distinguishing Sentiments

## Background

__Twitter__ has become a wildly sprawling jungle of information&mdash; 140 characters at a time. Somewhere between 350 million and 500 million tweets are estimated to be sent out _per day_. With such an explosion of data, on Twitter and elsewhere, it becomes more important than ever to tame it in some way, to concisely capture the essence of the data.

## News Mood

In this assignment, I've created a Python script to perform a sentiment analysis of the Twitter activity of various news oulets, and to present your findings visually.

The final output provides a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: BBC, CBS, CNN, Fox, and New York times.

## Trends and observations:

### 1. Twitter is constanly used to send tweets; some days are more productive than the others.
The mass media analyzed here uses Twitter to send tweets everyday. Most of the tweets are sent on Thursday and Friday, every hour or two. Then, on weekends, the amount of tweets falls, slowly increasing from Monday. 

### 2. All media sources included in our sentiment analysis send positive, negative, and neutral sentimental tweets. 
Plot 1: Overall, there are much more positive tweets than negative ones. Some media sources are generally more positive than the others: CBC and Fox are mostly represented in the 'positive' part of the plot. The 'negative' part shows the presence of mainly CNN and NYTimes, although with a more precise look these sources are well distributed all over the plot.  

![png](output_5_0.png)

### 3. Some of our media sources tend to be more consistent with their mood preferences, whereas the others have a more polar attitude toward the topic.
Plot 2: Fox, CBS, and NYTimes are relatively consistent with their sentiments; BBC and CNN gave more polar tweets.

![png](output_7_0.png)

### Tools used: tweepy, pandas, matplotlib, seaborn, textblob, and VADER.
