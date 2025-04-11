# STAT448 Assignment 2 – Predictive Regression Modelling
# STAT448A2

## 📄 Overview

This project is the submission for **STAT448-25S1 Assignment 2**, focused on predictive modelling using **R**. The assignment requires the construction and comparison of linear and penalised regression models across three different real-world datasets: residential building metrics, Parkinson’s speech data, and weather station recordings.

The project outputs an R Markdown report summarising model development, results, and interpretations, formatted for submission as a PDF or HTML document.

## 👥 Authors

- David Ewing (82171165)  
- Lillian Lee (32198314)

## 🎯 Objectives

- Build regression models (including Ridge, LASSO, and ElasticNet) for three domains:
  - Housing efficiency prediction
  - Parkinson’s disease severity estimation
  - Weather-based outcome forecasting
- Apply and interpret:
  - Correlation structures
  - Linear and penalised regression models
  - Backward and stepwise selection
  - Cross-validation and generalisation metrics
- Interpret results and model comparisons using British English style and technical rigour.

## 📊 Datasets

- **`Residen.RData`** – Residential building dataset with energy and architectural attributes  
- **`parkinsons.csv`** – Parkinson’s speech recordings with UPDRS scores  
- **`Weather_Station_data_v1.csv`** – Weather records with meteorological predictors

All datasets are pre-loaded in the `data/` folder.

## 📁 Report Structure

The final report will include the following sections for each question:

1. **Exploratory Analysis** – Graphs, correlations, summaries  
2. **Model Development** – Regression and selection methods  
3. **Validation** – Cross-validation, MSE/RMSE, model comparison  
4. **Conclusion** – Summary of selected models and interpretation  

All code is kept in the `doc/` folder, using embedded chunk labels and British English comments.

## 🔁 Reproducibility

- A fixed **random seed** of `82171165` is used throughout
- All analysis is written in **R**, using only permitted packages (`glm`, `dplyr`, `ggplot2`)
- No `caret`, `stepAIC()`, or `regsubsets()` used unless explicitly permitted

## 📅 Submission Details

- **Due**: Tuesday 29 April 2025, 9:00am  
- **Format**: A4 PDF or HTML rendered from `.Rmd`  
- **Naming**: Final output must include names and IDs  
- **Environment**: VS Code on Windows with R Project file `STAT448A2.Rproj`

## 📂 Project Folder Structure

\`\`\`plaintext
STAT448A2/
│
├── STAT448A2.Rproj            ← ✅ Project file for RStudio/VS Code
├── .vscode/                   ← ✏️ VS Code settings (extensions, settings)
├── data/                      ← 📁 Source data files (.RData, .csv)
├── doc/                       ← 📁 All RMarkdown and R scripts for modelling
├── images/                    ← 📁 Plots and figures used in the report
├── original/                  ← 📁 Original files prior to manipulation
├── Report/                    ← 📁 Output reports (PDF or HTML)
├── scripts/                   ← 📁 Additional helper scripts or test code
├── .gitignore                 ← 🗂️ Git ignored files
├── .RData, .Rhistory          ← 📂 R session files (not manually edited)
└── README.md                  ← 📘 This file
\`\`\`

---
