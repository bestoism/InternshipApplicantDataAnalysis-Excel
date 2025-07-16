# Exploratory Data Analysis: Internship Applicant Profile

![Project Cover Image](LINK_TO_YOUR_COVER_IMAGE.png)
*Note: You can upload your project cover image (the dashboard screenshot) to this repository and link it here to make your README more engaging.*

## Project Overview

This project is an end-to-end exploratory data analysis (EDA) case study performed on a fictional internship applicant dataset from Ousean Group. The primary objective was to clean and prepare raw data, identify the demographic profile of applicants, understand their departmental interests, and analyze the distribution of their self-reported skills. The entire process, from cleaning to visualization, was conducted exclusively using Microsoft Excel.

---

## 🔧 Tools Used

*   **Microsoft Excel:**
    *   Data Cleaning (Remove Duplicates, Filter, Find & Replace)
    *   Data Analysis (PivotTables, `COUNTIF` Function)
    *   Data Visualization (PivotCharts: Bar Chart, Pie Chart)
*   **Canva / PowerPoint:** (For final report design)

---

## 📂 Repository Contents

1.  **`Your_Report_Filename.pdf`**: The final report containing all data visualizations, in-depth analysis, key findings, and strategic recommendations.
2.  **`Your_Excel_Filename.xlsx`**: The complete Excel workbook, which includes:
    *   The raw, uncleaned data.
    *   The cleaned and prepared dataset.
    *   A sheet with all PivotTable analyses.
    *   A sheet with the skill frequency analysis.

---

## ⚙️ Project Workflow

1.  **Data Cleaning & Preparation:**
    *   Handled logical duplicates based on applicant names and timestamps.
    *   Corrected data inconsistencies in the "Gender" column (~10% of the data) to ensure a more accurate demographic analysis.
    *   Standardized unstructured text data in the "Skills" column by implementing a keyword search method (`COUNTIF` with wildcards) to enable frequency analysis.

2.  **Exploratory Data Analysis (EDA):**
    *   Utilized **PivotTables** to calculate descriptive statistics: total unique applicants (460), gender distribution, applicant count by province, and top universities.
    *   Analyzed departmental interests to identify the most sought-after departments.
    *   Created a gender-per-department matrix to uncover deeper demographic preferences.

3.  **Visualization & Reporting:**
    *   Developed relevant data visualizations (bar charts and pie charts) from each analysis table using **PivotCharts**.
    *   Compiled all findings and visuals into a comprehensive report that tells a clear, data-driven story.

---

## 📊 Key Findings

*   **Demographic Profile:** The applicant pool is nearly balanced, with a slight majority of Females (234) over Males (226). Most applicants originate from the West Java and East Java provinces.
*   **Departmental Interest:** The `Administration & Finance` and `Human Resources` departments are the two most popular choices, indicating a strong interest in core business functions.
*   **Skill Distribution:** Soft skills like **Leadership** (mentioned by 301 applicants) and **Public Speaking** (260 applicants) are the most frequently claimed skills. Among hard skills, **Editing** (78 applicants) and **Administration** (77 applicants) are the most common.

---

## 💡 Recommendations

Based on the findings, it is recommended that the recruitment team consider expanding promotional outreach to provinces outside the top 5 to enhance candidate diversity. Furthermore, for future application forms, it is highly advisable to convert free-text fields like "Skills" into a *dropdown* or *checklist* format to ensure data consistency and simplify future analysis processes.

---

**Developed by:** Ryan Besto Saragih 
**LinkedIn:** https://www.linkedin.com/in/ryan-besto-saragih/
