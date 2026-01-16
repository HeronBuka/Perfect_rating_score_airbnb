# Airbnb Perfect Rating Score Prediction 🏠⭐

## 📖 Project Overview
This project focuses on building a robust predictive model to identify high-potential Airbnb listings likely to achieve a "Perfect Rating Score." By accurately predicting high-quality listings, the model enables data-driven decision-making for resource allocation and targeted A/B testing strategies.

The solution involves an automated machine learning pipeline that handles data preprocessing, feature engineering, and advanced model tuning.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, LightGBM, CatBoost, XGBoost
* **Feature Engineering:** TF-IDF (Text Analysis), One-Hot Encoding
* **Validation Strategy:** Nested Holdout Validation

## ⚡ Key Technical Features
* **Automated Pipeline:** Built an end-to-end classification pipeline to process raw CSV data.
* **Advanced Feature Engineering:** Engineered **60+ features**, including extracting insights from textual reviews using **TF-IDF** and processing categorical variables into dummy variables.
* **Model Selection:** Trained and evaluated 6 different machine learning algorithms, optimizing for the best balance between precision and recall.

## 📊 Model Performance
The final model was optimized to minimize false positives (risk) while maximizing the identification of high-quality listings:

* **True Positive Rate (TPR):** ~50% (Successfully captured half of all top-tier listings)
* **False Positive Rate (FPR):** ~9.3% (Kept misclassification risk extremely low)
* **Validation Method:** Rigorous nested holdout validation to prevent overfitting.

## 🚀 Business Impact
* **Resource Allocation:** Enabled the prioritization of "high-lift" listings for marketing support and resource distribution.
* **Risk Quantification:** Quantified the risk of misclassification (FPR < 10%), ensuring reliable automated decision-making.
* **Strategic Testing:** Provided a qualified user base for A/B testing initiatives to improve overall platform quality.

## 📂 Project Structure
* `Airbnb_Prediction_Pipeline.ipynb`: The main Jupyter Notebook containing data cleaning, EDA, feature engineering, and modeling logic.
* `requirements.txt`: List of Python dependencies.

---
*Author: Wanlu (Kelsey) Bai*
