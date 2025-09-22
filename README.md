# Machine-Learning-Wine-quality-Prediction-and-clustering-
Machine learning project predicting and clustering wine quality using Python (pandas, scikit-learn). Includes regression, classification with PCA, and K-Means clustering.

# Wine Quality Prediction & Clustering (Python + scikit-learn)

This project applies supervised and unsupervised machine learning techniques to the 
[UCI Wine Quality dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality) 
to explore and predict wine quality based on physicochemical features.

## Project Highlights
- **Regression:** Built Linear and Ridge Regression models to predict wine quality.  
  - Achieved RMSE ≈ 0.724 (improved from baseline ≈ 0.88).  
- **Classification:** Applied PCA (90% variance explained) and compared Logistic Regression vs k-NN.  
  - Best accuracy: 84.1% using k-NN (k=12).  
- **Clustering:** Used K-Means (k=4) with PCA visualization.  
  - Effectively separated red vs white wines and revealed quality-based clusters.  

## Workflow
1. Data cleaning and preprocessing (handling missing values, scaling features).  
2. Feature engineering and dimensionality reduction (PCA).  
3. Training and evaluation of supervised models.  
4. Applying unsupervised clustering (K-Means).  
5. Visualization of results using PCA scatterplots and error metrics.  

## Technologies
- Python, pandas, NumPy  
- scikit-learn (Regression, Classification, PCA, K-Means)  
- Matplotlib / Seaborn for visualization  
- Jupyter Notebook for experimentation  

## Results
- Demonstrated the effectiveness of regularized regression (Ridge) in predictive tasks.  
- Showed PCA’s role in reducing dimensionality for better classification performance.  
- Clustering analysis uncovered meaningful patterns separating wine types and quality levels.  

---
