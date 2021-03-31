# social_network_analysis_twitter

# Aim
Social network analysis based on twitter data employing graph analysis methods, as well as different centrality measures in the graph, and edge prediction.

# Data
Existing data on the internet - 

• https://github.com/shaypal5/awesome-twitter-data

• https://www.kaggle.com/data/35739

Here the data taken is of one of the months of 2009

# Methodology
1. Choose a hashtag, and filter out tweets
2. build a mention graph for your chosen hash-tag. The mention graph is the mention relations between users. In this graph, each user is viewed as a node. If a user Alice mentions another user Bob in her tweet(s) with the @ sign, then an undirected edge connects Alice and Bob. The edge weight is the number of mentions in the tweets.
3. Content analysis - Analyze the most frequent non-stopwords in all the tweets and add hover information onto the graphs
4. Centrality analysis
5. Sentiment analysis
