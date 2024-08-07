# Medical Data Visualizer

## Overview

The "Medical Data Visualizer" project aims to analyze medical data to explore relationships between cardiac disease, body measurements, blood markers, and lifestyle choices. The project uses Python with Pandas, Seaborn, and Matplotlib for data cleaning, normalization, and visualization.

## Dataset

- **File:** `medical_examination.csv`
- **Description:** Contains medical examination data including age, height, weight, blood pressure, and lifestyle factors.

## Key Analysis

1. **Add `overweight` Column:**
   - Calculates BMI and adds a column to classify individuals as overweight or not.

2. **Normalize Data:**
   - Normalizes `cholesterol` and `gluc` values to binary format.

3. **Convert Data to Long Format:**
   - Reshapes the data for categorical plotting.

4. **Clean Data:**
   - Filters out incorrect or extreme values in height, weight, and blood pressure.

5. **Correlation Matrix:**
   - Creates and visualizes a heatmap of correlations between features.

## Visualizations

- **Categorical Plot:** Displays counts of various features split by cardiovascular disease status.
- **Correlation Matrix:** Heatmap showing the correlation between different features.

## Usage

Ensure that Pandas, Seaborn, and Matplotlib are installed. Load the dataset and run the provided Python scripts to perform the analysis and generate the visualizations.
