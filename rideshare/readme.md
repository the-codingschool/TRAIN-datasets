Dataset description:

Cleaned dataset, moderate difficulty

This dataset contains a variety of information related to rideshare trips, including temporal data, geographical data, weather conditions, and ride details. Based on your specific task or goal, various machine learning algorithms can be applied to this dataset, such as regression for predicting prices, classification for predicting cab types, or clustering for analyzing patterns in ride data.

ML Algorithms:
1. Linear Regression
2. KNN
3. K-Means Clustering

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/rideshare/rideshare_cleaned.csv"
df = pd.read_csv(url)
```
