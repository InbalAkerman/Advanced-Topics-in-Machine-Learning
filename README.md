
# Course Project: Advanced Topics in Machine Learning

## Dataset Description

This dataset focuses on assistance and expenses for families located within various local authorities across the country. It includes data on the number of families receiving assistance in different fields and the corresponding expenditures for each type of aid. Each entry in the dataset contains information about the types of assistance received, such as home aid, clothing, healthcare, financial debt, clubs, education, electronics, furniture, and more. Each type of assistance is represented by the number of aid baskets allocated and the total associated expense.

## Features of the Data

- *Year*: The year in which the data was recorded.
- *District*: The geographical district in which the locality is situated.
- *City*: The local authority name.
- *City Name*: The full name of the local authority.
- *Number of Families Receiving Assistance*: The number of families receiving assistance in each category.
- *Total Uses*: The total number of uses of the aid.
- *Number of Aid Baskets for Various Assistance Types*: The number of aid baskets allocated to the families for each assistance type.
- *Total Expenses for Each Assistance Type*: The total expenditure for each assistance category (e.g., clothing, healthcare, furniture, transportation, etc.).

## Analysis Potential

This dataset enables various analyses of assistance and expenses across different sectors. It allows for comparisons between local authorities, districts, and years, facilitating an in-depth understanding of trends and patterns in social aid distribution and its financial implications.

# Data

## 1. Data Cleaning and Organization
- Handling Missing Values
- Translation to English
- Organizing District Columns
- Value Transformation
- Handling Outliers

## 2. Feature Engineering
- 2.1 Cities: Hatzor and Ba'aneh

## 3. Analysis and Conclusions
- Comparison of "Total" Columns with Sum of Newly Created Columns
- Comparison of Basket Counts with Total per Basket
- Standard Deviation and Mean Comparison Between Basket Columns and Total Expenditures


## Methodology

### Supervised Machine Learning:
In this project, we applied five supervised classification models to predict outcomes based on the dataset. The models used were:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)

### Model Comparison 
- The models were compared using cross-validation to evaluate their performance. Additionally, a visual comparison was made through confusion matrices to assess how well the models classified the data.


### Unsupervised Machine Learning:
For unsupervised learning, we focused on clustering techniques to group data points based on similarity. The clustering methods used were:
- K-means Clustering
- Agglomerative Clustering
