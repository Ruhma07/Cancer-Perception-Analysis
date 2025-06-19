# Cancer Patients EDA - Exploratory Data Analysis

> A comprehensive exploratory data analysis (EDA) of a cancer patients dataset from the UAE, covering demographics, cancer types, treatment patterns, outcomes, and more.

---

## 📌 Project Overview

This project provides an in-depth **exploratory data analysis (EDA)** of a cancer patient dataset containing records for **10,000 patients** across various hospitals in the UAE. The dataset includes:

- Patient demographics (age, gender, nationality, emirate)
- Diagnosis details (cancer type, stage, date)
- Treatment information (type, start date, delay)
- Outcome (recovered, under treatment, deceased)
- Comorbidities and BMI
- Physician-wise outcomes

The goal is to uncover insights about cancer prevalence, treatment efficiency, survival rates, and demographic trends in UAE cancer patients.

---

## 🗂️ Dataset Structure

| Rows   | Columns | Description                                              |
|--------|---------|----------------------------------------------------------|
| 10,000 | 20      | Contains detailed medical and demographic data on cancer patients |

### Sample Fields

- `Patient_ID`: Unique identifier for each patient  
- `Age`, `Gender`, `Nationality`, `Emirate`  
- `Diagnosis_Date`, `Cancer_Type`, `Cancer_Stage`  
- `Treatment_Type`, `Treatment_Start_Date`, `Treatment_Delay`  
- `Outcome`, `Death_Date`, `Cause_of_Death`  
- `Smoking_Status`, `Comorbidities`, `Ethnicity`  
- `Weight`, `Height`, `BMI`  

---

## 🔍 Key Insights

### 🧑‍⚕️ Patient Demographics

- **Gender Distribution**: Majority female patients  
- **Nationality**: ~59% Emirati, ~41% Expatriate  
- **Age Distribution**: Most patients are aged **50–70 years**  
- **Top Emirates**: Abu Dhabi and Dubai  

### 🧬 Cancer Types & Stages

- **Top Cancer Types**:  
  - Breast  
  - Liver  
  - Leukemia  
  - Lung  

- **Stage Distribution**:  
  - Majority diagnosed at **Stage III or IV**  
  - ~30% in early stages (I or II)  

### ⚕️ Treatment Analysis

- **Treatment Types**:  
  - Chemotherapy, Radiation, Surgery, Immunotherapy (~25% each)  
- **Treatment Delay**:  
  - Varies by stage  
  - Some records show negative delays (treatment before diagnosis)  

### 🏥 Outcome & Mortality

- **Outcomes**:  
  - Majority recovered  
  - ~10% under treatment  
  - ~9.9% deceased  

- **Cause of Death**:  
  - Mainly **cancer complications**  

- **Mortality Trends**:  
  - Increases significantly with later stages  

### 📐 BMI Analysis

- **Average BMI**: ~26 (overweight category)  
- **Categories**:  
  - Normal: ~30%  
  - Overweight: ~35%  
  - Obese: ~20%  
  - Underweight: ~15%  

### 🩺 Physician Comparison

- Variation in outcomes between physicians  
- Recovery and mortality rates differ by doctor  

---

## 📊 Visualizations Included

- Gender, Nationality, Emirate Distribution  
- Age Group Distribution  
- Cancer Type & Stage Distribution  
- Heatmap: Cancer Type vs Stage  
- Treatment Type Distribution  
- Treatment Delay Histogram  
- Average Treatment Delay by Stage  
- Outcome Distribution  
- Alive vs Deceased Patients  
- Cause of Death  
- Mortality by Cancer Stage  
- BMI Distribution  
- BMI Category Breakdown  
- Outcomes by Physician  
- Cancer Outcomes by Type & Stage  

---
