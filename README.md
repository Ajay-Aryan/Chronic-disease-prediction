
# Chronic Disease Prediction

This project aims to predict the risk of three chronic diseases: Heart Disease, Diabetes, and Chronic Kidney Disease (CKD). It utilizes machine learning models trained on datasets containing relevant medical information to provide predictions based on user input.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Models and Datasets](#models-and-datasets)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Chronic diseases pose a significant health risk globally, contributing to a substantial portion of morbidity and mortality. Early detection and prediction of these diseases can aid in timely interventions and improve patient outcomes. This project offers predictive models for three prevalent chronic conditions: Heart Disease, Diabetes, and Chronic Kidney Disease.

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy

## How to Use
### Prerequisites
Ensure you have Python installed on your system along with the required libraries mentioned in the `requirements.txt` file.

### Installation
1. Clone this repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.

### Running the Application
1. Navigate to the directory containing the project files.
2. Run the individual Python scripts for each disease prediction:
    - `heart_disease_prediction.py`
    - `diabetes_prediction.py`
    - `kidney_disease_prediction.py`

## Models and Datasets
- **Heart Disease Prediction:**
    - Model: Naive Bayes Classifier
    - Dataset: `heart.csv`
- **Diabetes Prediction:**
    - Models: K-Nearest Neighbors (KNN) Classifier, Naive Bayes Classifier
    - Dataset: `diabetes_prediction_dataset.csv`
- **Chronic Kidney Disease (CKD) Prediction:**
    - Models: K-Nearest Neighbors (KNN) Classifier, Naive Bayes Classifier
    - Dataset: `chronic_kidney_disease_full.xlsx`

## Results
- Heart Disease Prediction:
    - Provides risk assessment based on user input.
- Diabetes Prediction:
    - Offers prediction of diabetes risk based on user-provided medical data.
- Chronic Kidney Disease (CKD) Prediction:
    - Predicts the likelihood of CKD based on various medical parameters provided by the user.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests for any enhancements or bug fixes.
