# Australia Weather

This data set was pulled from Kaggle. It contains the following information for each instance:
1. Location
2. WindSpeed
3. Humidity
4. Pressure
5. Temp
6. RainToday
7. RainTomorrow

This is a very large Australian weather dataset. It can be used to predict if it will rain today based
on temperature and pressure at 9 am. KNN can get roughly 70 - 85% accuracy. This version has
88,884 instances.

You can use the following code to load the data into google colaboratory:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/australia/australia_weather.csv"
df = pd.read_csv(url)
```
