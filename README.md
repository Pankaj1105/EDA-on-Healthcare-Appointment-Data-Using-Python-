# 🏥 Healthcare Appointment EDA 📊

> Analyzing patient behavior to uncover why medical appointments are missed — using Python & data science!

---

## 🔍 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a real-world healthcare dataset to uncover trends in patient appointment attendance and **no-show behavior**. The goal is to derive actionable insights for reducing no-shows and improving healthcare delivery.

---

## 🗂️ Dataset Description

The dataset (sourced from Kaggle) includes over **130,000 medical appointments** and features:

| Feature | Description |
|---------|-------------|
| `Gender` | Patient gender (M/F) |
| `Age` | Patient age |
| `Neighbourhood` | Location of the clinic |
| `Scholarship` | Whether the patient is enrolled in a welfare program |
| `Hypertension`, `Diabetes` | Health conditions |
| `SMS_received` | Whether a reminder SMS was sent |
| `No-show` | Whether the patient missed the appointment (target variable) |

---

## 🛠️ Tools & Technologies

- **Python 3.10+**
- **Jupyter Notebook**
- **pandas, numpy** – Data wrangling  
- **matplotlib, seaborn** – Visualization  
- **scikit-learn (optional)** – For future predictive modeling

---

## 📈 Key Insights

✅ **Female patients** booked more appointments than males  
✅ **Show rate** across most age groups was similar (~80%)  
✅ Patients with **hypertension/diabetes** showed higher attendance  
✅ **SMS reminders** did **not** increase attendance — in fact, no-show rate was higher for those who received SMS  
✅ Appointments were mostly scheduled on **weekdays**, with **very few on Saturdays** and **none on Sundays**

---

## 📊 Visuals Included

- Bar plots comparing attendance by gender, age, neighborhood, and health status  
- Correlation heatmaps  
- Weekday trends in scheduling  
- Boxplots for age distributions  

---

## 🧹 Project Workflow

1. **Load & Inspect Data** – Understand structure, check for missing values  
2. **Data Cleaning** – Drop irrelevant features, correct formats  
3. **Feature Engineering** – Extract day of week, create age bins, encode categorical variables  
4. **EDA & Visualization** – Univariate & bivariate analysis with graphs and summaries  
5. **Insights** – Summarize learnings and trends  

---
