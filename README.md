# Spotify: Predicting and analyzing music tasting.  

#### Spotify knows me better than I know myself? <br />

Verify if the songs suggested by **"Discover weekly playlist"** are based on my musical habits (the ones I like, share, save, and don't like). <br />
Find out through Exploratory Data Analysis and machine learning what features of a song I like/dislike and predict whether I like or dislike a song. .<br />
 
> Goal: Get a better understanding of musical behavior listening Spotify.<br />
  
Data set: Used an app created using the Spotify API "Sort Your Music" to fetch the data, you only need an Spotify account to get access. <br />
[Sort your music](http://sortyourmusic.playlistmachinery.com/index.html) <br />
 
#### Audio Analysis song attributes:<br />
- Beats Per Minute (BPM) - The tempo of the song.<br />
- Energy - The energy of a song - the higher the value, the more energtic. <br />
- Danceability - The higher the value, the easier it is to dance to this song. <br />
- Loudness - The higher the value, the louder the song. <br />
- Valence - The higher the value, the more positive mood for the song. <br />
- Length - The duration of the song. <br />
- Acoustic - The higher the value the more acoustic the song is. <br />
- Popularity - The higher the value the more popular the song is. <br />
 
#### Choosing the right estimator: Classification (Category - Labeled Data): <br />
#### Predictive model: Like or Dislike a song (Score: 70/30)  <br /> 
- Model : Logistic Regression - Score: 86% <br />
- Random Forest Classifier - Score: 89% <br />
- XGBOOST - Score:90% <br />

#### Tools an Python Libraries used:<br />
- Spotify API<br />
- Scikit-learn<br />
- Numpy<br />
- Pandas<br />
- Seaborn<br />
- Matplotlib<br />
- Xgboost<br />
- Sklearn - RandomForestClassifier<br />
- Sklearn - LogisticRegression<br />
