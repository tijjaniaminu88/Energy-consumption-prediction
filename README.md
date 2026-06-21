# Appliance Energy Consumption Prediction

## Project Overview

This project develops a machine learning model for predicting appliance energy consumption in smart buildings using environmental and temporal data.

## Dataset

UCI Appliances Energy Prediction Dataset.

Contains:
- Indoor temperature
- Humidity
- Weather variables
- Appliance energy consumption

## Models Used

- Linear Regression
- Random Forest
- Gradient Boosting

## Evaluation Metrics

- MAE
- RMSE
- R² Score


## How To Run

Install dependencies:

pip install -r requirements.txt

Open:

energy_prediction_model.ipynb

Run cells sequentially.


## Workflow

Dataset → Preprocessing → Feature Engineering → Model Training → Evaluation → Prediction

## Trained Model

the trained Random Forest model file is provided seperately because the file size exceeds the Github upload limit.

Download the trained model here:

https://drive.google.com/file/d/19OU3WK6DkLs12bmZC2Jkseg8qc3jIu9I/view?usp=sharing

After downloading, place the file in:

models/random_forest_model.pkl

The model can be loaded using:

'''python
import joblib

model = joblib.load("models/random_forest_model.pkl") 
