Dataset description:

Cleaned dataset, easy difficulty

The college admissions dataset contains information on various factors that could influence admission decisions. The dataset includes attributes such as admission status (admit), Graduate Record Examination (GRE) score, Grade Point Average (GPA), socioeconomic status (SES), gender (Gender_Male), race, and undergraduate rank (rank). These features provide insights into the characteristics of applicants and their likelihood of being admitted to a college or university. The dataset can be used for classification tasks, aiming to predict admission status based on these factors. Analyzing the dataset can involve exploring the relationships between the attributes and admission outcomes to understand the impact of variables such as GRE score, GPA, SES, gender, race, and rank on college admissions.

ML Algorithms:
1. K-Nearest Neighbors (KNN): KNN is a non-parametric algorithm that assigns a class label based on the majority class of its neighboring data points. It can work well for datasets with discernible clusters.
2. Logistic Regression: Logistic regression is a widely used algorithm for binary classification problems, such as predicting admission status (admit) based on the given features.

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/college_admissions/Admission.xlsx"
df = pd.read_excel(url)
```
