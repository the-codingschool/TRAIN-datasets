To import the data, you must first get the .zip file (since the unzipped file is too large), unzip it, and then load it into a dataframe. The code below shows how to do this.


```python
!wget https://github.com/the-codingschool/TRAIN-datasets/raw/main/world_values_survey/wave7.csv.zip -O data.csv.zip
!unzip data.csv.zip

import pandas as pd
df = pd.read_csv('/content/wave7.csv')
```
