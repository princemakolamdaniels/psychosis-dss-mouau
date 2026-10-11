# Decision Support System for Psychosis Diagnosis
### MOUAU Final Year Project 2023 - 85% Accuracy | Seeking MSc Thesis 2027

**Author:** Prince Nkemakolam Daniels  
**University:** Michael Okpara University of Agriculture Umudike (MOUAU), Abia State, Nigeria  
**Degree:** BSc Computer Science (2023)  
**Grade:** Second Class Lower (2.2) - Project Grade: B+ (75%)  
**Email:** Princemakolamdaniels@gmail.com  
**GitHub:** https://github.com/princemakolamdaniels/psychosis-dss-mouau  
**Location:** Port Harcourt, Rivers State, Nigeria

---

## 🧠 Project Overview
Built an AI-powered Clinical Decision Support System (DSS) to assist clinicians in early detection of psychosis, addressing the critical shortage of psychiatrists in rural Nigeria. System combines expert medical knowledge (DSM-5 criteria) with Machine Learning.

**Why this matters in Nigeria:** 1 psychiatrist per 1 million people in rural areas. Diagnosis is subjective and delayed 6-12 months.

## 🎯 Problem Statement
- Psychosis affects 3% of global population
- In Nigeria, limited access to mental health specialists
- Current diagnosis relies on subjective clinician judgment
- Need for low-cost, explainable, culturally sensitive screening tool

## 💡 My Solution
Developed hybrid system combining:

1. **Rule-Based Expert System:** Encoded DSM-5 criteria for psychosis (hallucinations, delusions, disorganized speech, negative symptoms)
2. **Machine Learning Model:** Random Forest classifier trained on 500 anonymized cases
3. **Web Dashboard:** Flask-based interface for clinicians

### Key Features:
- Symptom checklist: Auditory/visual hallucinations, persecutory delusions, speech disorganization, anhedonia, family history
- Risk stratification: Low / Medium / High (with recommended actions)
- Explainable output: Shows which symptoms contributed to prediction
- MySQL database for secure patient records
- Offline capable for rural clinics with poor internet

## 📊 Results & Performance
- **Accuracy: 85%**
- Precision: 82%
- Recall: 87%
- F1-Score: 84%
- Model: Random Forest (best) vs SVM (81%) vs Logistic Regression (78%)
- Validation: 5-fold cross-validation
- Dataset: 500 cases (300 psychosis, 200 control) - anonymized from literature + synthetic augmentation

## 🛠️ Technologies Used
- **Language:** Python 3.8
- **ML Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib
- **Database:** MySQL
- **Web Framework:** Flask
- **Tools:** Jupyter Notebook, VS Code, Git, MySQL Workbench

- Supervisor: Dr Mc. okoronkwo
- 
