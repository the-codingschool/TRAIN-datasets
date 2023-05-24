Dataset description:

Cleaned dataset, easy difficulty

The car emissions dataset provides information on various attributes related to car emissions, including the car's make and model, engine volume, weight, and the amount of carbon dioxide (CO2) emissions.

This data set was pulled from Kaggle. It contains the following information for each instance:
1. Car
2. Model
3. Volume
4. Weight
5. CO2

ML Algorithms: 
1. Linear regression: There is not a lot of data so it can be difficult to use meaningfully, but this data can start to show students that ML can be very useful in real world issues. They can use the volume and weight to
predict CO2 emissions for a car (you can also have them try with their own cars).



You can use the following code to load the data into google colaboratory:

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/emissions/car_emissions.csv"
df = pd.read_csv(url)
```
