# ece556-final-project - Salinity Prediction in the Mekong Delta

This repository presents a complete workflow for retrieving, processing, and modeling salinity data in the Mekong Delta using satellite observations and machine learning. The pipeline integrates remote sensing techniques with both classical and deep learning models to forecast salinity intrusion during dry seasons.

## 📁 Directory Overview

### `Mekong_data_retrieval.ipynb`
Satellite data retrieval using the `eemont` package and Google Earth Engine. Focuses on obtaining relevant spectral bands and indices for water analysis.

### `mekong-data-preprocessing.ipynb`
Processes the raw satellite and in-situ data: cleaning, merging, handling missing values, and preparing features for model training.

### `mekong_data_analysis.ipynb`
Visualizes spatial and temporal patterns of salinity across monitoring stations, aiding in understanding seasonal trends and distribution.

### `data-training-testing-set.ipynb`
Divides the processed dataset into training and testing subsets, ensuring temporal consistency and avoiding data leakage.

### `model/`
Includes notebooks implementing the predictive models:

- `RF.ipynb`: Random Forest regression.
- `merge7-8-xgboost.ipynb`: XGBoost with engineered feature combinations.
- `mlp.ipynb`: Multi-layer perceptron (MLP) model.
- `LSTM.ipynb`: Long Short-Term Memory network for sequential prediction.

## 🔧 Requirements

To run the notebooks, the following Python packages are recommended:

- `eemont`
- `geemap`
- `scikit-learn`
- `xgboost`
- `tensorflow` or `keras`
- `pandas`, `numpy`, `matplotlib`

## 📌 Purpose

The goal of this project is to develop a scalable, satellite-based salinity monitoring and forecasting framework that can support climate resilience and agricultural planning in vulnerable coastal regions like the Mekong Delta.
Here attached is my final report: https://drive.google.com/file/d/1ovZrpP1G42rK28_nQ8o91yJ8Q5Ixte8b/view?usp=sharing 

---


