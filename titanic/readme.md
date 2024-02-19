Dataset description:

Raw dataset, moderate difficulty

This data set was pulled from [Kaggle](https://www.kaggle.com/datasets/pavlofesenko/titanic-extended/data). It is the classic dataset from the [Kaggle Competition](https://www.kaggle.com/competitions/titanic/overview) extended with some data from wikipedia. The variables are:
1. PassengerID
2. Survived
3. Pclass
4. Name
5. Sex
6. Age
7. Sibsp
8. Parch
9. Ticket
10. Fare
11. Cabin
12. Embarked
13. Hometown
14. Boarded
15. Destination

ML algorithms:
1. Classification of Survived variable

You can use the following code to load the data into google colaboratory:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/banknote/banknote.csv"
df = pd.read_csv(url)
```
