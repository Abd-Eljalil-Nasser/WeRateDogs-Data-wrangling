# WeRateDogs-Data-wrangling
The purpose of this project is to practice data wrangling data .The dataset wrangled is the tweet archive 
of Twitter user @dog_rates, also known as WeRateDogs.WeRateDogs is a Twitter page that regularly shares pictures of dogs along with a catchy 
description and often a rating out of 10 for the dog in the picture, sometimes exceeds 10. Created in November 2015, it became popular so fast and at this moment has more than 8 million followers. In this analysis, there was an exploration for changes in the tweets’ favorites, retweets, and ratings over time.

## Data gathering
Data was gathered from three different sources: 
1. From WeRateDogs Twitter archive given by Udacity in csv format: 
2. Image prediction file downloaded programmatically using Requests library and the URL provided by Udacity in tsv format 
3. Data retrieved by querying Twitter's APIs and using Tweepy library:  I didn’t receive a confirmation from twitter developer so I used the file ‘Tweet-Json’ which 
provided by udacity .

## some findings 
1. Pupper is the most common dog in WeRateDogs tweets.  
2. retweet counts and favorite counts are positively correlated.  
3. t Number of favorite counts increase over years
