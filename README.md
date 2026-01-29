🚨 Network Intrusion Detection System (IDS)
Data Analytics & Machine Learning Project
📌 Project Overview
This project implements a data-driven Intrusion Detection System (IDS) that analyzes network traffic and classifies connections as normal or malicious. Using the KDD Cup 99 dataset, the project combines data analytics, feature engineering, machine learning, and business-ready visualization to demonstrate how data can be used to detect cybersecurity threats and support decision-making.
The focus is not only on model accuracy, but also on understanding traffic patterns, evaluating model behavior, and communicating insights through dashboards.
🎯 Objectives
Analyze large-scale network traffic data to identify malicious behavior
Apply data preprocessing and exploratory data analysis (EDA) to improve signal quality
Train and compare multiple machine learning models for intrusion detection
Evaluate model performance using classification metrics and confusion matrix analysis
Visualize network risks and model outcomes using Power BI dashboards
🧠 Dataset
KDD Cup 99 Intrusion Detection Dataset
Features include:
Network connection attributes (protocol, service, flags)
Traffic statistics (source bytes, destination bytes, error rates)
Labeled as normal or various attack types (DoS, Probe, R2L, U2R)
🔍 Data Analytics Workflow
1. Data Preprocessing & Feature Engineering
Cleaned and handled missing / infinite values
Encoded categorical variables (protocol_type, service, flag)
Scaled numerical features for model compatibility
Engineered analytical features such as:
Binary attack labels (normal vs attack)
Risk levels based on attack probability
Confusion-matrix categories (True Positive, False Positive, etc.)
2. Exploratory Data Analysis (EDA)
Analyzed distribution of:
Network protocols (TCP, UDP, ICMP)
Services most frequently targeted by attacks
Normal vs malicious traffic proportions
Identified high-risk protocols and services contributing to attack volume
3. Machine Learning Models
Trained and evaluated multiple supervised learning models:
Logistic Regression
Evaluation Metrics:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
4. Model Evaluation & Error Analysis
To enable deeper analysis, model outputs were enriched with:
True Positives
False Positives
False Negatives
True Negatives
This allowed analysis of:
False alarm behavior
Missed attacks
Model reliability across protocols and services
📊 Power BI Dashboard
An interactive Power BI dashboard was created to communicate insights clearly to non-technical stakeholders.
Dashboard Highlights:
Total network connections, detected attacks, and normal traffic
Attack probability and average risk score
Traffic composition by protocol and service
Model performance breakdown using confusion-matrix categories
Interactive filters for protocol, service, and risk level
⚠️ Note: Data transformations and feature engineering were performed in Python prior to visualization due to Power BI Service (online) limitations, reflecting a real-world cloud BI workflow.
🛠️ Tools & Technologies
Python: pandas, NumPy, scikit-learn
Machine Learning: classification models, evaluation metrics
Data Analytics: EDA, feature engineering, performance analysis
Visualization: Power BI (Service)
Environment: Jupyter Notebook (Anaconda)
📈 Key Takeaways
Demonstrates an end-to-end data analytics pipeline, from raw data to insights
Shows practical application of machine learning evaluation in cybersecurity
Highlights ability to work around tool limitations using proper data pipelines
Emphasizes insight generation and storytelling, not just model building
📌 Future Improvements
Add time-based traffic analysis
Compare Power BI dashboards with Tableau
Experiment with ensemble and deep learning models
Deploy model predictions via a lightweight API
👤 Author
Jasleen Kaur
Aspiring Data Analyst | Machine Learning & Analytics Enthusiast
📫 Feel free to connect or explore my other projects!
