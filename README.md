## Project 1: Ad Click Prediction Model
This project focuses on building and evaluating machine learning classification models to predict user ad engagement (click or no-click) based on demographic and behavioral data.

### Goal
The primary objective is to identify the most effective model and key features that drive ad clicks, providing actionable insights for digital marketing optimization.

Methodology Highlights
Data Preprocessing: Handled significant missing data through median (for age) and mode (for categorical features) imputation.

Feature Engineering: Applied One-Hot Encoding to categorical variables and standardized the numerical age feature.

Modeling: Trained and evaluated three classification algorithms (Logistic Regression, Decision Tree, and Random Forest).

Evaluation: Used standard classification metrics (Accuracy, Precision, Recall, F1-Score) to compare model performance and select the best predictor.

## College Student Placement Prediction: Exploratory Data Analysis and Classification
This notebook implements a machine learning approach to predict college student placement using a synthetic dataset of 10,000 students.

### The process involves:

Exploratory Data Analysis (EDA): Visualizing the distribution of the target variable (Placement) and key features like IQ.

Data Preprocessing: Dropping the unnecessary College_ID column, One-Hot Encoding the categorical Internship_Experience feature, and scaling the numerical features using StandardScaler.

Model Training and Evaluation: Training three classification models—Logistic Regression, Decision Tree, and Random Forest—and evaluating their performance using metrics like Accuracy and F1-Score. The Decision Tree and Random Forest models achieved a perfect F1-Score of 1.0000 on the test set.

Model Persistence: Saving the fitted StandardScaler object for future data transformation.
