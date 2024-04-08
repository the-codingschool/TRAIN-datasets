Dataset description:

Source: [Kaggle](https://www.kaggle.com/code/tunyaretsaengsrichan/zoo-classification/input?select=zoo.csv)

Cleaned dataset (to remove samples like 'girl' and 'vampire'), easy difficulty

Files:
- `animals.csv` 
- `animals_wo_names.csv` - Same as `animals.csv` but without **animal_name** column since it is the only non-integer column.
- `class.csv` - Groups the animal names by class type *(Mammal, Bird, Reptile, etc)* and assigns a number to each group.

This data set contains the following information for each sample (most are binary unless otherwise stated):

1. animal_name (string, probably should drop before training model)
1. hair
2. feathers
3. eggs
4. milk
5. airborne
6. aquatic
7. predator
8. toothed
9. backbone
10. breathes
11. venomous
12. fins
13. legs (number of legs)
14. tail
15. domestic
16. catsize (category size?)
17. class_type (1-7 found in class.csv)

ML Algorithms:
1. Classification

To import the dataset:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/animals/animals.csv"
df = pd.read_csv(url)
```
