# Practical 6: Statistical Analysis with TeachingRatings.csv

## Overview

This project uses Python to perform statistical analysis on the TeachingRatings dataset. The aim is to understand how teacher attributes (like gender, age, and tenure) relate to teaching evaluation scores and perceived beauty.

## Dataset Features

- `age`: Teacher’s age
- `gender`: Teacher’s gender
- `tenure`: Whether the teacher has tenure
- `beauty`: Teacher’s perceived beauty score
- `eval`: Teaching evaluation score
- Other columns: `minority`, `division`, `native`, `credits`, etc.

## Analyses Performed

### 1. T-test: Gender and Teaching Ratings

- **Goal:** Test if male and female teachers have different teaching evaluation scores (`eval`)
- **Method:** Welch’s t-test for independent samples
- **Output:** T-statistic, p-value, decision on null hypothesis

### 2. One-way ANOVA: Age Groups and Beauty

- **Goal:** See if beauty scores (`beauty`) vary across different age groups
- **Method:** Age is binned (`<35`, `35-44`, `45-54`, `55+`), then ANOVA compares means
- **Output:** F-statistic, p-value, decision on null hypothesis

### 3. Chi-square Test: Gender and Tenure Association

- **Goal:** Check if gender and tenure status are associated
- **Method:** Contingency table and Chi-square test of independence
- **Output:** Chi-square statistic, degrees of freedom, p-value, decision on null hypothesis

## How to Use

1. Add `TeachingRatings.csv` to your project folder.
2. Run the provided Python scripts for each analysis.
3. Review the console output for results and interpretations.

## Requirements

- Python 3+
- pandas
- scipy

Install using:
pip install pandas scipy


## Output

The scripts print:
- Key statistics and p-values for each test
- Whether the null hypothesis is rejected

---
