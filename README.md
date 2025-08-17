# Data Science Portfolio

Welcome to my Data Science portfolio! This repository contains multiple projects developed during my studies and personal work. Each project is organized in its own folder, and each folder contains a `README.md` in Italian that describes the project in detail, including data analysis, preprocessing steps, and code explanations.

## Repository Structure

Each project is stored in its own folder with the following structure:

Project1_Wine_Analysis/
├─ Wine_Quality_Analysis.ipynb
├─ README.md

Project2_Gun_Violence/
├─ Gun_Violence_Analysis.ipynb
├─ README.md

Project3_Food_Environmental_Impact/
├─ Food_Impact_Analysis.ipynb
├─ README.md

Project4_Music_Genre_Classification/
├─ Music_Classification.ipynb
├─ README.md


- Each folder contains a **Jupyter Notebook** with the full code and analysis.  
- The **README.md** inside each project folder provides a summary and instructions in English.  
- **Note:** The notebooks themselves contain explanations and comments in **Italian**, describing the steps, data manipulations, and results.

## Projects Overview

### 1. Wine Quality Classification
- **Folder:** `Project1_Wine_KNN`
- **Objective:** Classify wine quality based on physicochemical properties using K-Nearest Neighbors (KNN) and other machine learning models.
- **Details:** The project includes data cleaning, exploratory data analysis (EDA), feature scaling, and model evaluation.
- **Notebook:** See `Project1_Wine_KNN/Wine_KNN.ipynb` for full implementation.

### 2. Police Bias Analysis
- **Folder:** `Project2_PoliceBias`
- **Objective:** Analyze police activity and potential bias in stop-and-search practices using historical datasets.
- **Details:** Includes data preprocessing, visualization, and insights on bias patterns.
- **Notebook:** See `Project2_PoliceBias/Police_Bias.ipynb`.

### 3. Environmental Impact of Food Production
- **Folder:** `Project3_Food_Impact`
- **Objective:** Analyze the environmental impact of global food and feed production, including CO2 emissions, freshwater usage, and land use. Preprocessing steps prepare the dataset for predictive modeling.
- **Key Questions Explored:**
  - Which 5 foods and feeds have the largest environmental impact?
  - Which country has most successfully reduced its negative environmental impact over time?
- **Data Sources:** 
  - [World Food & Feed Production](https://www.kaggle.com/datasets/dorbicycle/world-foodfeed-production)
  - [Environmental Impact of Food Production](https://www.kaggle.com/selfvivek/environment-impact-of-food-production)
- **Notebook:** See `Project3_Food_Impact/Food_Impact_Analysis.ipynb`.

### 4. Music Genre Classification: Rock vs Hip-Hop
- **Folder:** `Project4_Music_Classification`
- **Objective:** Build a classifier to predict whether a song is Rock or Hip-Hop based on features such as energy, tempo, danceability, and acoustic metrics.
- **Steps:**
  - Data cleaning, outlier removal, and merging CSV and JSON datasets
  - Data visualization and exploratory analysis
  - Label encoding, feature scaling, and balancing with Random Under Sampling
  - Model training using Decision Tree and KNN classifiers
  - Model evaluation with classification reports
- **Data Sources:** [Google Drive dataset](https://drive.google.com/drive/folders/1vPd0qBCpWm_QEXM5NRynNrs72-pUuhSn?usp=sharing)
- **Notebook:** See `Project4_Music_Classification/Music_Classification.ipynb`.

## Notes
- All internal project READMEs are written in **Italian**.
- The main repository README is written in **English** for general overview purposes.
- Each project folder contains all relevant datasets and notebooks.
  
## How to Use

1. Clone the repository:  
```bash
git clone https://github.com/your_username/Portfolio_DataScience.git
