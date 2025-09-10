# Data-Storytelling-Analysing-Survival-on-the-Titanic

## 1. 📌 Project Overview

This project is an end-to-end Exploratory Data Analysis (EDA) on the famous Titanic dataset. The goal is to uncover insights about passenger survival during the disaster by cleaning the data, exploring patterns, and visualizing relationships.

Through data storytelling, the project highlights how factors such as gender, age, passenger class, and fare influenced survival chances.

---

## 2. ✨ Features

## 🔍 Data Cleaning & Preprocessing:

Handling missing values (Age, Cabin, Embarked).

Separating numerical, categorical, and high-cardinality data.

## 📊 Exploratory Data Analysis (EDA):

Univariate Analysis: Histograms, frequency tables, and box plots.

Bivariate Analysis: Survival by sex, passenger class, and age groups.

Multivariate Analysis: Combined effects of gender, class, and age.

## 📈 Key Insights:

## Overall Survival: About 38.4% of passengers survived the disaster.

## Gender:
Females had a much higher survival rate than males.
Adult men (Mr) had the lowest survival rate (~15%).

## Class (Pclass):
1st class passengers had the highest survival probability.
3rd class had the worst outcomes, especially for men.

## Age:
Children had better survival chances than adults.
The youngest passengers (infants/children under 10) had a noticeable survival advantage.

## Fare:
Higher fares correlated with higher survival (linked to class).
Distribution showed strong skewness with some very expensive tickets.

## Family Size & Companionship:
Passengers traveling with small families (2–4 members) had the best survival chances (up to ~70%).

Solo travelers had a much lower rate (~30%).
Very large families (5+) struggled with survival.

## IsAlone:
Being alone decreased survival chances significantly.
Being with at least one companion improved odds.

## Titles (from names):
Mrs (married women): ~80% survival.
Miss (unmarried women): ~70%.
Master (young boys): ~55–60%.
Mr (adult men): ~15%.
Rare titles (nobility, clergy, etc.): ~35–40%.

## Correlation Analysis:
Survival strongly correlated with sex, class, and fare.
Family features showed non-linear effects — moderate family sizes were beneficial, large sizes were harmful.
Pclass and fare were strongly negatively correlated.

---

## 3. 🛠️ Technologies Used

Language: Python

Libraries: Pandas, NumPy, Seaborn, Matplotlib

Platform: Google Colaboratory

---

## 4. 🏁 Conclusion

The Titanic dataset reveals that survival was not random — it was influenced by a combination of gender, class, age, fare, and family composition.This project demonstrates how structured storytelling combined with EDA can transform raw data into powerful insights.

-- Women and children were prioritized.

-- Wealthier passengers in 1st class had better chances.

-- Traveling with a small family group improved odds, while traveling alone or in very large families reduced them.

-- Titles extracted from names acted as a strong predictor of survival.

This analysis provides a clear storytelling perspective: the disaster’s outcomes reflected social hierarchies and evacuation priorities of the early 20th century.

---
