# Movie-Recommendation

I plan to create a Movie Recommendation System that will accept a user-supplied movie title as input and provide the top 50 recommended movies to the user based on the input movie.

For our purposes, I shall utilize a movie dataset. I'll filter out which attributes to include in order to train our model and which to remove because many of them are irrelevant for recommendation reasons.

I'll use the difflib package to compare the most common movie title to the one supplied by the user in order to adjust for spelling errors and typos. This assists us in avoiding mistakes and making our model more usable.

In this case, I'll use a count vectorizer and compute cosine values to discover similarities and deliver to the user the top 50 movies they should watch following the one they supplied. It is a recommendation algorithm based on content that works rather well!

