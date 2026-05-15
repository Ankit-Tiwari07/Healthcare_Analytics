# Healthcare_Analytics

🏥 Healthcare Readmission Prediction

📌 Project Overview

This project focuses on predicting 30-day hospital readmissions for diabetes patients using machine learning techniques. The goal is to help healthcare providers identify high-risk patients early and take preventive actions to improve patient outcomes and reduce hospital costs.

🎯 Objective

Predict whether a patient will be readmitted within 30 days
Identify key risk factors contributing to readmissions
Provide actionable insights for improving healthcare decision-making

📊 Dataset

Source: UCI Machine Learning Repository
Dataset: Diabetes 130-US Hospitals (1999–2008)
Total Records: 101,766
Target Variable: Readmission within 30 days

🧰 Tools & Technologies

Python
Pandas
NumPy
Matplotlib & Seaborn
Scikit-learn

🔄 Project Workflow

1. Data Preprocessing

Handled missing values (imputation & removal)
Encoded categorical variables
Removed irrelevant features

2. Exploratory Data Analysis (EDA)
   
Univariate & Bivariate analysis
Identified trends and correlations
Visualized key insights

3. Feature Engineering
   
Grouped diagnosis categories
Selected important features
Transformed variables for modeling

5. Model Building
   
Applied classification algorithms
Best Model: Random Forest

7. Model Evaluation
   
Accuracy: 75.54%
Precision: 19.49%
Recall: 38.09%
F1 Score: 25.79%
ROC-AUC: 0.65

📈 Key Insights

Patients with prior inpatient admissions have higher readmission risk
Emergency visits strongly correlate with readmissions
Elderly patients (70+) are more likely to be readmitted
Certain conditions like circulatory & respiratory diseases increase risk

⚠️ Challenges Faced

Class imbalance (only ~11% readmissions)
Missing values in key features
High cardinality categorical variables
Trade-off between precision and recall

💡 Business Impact

Identified high-risk patients for targeted interventions
Potential to prevent 600+ readmissions
Estimated multi-million dollar cost savings (~$4.6M net benefit)
Helps hospitals shift from reactive to proactive care

🏥 Recommendations

Implement risk scoring at discharge
Prioritize high-risk patients for follow-up care
Improve discharge planning and patient education
Integrate model into hospital systems (EHR)

🚀 Future Improvements
Apply advanced models (XGBoost, LightGBM)
Improve recall using SMOTE or class balancing
Include additional features (lifestyle, socioeconomic data)
Continuous model monitoring & retraining

📌 Conclusion

This project demonstrates how data analytics and machine learning can be used to predict hospital readmissions, optimize healthcare resources, and improve patient care through data-driven decision-making.

🔗 Author

Ankit Tiwari

Data Analyst
Skilled in Python, SQL, Machine Learning, and Data Analysis
