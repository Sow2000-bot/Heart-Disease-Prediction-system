# Heart Disease Data Analysis

## Overview

This repository contains a Jupyter notebook that analyzes heart disease data using various data processing and machine learning techniques. The primary objective is to predict heart disease occurrence based on several health indicators.

## Dataset

The dataset used in this analysis is the **Heart Disease Health Indicators** dataset from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 survey. It includes various health-related attributes such as blood pressure, cholesterol levels, BMI, smoking status, physical activity, and more.

## Requirements

To run the notebook, you will need the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies using the following command:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Contents

The notebook is divided into several sections:

1. **Importing Libraries**: Importing necessary libraries for data processing and visualization.
2. **Loading Data**: Loading the dataset and displaying the first few rows to understand its structure.
3. **Data Preprocessing**: Handling missing values, scaling features, and preparing the data for machine learning models.
4. **Exploratory Data Analysis (EDA)**: Visualizing data distributions and relationships between features.
5. **Model Training**: Training machine learning models to predict heart disease occurrence.
6. **Model Evaluation**: Evaluating model performance using metrics like accuracy, ROC curve, and confusion matrix.

## Usage

To run the notebook, simply clone this repository and open `CS 513 Group 5.ipynb` in Jupyter Notebook or Jupyter Lab. You can execute the cells sequentially to reproduce the analysis.

```bash
git clone <repository_url>
cd <repository_directory>
jupyter notebook "CS 513 Group 5.ipynb"
```

## Results

The notebook provides insights into the key factors contributing to heart disease and evaluates the performance of different machine learning models in predicting heart disease.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request with your proposed changes. Ensure your changes are well-documented and tested.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
