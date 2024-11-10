# Air Pollution and Cancer Stage Prediction

![image](https://domf5oio6qrcr.cloudfront.net/medialibrary/10245/GettyImages-1098018152.jpg)

## Project Overview

The goal of this project is to investigate the potential relationship between air pollution levels and the progression of cancer in patients, using both medical and environmental data. The analysis leverages machine learning techniques to predict the stage of cancer based on the data.

## Project Steps

### 1. Importing Libraries
At the start of the project, essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are imported for data processing, visualization, and building machine learning models.

### 2. Loading and Preliminary Data Analysis
Data is loaded from a CSV file. Preliminary analysis includes displaying the first few rows of the dataset, generating descriptive statistics, and reviewing information about columns and data types.

### 3. Data Cleaning
The data is cleaned by removing duplicates and checking for missing values to avoid errors in further analysis.

### 4. Target Variable Encoding
The target variable, i.e., the cancer stage (`Level`), is encoded into numerical values so it can be used in machine learning models. Unnecessary columns such as `Index` and `Patient ID` are also removed.

### 5. Data Visualization
The data is visualized to better understand the distribution of variables and the correlation between them. Techniques such as pie charts are used to show the distribution of cancer stages, and heatmaps are used to display correlations between variables.

### 6. Building Machine Learning Models
Various machine learning models are built in the project, including:

- K-Nearest Neighbors (KNN)
- Random Forest
- Naive Bayes
- Decision Tree

These models are trained and tested on the dataset, and their performance is compared to select the best model for predicting the cancer stage.

### 7. Model Evaluation
Models are evaluated using various metrics, such as confusion matrices, classification reports, and accuracy scores. These metrics help assess the effectiveness of each model and choose the one that yields the best results.

### 8. Conclusions
Based on the results of the analysis, conclusions are drawn about the potential link between air pollution and cancer progression. Additionally, the performance of different machine learning models in predicting cancer stages is evaluated.

## Potential Applications

The results of this project could be used for:

- Raising awareness about the impact of air pollution on health.
- Supporting policymakers in designing policies aimed at reducing air pollution.
- Assisting healthcare professionals in identifying patients at higher risk of advanced cancer stages.

This project contributes to research on environmental impacts on health and can help improve patients' quality of life while promoting environmental protection.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
