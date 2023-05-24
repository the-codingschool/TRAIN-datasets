Dataset description:

Cleaned dataset, moderate difficulty

The IMDb Reviews dataset consists of a collection of reviews from the IMDb website, along with their corresponding sentiment labels. Each review represents a piece of text, and the sentiment label indicates whether the review is positive or negative. This dataset is commonly used for sentiment analysis tasks, where the goal is to predict the sentiment of a given text.

ML Algorithms:
1. CNNs
2. Logistic regression

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/imdb_reviews/IMDB_Dataset.csv"
df = pd.read_csv(url)
```
