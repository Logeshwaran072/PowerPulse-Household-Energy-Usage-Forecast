# Notebook Folder README

## Overview

This folder contains Python scripts that document the entire process of the project, from data exploration to model testing. Each script is dedicated to a specific phase of the workflow, ensuring modularity and ease of understanding.

## Contents

1. **`eda.py`**

   - This script performs Exploratory Data Analysis (EDA) to uncover insights and patterns in the dataset.
   - Key visualizations and descriptive statistics are included to summarize the data.

2. **`preprocessing.py`**

   - Handles data preprocessing tasks, including:
     - Cleaning missing or inconsistent data.
     - Encoding categorical variables.
     - Outlier handling.
     - Skewness handling.
     - Scaling numerical features.
   - Prepares the datasets `x` (features) and `y` (target) for model training.

3. **`model_development.py`**

   - Focuses on model training and hyperparameter tuning.
   - Includes different machine learning models and evaluates their performance using training data.
   - Trained models are saved for future use.

4. **`model_testing.py`**

   - Validates the performance of trained models on test data.
   - Includes metrics and visualizations such as residual plots and actual vs. predicted comparisons.

## Instructions

### Running the Scripts

- **Order of Execution**: The scripts are designed to be executed in the following sequence:

  1. `eda.py`
  2. `preprocessing.py`
  3. `model_development.py`
  4. `model_testing.py`

- Ensure that the dataset and any required files are in the correct directories before executing the scripts.


### Prerequisites

- Install all required libraries mentioned in the project’s primary README or requirements file.
- Ensure consistent file paths if moving or renaming scripts or data files.

## Notes

- The scripts are modular, allowing updates or modifications to individual phases without affecting others.
- Use version control (e.g., Git) to track changes and maintain script integrity.

