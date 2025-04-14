
# 📊 Titanic Dataset - Exploratory Data Analysis (EDA)

## 🔍 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to discover hidden patterns and insights using Python libraries like **Pandas**, **Seaborn**, and **Matplotlib**.

---

## 📁 Dataset Used
- **Name:** Titanic - Machine Learning from Disaster  
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)  
- **File Used:** `train.csv`

This dataset contains information about passengers aboard the Titanic and whether they survived the disaster. The goal is to analyze key features that may have influenced survival.

---

## 🧹 Steps Performed
1. **Data Loading**  
   Used `pandas` to load the Titanic dataset.

2. **Data Cleaning**
   - Removed duplicates
   - Handled missing values (`Age`, `Embarked`, `Cabin`)
   - Converted data types
   - Created new features (like `FamilySize`)

3. **Exploratory Data Analysis**
   - Summary statistics using `.describe()`
   - Univariate and bivariate visualizations using Seaborn
   - Correlation heatmaps to understand relationships
   - Distribution analysis for age, fare, and class

4. **Insights & Observations**
   - Females had a higher survival rate than males.
   - Passengers in 1st class had better chances of survival.
   - Younger passengers were more likely to survive.
   - Fare also had some correlation with survival.

---

## 📈 Tools Used
- Python 🐍
- Jupyter Notebook 📓
- Pandas
- Matplotlib
- Seaborn

---

## 📄 Output Files
- `Titanic_EDA_Starter.ipynb` – Jupyter Notebook containing full analysis
- `train.csv` – Dataset file
- `EDA_Report.pdf` – PDF version of the notebook with visualizations and insights

---

## 🙋‍♀️ About the Task
This project was done as part of the **Elevate Lab Data Analyst Internship** - Task 5: Exploratory Data Analysis (EDA).
