# baton-rouge-crime-analysis
Exploratory data analysis project examining violent crime trends and neighborhood-level crime patterns in Baton Rouge using Python, pandas, and matplotlib.
# Baton Rouge Crime Analysis

## Project Overview
This project explores crime trends within Baton Rouge using publicly available crime data. The analysis focuses on neighborhood-level crime composition, violent crime trends over time, and differences in crime patterns across selected neighborhoods.

The goal of this project was to practice real-world data cleaning, exploratory data analysis (EDA), and visualization techniques while exploring meaningful public safety questions.

---

## Questions Explored
- Which Baton Rouge neighborhoods showed the highest violent crime burden?
- How did violent crime proportions change over time?
- Did neighborhoods follow similar or different crime trends?
- What proportion of reported crimes were property, society, or violent crimes?

---

## Tools Used
- Python
- pandas
- NumPy
- matplotlib
- Jupyter Notebook

---

## Data Cleaning
Key cleaning steps included:
- Standardizing inconsistent city labels
- Filtering records to Baton Rouge, Louisiana only
- Removing redundant columns
- Converting date columns to datetime format
- Extracting year and month features
- Creating a custom violent crime classification

---

## Key Findings
- Property crime represented the majority of reported incidents across neighborhoods.
- North Baton Rouge showed the highest overall crime burden.
- Violent crime proportions varied by neighborhood but generally remained within a similar range.
- North Baton Rouge and Brookstown demonstrated similar violent crime trends over time, suggesting broader city-wide influences on crime patterns.

---

## Limitations
- Publicly available crime data may contain inconsistencies or incomplete records.
- Reported crimes do not represent all crimes committed.
- Violent crime classifications required interpretation during data cleaning.

---

## Files Included
- `baton_rouge_crime_analysis.ipynb` — Full analysis notebook
- HTML export of completed notebook
