# Project 5: CalCOFI Oceanographic Data Analysis

## Context
The CalCOFI dataset represents the longest (1949–present) and most comprehensive (over 50,000 sampling stations) time series of oceanographic and larval fish data worldwide. It includes data on larval abundance for over 250 fish species, larval length frequency, egg abundance for commercially important species, as well as physical, chemical, and planktonic oceanographic data. These measurements, collected regularly over time and space, are valuable for documenting climate cycles in the California Current and biological responses to them.

## Objective
The main goal of this project is to explore relationships in the dataset and build predictive models using regression algorithms such as linear regression and decision tree regressors to answer questions like:

- Is there a relationship between water salinity and temperature? Support your answer with model outputs.
- Can we predict water temperature based on salinity?

## Data Sources
- CalCOFI dataset from Kaggle: [Download Link](https://www.kaggle.com/datasets/sohier/calcofi)

## Steps
1. Import libraries: pandas, numpy, matplotlib, seaborn, sklearn.
2. Load and inspect the dataset.
3. Clean data by filling missing values with the mean.
4. Explore correlations between salinity and temperature.
5. Visualize relationships using scatter plots and density plots (KDE).
6. Select relevant features (`Salnty`) and target (`T_degC`).
7. Train-test split of data.
8. Train a linear regression model to predict temperature.
9. Evaluate model performance using R² and Mean Squared Error.
10. Visualize results and interpret the relationship between features.

## Notebook
- `CalCOFI_Temperature_Prediction.ipynb`

## Notes
- All code comments are in **Italian**.
- Visualizations include heatmaps, scatter plots with KDE, and regression line plots.
- The notebook demonstrates data cleaning, exploratory data analysis, and regression modeling workflow.
