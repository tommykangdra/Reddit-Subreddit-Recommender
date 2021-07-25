# Reddit-Subreddit-Recommender
Social networks have seen tremendous year-on-year growth in the last decade. This last year especially, the effects of Covid-19 and all the devastation it left in its wake has encouraged people to take to the internet to satiate their need for human connection. Social networks are, however, complex beasts – today, there seems to 
be social circles and communities for just about anything under the sun. Yet, no single user would have perfect and up-to-date knowledge on all the available communities on a platform that are presently available. Subreddits are one such example. A subreddit (e.g. r/<subreddit-name>) is a sub-forum community within the giant social 
network umbrella, Reddit. In groups such as these, forum post submitters and commenters discuss common topics related to their respective subreddit groups.

## Objective
to design a subreddit recommendation engine using selected network link prediction and community detection algorithms to predict subreddit forum groups a particular user is likely to comment on.

## Tools
NetworkX, Spark

## Algorithm
Jaccard Similarity, Cosine Similarity, Louvain Algorithm

## Conclusion
In a nutshell, our recommenders with Jaccard Similarity and Louvain Algorithm have outperformed the baseline algorithm under all evaluation metrics. While the performance of recommender with Cosine Similarity was not as satisfactory under top-5 or top-10 evaluation metric, we analyzed that the algorithm may not be ideal in our case where number of a user’s comments in a subreddit tends not to be directly proportional to his or her fondness of the subreddit. In the long run, good recommenders will be beneficial for Reddit to increase its user engagement and stickiness, and also to expand its advertisement coverage to more relevant users. 