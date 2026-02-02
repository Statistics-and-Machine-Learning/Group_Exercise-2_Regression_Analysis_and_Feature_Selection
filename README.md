Regression Analysis with Proper Outlier Handling
📌 Project Overview

This project performs an end-to-end regression analysis on a real-world dataset with a strong focus on academically correct data preprocessing.
Special care is taken to handle outliers, feature scaling, and model evaluation in the right order to avoid data leakage and distorted results.

The notebook demonstrates best practices expected in statistics, machine learning, and data science coursework.

Key Objectives

Understand the structure of the dataset

Clean and preprocess numerical features correctly

Apply outlier removal without affecting the target variable

Scale features appropriately

Train and evaluate regression models

Compare model performance using standard metrics


Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook


Project Structure

📁 Regression-Analysis
│
├── regression_analysis_watson_updated.ipynb
├── README.md
└── requirements.txt (optional)


Data Preprocessing Steps
1️⃣ Data Exploration

Dataset shape and structure

Missing value analysis

Basic statistical summary

2️⃣ Feature Selection

Separation of:

Numerical features

Target variable (sold_count)



⚠️ Outlier Handling 


Outliers are removed only from feature columns

Target variable is explicitly excluded

IQR method is applied once using a combined mask
→ prevents aggressive row deletion




❌ What Was Avoided

Removing outliers column-by-column

Filtering the target variable

Scaling before outlier removal

This ensures:
✔ academic correctness
✔ minimal data loss
✔ unbiased model training



⚖️ Feature Scaling

Standardization applied after outlier removal

Ensures fair contribution of features during model training

🤖 Models Implemented

Linear Regression

(Optional if present) Ridge / Lasso / Random Forest


📈 Model Evaluation Metrics

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Results are compared to understand model performance and generalization.


📊 Visualizations

Feature distributions (before & after preprocessing)

Correlation heatmap

Actual vs Predicted values

🚀 How to Run the Project

Clone the repository:

git clone <https://github.com/Statistics-and-Machine-Learning/Group_Exercise-2_Regression_Analysis_and_Feature_Selection>


Navigate to the project folder:

cd Regression-Analysis


Open the notebook:

jupyter notebook


Run all cells in:

regression_analysis_watson_updated.ipynb

🎓 Academic Note

This project follows proper machine learning workflow standards, making it suitable for:

University assignments

Portfolio projects

GitHub showcase

Interview discussion


Collaborators

Saniya Shaikh
Shruti Bhandari
Sakshi Manjrekar
