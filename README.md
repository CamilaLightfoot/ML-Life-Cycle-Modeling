# ML-Life-Cycle-Modeling

## Project Overview
This project is part of my eCornell Machine Learning portfolio and focuses on the **modeling stage** of the ML life cycle.  
Using the **Airbnb NYC Listings** dataset, I trained and evaluated **Decision Tree (DT)** and **K-Nearest Neighbors (KNN)** classifiers, tuning their hyperparameters to identify the best‑performing model. The lab emphasizes **feature engineering**, **model comparison**, and **evaluation metrics** to guide predictive problem‑solving.

## Objectives
- Define the ML problem and prepare a feature matrix.  
- Perform one‑hot encoding for categorical variables.  
- Train and optimize Decision Tree and KNN models.  
- Compare model performance and select the optimal one.  
- Interpret results and discuss considerations for deployment.

## Methodology
1. **Data Preparation** – Feature engineering, one‑hot encoding, and scaling where needed.  
2. **Model Training** – Train DT and KNN classifiers with various hyperparameter configurations.  
3. **Evaluation** – Measure performance using accuracy and visualizations.  
4. **Comparison** – Analyze trade‑offs between DTs and KNNs to determine the most suitable model.  
5. **Conclusion** – Summarize findings and the best‑performing configuration.

## 📂 Files in this Repository
- **`CompareKNNsAndDTs.ipynb`** – Main Jupyter Notebook with full implementation, including training, evaluation, and comparison of DTs and KNNs.  
- **`CompareKNNsAndDTs.py`** – Script version of the notebook, containing the modeling logic for non‑notebook workflows.  
- **`airbnbData_train.csv`** – Airbnb NYC Listings training subset used for model building.

## 📊 Results & Key Findings
- Both DT and KNN models were trained and tuned across multiple hyperparameters.  
- Accuracy varies with configuration; the best model (per notebook) outperforms baseline and highlights the bias–variance trade‑off.  
- Visualizations (accuracy vs. hyperparameter) help select robust configurations and reveal overfitting at extreme depths (DT) or inappropriate k values (KNN).

## ▶️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<this-repo>.git
   cd <this-repo>
