# Cross-Platform-Movie-recommendation-system

In the spread of information, how to quickly find one’s favorite movie in such a large number of movies becomes a very important issue. Today we have so much content on so many platforms like Netflix, Amazon Prime, AppleTv, HBO, Hotstar, Voot, etc. These platforms have their own recommendation engines for their content, but there is no platform that suggests the content from the various platform altogether. I have tried to build a cross platform setup to recommend movies from different platform.

The Datasets used in this project are scraped from finder.com ( script in the repo).

I have used content based recommender based on genre tags to identify cosine similarity between movies with similar genre tags.

Use of NLTK library for preprocessing and cleaning of genre tags.

The Datasets are then combined and the final recommendation shows similar movies of Netflix and Amazon Prime.

The dataset consists of genre tags such as ‘Sci-fi’,’Drama’,’Romance’,’Comedy’ etc. and each movie has different tags of genres for eg. the movie ‘Ae Dil hai Mushkil’ has the tags ‘Bollywood’,’Drama’,’Romance’,’ World Cinema’. All the movies sharing the same or a maximum number of tags with this movie have the probability of being similar to this movie. Also, we have added some more features to refine the recommendations such as minimum IMDb Rating, same age rating, near about year of release, etc.

This is a work-in progress. I had ideas to recommend movies based on metadata, ratings, sentiment analysis of reviews etc.but I could not find a dataset which is similar for both platform which can be integrated easily.
