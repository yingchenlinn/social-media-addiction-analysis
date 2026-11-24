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


## Installation & Usage

### Requirements

This project uses Python and Jupyter Notebook for statistical analysis and data visualization.

Required Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Statsmodels
- SciPy

### Installation

Clone the repository:

```bash
git clone https://github.com/yingchenlinn/social-media-addiction-analysis.git
cd social-media-addiction-analysis
```

Install the required Python packages:

```bash
python -m pip install -r requirements.txt
```

### Running the Analysis

1. Open `Project.ipynb` using Jupyter Notebook.
2. Ensure that `Students Social Media Addiction.csv` is in the same directory.
3. Select **Kernel → Restart & Run All**.
4. Review the exploratory analysis, regression models, interaction effects, and diagnostic plots.

### Reproducibility

The notebook contains the original statistical analysis from our collaborative MATH 189 course project.

The analysis includes data preprocessing, exploratory data analysis, six regression models, and regression diagnostics.




## Project Files

- [Python Analysis Notebook](Project.ipynb)
- [Dataset](Students%20Social%20Media%20Addiction.csv)
- [Final Project Report](Final%20Project%20Report.pdf)
- [Project Proposal](MATH_189_Project_Proposal.pdf)
- [Python Dependencies](requirements.txt)



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
