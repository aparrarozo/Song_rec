# Song_recommender 

The song recommender project explores a key feature of most music streaming sevices. The user inputs a song they like and the recommender will analyse it and suggest a similar one. For the third project of the bootcamp, I put into practice different techniques of data collection such as web scraping and APIs requests and explored modelling methods such as clustering K-Means. 

# The Data
In order to create a large dataset to base the recommendations on, the Spotify API has been used in order to retreive data, covering the following parameters of the song: Title, URI, Artist, Popularity and its audio features (danceability, energy, key, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duratin in ms and time signature.

# Workflow
Web scraping the Hot 100 Billboard and creating a dataframe with the current hot 100 songs. Using Spotify API to create a large dataset with almost 60k songs and its audio features. Normalizing the data from the previous dataset and creating eight different clusters depending on the song audio features, with the K-means method. Creating the final prototype of the program, which checks if the user's choice is in the Hot 100 Billboard list and gives a hot recommendation if so. On the other side, if the song is not hot anymore, the program will recommend another song from Spotify based on the song audio features of the user's choice.
