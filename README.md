# 📊 Customer Churn Prediction and Retention Analysis

### Machine Learning | Data Analytics | Python | Streamlit

## 📌 About the Project

**Customer Churn Prediction and Retention Analysis** is a Machine Learning and Data Analytics project developed using Python and Streamlit.

Customer churn occurs when customers stop using a company's products or services. It is a major challenge for businesses because losing customers can affect business growth and revenue.

This project analyzes customer data to understand customer behavior, identify churn patterns, predict potential customer churn, and provide useful retention suggestions to help businesses improve customer retention.

The application combines interactive data visualization, machine learning predictions, customer risk classification, revenue analysis, and business insights in one place.

## 🎯 Project Objectives

- Analyze customer data and understand customer behavior.
- Identify patterns among customers who leave the company.
- Predict potential customer churn using Machine Learning.
- Classify customers into different churn risk levels.
- Analyze revenue associated with churned customers.
- Identify customer segments based on tenure.
- Generate business insights from customer data.
- Provide retention suggestions to help businesses reduce customer churn.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Streamlit | Interactive application development |
| Scikit-learn | Machine Learning |
| Random Forest Classifier | Customer churn prediction |

## 📂 Dataset Description

This project uses the **Telco Customer Churn Dataset**.

The dataset contains customer-related information, including:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

The dataset is cleaned and preprocessed before performing data analysis and machine learning.

## ✨ Key Features

### 1. Customer Churn Analysis
Analyzes the number of customers who left the company and those who continued using its services.

### 2. Interactive Data Visualization
Provides six different types of graphs:

- **Bar Graph:** Compares churned and retained customers.
- **Histogram:** Shows the distribution of numerical customer data.
- **Scatter Plot:** Identifies relationships between numerical customer variables.
- **Line Chart:** Displays customer trends across different tenure groups.
- **Pie Chart:** Shows the proportion of churned and retained customers.
- **Box Plot:** Compares numerical data distributions and identifies outliers.

### 3. Customer Trend Analysis
Groups customers according to their tenure:

- 0–12 months
- 13–24 months
- 25–48 months
- 49–72 months

Analyzes churn rate, average monthly charges, average total charges, and customer count.

### 4. Customer Churn Prediction
Uses the Random Forest Classifier machine learning algorithm to predict whether a customer is likely to leave the company.

### 5. Churn Risk Classification
Classifies customers into three risk categories:

- Low Risk
- Medium Risk
- High Risk

### 6. Revenue Loss Analysis
Estimates monthly and annualized charges associated with churned customers to understand the potential business impact of customer churn.

### 7. Customer Segmentation
Groups customers based on their tenure to understand customer behavior and retention patterns.

### 8. Customer Behaviour Analysis
Analyzes customer behavior based on:

- Contract Type
- Payment Method
- Internet Service
- Gender
- Online Security
- Tech Support

### 9. Business Insights
Provides useful insights based on customer data and analysis to help businesses understand churn patterns.

### 10. Personalized Retention Suggestions
Provides suggestions based on customer information and predicted churn risk to support customer retention decisions.

### 11. Machine Learning Model Evaluation
Evaluates the model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### 12. Data Filtering and Download
Allows users to filter customer information and download the customer churn risk report as a CSV file.

## ⚙️ Project Workflow

1. Dataset collection.
2. Data loading using Pandas.
3. Data cleaning and preprocessing.
4. Exploratory Data Analysis (EDA).
5. Customer behavior analysis.
6. Interactive graph generation.
7. Machine Learning model training.
8. Customer churn prediction.
9. Customer risk classification.
10. Business insights and retention suggestions.

## 🧠 Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is a supervised Machine Learning algorithm that uses multiple decision trees to make predictions.

In this project, it is used to predict customer churn based on customer-related information and classify customers according to their predicted churn risk.

## 📁 Project Folder Structure

```text
churn_app_project/
│
├── .venv/
│
└── churn_app/
    │
    ├── proj1.py
    ├── Data.csv
    └── README.md
```

## 🚀 How to Run the Project

Follow these steps to run the project on your local Windows system.

### Step 1: Open PowerShell

```powershell
cd "c:\Users\nehar\OneDrive\Desktop\churn_app_project"
```

### Step 2: Activate Virtual Environment

```powershell
.\.venv\Scripts\Activate.ps1
```

### Step 3: Open the Application Folder

```powershell
cd churn_app
```

### Step 4: Install Required Libraries

```powershell
pip install streamlit pandas numpy matplotlib seaborn scikit-learn
```

### Step 5: Run the Application

```powershell
streamlit run proj1.py
```

### Step 6: Access the Application

Streamlit will display a local URL in PowerShell. Open that URL in your web browser to access the application.

**Important:** Keep `Data.csv` in the same folder as `proj1.py`.

## 📊 Expected Outcomes

- Understand customer churn patterns.
- Identify customers who are likely to leave.
- Analyze customer behavior using interactive graphs.
- Classify customers based on churn risk.
- Understand the revenue impact associated with churn.
- Generate useful business insights.
- Support better customer retention decisions.

## 🔮 Future Enhancements

- Deploy the application online.
- Integrate real-time customer data.
- Explore additional Machine Learning algorithms.
- Improve prediction performance through model tuning.
- Add automated customer retention campaigns.
- Provide advanced customer behavior analysis.

## 🎓 Project Information

**Project Title:** Customer Churn Prediction and Retention Analysis

**Domain:** Machine Learning and Data Analytics

**Project Type:** Academic Case Study

**Programming Language:** Python

**Framework:** Streamlit

**Machine Learning Algorithm:** Random Forest Classifier

## 📝 Conclusion

This project demonstrates how Machine Learning and Data Analytics can help businesses understand customer behavior and predict potential customer churn.

By combining interactive visualizations, predictive modeling, customer risk classification, revenue analysis, and business insights, the project supports businesses in identifying potential customer loss and making better customer retention decisions.
