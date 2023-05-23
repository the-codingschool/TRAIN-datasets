Dataset description:

Cleaned dataset, easy difficulty

The breast cancer dataset contains information on various features of breast tumors, including mean radius, mean texture, mean perimeter, mean area, mean smoothness, and the diagnosis (malignant or benign) of each tumor. These features provide quantitative measurements related to the size, shape, and texture of the tumors. The dataset is commonly used for classification tasks to predict the diagnosis of breast tumors based on these features. Analyzing the dataset can involve exploring relationships between the mean measurements and the diagnosis to gain insights into potential patterns or factors that contribute to malignancy or benignity.
Use the following code to import data:

ML Algorithms:
1. Classification
2. Linear regression

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/breast_cancer/Breast_cancer_data.xlsx"
df = pd.read_excel(url)
```
