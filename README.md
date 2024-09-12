#Splotify Playlist  Mood Analyzer

#Project Overview
The purpose of this project is to create an algorithm that analyzes and recommends new playlists to Spotify listeners based on their listening patterns, more specifically, the moods of the songs that they listen to. 

#Data Sources
The data used in this project is from the Spotify API. The data includes the audio features of songs such as danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms, time_signature, and track popularity.

#Code Structure
The code is structured in the following way:
- Data Collection: The data is collected from the Spotify API using the spotipy library.
- Data Preprocessing: The data is preprocessed to remove any missing values and to normalize the data.
- Mood Analysis: The mood of the songs is analyzed using the audio features of the songs.
- Playlist Recommendation: Based on the mood of the songs, new playlists are recommended to the user.
- Evaluation: The performance of the algorithm is evaluated using the F1 score.
- Conclusion: The results of the project are summarized and future work is discussed.

#Collaborators and contributions
- Gabriela Coada: Data Sources, Project Overview, and Code Structure
- Jiwon Son: How It Works, Challenges Faced, and References 
