Dataset description:

Cleaned/messy datasets, moderate difficulty

The drinking water dataset contains various attributes related to water quality and potability. These attributes include hardness, solids content, chloramines concentration, conductivity, organic carbon levels, trihalomethanes, turbidity, and potability.

ML Algorithms:
1. Logistic regression
2. Decision trees

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/drinking_water/drinking_water_cleaned.csv"
df = pd.read_csv(url)
```
