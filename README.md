# Student Score Prediction

## About This Project

This project is  my initial practical work during my internship at **Elevvo Pathways**. The goal is to build a predictive model to estimate students' exam scores based primarily on their study hours and additional factors, using machine learning regression techniques.

---

## Project Overview

The project involves:

- **Data Exploration and Cleaning:**  
  - Loading the dataset and checking its structure and contents  
  - Handling missing values and removing duplicates  
  - Detecting and managing outliers in numeric and categorical data  

- **Data Analysis:**  
  - Exploring relationships between numeric features and the target (exam scores) using correlation and visualization  
  - Investigating categorical features and their impact on the target using group means and count plots  

- **Modeling:**  
  - Training and evaluating two types of regression models:  
    - **Linear Regression**  
    - **Polynomial Regression (degree 2)**  
  - Models were trained on different feature sets:  
    - Only study hours  
    - A selected subset of relevant features  
    - All available features to maximize prediction accuracy  

- **Evaluation:**  
  - Splitting data into training and testing sets for reliable model validation  
  - Using performance metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score to evaluate and compare models  

- **Visualization:**  
  - Plotting feature distributions, regression fit lines, and correlation heatmaps to better understand the data and model performance  

---

## Dataset

- The dataset used is **StudentPerformanceFactors.csv**, which contains various factors affecting students' exam scores such as study hours, attendance, parental involvement, and more.  
- All data files are included in this repository.

---

## How to Run

1. Clone or download this repository to your local machine.  
2. Make sure you have Python installed (recommended version 3.7+).  
3. Install the required Python packages:  

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
