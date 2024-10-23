# Diabetes Prediction Using Machine Learning

This project demonstrates how to build a machine learning model to predict diabetes using the Pima Indians Diabetes Database. The model is trained using a Decision Tree classifier and can be used to make predictions about whether a patient is likely to have diabetes based on various medical factors.

## Project Structure

- **diabetes.csv**: This dataset contains the medical data used to train the machine learning model. It includes features such as pregnancies, glucose level, blood pressure, skin thickness, insulin, BMI, diabetes pedigree, and age.
- **Untitled.ipynb**: This Jupyter notebook includes all the steps for preprocessing the data, training the model, evaluating its performance, and making predictions.

## Features

The dataset includes the following features:
- **Pregnancies**: Number of times the patient has been pregnant.
- **Glucose**: Plasma glucose concentration (in mg/dL).
- **Blood Pressure**: Diastolic blood pressure (in mm Hg).
- **Skin Thickness**: Triceps skin fold thickness (in mm).
- **Insulin**: 2-Hour serum insulin (in mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **Diabetes Pedigree Function**: A function which scores likelihood of diabetes based on family history.
- **Age**: The age of the patient in years.
- **Outcome**: Whether the patient has diabetes (1) or not (0) – this is the target variable.

## How to Run the Project

### Prerequisites

To run this project, you need to have the following installed:
- Python 3.7 or above
- Jupyter Notebook

### Steps

1. Clone the repository to your local machine.

2. Open the `Untitled.ipynb` Jupyter notebook.

3. Run all the cells to preprocess the data, train the model, and evaluate its performance.

4. To make a prediction based on user input, modify the input fields (such as pregnancies, glucose, etc.) and run the corresponding cell in the notebook to see the prediction output.

### Prediction Example

You can input your own values into the notebook and the model will predict if the person has diabetes or not. Example code:

pregnancies = 2
glucose = 138
blood_pressure = 80
skin_thickness = 35
insulin = 0
bmi = 30.1
diabetes_pedigree = 0.627
age = 47

### Make predictions based on input
predicted_diabetes = decision_tree.predict([[pregnancies, glucose, blood_pressure, skin_thickness, insulin, bmi, diabetes_pedigree, age]])


The output will inform if the model predicts that the patient has diabetes or not.

## Results

After training the model, you can expect performance metrics like precision, recall, and F1-score, which are generated in the notebook. Additionally, confusion matrices and classification reports are displayed for further insights.

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.
Let me know if you need any changes to this draft or additional details!
