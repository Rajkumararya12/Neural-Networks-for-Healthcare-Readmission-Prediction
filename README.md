# Neural Networks for Healthcare Readmission Prediction

## Project Overview
This project develops a neural network model to predict whether a patient is likely to be readmitted to the hospital based on clinical and demographic information. Early prediction of hospital readmission can help healthcare providers improve patient care and reduce healthcare costs.

## Objectives
- Predict patient readmission using a neural network model.
- Perform data preprocessing and feature engineering.
- Train and evaluate the model using performance metrics.
- Compare model performance using accuracy, precision, recall, F1-score, and ROC-AUC.

## Dataset
- **Description:** Each row represents a hospital visit for a patient. The target variable is
`readmitted_30_days` (0 = not readmitted, 1 = readmitted). Other columns include
age, BMI, vitals, chronic conditions, number of previous admissions, length of stay,
lifestyle factors, and insurance type.
## Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```
├── Neural_Network_Readmission.ipynb
├── healthcare_readmission_dataset.csv
├── README.md
└── requirements.txt
```

## Model Workflow
1. Data Loading
2. Data Preprocessing
3. Feature Engineering
4. Data Splitting
5. Neural Network Model Development
6. Model Training
7. Performance Evaluation
8. Prediction

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results
The neural network successfully predicts hospital readmission using patient healthcare records. Performance metrics demonstrate the effectiveness of the model for binary classification.

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Ensemble learning
- Explainable AI (SHAP/LIME)
- Deployment using Flask or Streamlit

## Author
Rajkumar Arya
