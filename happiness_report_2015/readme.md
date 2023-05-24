Dataset description:

Cleaned/messy datasets, moderate difficulty

The 2015 Happiness Report dataset provides information on various factors contributing to the happiness scores of different countries. The dataset includes the following variables:

1. Country: The name of the country.
2. Region: The region to which the country belongs.
3. Happiness Score: A measure of overall happiness or life satisfaction for each country.
4. GDP: The Gross Domestic Product per capita, indicating the economic well-being of a country.
5. Social Support: The level of social support and social networks available to individuals within a country.
6. Healthy Life Expectancy: The average life expectancy of individuals in terms of their overall health and well-being.
7. Freedom: The extent to which individuals have freedom of choice and can make life decisions.
8. Corruption Perception: The perception of corruption levels within a country.
9. Generosity: The extent to which individuals are inclined to help others and exhibit acts of generosity.
This dataset allows for the exploration and analysis of factors that contribute to happiness across different countries. It provides insights into the relationship between economic factors, social support, health, freedom, corruption perception, and generosity, and their influence on overall happiness scores.

1. Linear regression

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/happiness_report_2015/happiness_report_cleaned.xlsx"
df = pd.read_excel(url)
```
