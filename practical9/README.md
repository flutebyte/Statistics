📘 Practical 9 – K-Nearest Neighbors (KNN) Classification on the Iris Dataset

This practical focuses on applying the K-Nearest Neighbors (KNN) algorithm to classify flower species in the classic Iris dataset.
It includes data preprocessing, exploratory data analysis, feature scaling, model training, performance evaluation, and selecting the most suitable K value.

1. Importing Required Libraries

pandas – data manipulation

numpy – numerical computations

scikit-learn – dataset loading, preprocessing, model building, evaluation

matplotlib – plotting and visualizations

2. Loading the Iris Dataset

Load the dataset using load_iris()

Convert it into a pandas DataFrame

Assign species labels: setosa, versicolor, and virginica

3. Exploratory Data Analysis (EDA)

View the first few rows using head()

Generate statistical summaries using describe()

Use groupby() to calculate mean feature values for each species

4. Feature Scaling

Use StandardScaler() to standardize all numerical features

Fit and transform the dataset to improve KNN performance

5. Train–Test Split

Split the dataset into 80% training and 20% testing using train_test_split()

6. Training the KNN Model

Create a model using KNeighborsClassifier()

Train it on the scaled training data

Predict the species of the test samples

7. Model Evaluation

Display the Confusion Matrix

Compute the Accuracy Score

Generate a Classification Report (Precision, Recall, F1-score)

8. Finding the Best K Value

Iterate through K values from 1 to 20

Compute the error rate for each K

Select the K value that yields the lowest error

9. Error Rate Plot

Plot K values vs. error rates

Observe how model performance changes with different K values

Helps in determining the optimal K

10. Visualizing KNN Decision Boundary (2D)

Encode categorical species labels

Train a 2D KNN classifier using selected feature pairs

Plot decision boundaries to visualize classification regions
