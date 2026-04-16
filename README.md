# Student Behavior & Academic Performance Analysis

This project explores the relationship between student classroom behavior, lifestyle habits, and academic outcomes using Exploratory Data Analysis (EDA) and statistical testing.

---

## Objective

To analyze how factors such as study habits, screen time, sleep patterns, and classroom behavior influence:
- Academic performance (CGPA)
- Attention levels
- Academic stress

---

## Dataset

- **Source:** Primary data collected via Google Forms survey  
- **Samples:** 66 student responses  
- **Features:** 18 variables  

### Includes:
- Classroom behavior (participation, seating preference)
- Lifestyle habits (sleep, screen time)
- Academic metrics (CGPA, stress levels)

---

## Data Preprocessing

- Removed irrelevant columns (e.g., timestamp)
- Cleaned inconsistent entries (e.g., "6 hours", "8–9 hours")
- Handled missing values using:
  - Mean imputation
  - Median imputation
- Converted data types for numerical analysis

---

## Exploratory Data Analysis (EDA)

Key observations:
- Most students study **2–5 hours/day**
- Screen time averages around **5–7 hours/day**
- Academic stress levels are generally moderate to high

---

## Statistical Analysis

### Techniques Used:
- **Chi-Square Test (Hypothesis Testing)**
- **Pearson Correlation Analysis**

### Key Results:
- Most relationships showed **p-value > 0.05**
  → No statistically significant association  
- Weak negative correlation between:
  - Phone usage & attention (**-0.16**)  
- Weak relationships between:
  - Sleep vs stress  
  - Screen time vs stress  

---

## Key Insights

- Classroom behavior (seating, participation) showed **no strong impact** on CGPA  
- Lifestyle factors had **weak influence** on stress levels  
- Suggests other hidden factors (motivation, teaching quality) may play a larger role  

---

## Project Structure
