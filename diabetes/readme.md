Dataset description:

Cleaned dataset, moderate difficulty

The diabetes dataset contains various attributes related to diabetes diagnosis and patient characteristics. These attributes include the number of pregnancies (Pregnancies), glucose level (Glucose), blood pressure (BloodPressure), skin thickness (SkinThickness), insulin level (Insulin), body mass index (BMI), diabetes pedigree function (DiabetesPedigreeFunction), age (Age), and the diabetes outcome (Outcome).

This dataset is commonly used for predicting the presence or absence of diabetes in patients based on the given features. The attributes provide valuable information for assessing the risk factors associated with diabetes and understanding the relationship between these factors and the likelihood of developing the condition.

ML Algorithms:
1. Logistic regression
2. Decision trees


Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/diabetes/diabetes_prediction.xlsx"
df = pd.read_excel(url)
```
