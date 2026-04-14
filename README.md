
# 🏥 Hospital Doctor Utilization & Patient Cost Analysis

## 📌 Project Overview

This project analyzes hospital operational data to evaluate doctor utilization,
patient treatment patterns, and billing behavior. The objective is to identify
workload distribution among doctors, understand cost-driving factors, and support
data-driven decision-making in hospital management.

By integrating multiple datasets including doctor, patient, treatment, and billing
records, this analysis demonstrates how healthcare analytics can improve operational
efficiency and optimize hospital resources.

---

## 🎯 Business Problem

Hospitals face challenges such as:

- Uneven doctor workload distribution
- Overloaded medical specialties
- Increasing patient demand
- Rising treatment costs

This project addresses these challenges using structured data analysis and visualization.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze doctor workload distribution
- Measure doctor utilization
- Identify heavily loaded specialties
- Study patient admission patterns
- Analyze factors affecting billing
- Evaluate patient stay duration
- Support hospital resource planning

---

## 📊 Key Performance Indicators (KPIs)

The following KPIs were analyzed:

- Total Number of Doctors
- Total Number of Patients
- Total Number of Treatments
- Doctor Utilization Rate (%)
- Most Busy Specialty
- Most Common Diagnosis
- Average Patient Stay Duration
- Monthly Patient Admission Trends
- Revenue by Specialty
- Billing Distribution by Stay Duration

---

## 📂 Dataset Description

This project uses four datasets:

### Doctor Dataset (d1.csv)
- Doctor_ID
- Doctor_Name
- Specialty
- Experience_Years

### Patient Dataset (p1.csv)
- Patient_ID
- Admission_Date
- Discharge_Date
- Diagnosis

### Treatment Dataset (t1.csv)
- Treatment_ID
- Doctor_ID
- Patient_ID
- Treatment_Date
- Treatment_Minutes

### Billing Dataset (b1.csv)
- Patient_ID
- Total_Bill

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL (MySQL / WampServer)
- SQLAlchemy
- Jupyter Notebook

---

## 🔧 Data Preparation Steps

- Loaded datasets into Python
- Merged tables using common keys
- Converted date columns to datetime
- Created new columns:
  - Days Stayed
  - Treatment Hours
  - Month
  - Doctor Experience Category
- Handled missing values
- Converted numeric fields
- Stored processed data into SQL

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Specialty workload analysis
- Diagnosis frequency analysis
- Monthly admission trends
- Doctor utilization analysis
- Billing distribution analysis
- Relationship between stay duration and billing
- Revenue contribution by specialty

---

## 📊 Visualizations

Key visualizations created:

- Bar Charts – Specialty Workload
- Scatter Plots – Billing vs Stay Duration
- Boxplots – Billing Distribution by Stay Duration
- Line Charts – Monthly Patient Trends
- Utilization Charts – Doctor Workload

---

## 🔍 Key Insights

- Certain specialties handled significantly more treatments.
- Some doctors managed a large portion of treatments.
- Monthly patient admissions showed peak periods.
- Longer hospital stays generally resulted in higher billing.
- Billing variation indicates influence from diagnosis and treatment type.
- Workload imbalance suggests need for better scheduling.

---

## 🎯 Recommendations

- Balance workload across doctors
- Increase staffing in busy specialties
- Plan staffing during peak months
- Monitor patient stay duration
- Use predictive analytics for future demand
- Track doctor utilization regularly

---

## 🏁 Conclusion

This project demonstrates how healthcare data analytics can improve hospital
operations by identifying workload patterns, cost drivers, and patient trends.
The findings support better decision-making, efficient resource utilization,
and improved patient service quality.

---

## 🗄 SQL Integration

This project includes:

- Storing datasets into SQL tables
- Running SQL queries
- Counting distinct doctors
- Performing grouped aggregations
- Retrieving SQL data into Python

---

## 📁 Project Structure

Hospital-Doctor-Utilization-Analysis/

│── sample.ipynb  
│── README.md  
│── d1.csv  
│── p1.csv  
│── t1.csv  
│── b1.csv  

---

## 🚀 Future Improvements

- Build Power BI dashboard
- Add predictive analytics models
- Create automated reports
- Develop machine learning models

---

## 👨‍💻 Author

Name: (Add Your Name)  
Role: Aspiring Data Analyst  

Skills Demonstrated:

- Data Cleaning  
- Data Integration  
- SQL Querying  
- Data Visualization  
- Exploratory Data Analysis  

