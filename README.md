
# 📌 Healthcare Appointment No-Show Prediction

## 🔍 Project Overview
This project aims to predict whether a patient will miss their medical appointment using machine learning. It analyzes a real-world dataset from Brazil that contains information on appointment details, patient demographics, and health indicators. By identifying key no-show factors, this project helps optimize hospital scheduling and resource allocation.

## 📁 Dataset
- **Source**: [Kaggle – No-show appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **File Used**: KaggleV2-May-2016.csv
- Contains over 100,000 appointment records.

## 🛠️ Tools & Technologies
- **Python** (Pandas, Seaborn, Sklearn, Matplotlib)
- **Power BI** (for interactive dashboards)
- **Jupyter Notebook** (for model development)

## 📊 Features Used
- Age  
- Scholarship (0/1)  
- Hypertension (0/1)  
- Diabetes (0/1)  
- Alcoholism (0/1)  
- Handcap (0/1)  
- SMS_received (0/1)  
- No-show (Target: 1 = missed, 0 = attended)

## 🧪 Machine Learning Model
- **Model Used**: Decision Tree Classifier
- **Target Variable**: `No-show`
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report

## 📈 Power BI Dashboard
Interactive visuals include:
- Age group vs No-show rate
- SMS reminders vs Attendance
- Health conditions vs No-show
- Slicers to filter by conditions

## 📄 Folder Structure
```
📦 healthcare-no-show-prediction
├── healthcare_no_show_prediction.ipynb     # Python notebook with code
├── Healthcare_No_Show_Report.pdf           # Final 2-page report
├── Healthcare_No_Show_Dashboard.pbix       # Power BI dashboard
└── README.md                               # This file
```

## 📌 Key Insights
- Patients who **did not receive SMS** reminders were more likely to miss appointments.
- **Younger age groups** tend to have higher no-show rates.
- **Health conditions** like hypertension or diabetes did not significantly reduce no-shows.

## ✅ Outcome
A machine learning model was successfully built with reasonable accuracy. The Power BI dashboard enables hospitals to explore and act on no-show trends, improving appointment scheduling.
