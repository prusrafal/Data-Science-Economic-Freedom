# Data-Science-Forecasting-Policy-Impacts-on-Economic-Freedom

## Overview
This repository contains code for the final project for the course "Data Science, Prediction, and Forecasting" at Aarhus University in Denmark, as part of the MSc degree in Cognitive Science. The project involves the Economic Freedom Index Summary (EFIS) data analysis, including data preprocessing, analysis, modelling, and visualization using various data science techniques. The topic of the project is "Forecasting Policy Impacts on Economic Freedom: Machine Learning Approach." The analysis is based on data from the "Economic Freedom of the World" index, published by the Fraser Institute (Ausloos & Bronlet, 2021), which evaluates the extent to which the policies and institutions of countries support economic freedom.

## Keywords
`Data Science`, `Economic Freedom`, `Machine Learning`, `Policy Impact`, `Forecasting`, `Neural Networks`
## Project Structure

| Directory | File/Script Name    | Description                                                 |
|-----------|---------------------|-------------------------------------------------------------|
| **data/** | EFIS_data.xlsx      | The original dataset.                                       |
|           | cleaned_data.csv        | Cleaned data; low VIF, no missing values, skewed dataset, no outliers.|
|           | ready_data.csv          | Data extracted after removing columns with higher p-values. |
|           | target_data.csv         | The y variable used for prediction.                         |
| **src/**  | EFIS_DA.ipynb             | Data analysis code.                                         |
|           | EFIS_Model_Final.ipynb  | Prediction models.                                          |

## Usage
To replicate the study or explore the data with our analyses, follow these steps:

1. **Prepare Your Environment**:
   - Ensure you have Python and the necessary libraries installed.
   
2. **Download the Project Files**:
   - Clone this repository or download the files directly.

3. **Run the Analysis**:
   - Open the relevant Jupyter notebooks in the `src/` directory to view the primary analysis and models.

4. **Explore the Dataset**:
   - Load the dataset into your preferred data analysis tool (e.g., pandas in Python) to explore the dataset independently.

**Mount Google Drive (if using Google Colab)**:
   - If you are running the notebooks on Google Colab, ensure you mount your Google Drive to access the data files. Note that the `EFIS_Model___Final.ipynb` notebook includes mounting Google Drive files. If you want to run it locally, you should change the data directory paths accordingly.


## Authors
- Rafał Prus - [202100779@post.au.dk](mailto:202100779@post.au.dk)
- Milena Chołożyńska - [202100776@post.au.dk](mailto:202100776@post.au.dk)

## Dataset Source
- [Fraser Institute - Economic Freedom of the World 2023 Annual Report](https://www.fraserinstitute.org/studies/economic-freedom-of-the-world-2023-annual-report)
- [Fraser Institute - Dataset](https://www.fraserinstitute.org/economic-freedom/dataset?geozone=world&page=dataset&min-year=2&max-year=0&filter=0)
