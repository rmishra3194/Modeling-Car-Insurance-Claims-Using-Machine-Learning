🎯 Business Problem
The Los Angeles Police Department (LAPD) sought to transition from a reactive crime response model to a proactive, data-driven strategy. This project leverages machine learning to not only understand historical crime patterns but also to build a predictive model for forecasting crime types, enabling optimal resource allocation and targeted patrol strategies.

📊 Project Overview
This end-to-end data science project involves:

Exploratory Data Analysis (EDA) to uncover spatiotemporal and demographic trends.

Feature Engineering to create predictive features from raw data.

Machine Learning modeling using a Random Forest classifier to predict crime types.

Actionable Insights delivered to inform LAPD's strategic decision-making.

📁 Dataset
The dataset contains over 200,000 crime incidents from Los Angeles Open Data. Key features include:

Temporal: Date and time of occurrence (DATE OCC, TIME OCC)

Geographic: 21 Geographic Areas or Patrol Divisions (AREA NAME)

Demographic: Victim age, sex, and descent (Vict Age, Vict Sex, Vict Descent)

Incident Type: Crime description (Crm Cd Desc)

🛠️ Tech Stack
Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

Machine Learning: RandomForestClassifier, Logistic Regression, Feature Engineering, Model Evaluation

🔍 Key Steps & Methodology
Data Cleaning & Preprocessing

Handled missing values and parsed datetime features.

Engineered new features like HOUR OCC (hour of occurrence) from timestamps.

Exploratory Data Analysis (EDA)

Uncovered that crime peaks at 12 PM (noon), contrary to the common assumption of nighttime peaks.

Identified Central LA as the primary hotspot for nighttime crimes (10 PM - 4 AM).

Found that adults aged 26-34 are the most frequently targeted demographic.

Machine Learning Modeling

Objective: Predict the type of crime (Crm Cd Desc) based on time, location, and victim profile.

Model: Built and evaluated a RandomForestClassifier from sklearn.

Result: Achieved an accuracy of 88.5% (a significant improvement over random guessing given the multi-class problem with 100+ crime types).

Feature Importance: Analysis confirmed HOUR OCC and AREA NAME as the top predictors, validating EDA findings.

Insights & Recommendations

Resource Allocation: Recommend increasing patrols in the Central area during night hours and city-wide around noon.

Public Strategy: Suggest tailoring awareness campaigns for the 26-34 age demographic.

Foundation for Proactive Policing: Provides a data-backed foundation for daily forecast models of high-risk areas.

📈 Results
Delivered Critical Insights: Provided LAPD command staff with a data-driven profile of crime patterns.

Built a Predictive Foundation: Developed a model with 88.5% accuracy for predicting crime type.

Identified Key Drivers: Empirically validated time and location as the strongest predictors of crime.

Enabled Proactive Strategy: Outlined a clear path for the LAPD to move from reactive to proactive policing.
