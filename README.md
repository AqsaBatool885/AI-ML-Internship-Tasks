Task 1: Iris Dataset Exploration & Visualization
Problem Statement
The goal of this task was to perform Exploratory Data Analysis (EDA) on the classic Iris dataset to identify patterns that distinguish different flower species.

Technical Workflow
Data Cleaning: Inspected for missing values and confirmed data integrity.

Analysis: Used .describe() for statistical insights into sepal and petal dimensions.

Visualization: Created Scatter plots and Pair plots to visualize species clusters.

Key Insights
Species Separation: Petal length and width are the most significant features for classification.

Cluster Discovery: The Setosa species forms a completely distinct cluster, while Versicolor and Virginica have slight overlaps.

Task 3: Heart Disease Prediction (Classification)
Problem Statement
Build a predictive model to determine if a patient is at risk for heart disease based on clinical parameters like cholesterol, heart rate, and chest pain type.

Technical Workflow
Preprocessing: Handled missing values via median imputation and applied One-Hot Encoding to categorical features.

Feature Scaling: Used StandardScaler to normalize numeric data, ensuring the model treats all features equally.

Model Training: Implemented a Logistic Regression classifier for binary diagnosis.

Evaluation: Validated performance using a Confusion Matrix and ROC-AUC Curve.

Key Insights
Primary Risk Factors: Chest Pain Type (cp) and Maximum Heart Rate (thalach) were identified as the strongest predictors.

Model Performance: The model shows high diagnostic reliability with a strong AUC score, effectively minimizing False Negatives.est Pain Type (cp) and ST Depression (oldpeak) were the most influential factors in predicting heart disease risk.
