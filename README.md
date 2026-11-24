# Social Media Addiction and Student Well-Being

**MATH 189 | Statistical Analysis | Collaborative Course Project**

## Project Overview

This project investigates the relationship between social media addiction, mental health, and interpersonal conflict among students, with a particular focus on whether these associations vary across age groups.

Using a publicly available dataset and Python-based statistical methods, we conducted exploratory data analysis, regression modeling, interaction tests, and diagnostic analysis.

## Research Question

Does age moderate the relationship between social media addiction and student well-being, particularly mental health and relationship conflict?

## Dataset

The analysis uses the *Students' Social Media Addiction* dataset available on Kaggle.

- **Observations:** 705
- **Variables:** 13
- **Age range:** 18–24 years

Key variables include social media addiction score, daily usage hours, mental health score, relationship conflicts, age, and academic level.

The original survey provenance has not been independently verified.

## Methodology

### 1. Exploratory Data Analysis
- Examined student demographics and academic-level distributions.
- Visualized addiction scores across academic groups.
- Explored associations between addiction, mental health, and relationship conflict.

### 2. Regression Analysis
- Model 1: Simple Linear Regression
- Model 2: Multiple Linear Regression with demographic controls
- Model 3: Interaction Models incorporating Addiction Score × Age

### 3. Model Diagnostics
- Residuals vs. Fitted Values
- Q-Q Plot
- Assessment of regression assumptions

## Key Findings

- Higher addiction scores were associated with lower self-reported mental health scores.
- Higher addiction scores were associated with greater relationship conflict.
- The relationship between addiction scores and both outcomes varied with age.

In the fitted interaction models, increasing age strengthened the negative association with mental health scores and the positive association with relationship-conflict scores.

These findings describe statistical associations rather than causal effects.

## Technologies Used

Python · Pandas · NumPy · Matplotlib · Seaborn · Statsmodels · SciPy · Jupyter Notebook

## Project Files

- `Project.ipynb` — Python analysis, visualizations, and regression models
- `Students Social Media Addiction.csv` — Dataset
- `Project_Proposal.md` — Original research proposal
- `Final_Project_Report.pdf` — Original submitted report

## Team Members

- Amber Tang
- Emily Holguin
- Hikari Gregersen
- Yingchen Lin

## Project Attribution

This project was originally completed collaboratively for MATH 189.

Original team repository: `HGregersen/MATH189Project` (private).

This repository is a personal portfolio presentation of the collaborative project. The original computational methods are preserved, with corrections to the interpretation of the interaction models.

## Limitations

The analysis relies on observational data of uncertain provenance and cannot establish causality. The sample is also imbalanced across academic levels, with relatively few high school students. These limitations should be considered when interpreting the results.
