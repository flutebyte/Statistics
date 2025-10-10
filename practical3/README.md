# Practical 3 – Statistical Relationships and Data Visualization  

This practical explores data summarization, duplicate handling, and visual analysis using **Python (pandas, matplotlib, seaborn)**.  
The focus is on understanding relationships between instructor characteristics (age, gender, and course division) and teaching evaluations.

---

## 📘 Questions Overview

### **Q1. Identifying Duplicates and Computing Summary Statistics**
- Identified duplicate records using the `prof` column.  
- Calculated **mean** and **standard deviation** for age using all observations.  
- Filtered dataset to keep one observation per professor (n = 94) and recalculated summary statistics.  
- Compared how removing duplicates affects the averages.

**Key Insight:**  
Averaging across unique instructors slightly changes the mean and standard deviation, reducing bias caused by duplicate entries.

---

### **Q2. Teaching Evaluations by Course Division**
- Created a **bar chart** comparing average evaluation scores for *lower* vs *upper* division courses.  

| Course Division | Average Evaluation |
| ---------------- | ------------------ |
| Lower            | 4.35               |
| Upper            | 3.75               |

**Interpretation:**  
Instructors teaching **lower-division courses** received slightly higher average evaluations.

---

### **Q3. Relationship Between Age and Teaching Evaluation**
- Plotted a **regression plot** using seaborn to visualize how teaching evaluations change with age.  
- Found a **negative correlation**, indicating that evaluation scores tend to decline slightly as age increases.

---

### **Q4. Gender-Differentiated Scatter Plot**
- Created scatter plots showing **Age vs Teaching Evaluation** for male and female instructors.  
- Used color and style differentiation to visualize gender differences.

**Insight:**  
Female instructors tend to have slightly higher teaching evaluations in the simulated data, though the dataset is small.

---

### **Q5. Combined Regression Analysis by Gender**
- Used `sns.lmplot()` to visualize **age vs evaluation scores** with regression lines for each gender.  
- Demonstrated how linear trends differ between groups.

---

## 🧰 Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`

---

## 🧠 Key Insights
- Duplicate handling affects overall descriptive statistics.  
- Younger instructors often receive higher evaluation scores in this sample.  
- Gender and course level can influence teaching evaluations.  
- Visualization provides powerful insights into data relationships.

---

## 📂 Files
- `Statistics/practical3.ipynb` → Full Python code and analysis  
- `Statistics/practical3/README.md` → Documentation (this file)  

---

*Created by **Lavanya Garg** – Shoolini University (B.Tech, 2023–Present)*  
