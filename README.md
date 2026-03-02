INTRODUCTION

The Titanic dataset is one of the most commonly used datasets in data science and machine learning. It is based on the real-life disaster of the RMS Titanic, which sank on April 15, 1912.
The dataset includes passenger details such as age, gender, ticket class, fare, and survival status.
The main goal of this project is to analyze the dataset and understand which factors affected passenger survival.

DATASET OVERVIEW

The Titanic dataset contains information about passengers who were on the ship.
Important Columns:
PassengerId – Unique ID of each passenger
Survived – Survival status (0 = No, 1 = Yes)
Pclass – Ticket class (1 = First, 2 = Second, 3 = Third)
Name – Passenger name
Sex – Gender
Age – Age of passenger
SibSp – Number of siblings/spouses onboard
Parch – Number of parents/children onboard
Ticket – Ticket number
Fare – Ticket price
Cabin – Cabin number
Embarked – Port of boarding (C, Q, S)

Dataset Features:
Around 891 passenger records
Contains both numbers and text data
Some missing values in Age, Cabin, and Embarked columns
The dataset is useful for learning data analysis and classification problems.

METHODOLOGY

The dataset was imported using Pandas.
Missing values were handled by filling or removing them.
Different data analysis techniques such as filtering, sorting, grouping, and calculations were used to study survival patterns.

STATISTICAL ANALYSIS

Statistical methods like mean, sum, and groupby() were used.
The survival rate was analyzed based on gender, passenger class, age, and fare.
The results helped identify which factors had the biggest impact on survival.

CONCLUSION

The analysis shows that survival depended mainly on gender, passenger class, and age.
Key Findings:

Women and children had higher survival rates.
First-class passengers survived more than other classes.
Passengers who paid higher fares had better survival chances.
Third-class male passengers had the lowest survival rate.
