🏦 Insurance Purchase Prediction

This project predicts whether a customer will purchase insurance based on anonymized customer and vehicle data. It uses machine learning models to help businesses identify potential customers for targeted marketing and improved conversion rates.

📌 Project Overview
Performed data cleaning, preprocessing, and exploratory data analysis (EDA)
Handled imbalanced dataset using advanced techniques
Built and evaluated multiple models:
Logistic Regression
Random Forest
XGBoost (Final Model)
Applied threshold tuning to balance precision and recall
Achieved strong ROC-AUC and practical business performance
📂 Dataset

The dataset contains anonymized customer and vehicle-related features.

⚠️ Dataset is not included due to size restrictions.

🔗 Download Dataset Here:
(Add your dataset link here)

⚙️ Tech Stack
🖥️ Language
Python 3.x

📚 Libraries

pandas, numpy → Data preprocessing
matplotlib, seaborn → Visualization
scikit-learn → Model training & evaluation
xgboost → Final model

🚀 Project Workflow
🔹 Data Preprocessing
Handling missing values
Feature encoding
Train-test split

🔹 Exploratory Data Analysis (EDA)
Feature distribution analysis
Correlation checks
Class imbalance analysis

🔹 Model Building
Logistic Regression
Random Forest
XGBoost (selected model)

🔹 Model Optimization
Handled class imbalance using scale_pos_weight
Applied threshold tuning for better recall-precision balance

📊 Evaluation Metrics
ROC-AUC
Precision
Recall
F1-score
Confusion 
Matrix

📈 Results
Best Model: XGBoost
ROC-AUC: ~0.62
Recall: ~44%
Precision: ~5.8%

👉 The model provides a balanced trade-off between identifying potential customers and minimizing false positives.

💡 Key Insights

Customer-related features (ps_ind_*) significantly impact predictions
Vehicle-related features (ps_car_*) also influence decisions
Model helps identify high-probability customers for targeted marketing

🗂️ Project Structure
insurance-prediction/
│── data/                # Dataset (not included)
│── notebooks/           # Jupyter notebooks
│── models/              # Saved model (.pkl)
│── src/                 # Training & prediction scripts
│── app/                 # Streamlit dashboard
│── requirements.txt
│── README.md

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Pandhari Mane
Aspiring Data Scientist | Machine Learning Enthusiast
