# 🩺 Diabetes Prediction using Decision Tree Classifier

## 📘 Project Overview
This project applies a **Decision Tree Classifier** to predict whether a person has diabetes based on key health indicators.  
The dataset used is the **Pima Indians Diabetes Dataset**, a classic dataset often used for medical prediction problems.

We compare two different **Decision Tree splitting criteria**:
- **Entropy (Information Gain)**
- **Gini Index (Impurity Reduction)**

Both are evaluated on model accuracy and feature importance to understand how decision trees make predictions.

---

## 🧠 Objectives
- Build a **Decision Tree Classifier** to predict diabetes outcomes.
- Visualize the structure of trees using both Entropy and Gini criteria.
- Manually calculate **Entropy**, **Information Gain**, and **Gini Reduction** for better conceptual clarity.
- Compare model performance and interpret why a particular feature becomes the root node.

---

## 🧩 Dataset Description
The dataset `diabetes.csv` contains the following columns:

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body mass index |
| DiabetesPedigreeFunction | A function which scores likelihood of diabetes based on family history |
| Age | Age of the person |
| Outcome | Target variable (1 = Diabetes, 0 = No Diabetes) |

---

## ⚙️ Installation & Requirements
Make sure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib scikit-learn


## Conclusion

- Decision Trees are a simple yet powerful model for classification problems.

- Both splitting criteria (Entropy & Gini) performed similarly.

- The model is interpretable and shows which medical features most influence diabetes prediction.
 ---

## Tools & Technologies

- Python 3.x

- Pandas – Data manipulation

- NumPy – Numerical operations

- Matplotlib – Visualization

- Scikit-learn – Model training and evaluation
