Dataset description:

Cleaned dataset, easy difficulty

This data set was pulled from Kaggle. It also contains the following information for each sample:
1. mean
2. range
3. outliers
4. asymmetry
5. pulsar


ML Algorithms:
1. Classification

This dataset is good for classification. An example can be found [here](https://towardsdatascience.com/predicting-pulsar-stars-an-imbalanced-classification-task-comparing-bootstrap-resampling-to-smote-8cfbe037b807?gi=8ba89b2d8eae) and a background on the data can be found [here](http://ipta.phys.wvu.edu/files/student-week-2017/IPTA2017_KuoLiu_pulsartiming.pdf).
You can use the following code to load the data into google colaboratory:

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/pulsar/pulsar_stars.csv"
df = pd.read_csv(url)
```
