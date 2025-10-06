# 🦠 COVID-19 Global Data Analysis (EDA Project)

### 📘 Overview
This project explores and visualizes global **COVID-19 data** using Python.  
The goal is to perform **Exploratory Data Analysis (EDA)** and uncover insights about pandemic trends, country-level cases, and mortality patterns.

---

### 🎯 Objectives
- Clean and preprocess the dataset for accurate analysis  
- Perform **EDA** using Pandas to summarize and explore data  
- Visualize **country-wise** and **time-based** trends  
- Derive new metrics such as **Case Fatality Rate (CFR)**  
- Present clear and meaningful insights through visual storytelling  

---

### 🧩 Dataset Information
**Dataset:** `worldometer_coronavirus_daily_data.csv`  
**Columns:**
| Column Name | Description |
|--------------|-------------|
| `date` | Date of record |
| `country` | Country name |
| `cumulative_total_cases` | Total reported COVID-19 cases up to that date |
| `daily_new_cases` | New daily reported cases |
| `active_cases` | Number of active cases on that date |
| `cumulative_total_deaths` | Total deaths reported up to that date |
| `daily_new_deaths` | New daily reported deaths |

---

### ⚙️ Technologies Used
- **Python** 🐍  
- **Pandas** – Data manipulation  
- **Matplotlib** – Data visualization  
- **NumPy** – Numerical operations  

---

### 🧼 Steps Performed

#### 1️⃣ Data Loading & Inspection
- Read CSV data using Pandas  
- Displayed initial records, dataset shape, and column info  

#### 2️⃣ Data Cleaning
- Checked for missing and duplicate values  
- Handled nulls and standardized data types  
- Converted date column to datetime format  

#### 3️⃣ Feature Engineering
- Created **Case Fatality Rate (CFR)** = (Total Deaths / Total Cases) × 100  

#### 4️⃣ Exploratory Data Analysis
- Aggregated cases and deaths by country  
- Analyzed global patterns and top-affected countries  

#### 5️⃣ Data Visualization
- Bar charts for **Top 10 countries by cases and deaths**  
- Line charts for **daily trends** of selected countries

  
#### 6️⃣ Insights
- Certain countries contributed disproportionately to global cases  
- Clear temporal peaks showing pandemic waves  
- Strong correlation between new cases and deaths  

---

### 🧠 Key Learnings
- Improved understanding of **EDA workflow**  
- Strengthened data visualization and storytelling skills  
- Hands-on experience in working with real-world pandemic data  

---

### 🧾 Conclusion
This project demonstrates end-to-end **Exploratory Data Analysis (EDA)** using Python — from raw data cleaning to insight generation.  
It effectively showcases skills in **data wrangling, visualization, and interpretation**, valuable for analytics and data science roles.


