# 📊 Stack Overflow Developer Survey 2020 – Exploratory Data Analysis (EDA)

This project provides an exploratory data analysis of the 2020 Stack Overflow Developer Survey, which includes nearly 65,000 responses from developers across more than 180 countries. The goal is to uncover patterns in developer demographics, experience, education levels, job satisfaction, and work habits using Python-based data analysis.

This repository includes:

- Stackoverflow_2020_Analysis.ipynb — Full EDA notebook  
- countries-languages.csv — Supplemental dataset  
- survey_results_schema.csv — Column descriptions  
- survey_results_public.csv — Main survey dataset  
- so_survey_2020.pdf — Official survey documentation
- Stackoverflow_2020_Analysis.pdf — Exported report version

---

## 🧠 Project Goals

- Clean and prepare the original survey dataset  
- Explore demographic and professional characteristics of developers  
- Analyze trends in learning styles, experience, and work conditions  
- Summarize insights from the data through visualization and commentary  

---

## 📁 Dataset Overview

The dataset contains 61 columns and roughly 64k responses from developers, hobbyists, students, and technology professionals worldwide.  
A subset of 20 fields was selected in the notebook to focus the analysis on demographics, experience, and employment characteristics.

---

## 🧼 Data Cleaning Highlights

The notebook performs extensive preprocessing, including:

- Dropping unrealistic age values (below 10 or above 100)  
- Removing extreme working-hour values (greater than 140 per week)  
- Converting multi-selected gender entries into single values or marking them as missing  
- Converting numerical text fields (YearsCode, YearsCodePro, Age1stCode) into numeric types  
- Handling missing values appropriately for further analysis  

These steps prepare the dataset for accurate statistical and visual insights.

---

## 📊 Key Insights (Summary)

From the final summary of the notebook:

- Developers often begin coding early, commonly between ages 12 and 18.  
- Those who code as a hobby tend to start earlier and stay more engaged with continuous learning.  
- Job satisfaction is strongly influenced by work-life balance factors, such as flexible schedules, remote work opportunities, and healthy work environments.  
- Formal education levels vary widely, and practical coding experience often begins before or alongside higher education.  
- A significant percentage of respondents work around 40 hours per week, though overtime is common depending on job type and region.  

These insights provide a concise but meaningful understanding of developer trends in 2020.

---

## 🛠️ Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Jupyter Notebook  

---

## ▶️ How to Run the Notebook

1. Clone the repository.  
2. Install required Python libraries.  
3. Place all CSV files (survey_results_public.csv, survey_results_schema.csv, countries-languages.csv) in the same directory as the notebook.  
4. Open the notebook in Jupyter and run all cells to reproduce the analysis.

---

## 📜 License

This project is released under the MIT License.
