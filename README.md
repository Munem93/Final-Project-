# Chronic Kidney Disease Stage Prediction

This project aims to develop a machine learning model to predict the stage of chronic kidney disease (CKD) based on the levels of ACR (Albumin-to-Creatinine Ratio) and eGFR (Estimated Glomerular Filtration Rate). The dataset used for this project consists of the following features: Age, Gender, Revvd wait days for the first appointment, ACR, Creatinine result, eGFR, and Urea.

## Project Objectives:
- Develop a machine learning model to predict the stage of CKD using ACR and eGFR.
- Preprocess the dataset by adding the CKD stage column and perform train-test split for model training and evaluation.
- Evaluate the performance of different machine learning algorithms and select the best-performing model.
- Provide insights into the importance of ACR and eGFR in predicting CKD stage and their impact on patient management and treatment decisions.
- Investigate the potential of developing a prediction model using the kidney failure risk equation incorporating age, gender, ACR, and eGFR for predicting the risk of dialysis or kidney therapy.

## Benefits of this Project on the Practice:
- Early Detection: Timely detection of CKD can lead to early intervention and improved patient outcomes.
- Personalized Treatment: Accurate prediction of CKD stage allows for tailored treatment plans based on the severity of the disease.
- Efficient Resource Allocation: Identifying patients at a higher risk of progressing to advanced stages of CKD helps in allocating appropriate resources and interventions.
- Research Potential: The dataset and model created for this project can be utilized for future research on predicting the risk of dialysis or kidney therapy using the kidney failure risk equation.

## Implementation Steps:
1. Data Preprocessing: Clean the dataset, handle missing values, and add the CKD stage column based on ACR and eGFR values.
2. Train-Test Split: Split the dataset into training and testing subsets for model training and evaluation.
3. Model Selection: Evaluate the performance of various machine learning algorithms (e.g., decision trees, random forests, logistic regression, support vector machines) and select the best-performing model for
