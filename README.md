# Streaming-Projection-Model
This project predicts the streams based on many features, including danceability%, in spotify charts, energy%, and more. Analysis is found in the jupyter notebook file, along with the equation found to find how many streams a song would have (coefficients were found). Data was charted and graphed, along with the importance of the features using Random Forest. Predictions found using Linear Regression.

music.json - kaggle data was converted to json file to load
musicFixed.json - I ran a script to delete all missing data, i.e. any data that was left blank or had '' in its place.
Popular_Spotify_Songs.csv - This was the csv from Kaggle that was turned into music.json
streamProjection.ipynb - Jupyter notebook where all coding and analysis was done.

Streaming data found on Kaggle: https://www.kaggle.com/datasets/zeesolver/spotfy
