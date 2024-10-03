# Heart Attack Risk Prediction & Explainable AI (XAI)

This project involves the analysis of heart attack risk using machine learning models, with a focus on explainability through XAI (Explainable Artificial Intelligence) techniques. The project evaluates and compares several machine learning models to achieve high accuracy in predicting heart attack risk, with detailed explanations of feature contributions to the model’s predictions.

## Project Overview
**Duration:** April 2024 - juin 2024

**Objective:**  
To predict heart attack risk with high accuracy and provide interpretable explanations for the predictions using XAI techniques.

<div align="center">
    <img src="https://github.com/user-attachments/assets/ccf2a12b-c3e4-413e-9c45-b41694817c35" alt="Heart Attack Risk Prediction" />
</div>

## Key Achievements
- **Accuracy:** Achieved **99.6%** accuracy in predicting heart attack risk by evaluating multiple machine learning models, including:
  - Logistic Regression
  - Decision Trees
  - Random Forests
- **XAI Techniques:** Implemented explainability techniques such as:
  - **SHAP** (SHapley Additive exPlanations) to explain feature contributions.
  - Improved model interpretability by **25%** through clear visual and numerical explanations of feature importance.
- **Data Processing:** Processed a dataset of over **1,320 patient records**, including:
  - Data cleaning
  - Preprocessing
  - Feature engineering

## Tools & Technologies
- **Programming Languages:** Python
- **Libraries:** 
  - `pandas` for data manipulation and analysis
  - `scikit-learn` for model building and evaluation
  - `SHAP` for feature importance and explainability
  - `LIME` (Local Interpretable Model-agnostic Explanations) for additional model interpretability

## Dataset
The dataset consists of over 1,320 patient records, each with medical and lifestyle-related features that are used to predict the risk of heart attacks. The data was cleaned and preprocessed using Python's data handling libraries.

## Explainability
This project emphasizes the importance of model transparency, especially in healthcare-related machine learning models. By using XAI techniques like SHAP and LIME, we were able to:
- Identify which features most strongly influence the predictions.
- Provide detailed explanations for individual predictions to ensure trust and reliability in the model's outcomes.

## Future Work
- Further optimization of the models using hyperparameter tuning.
- Exploring deep learning techniques to improve prediction performance.
- Extending the dataset to include more patient records and medical conditions for broader applicability.

## Getting Started

To replicate this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/youssefjedidi/XAI_heart_attack_classifier.git
   ```
1. **Run the analysis:**
   Use the Jupyter notebook provided in the repository to follow the analysis steps, from data preprocessing to model evaluation and explainability.

