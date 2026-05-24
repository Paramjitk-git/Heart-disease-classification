# Heart Disease Classification

## About

This project uses machine learning to classify whether a patient has heart disease based on clinical health measurements from the UCI Cleveland Heart Disease dataset.

A Decision Tree classifier was implemented using Python and scikit-learn to analyze patient records and predict the presence of heart disease.

## Features

- Decision Tree classification model
- Data preprocessing and cleaning
- Binary heart disease prediction
- Model evaluation metrics
- Confusion matrix visualization
- Decision tree visualization
- Data analysis using pandas and matplotlib

## Technologies Used

- Python
- pandas
- scikit-learn
- matplotlib
- NumPy

## Dataset

Dataset used:
- UCI Cleveland Heart Disease Dataset

The dataset includes medical attributes such as:
- Age
- Chest pain type
- Blood pressure
- Cholesterol
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Thalassemia results

## Machine Learning Workflow

1. Load and preprocess dataset
2. Remove missing values
3. Convert target values into binary classification
4. Split data into training/testing sets
5. Train Decision Tree classifier
6. Evaluate model performance
7. Generate visualizations and metrics

## Results

Model evaluation results:
- Accuracy: 78.9%
- Precision: 78.0%
- Recall: 76.2%

## Files

- `classification_project.py` → Main machine learning implementation
- `processed.cleveland.data` → Dataset file
- `Heart_Disease_Classification_Final.pdf` → Project presentation/report

## Academic Context

Developed as part of a machine learning/data analysis academic project using supervised classification techniques and medical datasets.

## Future Improvements

- Compare multiple machine learning models
- Hyperparameter optimization
- Cross-validation
- ROC curve analysis
- Feature importance analysis
- Web-based prediction interface
