# Spotify_eda
A data analysis project using python

In this project i have analysed spotify data

Dataset contains of 2017 songs with attributes from Spotify's API. Each song is labeled "1" meaning author like it and "0" for songs author don't like. 
Author used this to data to see if author could build a classifier that could predict whether or not author would like a song.

Content:

Each row represents a song.

There are 16 columns. 13 of which are song attributes, one column for song name, one for artist, and a column called "target" which is the label for the song.

Here are the 13 track attributes: acousticness, danceability, durationms, energy, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, timesignature, valence.

Dataset is taken from kaggle.

Dataset link: https://www.kaggle.com/datasets/geomack/spotifyclassification?datasetId=1833&sortBy=voteCount


Methodology:
I am using numpy,matplotlib, seaborn,pandas

I have imported dataset there is an unwanted column so i have removed it 

I have preliminary data analysis like describe, null values in columns, columns data type, many more

I have analysed the dataset using some queries like:
Most Popular artist

Top loudest  tracks

Artist with the most danceable song

Top instrumentalness songs

Top 10 energetic tracks

Top 10 tracks with most valence

Artist with most number of songs (top 5)

Most liveness songs(top 5)

Songs with more danceability(top 10)

Most duration song

I did all the above data extractions using sort_values function, groupby function, ascending function, count function

I did visualiztion using seaborn, plots i did are bar plot , pie chart.
