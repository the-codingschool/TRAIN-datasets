Dataset description:

Cleaned/messy datasets, moderate difficulty

The Tokyo Olympics dataset provides information on the performance of different countries or National Olympic Committees (NOCs) in terms of gold, silver, and bronze medals won. Here's a summary of the dataset columns:

Rank: The overall rank of the NOC based on the total number of medals won.
Team/NOC: The name of the country or National Olympic Committee.
Gold Medal: The number of gold medals won by the NOC.
Silver Medal: The number of silver medals won by the NOC.
Bronze Medal: The number of bronze medals won by the NOC.
Total: The total number of medals (gold, silver, and bronze) won by the NOC.
Rank by Total: The rank of the NOC based on the total number of medals won.
NOCCode: The three-letter code assigned to each NOC.
Continent: The continent to which the NOC belongs.
The dataset provides a snapshot of the medal standings and rankings of countries during the Tokyo Olympics. It allows for analysis and comparison of countries' performances based on the number of medals won.

ML Algorithms:
1. Classification
2. Regression 
3. Clustering

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/tokyo_olympics/tokyo_2021_cleaned.xlsx"
df = pd.read_excel(url)
```
