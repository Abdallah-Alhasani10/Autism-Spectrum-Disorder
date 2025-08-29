# 🧠 Autism Spectrum Disorder (ASD) Prediction

This project is a Machine Learning pipeline to predict Autism Spectrum Disorder (ASD) based on medical and behavioral dataset.  
It involves data preprocessing, EDA, feature encoding, outlier handling, balancing imbalanced data, model training, hyperparameter tuning, and model evaluation.

---

## 📊 Dataset
- Source: train.csv
- Features include demographic information, behavioral scores, medical history, and screening results.
- Target variable: Class/ASD

---

## ⚙️ Project Workflow
1. Data Cleaning & Preprocessing
   - Dropped unnecessary columns
   - Handled missing values and inconsistent entries
   - Encoded categorical variables using LabelEncoder
   - Replaced outliers with median values
   - Balanced dataset using SMOTE

2. Exploratory Data Analysis (EDA)
   - Distribution plots (Age, Result, etc.)
   - Boxplots to detect outliers
   - Correlation heatmap for feature relationships

3. Modeling
   - Models trained:
     - Decision Tree
     - Random Forest
     - XGBoost
   - Hyperparameter tuning with RandomizedSearchCV

4. Evaluation
   - Accuracy, Confusion Matrix, Classification Report
   - Best model saved as best_model.pkl
   - Encoders saved as encoder.pkl

---

## 📈 Results
- The best model was selected based on cross-validation accuracy.
- Final evaluation metrics were reported on the test dataset.

---

## 🛠 Tech Stack
- Python 🐍
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Pickle

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Abdallah-Alhasani10/Autism-Spectrum-Disorder.git
   cd asd-prediction
