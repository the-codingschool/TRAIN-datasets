Dataset description:

Cleaned dataset, easy difficulty

This data set was pulled from Kaggle. It also contains the following information for each sample:
1. datetime
2. count
3. holiday
4. workday
5. temp
6. feels_like
7. temp_min
8. temp_max
9. humidity
10. wind_speed
11. weather_main

ML Algorithms:
1. Linear regression: This dataset is good for linear regression to predict “count".

You can use the following code to load the data into google colaboratory:

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/bikes/bike_share.csv"
df = pd.read_csv(url)
```
