## Project 1: Ad Click Prediction Model
This project focuses on building and evaluating machine learning classification models to predict user ad engagement (click or no-click) based on demographic and behavioral data.

### Goal
The primary objective is to identify the most effective model and key features that drive ad clicks, providing actionable insights for digital marketing optimization.

Methodology Highlights
Data Preprocessing: Handled significant missing data through median (for age) and mode (for categorical features) imputation.

Feature Engineering: Applied One-Hot Encoding to categorical variables and standardized the numerical age feature.

Modeling: Trained and evaluated three classification algorithms (Logistic Regression, Decision Tree, and Random Forest).

Evaluation: Used standard classification metrics (Accuracy, Precision, Recall, F1-Score) to compare model performance and select the best predictor.

## Project 2: College Student Placement Prediction: Exploratory Data Analysis and Classification
This notebook implements a machine learning approach to predict college student placement using a synthetic dataset of 10,000 students.

### The process involves:

Exploratory Data Analysis (EDA): Visualizing the distribution of the target variable (Placement) and key features like IQ.

Data Preprocessing: Dropping the unnecessary College_ID column, One-Hot Encoding the categorical Internship_Experience feature, and scaling the numerical features using StandardScaler.

Model Training and Evaluation: Training three classification models—Logistic Regression, Decision Tree, and Random Forest—and evaluating their performance using metrics like Accuracy and F1-Score. The Decision Tree and Random Forest models achieved a perfect F1-Score of 1.0000 on the test set.

Model Persistence: Saving the fitted StandardScaler object for future data transformation.
## Project 3: Gender Classification 
**Model Training Results**
I trained four different classification models. The data was standardized using StandardScaler before training.

### Model	Accuracy
SVC	0.9670

Logistic Regression	0.9660

Random Forest	0.9590

KNN	0.9590

Best Performing Model: Support Vector Classifier (SVC)

### Summary
* The dataset is balanced regarding the target variable gender.
* Numerical features show distinct overlapping distributions.
* Binary features show varying degrees of correlation with the target.
* SVC achieved the highest accuracy on the test set.

## Obesity Classification
1. EDA (Exploratory Data Analysis)
The notebook performs the following:

* Loads Obesity Classification.csv.
* Displays basic info and statistical summaries.
**Visualizations:**
* Count Plot: Shows balance of target classes (Obesity Levels).
* Dist Plot: Age distribution.
* Correlation Heatmap: To see relationships between features.
2. Data Preprocessing
**Label Encoding:** Converts Gender and Label to numeric values.
**splitting:** 80% Train, 20% Test.
**Scaling:** Uses StandardScaler to normalize numerical features.
3. Model Training
Trains the following models:
  1. Logistic Regression
  2. Random Forest Classifier
  3. Support Vector Machine (SVC)
  4. Gradient Boosting Classifier
4. Evaluation and Saving
Prints the Accuracy and Classification Report for each model.
Automatically selects the model with the highest accuracy.
Plots the Confusion Matrix for the best model.
Saves the best model to best_model.pkl and the scaler to scaler.pkl.

