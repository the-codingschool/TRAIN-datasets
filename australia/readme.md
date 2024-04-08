Dataset description:

Source: [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

Cleaned dataset, moderate difficulty

The dataset includes various weather-related information for each instance, such as location, wind speed, humidity, pressure, temperature, rain today, and rain tomorrow. The dataset can be used for predicting whether it will rain on a given day based on the wind speed, temperature, and pressure recorded at 9 am.


Files:
- `australia_weather.csv` - Cleaned, shortened, and simplified. Contains about 61% of the rows from the original dataset.
- `weatherAUS.csv` - Original dataset. Includes additional columns such as Date, WindDir, and conditions at 9am & 3pm. RainToday/RainTomorrow columns are strings rather than binary.


Features in `australia_weather.csv`:
1. Location
2. WindSpeed (km/hr)
3. Humidity (%)
4. Pressure (hPa or millibars)
5. Temp (&deg;C)
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
