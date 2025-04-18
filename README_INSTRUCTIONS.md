# 📘 Assignment Instructions Summary – STAT448A2

This document complements the main `README.md` by summarising the official STAT448 Assignment 2 instructions and assessment expectations. It serves as a persistent reference for David Ewing (82171165) and Lillian Lee (32198314).

---

## ✅ Project Context

This assignment uses **R** to fit and compare predictive regression models across three datasets: residential buildings, Parkinson’s speech features, and weather station data. You are expected to:

- Analyse and interpret multiple regression models for each dataset.
- Use penalised regression (Ridge, LASSO, ElasticNet) where required.
- Present results in a concise A4 report using **British English** conventions.

---

## 🧪 Required Modelling Tasks

- Use a mix of:
  - Correlation and exploratory plots
  - Linear regression and diagnostic interpretation
  - Backward and stepwise selection (if used, explain)
  - Ridge and LASSO regression
  - ElasticNet regression with cross-validation

- Evaluate models using:
  - **Cross-validation**, **Holdout test error**, **MSE**, **RMSE**
  - **Computational efficiency**, **Predictor selection**, **Stability**

---

## 🛠 Tools and Conventions

- Use only permitted R packages: `glm`, `dplyr`, `ggplot2`
- Avoid `stepAIC()` and `regsubsets()` unless explicitly approved
- All code and figures must be:
  - Reproducible with **random seed `82171165`**
  - Commented using **British English**

---

## 📁 Directory Use

This project is organised into folders:

- `.vscode/`: Local editor config
- `code/`: R scripts for data modelling (if not integrated into `.Rmd`)
- `data/`: Raw data files (`.RData`, `.csv`)
- `doc/`: Assignment specification and draft work
- `images/`: Graphical outputs (EDA, diagnostics, model visuals)
- `Report/`: Final submission report (PDF or HTML)
- `scripts/`: Optional scripts for helpers/logging/output control

---

## 📄 Report Requirements

- **PDF or HTML** – max 4 A4 pages
- Font ≥ 11pt, margins ≥ 2.5cm
- Structure:
  1. Introduction
  2. Exploratory analysis
  3. Model development and comparison
  4. Final model justification (with **75-word explanation**)
  5. Conclusion

---

## 📅 Submission

- **Deadline**: Tuesday 29 April 2025, 9:00 AM NZT
- Submit via the LMS as an A4 PDF or HTML file
- Include inline R code and commentary where appropriate

---

This file is autogenerated for clarity. For details or debugging workflows, refer to the main `README.md` or ask David Ewing.
