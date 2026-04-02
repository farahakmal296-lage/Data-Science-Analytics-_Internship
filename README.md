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
  
# Task 5: Personal Loan Acceptance Prediction

## 1. Task Objective
The primary objective of this project is to build a predictive model that identifies which customers are most likely to accept a personal loan offer. By analyzing the **Bank Marketing Dataset**, we aim to help the bank optimize its marketing strategies, reduce costs, and increase the conversion rate of their loan campaigns.

## 2. Approach
To achieve a reliable prediction, the following systematic approach was followed:

### **Data Preprocessing**
* **File Handling:** Managed the semicolon-delimited (`;`) structure of the raw `bank.csv` file to ensure proper column alignment.
* **Data Cleaning:** Cleaned column names by removing extra quotes and trailing spaces.
* **Label Encoding:** Converted categorical text features (such as `job`, `marital`, and `education`) into numerical format using `LabelEncoder`.
* **Feature Scaling:** Applied `StandardScaler` to normalize numerical features like `balance` and `age`, ensuring the Logistic Regression model treats all variables fairly.

### **Exploratory Data Analysis (EDA)**
* **Demographic Visualization:** Used **Seaborn** count plots and histograms to understand customer distributions.
* **Correlation Analysis:** Analyzed the relationship between job types, age groups, and the target variable (`y`) to identify high-conversion segments.

### **Model Training**
* **Data Splitting:** Divided the dataset into **80% training** and **20% testing** sets to validate performance.
* **Algorithm:** Trained a **Logistic Regression** classifier using the Scikit-Learn library.
* **Optimization:** Increased iterations (`max_iter=1000`) and used scaled data to ensure model convergence and stability.

## 3. Results and Insights

### **Model Performance**
* **Final Accuracy:** The model achieved a consistent accuracy of **79.00%**.
* **Evaluation Metrics:** The Classification Report confirmed balanced precision and recall scores, indicating the model is reliable for both predicting acceptance and rejection.

### **Key Insights**
* **Demographic Impact:** Younger age groups and specific job categories (such as management and technicians) showed a significantly higher frequency of loan engagement.
* **Data Quality Importance:** Proper feature scaling was crucial; without it, the model faced convergence issues due to the wide range of financial values in the `balance` column.
* **Business Value:** With a **79% success rate**, the bank can now pre-screen its database to focus marketing efforts on the "High Probability" segment, significantly improving Return on Investment (ROI) and reducing telemarketing costs.
*
