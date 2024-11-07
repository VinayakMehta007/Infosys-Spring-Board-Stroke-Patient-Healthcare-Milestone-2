# Infosys-Spring-Board-Stroke-Patient-Healthcare-Milestone-2

# Stroke Prediction Data Analysis and Preparation

## Project Overview

This project involves exploring and preparing a healthcare dataset to predict stroke occurrences based on various patient attributes. The dataset includes factors such as age, gender, hypertension, heart disease, average glucose level, BMI, and lifestyle indicators (work type, smoking status, and residence type). The project is divided into data visualization, exploratory analysis, and data encoding for model-readiness.

## Milestone Tasks

### I. Data Visualization and Exploration
We perform an initial analysis to understand key patterns and insights in the data:

1. **Key Questions**:
   - How do age and BMI relate to stroke risk?
   - What impact do glucose levels have on stroke occurrences?
   - How do lifestyle factors, like work type and smoking status, correlate with stroke?
2. **Visualization**: We created graphs to identify relationships between variables and stroke incidence, including:
   - Age and BMI distributions for stroke/non-stroke groups
   - Glucose levels and their relationship to stroke
   - Stroke occurrences by work type and smoking status
3. **Observations**:
   - Age and glucose levels show a strong correlation with stroke.
   - Certain work types and smoking history may elevate stroke risk.

### II. Data Encoding for Model Preparation
This stage includes transforming categorical data into binary format for compatibility with machine learning models.

1. **Encoding Process**:
   - Convert `Residence_type` to a binary column (0 for Rural, 1 for Urban).
   - Convert `work_type` into binary columns for major work types (Never_worked, Private, Self-employed).
   - Convert `smoking_status` into binary columns for different smoking histories (formerly smoked, never smoked, smokes).
2. **Resulting Dataset**:
   - We created a new dataset, `df_model`, with the necessary transformations applied, making it ready for modeling.

## Files

- `healthcare-dataset-stroke-data.csv`: Original dataset.
- `df_model.csv`: Preprocessed dataset ready for model training.
- `data_analysis.ipynb`: Notebook containing code for data exploration, visualization, and encoding.

## Requirements

- Python 3.8+
- Libraries: `pandas`, `seaborn`, `matplotlib`

## Usage

1. Run `data_analysis.ipynb` to view data visualizations and preprocessing steps.
2. Use `df_model.csv` as input for predictive modeling.

