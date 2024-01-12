Our song recommender app is designed to take a song and an artists our users love and recommend them 5 other similar songs from Spotify to fall in love with.

How does it work?
- Our algorithm takes the user's song and fetches the song's audio features from Spotify over the unique song ID
- The user song is compared against our database of popular songs: the top100 from Billboard and ~2500 other popular songs, all clustered by our algorithm based on their audio features to group their overall mood
- If the user song is one of the Billboard Top100, our app recommends another 5 songs from the Top100 belonging to the same cluster, a.k.a. with a similar mood and feeling
- If the user song is not one of the Billboard Top100, the app recommends another 5 similar songs from the remaining ~2500 popular songs in our database, also based on their clustering like the above.
- The users can enjoy the recommendations and repeat the search how many time they like :)

  
