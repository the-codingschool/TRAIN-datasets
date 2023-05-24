Dataset description:

Cleaned dataset, moderate difficulty

The weather history dataset provides information about various weather attributes recorded over time. The dataset includes the following features:

1. Formatted Date: The date and time of the weather recording.
2. Summary: A brief summary or description of the weather conditions.
3. Precip Type: The type of precipitation, such as rain or snow.
4. Temperature (C): The temperature in Celsius.
5. Apparent Temperature (C): The perceived temperature, which takes into account factors like wind chill.
6. Humidity: The relative humidity.
7. Wind Speed (km/h): The speed of the wind in kilometers per hour.
8. Wind Bearing (degrees): The direction of the wind in degrees.
9. Visibility (km): The visibility in kilometers.
10. Loud Cover: A measurement related to the presence of loud noises.
11. Pressure (millibars): The atmospheric pressure in millibars.
12. Daily Summary: A summary of the weather conditions for the day.


The dataset provides a comprehensive record of weather data over time, allowing for analysis and exploration of weather patterns and relationships between different variables

ML Algorithms:
1. Linear regression

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN-datasets/main/weather_history/weatherHistory.csv"
df = pd.read_csv(url)
```
