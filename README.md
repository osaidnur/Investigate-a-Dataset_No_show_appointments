# 📊 No-Show Medical Appointments Analysis

This project explores a real-world medical dataset to understand the factors that contribute to missed appointments. By analyzing various patient and appointment-related features, we aim to uncover actionable insights that could help healthcare providers reduce no-show rates and improve patient attendance.

## 📚 Table of Contents

- [Project Objective](#-project-objective)
- [Dataset Overview](#-dataset-overview)
- [Analysis Focus](#-analysis-focus)
- [Key Findings](#-key-findings)
- [How to Use](#-how-to-use)

---

## 🧠 Project Objective

To analyze a dataset of medical appointments and identify the key factors that influence whether a patient shows up or not. This includes exploring correlations between attendance and variables such as:

- Age
- Gender
- Medical conditions
- SMS reminders
- Scholarship status
- Scheduled vs. appointment day

---

## 📁 Dataset Overview

The dataset used in this project contains records of over 100,000 medical appointments in Brazil. Each record includes attributes like:

- Patient ID
- Appointment Date & Scheduled Date
- Demographics (Age, Gender)
- Medical Information (Hypertension, Diabetes, Alcoholism, etc.)
- Whether the patient received an SMS reminder
- Whether the patient showed up

---

## 🔍 Analysis Focus

We perform exploratory data analysis (EDA) to examine:

- How age and gender influence attendance
- The role of chronic illnesses in appointment behavior
- The effectiveness of SMS reminders
- Trends and anomalies in scheduling patterns

---

## ✅ Key Findings

- Certain age groups are more likely to miss appointments.
- Receiving an SMS reminder is loosely correlated with higher attendance.
- Patients with specific health conditions (like hypertension) tend to be more reliable.
- The gap between scheduling and appointment date may influence show-up rates.

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/osaidnur/Investigate-a-Dataset_No_show_appointments.git
   cd Investigate-a-Dataset_No_show_appointments
   ```

2. Open the Jupyter Notebook to explore the analysis:

   ```bash
   jupyter notebook no_show_appointments.ipynb
   ```

3. Ensure you have the required libraries installed:

   ```bash
   pip install pandas matplotlib seaborn
   ```
