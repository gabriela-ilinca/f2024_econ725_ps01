#Spotify Playlist  Mood Analyzer

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

#How It Works
1. Collecting the Data: Collect song data such as the rhythm, tempo, energy, and genre using Spotify's API.
2. Processing the Data: Clean and extract relevant features of the data to collect only information regarding each song's mood.
3. Categorization: Classify each of the songs listened to by each listener into mood categories.
4. Recommendation: Using this classified data, creating a playlist based on mood profile, and then suggest new songs to the listener.


#Challenges Faced
The main challenge faced in this project was collecting the data from the Spotify API. The API has a rate limit of 10 requests per second, which made it difficult to collect a large amount of data. To overcome this challenge, the data was collected in increments and stored in a CSV file. 


#References
- https://developer.spotify.com/documentation/web-api/
- https://spotipy.readthedocs.io/en/2.16.1/
