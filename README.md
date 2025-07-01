# 📦 E-Commerce Delivery Prediction - Capstone Project

## 📁 Project Overview

This capstone project aims to build a machine learning model that predicts whether a product in an e-commerce setting will be delivered **on time (0)** or **delayed (1)**. The goal is to assist the company in improving customer satisfaction by identifying high-risk deliveries in advance.

---

## 📊 Dataset Description

The dataset is provided by an international e-commerce company and includes 10,999 records with the following features:

- **Warehouse block** (A–F)
- **Mode of shipment** (Ship, Flight, Road)
- **Customer care calls**
- **Customer rating** (1 to 5)
- **Cost of the product**
- **Prior purchases**
- **Product importance** (low, medium, high)
- **Gender**
- **Discount offered**
- **Weight in grams**
- **Reached on time** (Target: 1 = Delayed, 0 = On time)

---

## 🔧 Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Tableau (for BI dashboard)

---

## 🔬 Project Workflow

### ✅ Data Cleaning & Preprocessing
- Handled missing values and duplicates
- Performed one-hot encoding for categorical variables
- Scaled numerical features using Min-Max Scaling

### 📊 Exploratory Data Analysis (EDA)
- Visualized numerical and categorical feature distributions
- Correlation heatmap and pair plots
- Feature engineering (interaction terms, date features)

### 🤖 Model Training & Evaluation
- Trained and evaluated:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)
- Evaluation metrics: Accuracy, F1-score, ROC AUC, Confusion Matrix
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV

### 📈 Business Intelligence Dashboard
- Built interactive visualizations in Tableau using the cleaned dataset

---

## 🏁 Final Results

| Model                  | Accuracy | F1 Weighted | ROC AUC   |
|------------------------|----------|-------------|-----------|
| Logistic Regression    | 0.8535   | Moderate    | Moderate  |
| Random Forest (Tuned)  | **Highest** | **Best**  | **Best**  |
| KNN (Tuned)            | Moderate | Moderate    | Moderate  |

---

## 📂 Project Structure

E-Commerce-Delivery-Prediction/
├── cleaned_ecommerce_data.csv # Final processed dataset for BI tools
├── Capstone_Project.ipynb # Jupyter notebook with full analysis
├── E_Commerce.csv # Raw dataset
├── README.md # Project documentation (you are here)
└── /visuals # Optional: exported images or Tableau screenshots

## Vaibhav Vaish
- Data Science Summer Bootcamp - Capstone Project 1

