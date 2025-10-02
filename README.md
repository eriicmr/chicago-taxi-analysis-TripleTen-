# 🚖 Chicago Taxi Data Analysis – Sprint 7 Project  

This project analyzes **Chicago taxi rides** using datasets extracted from SQL queries.  
The goal is to explore ride distributions across taxi companies and neighborhoods, and to test whether **rainy weather affects ride duration from the Loop to O'Hare International Airport**.  

---

## 📌 Project Overview  

The analysis is divided into two main parts:  

1. **Exploratory Data Analysis (EDA)**  
   - Imported and inspected two CSV files:  
     - `project_sql_result_01.csv`: number of rides per taxi company (Nov 15–16, 2017)  
     - `project_sql_result_04.csv`: average rides per neighborhood (Nov 2017)  
   - Verified datatypes and performed cleaning where necessary  
   - Identified the **top 10 neighborhoods** by ride volume  
   - Visualized:  
     - Taxi companies vs. number of rides  
     - Top 10 neighborhoods as destinations  
   - Wrote insights and conclusions for each visualization  

2. **Hypothesis Testing**  
   - Used `project_sql_result_07.csv` (rides from Loop → O’Hare)  
   - Tested the hypothesis:  
     - **H0 (Null):** Average ride duration on rainy Saturdays = average ride duration on other days  
     - **H1 (Alt):** Average ride duration on rainy Saturdays differs from other days  
   - Defined significance level (α) and applied a **two-sample t-test**  
   - Interpreted results in plain language (business decision focus)  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas` (data manipulation)  
  - `numpy` (numerical operations)  
  - `matplotlib`, `seaborn` (visualizations)  
  - `scipy.stats` (hypothesis testing)  

---

## 📂 Dataset  

Files provided:  
- `project_sql_result_01.csv` — number of rides by company  
- `project_sql_result_04.csv` — average rides per neighborhood  
- `project_sql_result_07.csv` — rides from Loop → O’Hare, with timestamps, weather, and duration  

---

## 🎯 Key Learning Outcomes  
- Practiced combining **SQL outputs with Python analysis**  
- Strengthened ability to **visualize distributions** and interpret insights  
- Applied **statistical hypothesis testing** in a real business context  
- Improved skills in explaining results for **both technical and non-technical audiences**  

---

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/eriicmr/chicago-taxi-analysis.git
