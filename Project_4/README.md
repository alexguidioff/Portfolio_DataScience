# Music Genre Classification: Rock vs Hip-Hop

## Context
This project uses machine learning to classify songs as Rock or Hip-Hop without listening to them. By analyzing song features, we train a model to predict the genre based on data alone.

## Objective
Using a dataset of Rock and Hip-Hop songs, the goal is to:

- Explore and visualize the data
- Preprocess features
- Train machine learning models to classify songs
- Evaluate model performance

## Data Sources
- CSV and JSON datasets containing song metadata and metrics.  
[Google Drive Link](https://drive.google.com/drive/folders/1vPd0qBCpWm_QEXM5NRynNrs72-pUuhSn?usp=sharing)

## Steps
1. Import libraries and load datasets.
2. Data cleaning and outlier removal using standard deviation.
3. Merge CSV and JSON datasets on `track_id`.
4. Data visualization: feature distributions and class imbalance.
5. Encode labels: `Rock = 0`, `Hip-Hop = 1`.
6. Split data into features (`X`) and labels (`y`).
7. Feature scaling using `StandardScaler`.
8. Balance classes using Random Under Sampling.
9. Train-test split (25% test set).
10. Train models: Decision Tree (entropy criterion) and K-Nearest Neighbors (KNN).
11. Evaluate models using classification reports.

## Notebook
- `Music_Classification.ipynb`

## Notes
- All code comments are in **Italian**.
- Visualizations include distributions of song features and class balances.
- The notebook demonstrates preprocessing, modeling, and evaluation workflow.
