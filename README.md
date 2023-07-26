# Tweet_Impressions
The goal of this project was to create a process or application that could quickly describe the
major topics or themes and summarize sentiments in tweets reacting to the launch of Beyond
Meat & KFC’s plant-based chicken nuggets. This type of real time real world feedback informs
stakeholders with the early opinions and judgements of the new product that might be difficult to
get in a market research setting.

#Data Description:
● Tweet queries were built iteratively to insure only relevant tweets were included, order of
words were preserved when necessary, see example queries below:
-"Beyond+Meat+kfc -is:retweet" ,
-"Beyond+Meat+chicken -filter:retweets",
-beyond+fried+chicken OR beyond+plant-based OR beyond+nuggets
-filter:retweets"
-“Beyond Meat”* -filter:retweets"
Tweets were compiled starting January 4th, 2022
Analysis aims to included roughly 5,000 tweets, unfortunately rate max and code errors
resulted in a smaller than desired corpus

#Tools:
-Tweepy along with the Twitter developer API is used to gather tweets
-NLTK Vader, for sentiment analysis
-Scapy
-Pipeline
-Parts of Speech tagging
-LSA, NMF, vs Corex, for topic modeling
