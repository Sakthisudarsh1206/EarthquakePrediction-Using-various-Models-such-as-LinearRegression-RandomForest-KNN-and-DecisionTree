**Earthquake Magnitude Prediction**

This project focuses on predicting the magnitude of earthquakes using machine learning techniques. The aim is to develop models that can accurately predict the magnitude of earthquakes based on various features such as location coordinates, depth, and other seismic attributes.

**Overview**
The project consists of the following main components:

Data Collection: Earthquake data is collected from the US Geological Survey (USGS) database.
Data Preprocessing: Data is cleaned, missing values are handled, and outliers are identified and treated.
Model Building:
Linear Regression: A basic linear regression model is trained using latitude, longitude, and depth as features to predict earthquake magnitude.
Random Forest Regression: A more complex ensemble model is trained using Random Forest Regression to capture non-linear relationships between features and target.
KNN Regressor: K-Nearest Neighbors Regression model is employed to predict earthquake magnitude based on similar seismic attributes.
Decision Tree Regressor: A decision tree-based model is trained to predict earthquake magnitude.
Model Evaluation: The performance of each model is evaluated using metrics such as Mean Squared Error (MSE) and R-squared score.
Results Analysis: A comparative analysis is conducted to compare the performance of different models with and without outlier removal.


**Dependencies**
The project relies on the following dependencies:
Python 3.x
pandas
numpy
seaborn
matplotlib
scikit-learn

**Usage**
Ensure that the earthquake dataset (usgs_main.csv) is available in the project directory.
Run the EarthQuake_Prediction.ipynb Jupyter Notebook to execute the entire pipeline, including data preprocessing, model training, evaluation, and result analysis.
Experiment with different models and hyperparameters to improve prediction accuracy.
