# MIMIC-Predictive-Modeling

Final Project for course Biostats823 (2020 fall) at Duke : Predictive Modeling with MIMIC Dataset


## Team Info

**Team Name** : Team One

**Team Members** (in alphabetical order):

- Feng, Yuan - Master of Interdisciplinary Data Sciencse, Duke University - [GitHub: yuan-feng1](https://github.com/yuan-feng1)
- Han, Mengyue - Master of Biostatistics, Duke University - [GitHub: zhhmyz](https://github.com/zhhmyz)
- Qiu, Zhi (Heather) - Master of Statistical Science, Duke University - [GitHub: ZhiQiu976](https://github.com/ZhiQiu976)
- Xu, Zhenhui - Master of Biostatistics, Duke University - [GitHub: zhenhuixu](https://github.com/zhenhuixu)


## Data

[MIMIC](https://mimic.physionet.org)
- Deidentified health data associated with ~60,000 ICU admissions (53,432 adult patients and 8,100 neonatal patients) from June 2001 to October 2012
- Includes demographics, vital signs, laboratory tests, medications, and more


## Project

### Project Objective

- Purpose
    * Predict Patients' Discharge Location
    * More specifically, a classification system built with machine learning models to predict the discharge location of patients with ICU admission based on their demographics, vital signs, laboratory tests, medications information, etc.
    
- Audience
    * Our platform aims to serve the hospital administration team, the inquisitive researchers and curious patients
    * The multi-page dashboard serves as a tool to monitor occupancy and clinical results of patients, and provide comprehensive demonstration
    * The online ML prediction model provides real-time results of clinical outcome, which will aid in decision-making process of patients and doctors

- Benefits
    * Provide information about hospital utilizations, such as hospital bed occupancy and other key resources as a clinical decision system
    * Predict clinicians of the mortality rate of patients at the admission of hospital so health providers can be well informed as they perform clinical procedures
    * Display the predictions by dashboard and inform the clinicians of the overall trend of hospital utilizations.
    * Decrease the risk of adverse hospital-acquired events, and improve scheduling and satisfaction for patients
    
- Data Product
    - Multi-Page Dashboard held on Cloud Platform
    - Online ML Algorithm for Real-Time Prediction
    - [Deployed Dashboard](https://bios823-mimic-dashboard.ue.r.appspot.com/) / [GitHub Link for Construction of Dashboard](https://github.com/biostats823-final-project/MIMIC-Dashboard)


### Project Plan

- Data Plan
    - Extract, Load, Transform
    - Data cleaning, check for missing values & outliers, fix if unbanlanced data
    - EDA
    - Feature selection
    
- ML Plan
    - Different model training (Dummy, Naive Bayers, SVM, Random Forst, Xgboost, etc.)
    - Model selection based on accuracy and a series of popular metrics
    - Model evaluation 
    - Model visualization

- Operations Plan
    - Branches on GitHub, version control with git
    - Logging can be retrived from commits comments and ReadMe updates

- Technology Stack
    - Database Management: SQL
    - Online cloud platforms: GCP
    - Data processing: pandas, numpy, missingno
    - Visualization: pyplot, seaborn
    - Machine Learning Implementation: scikit-learn, optuna, xgboost
    - Deployment and Interaction: dash


### Team Member Responsibility

- Biweekly meeting and continuous cooperation
- All teammates would participated in the data exploration stage (ETL, EDA, feature selection)
- Each team member would take chage of some of the ML models in the ML exploration stage
- Equally split tasks for write-up, code cleaning, dashboard construction and cloud platform deployment.






