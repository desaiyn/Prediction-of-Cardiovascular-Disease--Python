CardioHealth Insights: Predictive Model for Cardiovascular Disease


Project Overview:
Cardiovascular diseases are a leading cause of global mortality, with preventive
measures crucial for public health. This project employs Machine Learning (ML)
to predict the presence or absence of cardiovascular disease based on individual
health data.
Problem Statement:
Develop a predictive model that analyzes health information to identify individuals
at risk of cardiovascular disease, facilitating early intervention and personalized
health recommendations.
Why it Matters:
Cardiovascular diseases, including ischemic heart disease, contribute to 32% of
global deaths. Early detection through ML can empower individuals to adopt
proactive health measures, potentially saving lives.
Dataset Details:
The dataset contains health information for 70,000 individuals, with features such
as age, gender, blood pressure, cholesterol levels, and lifestyle habits. The goal is
to predict the presence or absence of cardiovascular disease (binary classification).
Features:
- Age (in days)
- Height (in cm)
- Weight (in kg)
- Gender (categorical code)
- Systolic Blood Pressure (ap_hi)
- Diastolic Blood Pressure (ap_lo)
- Cholesterol (1: normal, 2: above normal, 3: well above normal)
- Glucose (1: normal, 2: above normal, 3: well above normal)
- Smoking (binary)
- Alcohol Consumption (binary)
- Physical Activity (binary)
Target Variable:
- Cardio (binary) - Presence or absence of cardiovascular disease
Model Selection:
Two models were chosen for their efficiency and speed:
1. Decision Tree Classifier: Efficient and interpretable, suitable for binary
classification tasks.
2. MLP Classifier (Multi-layer Perceptron): Offers high accuracy and handles
large-scale data efficiently.
Data Split:
The dataset is split into training (70%) and testing (30%) sets for model evaluation.
Implementation:
The project utilizes Python, scikit-learn, and MLP Classifier for training and
evaluation. Decision Tree provides interpretability, while MLP Classifier focuses
on accuracy.
GitHub Project Description:
This GitHub repository contains code and documentation for a Cardiovascular
Disease Prediction model using Machine Learning. It includes:
- Data Exploration: Jupyter notebooks exploring the dataset and visualizing key
insights.
- Model Development: Implementation of Decision Tree and MLP Classifier for
predictive modeling.
- Evaluation Metrics: Assessment of model performance using accuracy, precision,
recall, and F1-score.
- Project Documentation: Detailed explanation of the dataset, model selection, and
implementation steps.
- Results: Summary of findings and insights from the trained models.
Future Work:
Continuous improvement and model refinement based on new data and emerging
research to enhance prediction accuracy.
Contributions:
Contributions and feedback from the open-source community are welcome to
further enhance the project's impact on cardiovascular health.
Let's work together to predict and prevent cardiovascular diseases!
