# Student Rating Dataset Analysis

## Overview
This Jupyter Notebook performs an analysis of a simulated Student Rating Dataset. The dataset contains information about professors’ age, gender, minority status, tenure, and student evaluation scores. The main goal of this analysis is to answer specific questions about tenure, demographics, and evaluation trends using Python visualization and statistical tools.

---

## Dataset
Since the exact Kaggle dataset was not available, a simulated dataset was created with the following columns:

- `age` : Age of the professor
- `gender` : Gender of the professor (Male/Female)
- `minority` : Whether the professor belongs to a visible minority (Yes/No)
- `tenure` : Tenure status (Yes/No)
- `eval` : Student evaluation score (2.5 - 5.0 scale)

The dataset contains 50 sample entries, designed to reflect realistic distributions.

---

## Analysis Tasks

1. **Percentage of visible minorities who are tenured**
   - Calculates the proportion of minority professors holding tenure.
   - Provides insights into whether tenure status differs based on minority status.

2. **Average age by tenure**
   - Computes the mean and standard deviation of age for tenured and non-tenured professors.
   - Helps to understand whether tenure correlates with age.

3. **Age distribution graph**
   - Visualizes age using a histogram to understand spread and distribution.
   - Histogram chosen over boxplot for clarity of distribution.

4. **Gender distribution**
   - Explains the difference between `pyplot.bar` (vertical) and `pyplot.barh` (horizontal) plots.
   - Plots the gender distribution of professors using a bar chart.

5. **Median evaluation score for tenured professors**
   - Calculates the median student evaluation score among tenured faculty.
   - Provides insight into how tenured professors are rated by students.

---

## Libraries Used
- `pandas` : For data manipulation and analysis
- `numpy` : For numerical operations and data simulation
- `matplotlib` : For plotting graphs
- `seaborn` : For enhanced visualization style

---

## How to Use
1. Open the `StudentRatingAnalysis.ipynb` notebook in Jupyter.
2. Run each cell sequentially to see outputs and visualizations.
3. All graphs and statistics are generated from the simulated dataset included in the notebook.

---

## Notes
- This analysis uses a simulated dataset for educational purposes.
- The notebook is structured with explanations and comments for clarity and understanding.
- The results are reproducible by setting a random seed (`np.random.seed(42)`).

---

