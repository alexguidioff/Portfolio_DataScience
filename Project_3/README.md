# Environmental Impact of Food Production

## Context
The world's population is expected to grow from 7.3 billion today to 9.7 billion by 2050. Feeding this growing population is a major challenge for organizations, entrepreneurs, and philanthropists in the food and agriculture sectors.  

These solutions range from changing the way we grow and produce food to changing the way we consume it. Moreover, climate change is affecting agriculture, and as the population grows and becomes wealthier, the demand for food, energy, and water has increased sharply. These resources are strongly interconnected: food production requires water and energy; traditional energy production requires water; agriculture can provide energy and water.

## Objective
This project analyzes the environmental impact of global food and feed production. Using available datasets, we explore which foods have the highest impact and which countries have improved over time. The project includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing (scaling, encoding)
- Preparing the dataset for a hypothetical predictive model

### Key Questions
- Which 5 foods and feeds have the largest environmental impact?
- Which country has most successfully reduced its negative environmental impact over time?

## Data Sources
1. [World Food & Feed Production Dataset (Kaggle)](https://www.kaggle.com/datasets/dorbicycle/world-foodfeed-production)
   - Covers food and feed production for over 245 countries and territories from 1961 to the most recent year.
2. [Environmental Impact of Food Production Dataset (Kaggle)](https://www.kaggle.com/selfvivek/environment-impact-of-food-production)
   - Includes 43 common foods with metrics such as water usage and greenhouse gas emissions.

## Steps
1. Load and inspect the datasets using Pandas.
2. Clean, preprocess, and merge datasets.
3. Focus analysis on key metrics: total emissions, freshwater usage, and land use.
4. Aggregate data by decade and country.
5. Identify the top 10 producers and top-impact foods.
6. Visualize results using bar plots and pie charts.
7. Apply scaling (StandardScaler) to prepare data for predictive modeling.

## Notebook
- `Food_Impact_Analysis.ipynb`

## Notes
- All code comments are written in **Italian**.
- Plots and tables help identify environmental trends across countries and decades.
