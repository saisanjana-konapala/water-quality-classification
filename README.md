# Water Quality Classification using Machine Learning
#week-1
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

#week-2

## ⚙️ Workflow

1️⃣ Importing Libraries

We use Python libraries like:

pandas, numpy → Data handling

matplotlib, seaborn → Visualizations

scikit-learn → ML model building

2️⃣ Data Loading & Exploration

Loaded dataset into a Pandas DataFrame.

Checked missing values and handled them with median imputation.

Explored dataset using .info(), .describe(), .isnull().sum().

3️⃣ Model Selection (Rectification Step)

Compared several models (Logistic Regression, Decision Tree, Random Forest).

Found that Random Forest Classifier performed the best in terms of accuracy and balance between classes.

4️⃣ Model Implementation

Trained Random Forest using train-test split (80-20).

Tuned hyperparameters for better performance.

5️⃣ Evaluation

Evaluated performance using:

✅ Accuracy Score

✅ Classification Report (Precision, Recall, F1-score)

✅ Confusion Matrix Heatmap

Created attractive visuals (bar charts, dark-theme confusion matrix).

## 📈 Results

Best Model: Random Forest Classifier 🌳

Accuracy Achieved: ~72–76%

The model performs better at detecting Not Potable (unsafe) water than Potable water.

## 🔮 Next Steps

Improve accuracy with feature engineering and hyperparameter tuning.

Balance dataset using oversampling (SMOTE) or class weights.

## 👩‍💻 Improvisations Done

Organized workflow into clear steps (import → explore → model → evaluate).

Implemented multiple models to check which one is best.

Added attractive dark theme visualizations for accuracy & confusion matrix.

Wrote a clean README.md for better understanding.

