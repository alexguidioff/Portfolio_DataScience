# Wine Classification with KNN

**Objective:**  
Create a predictive model to classify wines produced by three Italian cultivators based on their chemical properties using K-Nearest Neighbors (KNN).

**Dataset:**  
The dataset is provided by the `scikit-learn` library:
- 178 samples
- 13 chemical features
- 3 wine classes (`target_names`)

**Methodology:**  
1. Shuffle and split data into training and testing sets (80/20)  
2. Build a KNN model with different `k` values  
3. Evaluate performance using accuracy  
4. Visualize accuracy as a function of `k`

**Key Results:**  
- Optimal accuracy observed around `k=3`  
- Accuracy vs. `k` plot included in the notebook

**Required Libraries:**  
```python
scikit-learn, numpy, matplotlib
