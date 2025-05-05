# Lung Cancer Risk Analysis

## 📊 Project Overview
This project explores the relationship between lifestyle, environmental, and healthcare-related factors and lung cancer diagnosis across countries. The analysis uses the "Lung Cancer Prediction Dataset" and follows the six-step data analysis process from the Google Data Analytics Certificate.

---

## 🔍 Business Task
Identify key risk factors associated with lung cancer diagnoses globally to inform prevention strategies and improve public health outcomes, especially in developing countries.

---

## 👥 Stakeholders
- NGOs focused on public health
- Ministries of Health and policy makers
- Health insurance analysts
- Global health researchers

---

## 🧰 Tools Used
- **Google Sheets** – Initial exploration and data dictionary
- **SQL (Beekeeper Studio)** – Data cleaning and transformation
- **R (dplyr, ggplot2)** – Analysis and visualization
- **Tableau Public** – Interactive dashboards
- **GitHub** – Project hosting and documentation

---

## 🔄 Google Data Analytics Process

### 1. Ask
- What factors are most associated with lung cancer diagnosis?
- How do rates differ between developed and developing countries?
- What role do air pollution and healthcare access play?

### 2. Prepare
- Dataset uploaded to Google Sheets for initial review
- Created a data dictionary to define columns

### 3. Process
- Cleaned and standardized data using SQL queries (see `sql/cleaning_queries.sql`)
- Removed inconsistent entries (e.g. 'None')
- Encoded categorical variables (e.g. Yes/No → 1/0)

### 4. Analyze
- Used R and ggplot2 to find correlations and patterns
- Created visualizations (barplots, histograms, heatmaps)
- Compared key variables across groups (smokers vs non-smokers, country types, etc.)

### 5. Share
- Report created in R Markdown (`r/analysis.Rmd`)
- Tableau dashboard published [here](https://public.tableau.com/)

### 6. Act
- Recommend early screening initiatives in high-risk groups
- Suggest awareness campaigns in countries with poor healthcare access

---

## 📂 Repository Structure
```
lung-cancer-risk-analysis/
├── data/
│   └── lung_cancer_dataset_clean.csv
├── sql/
│   └── cleaning_queries.sql
├── r/
│   └── analysis.Rmd
├── tableau/
│   └── dashboard_link.txt
├── README.md
└── LICENSE
```

---

## 📫 Contact
Feel free to reach out via LinkedIn to collaborate or discuss this project!
