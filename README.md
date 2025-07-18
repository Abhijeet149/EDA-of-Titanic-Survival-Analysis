# 🚢 EDA of Titanic Survival Analysis

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced the survival of passengers. Using Python libraries such as Pandas, Matplotlib, and Seaborn, we explore patterns and insights related to passenger demographics, ticket class, embarkation, and more.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Tools & Technologies](#tools--technologies)
- [Key Questions](#key-questions)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Insights & Observations](#insights--observations)
- [How to Run](#how-to-run)
- [Screenshots](#screenshots)
- [License](#license)
- [Author](#author)

---

## 📊 Project Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. This analysis aims to uncover the key features that impacted passenger survival. We analyze variables such as:

- Gender
- Age
- Passenger Class
- Embarkation Port
- Fare
- Family Aboard

---

## 📂 Dataset Description

- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- **Files:**
  - `train.csv`: Contains training data with survival status.
  - `test.csv`: For testing (optional for this EDA).
  
---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ❓ Key Questions

- What factors influenced passenger survival the most?
- Did women and children have a higher survival rate?
- How did class or fare price affect survival?
- Which embarkation port had the most survivors?

---

## 📈 Exploratory Data Analysis

The notebook includes:

- Data Cleaning & Missing Value Treatment
- Univariate & Bivariate Analysis
- Correlation Heatmaps
- Survival Rate Comparisons by:
  - Gender
  - Age Groups
  - Passenger Class
  - Embarked Port
  - Fare Range
  - SibSp (Siblings/Spouses Aboard)
  - Parch (Parents/Children Aboard)

---

## 💡 Insights & Observations

- Female passengers had a much higher survival rate.
- Passengers in 1st class had better survival odds.
- Children (age < 10) had higher chances of survival.
- People who paid higher fares tended to survive more.
- Port of embarkation showed slight differences in survival rate.

---

## ▶️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/EDA-of-Titanic-Survival-Analysis.git
   cd EDA-of-Titanic-Survival-Analysis
