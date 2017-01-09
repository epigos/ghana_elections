# Twitter analysis of Presidential election in Ghana


This contains source code and dataset used in my analysis of the President elections in Ghana.
The analysis involves sentiment analysis of twitter by detecting polarity and also emotions displayed by the writer of the tweet using machine learning algorithms.

Here is the blog post; [Ghana Presidential Election 2016 — Twitter Analysis Part 1](https://medium.com/@epigos/ghana-presidential-election-2016-twitter-analysis-part-1-57ffa6f7e1c6#.pyt37na1k)

The ipython notebook contanins the source code.

### Install dependencies

```
pip install -r reqirements.text
```

### Start notebook
```
jupyter notebook
```

### Description

Datasets used can be found the `data` directory.

Description of Dataset (`2016_election_tweets_part_1`)

    1. favorites - number of favorites of tweet.
    2. hashtag - hashtag from which tweets was collected.
    3. permalink - link to the tweet on twitter.
    4. retweets - number of retweets of tweet.
    5. score - the sum of favorites and retweets of the tweet.
    6. text - the tweet itself.
    7. timestamp - datetime of tweet.
    8. username - user who made the tweet.


The `model` directory contains saved models used in the analysis;

    1. emotion_model - used in detecting emotions of tweets.


The `plots` directory contains all saved plots as images.
