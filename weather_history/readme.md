Dataset description:

Cleaned dataset, moderate difficulty

The weather history dataset provides information about various weather attributes recorded over time. The dataset includes the following features:

Formatted Date: The date and time of the weather recording.
Summary: A brief summary or description of the weather conditions.
Precip Type: The type of precipitation, such as rain or snow.
Temperature (C): The temperature in Celsius.
Apparent Temperature (C): The perceived temperature, which takes into account factors like wind chill.
Humidity: The relative humidity.
Wind Speed (km/h): The speed of the wind in kilometers per hour.
Wind Bearing (degrees): The direction of the wind in degrees.
Visibility (km): The visibility in kilometers.
Loud Cover: A measurement related to the presence of loud noises.
Pressure (millibars): The atmospheric pressure in millibars.
Daily Summary: A summary of the weather conditions for the day.
The dataset provides a comprehensive record of weather data over time, allowing for analysis and exploration of weather patterns and relationships between different variables

ML Algorithms:
1. Linear regression

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/credit_card_fraud/card_transdata.csv"
df = pd.read_csv(url)
```
