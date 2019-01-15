# Tweetalizer
Shows a real-time top tweets visualization on the US map based on user selection

## TODO
0. Create a twitter stream with updated keys and tokens
1. Create the spouts and bolts 
2. Use required open sourced bolts whereever needed
3. Flow the twitter stream through the count bolt
4. Count bolt counts the num of likes and retweets on any tweet and pass it to the Top-tweets bolt
5. Top-tweets bolt takes in the tweets and their count and picks the top 50 tweets with the highest count
6. Implement US map visualization and display the top 10 tweets using the tweet's geolocation per state.
7. Display less or no tweets if found.

