**Dataset description:**

This comprehensive dataset provides a wide-ranging overview of global education, offering deep insights into the evolving educational environments across various countries and regions. It includes essential data covering a broad spectrum of educational indicators, such as out-of-school rates, completion rates, proficiency levels, literacy rates, birth rates, and enrollment statistics for primary and tertiary education. This rich resource serves as a crucial tool for researchers, educators, and policymakers who are committed to analyzing, improving, and reforming educational systems around the world.

<br />

**Source:** [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/world-educational-data/data)

<br />

**Files:**

- `Global_Education.csv` - **Original, cleaned dataset**. Ideal for regression tasks, no classification.
- `global_education_class.csv` - Unlike the original, there are no separate columns for Male/Female distinction, instead the number of rows is doubled (one row with female stats, another with male stats) and there is an added column **"Gender"** where Female=1 and Male=0. Ideal use would be for ML classification by Gender and other regression tasks.

<br />

**Attribute Information:** For Global_Education.csv

|      |      |      |
| :--: | :--- | :--- |
| 1 | Country | Name of the countries and areas |
| 2 | Latitude  | Latitude coordinates of the geographical location |
| 3 | Longitude | Longitude coordinates of the geographical location |
| 4 | OOSR_Pre0Primary_Age_Male | Out-of-school rate for pre-primary age males |
| 5 | OOSR_Pre0Primary_Age_Female | Out-of-school rate for pre-primary age females |
| 6 | OOSR_Primary_Age_Male | Out-of-school rate for primary age males |
| 7 | OOSR_Primary_Age_Female | Out-of-school rate for primary age females |
| 8 | OOSR_Lower_Secondary_Age_Male | Out-of-school rate for lower secondary age males |
| 9 | OOSR_Lower_Secondary_Age_Female | Out-of-school rate for lower secondary age females |
| 10 | OOSR_Upper_Secondary_Age_Male | Out-of-school rate for upper secondary age males |
| 11 | OOSR_Upper_Secondary_Age_Female | Out-of-school rate for upper secondary age females |
| 12 | Completion_Rate_Primary_Male | Completion rate for primary education among males |
| 13 | Completion_Rate_Primary_Female | Completion rate for primary education among females |
| 14 | Completion_Rate_Lower_Secondary_Male | Completion rate for lower secondary education among males |
| 15 | Completion_Rate_Lower_Secondary_Female | Completion rate for lower secondary education among females |
| 16 | Completion_Rate_Upper_Secondary_Male | Completion rate for upper secondary education among males |
| 17 | Completion_Rate_Upper_Secondary_Female | Completion rate for upper secondary education among females |
| 18 | Grade_2_3_Proficiency_Reading | Proficiency in reading for grade 2-3 students |
| 19 | Grade_2_3_Proficiency_Math | Proficiency in math for grade 2-3 students |
| 20 | Primary_End_Proficiency_Reading | Proficiency in reading at the end of primary education |
| 21 | Primary_End_Proficiency_Math | Proficiency in math at the end of primary education |
| 22 | Lower_Secondary_End_Proficiency_Reading | Proficiency in reading at the end of lower secondary education |
| 23 | Lower_Secondary_End_Proficiency_Math | Proficiency in math at the end of lower secondary education |
| 24 | Youth_15_24_Literacy_Rate_Male | Literacy rate among male youths aged 15-24 |
| 25 | Youth_15_24_Literacy_Rate_Female | Literacy rate among female youths aged 15-24 |
| 26 | Birth_Rate | Birth rate in the respective countries/areas |
| 27 | Gross_Primary_Education_Enrollment | Gross enrollment in primary education |
| 28 | Gross_Tertiary_Education_Enrollment | Gross enrollment in tertiary education |
| 29 | Unemployment_Rate | Unemployment rate in the respective countries/areas |

<br />

**ML Applications:**
- Regression (Logistic?, DecisionTree, RandomForest)
- Classification

<br />

**Potential Use Cases** (from Kaggle)**:**
- **Global Education Analysis:** Evaluate the status of education in different countries and regions, identifying disparities and trends.
- **Gender Disparities:** Analyze gender-based differences in education, including out-of-school rates and literacy.
- **Education Policy Evaluation:** Use completion rates to assess the effectiveness of education policies.
- **Proficiency Analysis:** Investigate students' proficiency in reading and math at different education levels.
- **Socioeconomic Impact:** Study the relationship between education and unemployment rates.
- **Geospatial Analysis:** Explore geographical patterns of education indicators.

<br />

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/global_education/Global_Education.csv"
df = pd.read_csv(url)
```