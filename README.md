# Hospital-Readmission-Analysis
This project analyzes hospital data to find causes of patient readmissions and predict high-risk cases using machine learning, helping hospitals improve care, reduce costs, and plan effective follow-ups.

# Hospital Readmission Analysis

###  Project Overview
This project analyzes hospital admission data to identify key factors influencing patient readmissions and predict high-risk cases. Using exploratory analysis and machine learning, it uncovers insights to reduce readmission rates, improve patient care, and support hospital decision-making for better resource planning and patient outcomes.

---

###  Objectives
- Analyze patterns in patient admissions and readmissions  
- Identify key drivers contributing to high readmission rates  
- Predict patients at risk using ML models  
- Support proactive follow-up and care decisions  

---

###  Dataset
- Source: Hospital Admission Records  
- Target Variable: `readmitted` (1 = Yes, 0 = No)  
- Features include demographics, diagnoses, stay duration, and visit history

---

###  Tech Stack
| Tool | Purpose |
|--------|---------|
| Python | Data Analysis & Modeling |
| Pandas, NumPy | Data Wrangling |
| Matplotlib, Seaborn | Visualization |
| Scikit-Learn | Machine Learning |

---

###  Steps Performed
1. Data Cleaning & Preprocessing  
2. Feature Engineering (LACE score, visit metrics, LOS, etc.)  
3. Exploratory Data Analysis (patterns & trends)  
4. Machine Learning (Logistic Regression, Random Forest)  
5. Risk Scoring & High-Risk Patient Export  

---

###  ML Models Used
| Model | Purpose |
|---------|---------|
| Logistic Regression | Baseline prediction |
| Random Forest | Final risk model |

---

###  Key Outcomes
- Identified major drivers of readmission  
- Built predictive model to flag high-risk patients  
- Exported top high-risk cases for intervention  
