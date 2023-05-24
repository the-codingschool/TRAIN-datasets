Dataset description:

Cleaned dataset, easy difficulty

The Mall Customers dataset contains information about customers visiting a mall, including their CustomerID, Gender, Age, Annual Income, and Spending Score. The CustomerID serves as a unique identifier for each customer. Gender represents the customer's gender, while Age indicates their age group. Annual Income represents the customer's annual income in thousands of dollars, and Spending Score represents a score ranging from 1 to 100, indicating the customer's spending habits and preferences in the mall. This dataset can be used for various purposes, such as customer segmentation, understanding buying patterns, and targeted marketing strategies.

ML Algorithms:
1. K-Means Clustering
2. Linear Regression

Use the following to load the data:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/mall_customers/Mall_Customers.csv"
df = pd.read_csv(url)
```
