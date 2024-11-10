# Air Pollution and Cancer Stage Prediction

![image](https://cdn-assets-eu.frontify.com/s3/frontify-enterprise-files-eu/eyJvYXV0aCI6eyJjbGllbnRfaWQiOiJjbGllbnQtY2hkcnR4NWphaHV0Y2hsdiJ9LCJwYXRoIjoiaWhoLWhlYWx0aGNhcmUtYmVyaGFkXC9maWxlXC9TZDdSWHNVc296YU1OcDVUS1NGZS5qcGcifQ:ihh-healthcare-berhad:3UnWSiHh7OJoyloGUOWG64SKUTdKFnSx7sY5d1IrFN0?width=854&height=480&crop=fp&fp=0.5%2C0.5&fp_zoom=1)

## Project Overview

The goal of this project is to investigate the potential relationship of, for example: spiders, edema, cholesterol and tryglicerides to the progression of liver cirrhosis, using medical data. The analysis leverages machine learning techniques to predict the stage of cirrhosis based on the data.

## Project Steps

### 1. Importing Libraries
At the start of the project, essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, TensorFlow and Keras are imported for data processing, visualization, and building machine learning models.

### 2. Loading and Preliminary Data Analysis
Data is loaded from a CSV file. Preliminary analysis includes displaying the first few rows of the dataset, generating descriptive statistics, and reviewing information about columns and data types.

### 3. Data Cleaning
The data is cleaned by removing duplicates and checking for missing values to avoid errors in further analysis.

### 4. Target Variable Encoding
The target variable, i.e., the cirrhosis stage (`Stage`), is encoded into numerical values so it can be used in machine learning models. No columns were removed, because they all have impact on the stage of cirrhosis.

### 5. Data Visualization
The data is visualized to better understand the distribution of variables and the correlation between them. Techniques such as pie charts are used to show the distribution of cirrhosis stages, and heatmaps are used to display correlations between variables.

### 6. Building Machine Learning Models
Our model is a neural network based on an MLP (Multi-Layer Perceptron) architecture with Dropout. We introduce appropriate densities, which are powers of two, reducing them by half at each layer until reaching the final density of 3, as we have three outputs. We use the RELU activation function for these layers, followed by SOFTMAX at the end. Between the dense layers, we apply Dropout with varying values (typically between 0.3 and 0.1).

This model are trained and tested on the dataset to predict the best stage of cirrhosis.

### 7. Model Evaluation
Models are evaluated using various metrics, such as confusion matrices, classification reports, and accuracy scores. Thanks to this, we can determine the optimal dropout value for our model, as well as the ideal initial density for the layers

### 8. Conclusions
Based on the results of the analysis, conclusions are drawn between physical and neurological symptoms and liver cirrhosis and/or HCV progression. Additionally, the performance of different machine learning models in predicting liver cirrhosis stages is evaluated.

## Potential Applications

The results of this project can be used to:

- Raise awareness of HCV and/or cirrhosis testing when symptoms are noticed
- Help healthcare professionals identify patients at higher risk of advanced stages of cirrhosis and HCV.

This project contributes to research on environmental impacts on health and can help improve patients' quality of life while promoting environmental protection.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Keras
