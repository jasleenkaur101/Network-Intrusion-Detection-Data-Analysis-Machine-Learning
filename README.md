# Network Intrusion Detection System (IDS)
## Cyber Data Analytics & Machine Learning Project

## Project Overview
This project implements a data-driven Intrusion Detection System (IDS) that analyzes network traffic and classifies connections as normal or malicious. Using the KDD Cup 99 dataset, the project combines data analytics, feature engineering, machine learning, and visualization to demonstrate how data can be used to detect cybersecurity threats and support decision-making.

The project focuses not only on model accuracy but also on understanding traffic patterns, evaluating model behavior, and communicating insights through dashboards.

---

## Objectives
- Analyze large-scale network traffic data to identify malicious behavior  
- Apply data preprocessing and exploratory data analysis (EDA) to improve data quality  
- Train and compare multiple machine learning models for intrusion detection  
- Evaluate model performance using classification metrics and confusion matrix analysis  
- Visualize network risks and model outcomes using Power BI dashboards  

---

## Dataset
- KDD Cup 99 Intrusion Detection Dataset  
- Features include network protocol information, service types, traffic statistics, and labeled attack categories  
- Traffic classified as normal or attack types such as DoS, Probe, R2L, and U2R  

---

## Data Analytics Workflow

### Data Preprocessing & Feature Engineering
- Cleaned and handled missing and infinite values  
- Encoded categorical variables (protocol_type, service, flag)  
- Scaled numerical features  
- Engineered analytical features including:
  - Binary attack labels (normal vs attack)
  - Risk levels based on attack probability
  - Confusion matrix categories (True Positive, False Positive, False Negative, True Negative)

---

### Exploratory Data Analysis (EDA)
- Analyzed distribution of network protocols and services  
- Examined normal vs malicious traffic proportions  
- Identified high-risk services and protocols contributing to attack frequency  

---

### Machine Learning Models
The following models were trained and evaluated:
- Logistic Regression  
- Naive Bayes  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

Evaluation metrics included:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

### Model Evaluation & Error Analysis
- Generated confusion-matrix-based features to analyze model prediction behavior  
- Analyzed false positives and false negatives to assess model reliability  
- Used evaluation results to support data-driven insights  

---

## Power BI Dashboard
An interactive Power BI dashboard was developed to visualize:
- Total network connections and detected attacks  
- Attack probability and risk distribution  
- Traffic breakdown by protocol and service  
- Model performance using confusion matrix categories  

Note: Data preprocessing and feature engineering were performed in Python prior to visualization due to Power BI Service limitations.

---

## Tools & Technologies
- Python (pandas, NumPy, scikit-learn)  
- Data Analytics and Exploratory Data Analysis  
- Machine Learning (classification models)  
- Power BI (Service)  
- Jupyter Notebook (Anaconda)  

---

## Key Takeaways
- Demonstrates an end-to-end data analytics pipeline from raw data to insights  
- Highlights practical application of machine learning evaluation in cybersecurity  
- Shows ability to communicate analytical insights through dashboards  
- Reflects real-world data workflows and tool limitations  
 

---

## Author
Jasleen Kaur  
Aspiring Data Analyst | Machine Learning & Data Analytics
