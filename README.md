# 🍷 Wine Quality Prediction using Random Forest and Feature Selection

## Overview
This project aims to predict the quality of Portuguese red wine samples using their physicochemical attributes.  
By applying machine learning techniques, exploratory data analysis, feature selection, and model calibration, we enhance predictive accuracy and interpretability.

## Objective
- Predict whether a wine sample is classified as "good" or "bad" based on features like acidity, sugar, pH, alcohol, etc.
- Explore the trade-off between model complexity and prediction performance.
- Apply feature selection techniques to optimize model efficiency.

## Dataset
- **Source:** UCI Machine Learning Repository [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- **Records:** 1599 samples (Red wine)
- **Features:** 11 physicochemical variables + quality label

---

## Techniques Used
- Exploratory Data Analysis (EDA)
- Random Forest Classifier
- Model Calibration (Sigmoid method)
- Feature Importance Analysis (MDI, Permutation Importance)
- Feature Selection via Hierarchical Clustering (Dendrograms)
- Hyperparameter Tuning (GridSearchCV)

---

## Project Structure
| File/Folder | Description |
|:------------|:------------|
| `wine_project_full.ipynb` | Full Jupyter notebook with code, analysis, and modeling |
| `README.md` | Project overview and documentation |
| `requirements.txt` | List of Python libraries needed |
| `images/` | Visualizations used in this project |

---

## Key Visualizations
### 1. Wine Quality Distribution
![Wine Quality Histogram](images/wine_quality_histogram.png)

### 2. Violin Plots of Features vs Quality
![Violin Plot Features](images/violin_plot_features.png)

### 3. Pearson and Spearman Correlation Heatmaps
![Correlation Heatmaps](images/correlation_heatmaps.png)

### 4. Random Forest Feature Importances
![Feature Importances](images/feature_importances.png)

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wine-quality-prediction.git
