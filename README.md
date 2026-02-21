📌 Project Overview

This project aims to analyze and predict customer churn for a telecom company. The goal is to identify customers who are likely to leave the service and provide actionable insights to improve customer retention strategies.

The project includes SQL-based data analysis, machine learning modeling in Python, and interactive dashboard visualization using Power BI.



🎯 Business Problem

Customer acquisition is more expensive than customer retention. Telecom companies need to identify high-risk customers early to reduce churn and revenue loss.




🛠️ Tech Stack

MySQL – Data storage and SQL analysis

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn) – Data preprocessing and ML

Power BI – Interactive dashboard visualization

Jupyter Notebook – Development environment



📂 Dataset

Telco Customer Churn Dataset

7,043 customer records

20+ features

Target variable: Churn (Yes/No)

🔎 Project Workflow

1️⃣ Database & SQL Analysis

Created database in MySQL

Imported dataset using LOAD DATA INFILE

Calculated churn rate

Analyzed churn by:

Contract type

Payment method

Tenure

Monthly charges

Identified high-risk customer segments




2️⃣ Data Cleaning & EDA (Python)

Removed unnecessary columns

Handled missing values

Encoded categorical variables

Performed exploratory data analysis

Identified key churn drivers

3️⃣ Machine Learning Model

Built Logistic Regression and Random Forest models

Evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Final Model: Random Forest
Accuracy: ~82–85%



4️⃣ Power BI Dashboard

KPI cards (Total Customers, Churn Rate)

Contract-wise churn analysis

Payment method analysis

Tenure segmentation

Monthly charges comparison

Interactive slicers




📈 Key Insights

Month-to-month contract customers have the highest churn rate

Customers with low tenure churn more

Higher monthly charges increase churn probability




🚀 How To Run This Project

1️⃣ MySQL Setup

Create database

Import dataset using LOAD DATA INFILE

2️⃣ Python Setup
pip install pandas numpy scikit-learn matplotlib seaborn

Run the Jupyter Notebook to train the model.

3️⃣ Power BI

Connect to MySQL database or import processed dataset

Load provided dashboard file










🚀 How To Run This Project


1️⃣ MySQL Setup

Create database

Import dataset using LOAD DATA INFILE

2️⃣ Python Setup
pip install pandas numpy scikit-learn matplotlib seaborn

Run the Jupyter Notebook to train the model.

3️⃣ Power BI

Connect to MySQL database or import processed dataset

Load provided dashboard file

📊 Project Architecture

MySQL → Python (ML) → Power BI Dashboard

💡 Future Improvements

Hyperparameter tuning

Deployment using Streamlit

Real-time churn prediction API

Model performance optimization
