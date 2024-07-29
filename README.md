# Naive Bayes Heart Disease Prediction

This repository contains code to build a Naive Bayes model to predict the presence of heart disease based on a set of medical attributes.

## Dataset

The dataset used for this project contains the following attributes:
- `age`: Age of the patient
- `sex`: Gender of the patient
- `cp`: Chest pain type (4 values)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl
- `restecg`: Resting electrocardiographic results (values 0, 1, 2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
- `target`: Diagnosis of heart disease (0 = no disease, 1 = disease)

## Project Structure

- `NaiveBayes.ipynb`: The Jupyter Notebook containing the code for loading the data, preprocessing, and training the Naive Bayes model.
- `heart.csv`: The dataset used for training and testing the model.

## Requirements

To run the code in this repository, you will need the following packages:

- pandas
- numpy
- scikit-learn
- matplotlib (optional, for visualization)

You can install these packages using pip:

```sh
pip install pandas numpy scikit-learn matplotlib
