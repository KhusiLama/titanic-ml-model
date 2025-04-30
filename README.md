# Titanic Survival Prediction

This project aims to develop a machine learning model to predict whether a passenger survived the Titanic disaster using data from the famous Kaggle Titanic dataset.

## Dataset

We use the Titanic dataset which contains information such as:
- Passenger class
- Sex
- Age
- Fare
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Port of embarkation

## Objective

To build a classification model that can accurately predict the survival of a passenger using the provided features.

## Key Steps

1. *Data cleaning and preprocessing*
   - Handling missing values (e.g., Age and Fare)
   - Dropping non-informative columns (e.g., Name, Ticket, Cabin)
2. *Feature encoding*
   - Converting categorical variables (e.g., 'Sex' and 'Embarked') into numerical format
3. *Model training*
   - Using *Random Forest Classifier* from scikit-learn
4. *Model evaluation*
   - Calculating accuracy
   - Displaying a confusion matrix

## Visualization

- Confusion matrix heatmap to understand the model’s prediction distribution
- Count plots to visualize survival based on gender and class

## Dependencies

Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
