# 🧠 Stroke Prediction – Data Preprocessing Project

## 📌 Project Overview
This project focuses on data preprocessing of the Stroke Prediction dataset. The main objective is to clean and prepare the dataset for future machine learning model development.

## 📊 Dataset Information
- Total Records: 5110
- Total Features: 12
- Target Variable: stroke

The dataset contains demographic and health-related information used to analyze stroke risk factors.

## 🧹 Data Preprocessing Steps

1. Data Cleaning
   - Removed unnecessary columns (e.g., ID column)
   - Checked data types

2. Handling Missing Values
   - Identified missing values in the BMI column
   - Replaced missing values using mean/median method

3. Encoding Categorical Variables
   - Converted categorical columns (gender, work_type, smoking_status, etc.) into numerical format

4. Checking Class Imbalance
   - Analyzed distribution of stroke vs non-stroke cases

5. Basic Data Analysis
   - Generated summary statistics
   - Created distribution plots for important features like Age

## 📈 Key Observations
- The dataset is highly imbalanced.
- Age plays a major role in stroke occurrence.
- Hypertension and heart disease increase stroke risk.
- Some columns required preprocessing before modeling.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib

## 🎯 Conclusion
The dataset has been successfully cleaned and preprocessed, making it ready for further machine learning model development.
