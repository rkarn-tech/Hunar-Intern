# Hunar Internship Tasks :-

## 📌 Task 1 - Data Cleaning

## 📌 Objective
The objective of this task is to clean the given dataset using Python and Pandas.

## 🛠️ Tools Used
- Python
- Pandas
- Jupyter Notebook

## 📂 Dataset
- food_coded.csv

## ✅ Tasks Performed
- Imported the dataset
- Viewed the first five rows
- Checked dataset information
- Identified missing values
- Filled numerical missing values using Median
- Filled categorical missing values using Mode
- Verified that all missing values were removed
- Checked duplicate rows
- Verified data types
- Saved the cleaned dataset

## 📁 Files Included
- Data_Cleaning_Task1.ipynb
- food_coded.csv
- food_coded_cleaned.csv

  ## 🎯 Result
The dataset was successfully cleaned and prepared for further analysis.

## 📌 Task 2 - 🏠 House Price Prediction using Linear Regression

## 📌 Objective
The objective of this task is to build a Machine Learning model using Linear Regression to predict house prices based on various house features.

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset
- house price data.csv

## ✅ Tasks Performed
- Imported the required libraries
- Loaded the house price dataset
- Explored the dataset using head(), shape(), info(), and describe()
- Checked for missing values
- Checked for duplicate records
- Selected relevant features
- Split the dataset into training and testing sets
- Built a Linear Regression model
- Trained the model using training data
- Predicted house prices on test data
- Evaluated the model using MAE, MSE, and R² Score

## 📊 Model Evaluation
- **MAE:** 210,908.17
- **MSE:** 986,921,767,056.12
- **R² Score:** 0.0323

## 📁 Files Included
- House_Price_Prediction.ipynb
- house price data.csv

## 📌 Conclusion
A Linear Regression model was successfully developed to predict house prices. The complete machine learning workflow was implemented, including data preprocessing, feature selection, model training, prediction, and evaluation. The R² score is low due to the dataset quality and the use of a basic Linear Regression model, but the project successfully demonstrates the end-to-end machine learning process.


## 📌 Task 3 - 🩺 Breast Cancer Classification using K-Nearest Neighbors (KNN)

## 📌 Objective

The objective of this project is to build a Machine Learning model using the K-Nearest Neighbors (KNN) algorithm to classify breast cancer tumors as **Malignant (M)** or **Benign (B)**.

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## 📂 Dataset

- breast_cancer.csv

## ✅ Tasks Performed

- Imported the required libraries
- Loaded the breast cancer dataset
- Explored the dataset
- Checked dataset information
- Verified missing values
- Removed the unnecessary **id** column
- Encoded the target variable (M → 1, B → 0)
- Split the dataset into training and testing sets
- Applied feature scaling using StandardScaler
- Trained a K-Nearest Neighbors (KNN) classifier
- Made predictions on the test dataset
- Evaluated the model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Compared different K values (1–20)
- Visualized **K Value vs Accuracy** using a line graph

## 📈 Results

- **Accuracy (K = 5):** 94.74%
- **Best Accuracy:** 96.49% (K = 9)


## 📊 Conclusion

The K-Nearest Neighbors (KNN) model successfully classified breast cancer tumors with an accuracy of **94.74%** using **K = 5**. After testing multiple values of **K (1–20)**, the highest accuracy of **96.49%** was achieved at **K = 9**. The model demonstrated strong performance based on Accuracy, Confusion Matrix, and Classification Report, making it effective for binary classification of breast cancer.


# Hunar Internship - Task 4

## Assignment 1: NumPy Array

### 📌 Objective
Create a NumPy matrix from user input and calculate the sum of its diagonal elements using a loop.

### 🛠️ Tools Used
- Python
- NumPy
- Jupyter Notebook

### 📂 Task Performed
- Imported the NumPy library
- Accepted the order of the matrix from the user
- Accepted matrix elements
- Created a NumPy array
- Calculated the sum of the main diagonal elements using a loop
- Displayed the final result

### 📈 Outcome
Successfully created a NumPy array and calculated the sum of its diagonal elements using a loop.
