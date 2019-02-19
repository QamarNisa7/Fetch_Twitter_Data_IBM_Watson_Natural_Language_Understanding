# Fetch_Twitter_Data_IBM_Watson_Natural_Language_Understanding
Fetch tweets and relevant data of a public twitter account using Tweepy Library, perform word processing on the tweets using IBM Watson Natural Language Understanding API to check the sentiments, context, tone etc of the tweets.

## Attached are 3 Jupyter Python Notebooks for this project:
### Tweet Analytics_Tweepy_Data_gathering:
Gather tweets of a user using their @HandleName via Tweepy Library. Here I am taking basic data, you can gather more (check tweepy library details for that)

#### Credentials:
This Code uses tweets as the data source. To pull tweets programmatically from Twitter, you use the Twitter APIs, for which you need OAuth credentials.
1. If you do not have a Twitter account, sign up for one.
2. Get the access tokens by following these [instructions](https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens). When you are done, you should have the following four credentials: consumer key, consumer key secret, access token, and access token secret. Copy these credentials and put them in the notebook.

Sign up to IBM Cloud, Go to Catalog, Create service "Watson Natural Language Understanding", copy its credentials.
