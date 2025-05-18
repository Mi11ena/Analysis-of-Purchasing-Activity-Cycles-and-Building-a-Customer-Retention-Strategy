# Customer Retention Strategy: Behavioural Segmentation & Churn Prediction

This repository contains the full pipeline for the Bachelor Thesis. The project uses real transactional data from a children's goods e-commerce company, covering purchase history over one year.

## Project Structure

- `0. Draft_Research.ipynb` – Initial problem framing and research background.  
- `0.5. Draft_all.ipynb` – Combined draft with early versions of all project stages.  
- `1. Preprocessing.ipynb` – Data cleaning, transformation into customer–quarter format, and feature engineering.  
- `2. Clustering.ipynb` – Customer segmentation using KMeans, GMM, and RFM.  
- `3. Churn_Prediction.ipynb` – Baseline models for segment transition prediction.  
- `3.5. Prediction_Improvement.ipynb` – Final model using MLPClassifier with improved accuracy and macro F1-score.  
- `4. Business_Effect.ipynb` – Financial impact analysis of churn and segment-based retention strategies.

## Highlights

- Combines unsupervised (KMeans, GMM) and supervised (CatBoost, MLPClassifier) ML methods  
- Uses RFM segmentation to enhance business interpretability  
- Predicts customer segment transitions rather than binary churn  
- MLPClassifier achieved the highest prediction quality across all segments  
- Practical recommendations aligned with business impact
