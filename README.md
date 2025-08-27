# 🫀 Heart Disease Predictor

This project uses machine learning to predict the presence of heart disease based on patient health metrics. Built in **Google Colab**, it leverages a dataset from **Kaggle**, applies **Logistic Regression** and **Random Forest Classifier**, and visualizes results using **Matplotlib**.

## 📌 Overview

- **Platform**: Google Colab  
- **Language**: Python  
- **Dataset**: [Kaggle Heart Disease Dataset](https://www.kaggle.com/)  
- **Models Used**: Logistic Regression, Random Forest Classifier  
- **Visualization**: Matplotlib  

## 📊 Dataset Features

The dataset includes medical attributes such as:

- Age, Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Serum Cholesterol  
- Fasting Blood Sugar  
- Resting ECG Results  
- Max Heart Rate Achieved  
- Exercise-Induced Angina  
- ST Depression  
- Slope of ST Segment  
- Number of Major Vessels  
- Thalassemia  
- Target (Heart Disease Presence)

## 🧠 Model Training

Two classification models were trained:

### Logistic Regression
- Simple and interpretable  
- Good baseline performance

### Random Forest Classifier
- Ensemble method  
- Handles feature interactions and non-linearities  
- Typically higher accuracy

## 📈 Visualizations

Using Matplotlib, the notebook includes:

- Feature distributions  
- Correlation heatmaps  
- ROC curves  
- Accuracy and confusion matrices

## ✅ Results

Model performance was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC

Random Forest showed better predictive performance, while Logistic Regression offered clearer interpretability.

## 🚀 How to Run

1. Clone the repository  
2. Open `DiseasePredictor.ipynb` in Google Colab  
3. Upload the dataset or connect to Kaggle  
4. Run all cells to train and evaluate models

## 🔧 Future Enhancements

- Hyperparameter tuning (GridSearchCV)  
- Cross-validation  
- Feature engineering  
- Deployment via Flask or Streamlit

## 📬 Contact

Created by [Mukesh](https://github.com/Mukesh2806). Contributions and suggestions are welcome!

---

*This project is part of my journey into applying machine learning to real-world problems.*
