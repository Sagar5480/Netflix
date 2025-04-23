# 📊 Netflix EDA (Exploratory Data Analysis)

## 🚀 Project Overview

This project explores and analyzes the Netflix dataset to uncover patterns in content types, release years, ratings, and regional distribution. It involves cleaning, transformation, and visualization to generate meaningful insights that can guide content strategy and platform decisions.

---

## 🧰 Tools & Libraries Used

- **Python** (pandas, numpy, seaborn, matplotlib)
- **Jupyter Notebook**
- **scikit-learn** for Label Encoding

---

## 📂 Dataset Details

- **Rows**: 8807
- **Columns**: 12
- Contains information like show ID, title, director, cast, country, rating, release year, duration, and category (TV Show or Movie)

---

## 🔧 Key Steps

### 1. **Data Cleaning**

- Removed null values
- Label encoding applied to categorical columns
- Corrected data types for efficient processing

### 2. **Exploratory Data Analysis**

- Visualized distributions for:
  - Type (TV Show vs Movie)
  - Release Year
  - Country
  - Rating
- Plotted relationships:
  - Duration vs Rating
  - Type vs Rating
  - Type vs Cast
  - Rating vs Cast
  - Rating vs Release Year

---

## 📈 Insights

1. **Movies dominate Netflix** but TV Show additions are rising steadily.
2. **Country** and **Rating** are negatively correlated, suggesting regional preferences.
3. Viewers tend to watch shows **based on directors** they recognize.
4. **Content peaked in 2019**, followed by a dip likely due to the COVID-19 pandemic.
5. **United States** leads in content production on Netflix.

---

## 🧠 Conclusion

This EDA reveals the evolution of Netflix's content library and user preferences. It supports decisions in regional expansion, content acquisition, and user personalization.

---

