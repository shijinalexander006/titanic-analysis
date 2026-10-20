# titanic-analysis
Exploratory data analysis of the Titanic dataset using Pandas and Matplotlib


# Titanic Survival Analysis

Exploratory data analysis of the Titanic passenger dataset to find which factors were linked to survival.

## Dataset
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) (Kaggle), 891 passengers, 12 columns.

## Tools
Python, Pandas, Matplotlib, Google Colab

## Key findings
- **Overall survival:** 342 of 891 passengers (38.4%) survived.
- **Gender:** Women survived at about 74% compared with about 19% for men.
- **Class:** Survival fell with ticket class: 63% (1st), 47% (2nd), 24% (3rd).
- **Missing data:** `Age` had 177 missing values (filled with the median), `Cabin` had 687, and `Embarked` had 2.
- **Age:** Children had the highest survival rate and seniors the lowest.

## What I did
- Loaded and inspected the data
- Handled missing values
- Created an age-group feature with `pd.cut`
- Used `groupby` and bar charts to compare survival across groups

## Files
- `titanic_analysis.ipynb`: full analysis with code and charts

## Next steps
Build a machine learning model to predict survival.
