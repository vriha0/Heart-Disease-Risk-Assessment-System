
# Intelligent Heart Disease Risk Assessment System

## Overview
The Intelligent Heart Disease Risk Assessment System is an AI‑powered clinical decision support application that predicts the likelihood of heart disease using patient medical parameters. The system combines machine learning and an interactive web interface to provide real‑time risk analysis and interpretable probability output.

The objective of this project is to demonstrate an end‑to‑end machine learning deployment pipeline — from data preprocessing and model training to a publicly accessible web application.

This application is designed as an educational healthcare support tool and not as a substitute for professional medical diagnosis.

---

## Objectives
• Predict heart disease risk using clinical features  
• Provide probability‑based interpretation rather than only binary output  
• Implement a full machine learning pipeline  
• Deploy the model as an interactive web application  
• Demonstrate practical AI usage in healthcare analytics

---

## Technology Stack

| Component | Technology Used |
|----------|----------|
| Programming Language | Python |
| Machine Learning | Scikit‑Learn |
| Data Processing | Pandas, NumPy |
| User Interface | Streamlit |
| Model Storage | Pickle |
| Deployment | Streamlit Cloud |

---

## System Workflow

1. The user enters patient clinical data in the web interface.
2. Inputs are validated and structured into a dataset format.
3. Data is converted into a Pandas DataFrame matching the training schema.
4. The saved machine learning pipeline processes the input.
5. The model predicts:
   - Disease classification (Risk / No Risk)
   - Probability of heart disease
6. The result is visualized in the interface with risk interpretation and recommendation.

---
## Input Features

The prediction model uses the following medical parameters:

- Age
- Gender
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate Achieved
- Exercise‑Induced Angina
- ST Depression (Oldpeak)
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia Type

---
## Machine Learning Model

The system uses a supervised classification approach.

Key implementation details:
- Scikit‑Learn Pipeline for preprocessing + prediction
- ColumnTransformer for handling feature transformations
- Probability‑based prediction using `predict_proba()`

### Evaluation Metrics
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1‑Score

---

## Application Features
• Interactive clinical input form  
• Real‑time prediction  
• Risk percentage display  
• Visual risk indicator (progress bar)  
• Basic clinical recommendation  
• Publicly deployed web app

---

## System Architecture

User Input  
↓  
Streamlit Web Interface  
↓  
Input Validation & Feature Processing  
↓  
Pandas DataFrame Construction  
↓  
Machine Learning Pipeline  
↓  
Prediction & Probability Calculation  
↓  
Risk Visualization & Recommendation

---

## Running the Project Locally

### 1. Clone the Repository git clone https://github.com/krishna-dave206/Heart-Disease-Risk-Assessment-System.git
### 2. Install Dependencies                                                                                                                                                                                                                                                             pip install -r requirements.txt 
### 3. Run the Application                                                                                                                                                                                                                                                                streamlit run app.py
---

## Deployment
The application is deployed using Streamlit Cloud and accessible through the public project link provided in submission.

---

## Disclaimer
This project is created for educational and research purposes only.  
It should not be used for real medical diagnosis or treatment decisions. Always consult a qualified healthcare professional.

---

## Team Members
Krishna Dave  
Vriha Dholiya  
Rishita Boisnobi


