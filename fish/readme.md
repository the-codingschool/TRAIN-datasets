Dataset description:

Source: [Kaggle](https://www.kaggle.com/datasets/vipullrathod/fish-market)

Cleaned dataset, moderate difficulty

This data set was pulled from Kaggle. It also contains the following information for each sample:
1. Species
2. Weight
3. Length1
4. Length2
5. Length3
6. Height
7. Width
8. Price

ML Algorithms:
1. Classification
2. Linear regression 


Note that the price column is artificial so this should just be used for practice, not drawing conclusions. 

You can use the following code to load the data into google colaboratory:

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/fish/fish_market.csv"
df = pd.read_csv(url)
```
