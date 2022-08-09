># Project5-Unsupervised_ML
>## Spotify_playlist

Moosic is a little start up that creates curated playlists done by music experts and specialists in old and new trends. Users can subscribe to their website and listen to these playlists through their preferred Music App like Spotify.

>## Tasks:
* Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria?
When you listen to two rock ballads, two operas or two drum & bass songs, you identify them as similar songs? Are these similarities detectable using the audio features from Spotify?

* Is K-Means a good method to create playlists? Would you stick with this algorithm moving forward, or explore other methods to create playlists?

>## Summary of work done so far:

* Data Collection
  - Data from spotify music app (5200 songs)

* Exploratory Data Analysis, data cleaning and data visualization
  - Drop unused columns
   - Remove outliers
    - Plotted different graphs to understand the relationship amongst different song features 

* Data Scaling methods used
  - MinMaxScalar
  - StandardScalar
   - RobustScaler

* K-means clustering
  - Used “Elbow-Method” to define amount of clusters (=playlists)
   - Use Silhouette score to decide on best scaler
