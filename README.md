# Lifestyle-Health-Risk-Prediction
Predictive analytics project to assess health risk in young adults using ML

## 📌 Project Overview
This project uses predictive analytics and machine learning to assess health risk in young adults (18–30 years) based on lifestyle habits such as sleep, stress, diet, screen time, and physical activity.

## 🎯 Objectives
- Predict a continuous Health Risk Score (Regression)
- Classify individuals into Low / Moderate / High risk categories
- Identify lifestyle behavior patterns using clustering
- Compare multiple ML algorithms to identify the best model

## 📊 Dataset
- Primary dataset collected using Google Forms
- ~550 responses, 24 features
- Lifestyle, behavioral, and psychological indicators
- Non-invasive survey-based data

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🤖 Models Used
### Regression
- Linear Regression
- Polynomial Regression
- Random Forest Regressor

### Classification
- Logistic Regression
- SVM
- Decision Tree
- KNN
- Random Forest Classifier

### Clustering
- K-Means with PCA

## 📈 Results
- Linear Regression achieved MAE = 0.0 and R² = 1.0
- Random Forest Classifier achieved 96.5% accuracy and F1-score of 0.96

## 📁 Project Structure
Lifestyle-Health-Risk-Prediction/
│
├── data/
│   ├── raw_data.xlsx
│   ├── processed_data.csv
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_regression_models.ipynb
│   ├── 03_classification_models.ipynb
│   ├── 04_clustering_pca.ipynb
│   ├── 05_model_comparison.ipynb
│
├── visuals/
│   ├── correlation_heatmap.png
│   ├── model_comparison.png
│   ├── pca_clusters.png
│
├── report/
│   ├── Project_Report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore


## 🚀 Future Scope
- Wearable device integration
- Longitudinal health tracking
- Deep learning models

## 👩‍💻 Author
Prachi  
B.Tech CSE | Data Science & ML Enthusiast
