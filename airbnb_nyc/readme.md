Dataset Description:

Cleaned/messy datasets, moderate difficulty

The dataset provides a comprehensive overview of the listing activity and metrics for Airbnb in New York City (NYC) throughout the year 2019. It encompasses information about hosts, guests, and properties, including details such as neighborhood, room type, price, availability, and reviews. This dataset offers valuable insights into the dynamic and diverse Airbnb market in NYC, allowing for analysis of factors such as popular neighborhoods, pricing trends, host dynamics, and overall guest satisfaction. By exploring this dataset, researchers and analysts can gain a deeper understanding of the impact and behavior of Airbnb in one of the world's most vibrant cities, providing a foundation for informed decision-making and further exploration of the NYC hospitality landscape.

ML Algorithms:
1. Regression Algorithms: Regression models can be employed to predict the price of Airbnb listings based on various features such as neighborhood, room type, and availability.
2. Classification Algorithms: Classification algorithms can be used to categorize listings into different groups based on criteria such as neighborhood group, room type, or host characteristics.
3. Clustering Algorithms: Clustering algorithms can help identify patterns and group similar listings together based on various attributes like location, price range, or availability.

To import messy dataset:

import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN-datasets/main/airbnb_nyc/listings.csv"
df = pd.read_csv(url)

To import cleaned dataset:

import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN-datasets/main/airbnb_nyc/listings_cleaned.csv"
df = pd.read_csv(url)
