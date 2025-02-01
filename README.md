# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to parse and analyze data retrieved from APIs to perform stastical analysis with Python. Specifically, I compared the number of bikes available in rental stations to various characteristics of places of interest in the city of Toronto

## Process
+ called the citybik.es API to retrieve bike station info in the city
+ called the Yelp Fusion and FourSquare Places API for information on places of interest within 1km of each station
+ parsed and cleaned the data from each API using Pandas
+ performed exploratory data analysis (EDA) using Pandas, Scikit, Matplotlib and Seaborn
+ built a linear regression model 

## Results
The model showed that there was a correlation between certain attributes of the places of interest and the number of bikes at nearby rental stations, albeit a weak one. I was also able to confirm that there was a statistically significant difference between the different categories of places with a Kruskal-Wallis test.

Regression Results:

![image 1](https://github.com/user-attachments/assets/c6c1d767-6f85-41dd-b002-91e4f3d1a460)

Variance Between Categories:

![image 2](https://github.com/user-attachments/assets/898c575a-17f1-4c87-9174-d6b3c20075c8)

## Challenges 
Since we were limited to using generalised linear models, there wasn't much information to use for the analysis.

## Future Goals
I would like to explore other models and analysis methods that were outside the purview of this project, but would provide deeper insights.

