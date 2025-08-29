# Water Quality Classification using Machine Learning

## 📌 Project Overview
This project applies **AI/ML techniques** to classify water as **potable (safe to drink)** or **not potable** based on water quality parameters.  
The dataset is taken from the [Kaggle Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability).

## 📂 Files in Repository
- Water_Quality_EDA.ipynb → Jupyter Notebook with data loading.
- water_potability.csv → Dataset (9 water quality features + target).
- README.md → Project documentation.

## 🧪 Dataset Details
The dataset includes the following features:
- pH  
- Hardness  
- Solids  
- Chloramines  
- Sulfate  
- Conductivity 
- Organic_carbon  
- Trihalomethanes 
- Turbidity  
- Potability (target: 0 = Not potable, 1 = Potable)

## ⚙️ Steps Completed
1. Imported necessary libraries.  
2. Loaded dataset from CSV.  
3. Performed exploratory analysis using .info(), .describe(), and .isnull().sum() to check missing values.

## 🚀 Next Steps
- Handle missing values.  
- Feature scaling and preprocessing.  
- Model training (Random Forest, XGBoost, etc.).  
- Evaluate performance (accuracy, F1-score, confusion matrix).  

## 📖 How to Run
1. Clone this repository:  
   bash
   git clone https://github.com/saisanjana-konapala/water-quality-classification.git
