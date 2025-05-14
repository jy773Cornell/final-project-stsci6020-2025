# 📘 final-project-stsci6020-2025

This project investigates how various lifestyle and behavioral factors affect students' academic performance using a synthetic dataset. Linear regression and variable selection techniques are applied to quantify the influence of different predictors on final exam scores.

---

## 📌 Introduction

This project explores how habits such as study time, sleep, exercise, and screen time relate to academic outcomes. Using a simulated dataset of 1,000 students from Kaggle, the analysis includes:

- Fitting linear regression models to predict exam scores
- Checking and correcting regression assumptions
- Performing variable selection using:
  - **Branch and Bound (best subset selection)**
  - **LASSO regression (with cross-validation)**
- Interpreting the practical impact of each predictor

---

## ▶️ How to Run the Analysis

### Requirements
- **R version**: 4.4.1
- **Environment**: RStudio

### Instructions
1. Clone this repository or download the project files.
2. Open the `.Rmd` file in RStudio (located in the `scripts/` folder).
3. Run each code chunk interactively or knit the full report (HTML or PDF).
4. Make sure the required packages are installed:

```r
install.packages(c("tidyverse", "leaps", "glmnet", 
                   "caret", "boot", "sandwich", "lmtest"))
