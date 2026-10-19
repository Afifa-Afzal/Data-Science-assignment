# Exploratory Data Analysis (EDA) on Student Exam Performance

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a student exam performance dataset using Python. The purpose is to understand the dataset, identify patterns and relationships between variables, and explore factors associated with students' final exam scores.

## 🎯 Objectives

- Understand the structure and characteristics of the dataset.
- Inspect data types and check for missing values.
- Perform univariate analysis to understand individual variables.
- Perform bivariate and multivariate analysis to explore relationships.
- Visualize distributions, correlations, and potential outliers.
- Summarize key findings from the analysis.

## 📂 Dataset Information

The dataset used in this project is `student_exam_performance.csv`.

- **Number of records:** 10
- **Number of columns:** 12
- **Target variable:** `Final_Exam_Score`
- **Classification variable:** `Pass_Fail`

### Main Features

- `Student_ID`
- `Gender`
- `Age`
- `Study_Hours_Per_Week`
- `Attendance_Percentage`
- `Previous_Score`
- `Parental_Education_Level`
- `Internet_Access`
- `Extracurricular_Activities`
- `Sleep_Hours`
- `Final_Exam_Score`
- `Pass_Fail`

> **Dataset source:** Add the original dataset source URL here, if available.

## 🛠️ Tools and Libraries

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Analysis Performed

1. **Data Overview:** Inspected dataset dimensions, columns, data types, and summary statistics.
2. **Data Quality Check:** Checked missing values in all columns.
3. **Univariate Analysis:** Examined numerical distributions and the pass/fail class distribution.
4. **Bivariate Analysis:** Explored relationships between study hours, attendance, previous scores, and final exam scores.
5. **Correlation Analysis:** Used a correlation heatmap to examine relationships among numerical variables.
6. **Multivariate Analysis:** Visualized relationships among study hours, attendance, and final exam scores.
7. **Outlier Detection:** Used the Interquartile Range (IQR) method to check potential outliers in final exam scores.
8. **Key Findings:** Summarized the main patterns observed in the dataset.

## 📊 Key Findings

- The dataset contains 10 student records and 12 columns.
- No missing values were found in the dataset.
- The average final exam score is **71.8**.
- Seven students passed and three students failed.
- Study hours and final exam scores show a strong positive correlation in this dataset.
- Attendance and previous scores also show strong positive relationships with final exam scores.
- The IQR method identified no potential outliers in `Final_Exam_Score`.

## ⚠️ Limitations

- The dataset contains only 10 records, which is too small to draw reliable conclusions about a wider student population.
- Correlation does not imply causation.
- Findings may differ when analyzed using a larger and more representative dataset.

## 📁 Project Files

- `Data_science_assignment_.ipynb` — Jupyter/Google Colab notebook containing the EDA code, visualizations, and analysis.
- `Assignment_3_EDA_Report.docx` — Written report summarizing the analysis and findings.
- `student_exam_performance.csv` — Dataset file, if included in the repository.

## 🚀 How to Run

1. Download or clone this repository.
2. Open `Data_science_assignment_.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the dataset or update its file path if necessary.
4. Run the notebook cells in order to reproduce the analysis and visualizations.

## ✅ Conclusion

This project demonstrates the use of Python-based exploratory data analysis to understand student exam performance. The analysis identifies patterns and relationships among study hours, attendance, previous scores, sleep hours, and final exam results. Further analysis with a larger dataset would be needed to validate these observations.

---

**Assignment:** No. 3 — Exploratory Data Analysis (EDA)  
**Status:** Completed
