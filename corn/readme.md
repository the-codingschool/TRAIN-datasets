Dataset description:

Cleaned dataset, moderate difficulty

The corn dataset provides information on corn production across different states and years. It includes attributes such as the state name (state_name), year, time of harvest (load_time), area in acres (area_acre), mass in bushels (mass_bushel), and yield in bushels per acre (yield_bu_per_ac). The dataset allows for analyzing corn production trends and comparing yields across states and years. It can be used for various tasks such as forecasting yields, identifying factors influencing corn production, and assessing the impact of different variables on crop productivity. Exploring the dataset can provide insights into the dynamics of corn production and help inform decision-making in the agricultural industry.

ML Algorithms:
1. Linear Regression: Linear regression can be used to predict the yield of corn based on the given features such as area and mass. It establishes a linear relationship between the input variables and the target variable.
2. Decision Trees: Decision trees can capture non-linear relationships between the features and the yield of corn. They can provide insights into important features and help understand the decision-making process.

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/corn/corn_data_cleaned.csv"
df = pd.read_csv(url)
```
