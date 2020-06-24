# Spotify: Predicting and analyzing music tasting.  

Spotify knows me better than I know myself?
Verify if the songs suggested by “Discover weekly playlist” are based on my musical habits (the ones I like, share, save, and don't like). Find out through Exploratory Data Analysis and machine learning what features of a song I like/dislike and predict whether I like or dislike a song. 
 
Goal: Get a better understanding of musical behavior listening Spotify.
 
Data set: Used an app created using the Spotify API "Sort Your Music" to fetch the data, you only need an Spotify account to get access. 
 
Audio Analysis song attributes:
Beats Per Minute (BPM) - The tempo of the song.
Energy - The energy of a song - the higher the value, the more energtic. song
Danceability - The higher the value, the easier it is to dance to this song.
Loudness - The higher the value, the louder the song.
Valence - The higher the value, the more positive mood for the song.
Length - The duration of the song.
Acoustic - The higher the value the more acoustic the song is.
Popularity - The higher the value the more popular the song is.
Rnd - A randon number. Sort by this column to shuffle your playlist.
 
Choosing the right estimator: Classification (Category - Labeled Data): Predictive model: Like or Dislike a song (Score: 70/30)
Model : Logistic Regression - Score: 86%
Random Forest Classifier - Score: 89%
XGBOOST - Score:90%

Tools an Python Libraries used:
Spotify API
Scikit-learn
Numpy
Pandas
Seaborn
Matplotlib
Xgboost
sklearn - RandomForestClassifier
sklearn - LogisticRegression
