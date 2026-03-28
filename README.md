# Cybersecurity: Suspicious Web Threat Interactions

## Project Overview

This project focuses on analyzing web traffic data to identify suspicious activities and potential 
cyber threats. The dataset is collected from AWS CloudWatch logs, containing detailed information 
about network interactions.
Using data analysis, visualization, and machine learning techniques, the project detects abnormal 
patterns such as unusual data transfer, suspicious countries, and malicious web activity.

## Objectives
Analyze web traffic data to detect suspicious behavior
Identify abnormal patterns in bytes transferred
Perform country-wise analysis of suspicious traffic
Build a machine learning model to classify traffic as Normal or Suspicious
Create an interactive dashboard for traffic monitoring
## 🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib & Seaborn
Plotly
Scikit-learn
TensorFlow / Keras
Jupyter Notebook
## 📂 Dataset Information

The dataset contains web traffic logs with features such as:

bytes_in, bytes_out
src_ip, dst_ip
src_ip_country_code
protocol, dst_port
detection_types
creation_time, end_time
## ⚙️ Project Workflow
### 1️⃣ Data Preprocessing
Converted timestamps to datetime format
Created duration_seconds feature
Handled categorical variables
Standardized numerical features
### 2️⃣ Exploratory Data Analysis (EDA)
Traffic distribution analysis
Suspicious activity by country
Bytes transfer patterns
Data visualization using charts
### 3️⃣ Feature Engineering
Selected important features like:
bytes_in
bytes_out
duration_seconds
country code
### 4️⃣ Machine Learning Model
Built a Neural Network model
Classified traffic into:
Normal
Suspicious
Applied feature scaling and train-test split
### 5️⃣ Dashboard
Created an interactive dashboard using Plotly
Included filters and KPI metrics:
Total Sessions
Suspicious Traffic
Country-wise analysis
