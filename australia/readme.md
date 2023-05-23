Dataset description:

Cleaned dataset, moderate difficulty

The dataset includes various weather-related information for each instance, such as location, wind speed, humidity, pressure, temperature, rain today, and rain tomorrow. The dataset can be used for predicting whether it will rain on a given day based on the temperature and pressure recorded at 9 am.

1. Location
2. WindSpeed
3. Humidity
4. Pressure
5. Temp
6. RainToday
7. RainTomorrow

ML Algorithms: 
1. Classification: KNN

You can use the following code to load the data into google colaboratory:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/australia/australia_weather.csv"
df = pd.read_csv(url)
```
