# Iris Flower Classification

## Project Overview
The Iris Flower Classification project is a Machine Learning classification project that predicts the species of an iris flower based on its flower measurements. The model classifies flowers into three species:

1. Iris-setosa
2. Iris-versicolor
3. Iris-virginica

The project was implemented using Python and Machine Learning libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Pickle

## Dataset Information
The dataset contains flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Variable:
- Species

## Steps Performed
1. Data Loading
Loaded dataset using Pandas
Checked rows, columns, and data types
2. Data Analysis
Checked missing values
Performed statistical analysis using describe()
Verified dataset balance using value_counts()
3. Data Visualization
Created count plots
Generated pair plots
Generated correlation heatmap

### Machine Learning Models Used
- Logistic Regression
- Decision Tree 

### Model Training
- Split dataset into training and testing sets
- Trained models using training data
- Evaluated models using testing data

### Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report
- The models achieved high accuracy because the dataset is clean, balanced, and easy to classify.

### Model Saving and Prediction
- Saved trained model using Pickle
- Loaded saved model successfully
- Made predictions using custom flower measurements

## Observations
- Iris-setosa was clearly distinguishable
- Iris-versicolor and Iris-virginica showed slight overlap
- Petal length and petal width had strong positive correlation

## Conclusion
This project helped in understanding the complete Machine Learning workflow including:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training
- Model evaluation
- Prediction using trained models
- Saving and loading ML models
