# WeRateDogs
We analyze the dataset from the tweet archive of Twitter user @dog_rates also known as WeRateDogs. 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dogs. 
These ratings almost always have a denominator of 10. 
The numerators, though? Almost always greater than 10. 11/10, 13/10, etc. Why? Because "they're good dogs Brent."

Some of the data were sourced from the WeRateDogs Twitter archive made available to Udacity,
where we gathered it by downloading it.
Udacity ran it through a neural network to detect the presence of a dog in every image 
and predicted the breed of the dog whereapplicable. 
A result of this was provided to us and downloaded into our workspace.
We further queried Twitter's API to enrich our data further.
In our analysis, we asked:
1. Which was the most popular tweet through favourite count and retweet count?
2. Which was the most common dog breed?
3. Was there a relationship between the rating_numerator and the favorite_count?
