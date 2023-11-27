# Mental Stress Detection Project

## Overview
This repository contains the code for a machine learning project focused on detecting mental stress. The project involves the analysis of textual data to identify patterns associated with stress levels. The dataset used for this project was sourced from Kaggle in CSV format.

## Project Structure
The project follows a structured workflow with the following key steps:

### 1. Importing Libraries and Loading Dataset
- Necessary Python libraries are imported to facilitate data analysis and machine learning.

### 2. Data Preparation
- The dataset is loaded and prepared for further analysis.

### 3. Text Processing
- Textual data is processed to extract relevant features for stress detection.

### 4. Regular Expressions for Cleaning the Text Data
- Regular expressions are applied to clean and preprocess the text data.

### 5. Vectorization
- The text data is transformed into numerical format using two techniques:
  - Bag of Words/Count Vectorizer
  - TF-IDF (Term Frequency-Inverse Document Frequency)

### 6. Model Building
- Machine learning models are constructed using two different vectorization approaches:
  - Models with Bag of Words:
    - Logistic Regression
    - Multinomial Naive Bayes
    - Random Forest Classifier
  - Models with TF-IDF:
    - Logistic Regression
    - Multinomial Naive Bayes
    - Random Forest Classifier

### 7. Validation
- The performance of the models is assessed through validation techniques.

### 8. Generating Predictions
- The final step involves using the trained models to generate predictions on new data.

## Tools Used
- Jupyter Notebook
- Visual Studio Code

## Language
- Python

## Raw Data
- The raw data for this project is in CSV format and was obtained from Kaggle.

## Usage
1. Clone the repository.
2. Open and run the Jupyter Notebook in a Python environment with the required dependencies installed.

Feel free to explore and adapt the code to suit your needs. If you have any questions or suggestions, please feel free to reach out!
