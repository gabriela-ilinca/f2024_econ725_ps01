





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