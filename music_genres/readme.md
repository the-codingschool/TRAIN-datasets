Dataset description:

Cleaned/messy datasets, moderate difficulty


The Music Genres dataset contains information about different music tracks. Each instance in the dataset is identified by an instance ID and includes the following features: instance_id, artist_name, track_name, popularity, acousticness, danceability, duration_ms, energy, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, valence, music_genre

ML Algorithms:
1. Classification
2. Linear regression


Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/music_genres/music_genres_cleaned.csv"
df = pd.read_csv(url)
```
