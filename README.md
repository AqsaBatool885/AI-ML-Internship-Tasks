# AI/ML Engineering Internship - DevelopersHub Corporation

## Task 1: Exploring and Visualizing a Simple Dataset

### Objective
The goal of this task was to build a foundation in data exploration by loading, inspecting, and visualizing a real-world dataset to understand trends and distributions.

### Dataset Used
**Iris Dataset:** A classic dataset containing 150 samples of iris flowers, with 4 features (sepal length, sepal width, petal length, petal width) and 1 target variable (species).

### Models Applied
* **Data Manipulation:** Pandas
* **Data Visualization:** Seaborn and Matplotlib
* **Statistical Analysis:** Descriptive Statistics (`.describe()`)

### Key Results and Findings
* **Species Separation:** The scatter plot showed that the *Setosa* species is easily distinguishable from *Versicolor* and *Virginica* based on petal length and width.
* **Distributions:** Most features follow a relatively normal distribution, though petal measurements show a clear "gap" between species groups.
* **Outliers:** Box plots revealed a few minor outliers in the `sepal_width` for the *Virginica* species, but the data is generally clean.

* Task 3: Heart Disease Prediction (Description)
Objective: To develop a machine learning pipeline that predicts the likelihood of heart disease in patients based on 14 clinical health markers. This task focused on handling medical data, where minimizing "False Negatives" (missing a sick patient) is a top priority.

Key Technical Steps: * Data Cleaning: Handled missing values using median/mode imputation to maintain dataset integrity.

Feature Engineering: Implemented One-Hot Encoding to convert categorical clinical data into a mathematical format, expanding the feature set to 22 variables.

Feature Scaling: Used StandardScaler to ensure features like "Cholesterol" (high range) and "Sex" (binary) were on the same scale for the Logistic Regression model.

Modeling: Applied a Logistic Regression classifier to determine risk probability.

Evaluation & Performance: * Confusion Matrix: Used to visualize the model's accuracy in identifying true heart disease cases vs. healthy individuals.

ROC-AUC Curve: Achieved a high AUC score, demonstrating the model's effectiveness in distinguishing between classes.

Feature Importance: Identified that Chest Pain Type (cp) and ST Depression (oldpeak) were the most influential factors in predicting heart disease risk.
