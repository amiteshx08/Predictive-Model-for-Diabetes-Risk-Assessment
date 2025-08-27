# Predictive-Model-for-Diabetes-Risk-Assessment
This project aims to predict the onset of diabetes in patients based on key diagnostic health metrics. Using the Pima Indians Diabetes Database. 
The main objective of this project is to predict the likelihood of diabetes in patients based on medical and demographic attributes using a Logistic Regression model.

The model achieves an AUC score of 0.85, indicating strong classification performance.

📊 Dataset

Source: Pima Indian Diabetes Dataset

Features: 8 medical predictor variables (e.g., glucose level, BMI, age, insulin, etc.)

Target: Binary outcome (1 = Diabetes, 0 = No Diabetes)

⚙️ Data Preprocessing

The dataset was cleaned and preprocessed before model training. Steps included:

Handling Outliers: Applied detection and treatment to remove extreme values.

Missing Value Imputation: Used the IQR (Interquartile Range) technique to impute missing or invalid entries.

Standardization: Standard scaled features for better performance of Logistic Regression.

Data Splitting: Train-test split for unbiased evaluation.

🤖 Model

Algorithm: Logistic Regression

Evaluation Metric: AUC-ROC (Area Under the Curve)

Result: AUC = 0.85

📈 Results

ROC Curve plotted to visualize classifier performance.

Achieved a good tradeoff between sensitivity and specificity.

Outperformed baseline models on this dataset.

🛠️ Tech Stack

Python 3

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn
