# 🧠 Stroke Prediction using Machine Learning

This data science project aims to predict the likelihood of a patient experiencing a stroke based on various health and lifestyle factors such as gender, age, existing diseases, and smoking status. By leveraging machine learning techniques, the model provides insights into stroke risk, which can help in early detection and preventive healthcare.

📌 Problem Statement

According to the World Health Organization (WHO), stroke is the second leading cause of death worldwide, accounting for approximately 11% of all deaths. Identifying individuals at high risk can significantly reduce the impact of strokes through timely intervention.

This project builds a predictive model using patient data to estimate stroke risk.

📊 Dataset Information

The dataset contains medical and demographic information of patients, with the following features:

id: Unique identifier

gender: "Male", "Female", or "Other"

age: Age of the patient

hypertension: 0 → no hypertension, 1 → has hypertension

heart_disease: 0 → no heart disease, 1 → has heart disease

ever_married: "No" or "Yes"

work_type: "Children", "Govt_job", "Never_worked", "Private", "Self-employed"

Residence_type: "Rural" or "Urban"

avg_glucose_level: Average glucose level in blood

bmi: Body Mass Index

smoking_status: "Formerly smoked", "Never smoked", "Smokes", "Unknown"

stroke: 1 → patient had a stroke, 0 → did not have a stroke

⚙️ Methodology

### Data Preprocessing

Handling missing values

Encoding categorical variables

Normalization/standardization of numerical features

### Exploratory Data Analysis (EDA)

Distribution analysis

Correlation heatmaps

Feature importance visualization

### Model Development

Train/test split

Classification models such as:

Logistic Regression

K Nearest Neighbour

Decision Tree

Support Vector Machine (SVM)

### Model Evaluation

Accuracy, Precision, Recall, F1-score

ROC-AUC curve

🚀 Tech Stack

Programming Language: Python 🐍

Libraries:

pandas, numpy → Data manipulation

matplotlib, seaborn → Data visualization

scikit-learn → Machine learning models

📈 Expected Outcomes

A robust predictive model for stroke risk

Insights into the most influential risk factors

Data-driven recommendations for preventive healthcare

📌 Future Work

Deploying the model using Flask/Django or Streamlit for real-time predictions

Enhancing model accuracy with deep learning techniques

Expanding the dataset for improved generalization

🙌 Acknowledgements

World Health Organization (WHO) for context on stroke statistics

📝 License

This project is licensed under the MIT License - see the LICENSE
 file for details.
