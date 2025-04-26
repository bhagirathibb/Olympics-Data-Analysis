#  Olympics Data Analysis Project

## Problem Statement

Analyze and visualize the Olympic Games dataset (1976 to 2008) to uncover insights into athlete performance, country dominance, gender distribution, and event trends. Extend the analysis with machine learning to predict the likelihood of medal wins.

---

## Dataset Description

This dataset contains detailed records of medal winners in the Summer Olympics between **1976 and 2008**, including:

-  City & Year
- Medal Type (Gold, Silver, Bronze)
- Athlete, Gender, Country
- Sport, Discipline, Event

It allows for both historical analysis and predictive modeling.

---

## 🛠Tools & Technologies

- **Python 3.x**
- **Pandas, NumPy** – Data cleaning & transformation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning (Logistic Regression)

---

##  Project Workflow

### 1. Data Preparation
- Imported and loaded CSV file using pandas.
- Dropped null values.
- Cleaned irrelevant columns like `Event_gender` and `Country_Code`.
- Converted `Year` column to integer.

### 2. Exploratory Data Analysis (EDA)
- Counted total medals by country.
-  Trend of medals over the years.
-  Gender distribution across Olympic events.
- Top athletes with the most medals.
- Identified cities that hosted most Olympics and events.
- Identified sports with the highest number of events.
-  Country performance breakdown by sport and year.
-  Detected athletes who switched sports or disciplines.

### 3. Visualizations
- Bar plots for top athletes, countries, and gender participation.
- Line plots for medal trends over time.
- Pie charts for gender distribution.
- Interactive breakdown of top 5 performing countries per year.
- Dominant countries per sport visualized using seaborn.

### 4. Machine Learning – Medal Prediction
- Cleaned and encoded categorical data.
- Created a binary target for medal prediction.
- Trained a **Logistic Regression** model to predict medal wins based on:
  - Country
  - Sport
  - Gender
  - Event gender
- Evaluated using accuracy score, confusion matrix, and classification report.

---

## Key Results & Insights

- 🇺🇸 **USA**, 🇷🇺 **Soviet Union/Russia**, and 🇩🇪 **Germany** dominated Olympic medals.
-  Male athletes significantly outnumbered females in medal counts.
- Top athlete: **Michael Phelps** with a staggering 16 medals.
- Wrestling, Judo, and Weightlifting had the most unique events.
-  Logistic regression model gave a baseline ability to predict medal wins based on country and sport features.

---


