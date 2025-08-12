# Sleep Quality Analysis and Prediction

This repository contains a Jupyter notebook that performs an exploratory data analysis (EDA) on a dataset related to sleep patterns and builds a simple linear regression model to predict Sleep Quality based on Sleep Duration.

## Project Overview

The primary goal of this analysis is to:
1.  Understand the structure and key features of the sleep dataset.
2.  Explore the relationship between various factors, particularly focusing on the correlation between Sleep Duration and Sleep Quality.
3.  Build a predictive model to estimate Sleep Quality from Sleep Duration.

## Dataset

The dataset contains information about individuals, including:
*   **Age**
*   **Gender**
*   **Sleep Quality** (Target Variable)
*   **Sleep Duration (Hours)**
*   Daily Steps
*   Calories Burned
*   Physical Activity Level
*   Dietary Habits
*   Sleep Disorders
*   Medication Usage
*   Bedtime
*   Wake-up Time

## Key Findings & Analysis

The notebook demonstrates the following steps:

1.  **Data Loading & Inspection:** The dataset is loaded and its basic structure, data types, and summary statistics are examined.
2.  **Exploratory Data Analysis (EDA):**
    *   A heatmap of the correlation matrix is generated to visualize the relationships between all numeric features.
    *   The analysis highlights a strong positive correlation between `Sleep_Duration_Hours` and `Sleep Quality`.
3.  **Model Building:**
    *   A simple Linear Regression model is trained using `Sleep_Duration_Hours` as the predictor variable to predict `Sleep Quality`.
    *   The model's performance is evaluated using the R-squared (R²) score.
4.  **Results:**
    *   The Linear Regression model achieved an **R² score of approximately 0.844**.
    *   This indicates that about 84.4% of the variation in Sleep Quality can be explained by Sleep Duration alone, suggesting a very strong predictive relationship.

## Files

*   `sleep_analysis.ipynb`: The main Jupyter notebook containing all the code, analysis, visualizations, and results.
*   `Health_Sleep_Statistics.csv`: The raw text or the data set output from the notebook (provided for reference).

## How to Run

1.  Clone this repository.
2.  Ensure you have Python installed along with the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
3.  Open the `sleep_analysis.ipynb` file in Jupyter Notebook or JupyterLab.
4.  Run the cells sequentially to reproduce the analysis.

## Dependencies

*   Python 3.x
*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn

