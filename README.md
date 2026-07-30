# Diabetes Prediction System

## Overview
The Diabetes Prediction System is a Machine Learning project developed using Python to predict whether a person has diabetes based on medical attributes. The project uses the Logistic Regression algorithm for binary classification.

## Features
- Loads the diabetes dataset using Pandas.
- Checks dataset information and missing values.
- Converts the `Outcome` column into numeric values.
- Splits the dataset into training and testing sets.
- Trains a Logistic Regression model.
- Evaluates the model using accuracy score.
- Predicts whether a patient has diabetes based on input values.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Google Colab

## Machine Learning Algorithm
- Logistic Regression

## Dataset
- `diabetes.csv.xls`

## Project Structure
```
DiabetesPredictionSystem.ipynb
diabetes.csv.xls
README.md
```

## Workflow
1. Import required libraries.
2. Load the diabetes dataset.
3. Explore the dataset.
4. Check for missing values.
5. Convert the target (`Outcome`) into numeric values.
6. Split the data into training and testing sets.
7. Train the Logistic Regression model.
8. Calculate training accuracy.
9. Predict whether a patient has diabetes using sample input data.

## Sample Input
```
(148, 75, 35, 0, 33.6, 0.627)
```

## Output
The model predicts one of the following:
- **Diabetes**
- **No Diabetes**

## Libraries Used
- NumPy
- Pandas
- scikit-learn

## How to Run
1. Open `DiabetesPredictionSystem.ipynb` in Google Colab or Jupyter Notebook.
2. Place `diabetes.csv.xls` in the same folder as the notebook.
3. Run all the cells in order.
4. Enter input values to obtain the diabetes prediction.

## Future Enhancements
- Improve model accuracy using additional machine learning algorithms.
- Develop a web application using Flask or Streamlit.
- Add graphical data visualizations and performance comparisons.

## License
This project is created for educational and learning purposes.
