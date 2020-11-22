# Classify Song-Genres from Audio Data

Here we use a dataset comprised of songs of two music genres (Hip-Hop and Rock), and I will train a classifier to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com) (now part of Spotify).

First, I will use the pandas and seaborn packages for the following steps.

1. Subsetting the data
2. Aggregating all information
3. Creating plots for trend analysis

Secondly, I will use the scikit-learn package for predicting that if we can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. 
