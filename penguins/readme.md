Dataset description

Clean/messy datasets, moderate difficulty

The Penguin dataset provides information about penguins and includes the following features for each instance:

Sample Number: Unique identifier for each penguin sample.
Species: The species of the penguin, which can be Adelie, Chinstrap, or Gentoo.
Region: The region where the penguins were observed.
Island: The specific island where the penguins were observed.
Stage: The stage of life of the penguins, such as adult or chick.
Individual ID: The unique identifier for each individual penguin.
Clutch Completion: Indicates whether the clutch of eggs was completed.
Date Egg: The date when the egg was observed.
Culmen Length (mm): The length of the culmen (bill) of the penguin in millimeters.
Culmen Depth (mm): The depth of the culmen (bill) of the penguin in millimeters.
Flipper Length (mm): The length of the flipper of the penguin in millimeters.
Body Mass (g): The body mass of the penguin in grams.
Sex: The gender of the penguin, which can be male or female.
Delta 15 N (o/oo): The nitrogen isotope ratio for the penguin.
Delta 13 C (o/oo): The carbon isotope ratio for the penguin.
Comments: Additional comments or notes about the penguin observations.
This dataset provides valuable information about penguins, including their species, physical characteristics, location, and other relevant details. 

ML Algorithms:
1. Classification
2. Clustering
3. Regression


Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/penguins/penguins_lter.csv"
df = pd.read_csv(url)
```
