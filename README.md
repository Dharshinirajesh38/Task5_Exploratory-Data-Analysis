# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The objective is to identify patterns, trends, relationships, and factors that influenced passenger survival during the Titanic disaster.

## Objective

To explore the Titanic dataset through statistical analysis and visualizations and extract meaningful insights using Python libraries such as Pandas, Matplotlib, and Seaborn.

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The dataset used is the Titanic dataset from Kaggle.

Dataset Features:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

## Analysis Performed

### Data Inspection

* Dataset information using df.info()
* Missing value analysis using df.isnull().sum()
* Statistical summary using df.describe()

### Visualizations

* Survival Distribution
* Gender vs Survival
* Age Distribution Histogram
* Fare Distribution Boxplot
* Correlation Matrix
* Correlation Heatmap
* Pair Plot Analysis
* Passenger Class vs Survival

## Key Findings

1. More passengers died than survived.
2. Female passengers had a significantly higher survival rate than male passengers.
3. First-class passengers were more likely to survive than second and third-class passengers.
4. Most passengers were between 20 and 40 years old.
5. Fare distribution contained several outliers, indicating some passengers paid exceptionally high ticket prices.
6. Age, Cabin, and Embarked columns contained missing values.
7. Passenger class and fare showed meaningful relationships with survival.

## Conclusion

Exploratory Data Analysis revealed that gender, passenger class, and fare were important factors affecting survival. The analysis also highlighted data quality issues such as missing values and outliers. Overall, EDA helped uncover valuable insights and patterns within the Titanic dataset.

## Author
Dharshini R
Data Analyst
