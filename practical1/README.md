# Practical 1: Statistical Foundation of Data Sciences

**Subject Name:** Statistical Foundation of Data Sciences  
**Subject Code:** CSU1658 Practical  

## Description
This folder contains the Jupyter notebook `practical1.ipynb` for Practical 1 of the subject Statistical Foundation of Data Sciences.  
The notebook demonstrates the creation and analysis of a synthetic dataset with **NaN values**, along with various statistical computations, standardization, and array operations.  

## Instructions
- Use either **Google Colab** or **Jupyter Notebook**.  
- Generate a synthetic dataset including some **NaN values**.  
- Keep the **random seed = 42** initially; modify if required for different scenarios.  

## Objectives
- To understand and apply fundamental statistical concepts practically.  
- To practice coding, data analysis, and visualization in a structured manner.  
- To handle missing data and perform calculations like mean, median, weighted mean, and standardization correctly.  
- To explore array operations, reshaping, indexing, and broadcasting.  

## Problem Statements

**Problem 1:**  
- Compute:  
  a) Mean  
  b) Median  
  c) Age-weighted mean of income  
- Ignore NaNs where appropriate.  
- Explain when a **weighted mean** is preferable.

**Problem 2:**  
- Standardize income (**z-score**).  
- Report how many incomes are **outliers** using the rule |z| > 3.  
- Handle NaNs correctly without dropping entire rows unnecessarily.

**Problem 3:**  
- Create **age bins**: [18-25), [25-35), [35-45), [45-60).  
- Compute for each bin:  
  - Count of observations  
  - Mean income  
  - Median income  
- Present the result as a **tidy DataFrame** sorted by age bin.

**Problem 4:**  
- Create a **multi-dimensional array**.  
- Showcase operations:  
  - **Shape & Resize:** shape, size, transpose, flatten  
  - **Indexing:** negative indexing, slicing errors  
  - **Arithmetic Operations:** broadcasting, dot product  

## How to Run
1. Open `practical1.ipynb` in **Jupyter Notebook** or **Google Colab**.  
2. Run the cells sequentially to see computations and outputs.  
3. Ensure required libraries are installed:
```bash
pip install numpy pandas matplotlib seaborn


## Author
Lavanya

## Notes
- Ensure required libraries are installed:  
```bash
pip install numpy pandas matplotlib seaborn
