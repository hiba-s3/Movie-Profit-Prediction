# Movie-Profit-Prediction
##  Overview
This repository demonstrates a complete solution to **predict a movie's profit** before release using machine learning.  
The provided dataset contains key features such as budget, crew information, release details, and more.  
The goal is to build models that estimate profit (or revenue) and enable data-driven decision-making in the film industry.

---
## 🎯 Dataset
The dataset used in this project can be downloaded from Google Drive:  
[📂 Download Dataset](https://drive.google.com/file/d/1fQ6NfLqpjuji_aEUjv_8lQZ1QffAHztt/view?usp=sharing)

---

##  Pipeline Overview

1. **Data Loading & Exploration**  
   - Load dataset from the Google Drive link.
   - Inspect data: missing values, distribution of key variables like revenue, budget, release year, etc.

2. **Feature Engineering**  
   - Process categorical variables (e.g., genre, production companies, director).
   - Extract date information (month, year) and temporal features.
   - Create combined features—e.g., budget-to-runtime ratio, star power from cast/director popularity.

3. **Modeling Approaches**  
   - Baseline: Simple Linear Regression, Ridge, Lasso.
   - Tree-based models: Random Forest, XGBoost, LightGBM, CatBoost.
   - Ensemble methods and stacking for improved performance.

4. **Evaluation**  
   - Metrics: RMSE, MAE,  R², Accuracy.
   - Use cross-validation for robust performance estimates.
   - Visualize actual vs. predicted profit.

5. **Hyperparameter Tuning**  
   - Grid search or randomized search across model parameters.
   - Track best-performing combinations.

---

##  Usage Instructions

```bash
git clone https://github.com/hiba-s3/movie-profit-prediction.git
cd movie-profit-prediction
pip install -r requirements.txt
