Dataset description:

Cleaned dataset, moderate difficulty

The credit card fraud dataset contains various attributes related to credit card transactions. These attributes include distance from home, distance from the last transaction, ratio to median purchase price, repeat retailer indicator, chip usage indicator, PIN number usage indicator, online order indicator, and fraud label. These features provide insights into different aspects of credit card usage and transaction behavior. The dataset can be used for various tasks, such as fraud detection, analyzing customer purchasing patterns, or predicting transaction outcomes. Analyzing the dataset can help identify patterns or anomalies in credit card usage and provide valuable insights for improving security measures and detecting fraudulent activities.

ML Algorithms:
1. KNN
2. Logistic regression

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/credit_card_fraud/card_transdata.csv"
df = pd.read_csv(url)
```
