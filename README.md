# 🍷 Wine Quality Predictor

A machine learning project that predicts the quality of wine based on its physicochemical attributes using a **Random Forest model**.

---

## 💡 Project Overview

This repository contains code to build, train, and evaluate a machine learning model that predicts wine quality on a scale from 0 to 10 using attributes such as acidity, sugar content, pH, and more.

The model helps users:
- Understand patterns in wine quality
- Predict quality scores for new wine samples
- Explore feature importance using data visualization

This project is ideal for learning end-to-end machine learning workflows including **EDA, model training & evaluation, and saving/exporting models**. :contentReference[oaicite:2]{index=2}

---

## 📄 Table of Contents

- [📁 Dataset](#-dataset)  
- [🛠️ Features](#️-features)  
- [⚙️ Installation](#-installation)  
- [🚀 Usage](#-usage)  
- [📊 Model Evaluation](#-model-evaluation)  
- [🔍 Results & Insights](#-results--insights)  
- [🧠 Contributing](#-contributing)  
- [📝 License](#-license)

---

## 📁 Dataset

We use the **Wine Quality dataset** from the UCI Machine Learning Repository. This dataset contains physicochemical measurements of red and white wines along with expert-assigned quality scores. :contentReference[oaicite:3]{index=3}

**Key features in the dataset include:**
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free & Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Quality (Target)

---

## 🛠️ Features

✔︎ Exploratory Data Analysis (EDA)  
✔︎ Data preprocessing (cleaning, scaling, splitting)  
✔︎ Random Forest machine learning model  
✔︎ Model evaluation (accuracy, confusion matrix, feature importance)  
✔︎ Export saved model for future predictions

---

## ⚙️ Installation

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/divgandhi179-pixel/Wine_quality_predictor.git
   cd Wine_quality_predictor

   🚀 Usage

To explore and run the project:

Open the notebook:

jupyter notebook wine_quality_prediction.ipynb

Run all cells to:

Load and inspect the dataset

Perform EDA

Train the model

Evaluate model performance

Visualize feature importance

Use the saved model to predict new wine samples:

from joblib import load

model = load("random_forest_model.joblib")
prediction = model.predict(new_wine_features)
📊 Model Evaluation

We evaluate the model using metrics such as:

Accuracy Score

Confusion Matrix

Feature Importance

This helps assess how well the model predicts actual wine quality and which chemical attributes influence predictions the most.

🔍 Results & Insights

✨ Random Forest is used due to its strong performance on tabular data.
✨ Feature importance can show which chemical properties most influence predicted quality.
✨ You can extend this project by comparing other models like XGBoost, Gradient Boosting, or SVM for improved performance
