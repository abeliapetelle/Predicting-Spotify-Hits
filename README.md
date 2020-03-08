# Predicting-Spotify-Hits

# Objective :\
Predicting spotify hits using supervised machine learning algorithms 

# Context :\
Every music producer wants to put the track that has the best chance of becoming a hit at the first posoition of the album.
But how do you know if the song has a chance of becoming a hit?

Music tracks can be analyzed using a large number of parameters such as their key, the level of danceability, the acousticness, they duration, etc. By analyzing these parameters and trying to find the best supervised machine learning model, we can try to predict which tracks have the most potential to become a hit.

Data :
This is a dataset consisting of features for tracks fetched using Spotify's Web API. I took only the smaller version of it from Kaggle.
The tracks are labeled '1' or '0' ('Hit' or 'No hit') depending on some criterias of the author.

The author's condition of a track being "No hit" is as follows:
- The track must not appear in the 'hit' list of that decade.
- The track's artist must not appear in the 'hit' list of that decade.
- The track must belong to a genre that could be considered non-mainstream and / or avant-garde.
- The track's genre must not have a song in the 'hit' list.
- The genre list for the particular decades are as follows:
- The track must have 'US' as one of its markets.

Method :
As we want to predict which class a track is part of which (hit or no hit), we will use classification algorithms.

Process:
- Data manipulation
- Exploratory data analysis
- Supervised learning
- Supervised learning with PCA
- Summary
