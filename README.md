# sentiment-analysis
this is sentiment analysis program that fetches tweets from twitter using python

import re
import tweepy
from tweepy import OAuthHandler
from textblob import TextBlob

consumer_key=''//you get from twitter 
consumer_secret=''//you get from twitter
access_token=''//you get from twitter
access_token_secret=''//you get from twitter

#create OAuthHandler object
  s.auth=OAuthHandler(consumer_key,consumer_secret)
  #access to token and token secret
  s.auth.set_access_token(access_token,access_token_secret)
  #create tweepy 
  s.api=tweepy.API(s.auth)

  except:
    print("Error:Authentication failed")
    
    tweets=api.searcg("IPL")
for tweet in public_tweets;
print tweet.text
analysis=TextBlob(tweet.text)
print(analysis.sentiment)
