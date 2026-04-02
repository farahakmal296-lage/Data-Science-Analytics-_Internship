# Data Science & Analytics Internship Tasks

This repository contains the tasks completed during the Data Science & Analytics Internship at DevelopersHub Corporation.

## Task 1: Exploring and Visualizing a Simple Dataset

### 1. Task Objective
The primary goal of this task is to perform Exploratory Data Analysis (EDA) on the **Iris Dataset**. It is intended to demonstrate proficiency in data loading, summarization, and professional visualization.

### 2. My Approach
* **Data Inspection:** The dataset structure was verified using `.shape`, `.columns`, and `.head()`.
* **Data Cleaning:** A check for missing values was conducted to ensure data integrity.
* **Visualization:** * A **Scatter Plot** was generated to analyze the relationship between sepal dimensions.
    * A **Histogram** was utilized to examine the distribution of petal lengths.
    * A **Box Plot** was created to evaluate data spread and detect outliers.

### 3. Results and Insights
* The **Setosa** species is found to be significantly smaller and easily distinguishable from others.
* A strong correlation is observed between petal measurements and species classification.
* No missing values were detected, confirming the reliability of the dataset.

## Task 2: Credit Risk Prediction and Analysis

### 1. Task Objective
The primary objective of this task is to develop a classification model that determines the creditworthiness of loan applicants. It is intended to analyze historical customer data to minimize financial risk for lending institutions.

### 2. My Approach
A structured Machine Learning workflow was followed to ensure the reliability of the predictions:
* **Data Inspection:** The dataset was thoroughly examined for structural integrity and column types.
* **Data Cleaning & Preprocessing:** * Missing values in categorical columns (e.g., Gender, Married) were handled using **Mode Imputation**.
    * Numerical null values (e.g., LoanAmount) were addressed using **Median Imputation** to avoid the influence of outliers.
* **Exploratory Data Analysis (EDA):** * A **Count Plot** was generated to visualize the impact of Credit History on Loan Status.
    * A **Box Plot** was utilized to analyze the distribution of Applicant Income across approved and rejected loans.
* **Model Readiness:** The data was transformed and encoded, making it suitable for classification algorithms.

### 3. Results and Insights
* **Key Indicator:** It is observed that **Credit History** is the most significant predictor of loan eligibility. Applicants with a positive history are found to have a much higher approval rate.
* **Income Factor:** While income is a factor, it is noted that high income alone does not guarantee approval if the credit history is poor.
* **Data Quality:** After preprocessing, a clean and balanced dataset was achieved, providing a solid foundation for model training.
