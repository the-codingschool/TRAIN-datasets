Dataset description:

Cleaned dataset, moderate difficulty

This dataset provides information about various songs, including their artists, durations, explicit content, release years, popularity, and several audio features such as danceability, energy, loudness, and more. It can be used for various analyses and tasks such as music genre classification, predicting song popularity, building recommendation systems, or exploring the relationships between audio features and song attributes.

ML Algorithms:
1. KNN
2. Linear Regression
3. K-means clustering

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/spotify/songs_normalize.csv"
df = pd.read_csv(url)
```
