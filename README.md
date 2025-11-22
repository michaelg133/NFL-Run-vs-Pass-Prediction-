# NFL-Run-vs-Pass-Prediction-

## Overview
This project uses machine learning to predict whether an NFL offensive play will be a RUN or a PASS before the ball is snapped.  
The system analyzes structured game information such as down, distance, yard line, quarter, score differential, formation, and personnel groupings.  
The goal is to understand how predictable offensive play-calling is using only pre-snap context.

This milestone includes the initial setup for the project along with example input and output data.

## Authors
Michael Gomes  
https://github.com/michaelg133

## Example Input and Output

| Input (first few rows of dataset) | Output (labels) |
|----------------------------------|-----------------|
| ![Input](input_example.png)      | ![Output](output_example.png) |

## Dataset
Source: Kaggle – NFL Play-by-Play (2009–2018)  
Target Variable: PlayType (RUN or PASS)  
The dataset includes pre-snap features such as down, distance, formation, personnel, and field position.

## Baseline Model
The baseline model for this project will be a Logistic Regression classifier using features such as:
- Down  
- Distance  
- Yard Line  

This will provide a simple, interpretable starting point.

## Planned Main Model
The main model will likely be one of the following:
- Gradient Boosting (XGBoost or LightGBM)
- LSTM sequence model (if sequential features are added)

These models can capture more complex relationships in the data.

## Evaluation Metrics
The system will be evaluated using:
- Accuracy
- F1 Score
- Confusion Matrix

These metrics are appropriate for a binary classification task.

## Repository Contents
- README.md  
- input_example.png  
- output_example.png  

More project files will be added in future milestones.
