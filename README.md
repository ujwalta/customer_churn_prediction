📊 Customer Churn Prediction using Deep Learning

This project focuses on predicting customer churn using data preprocessing, exploratory data analysis (EDA), and an Artificial Neural Network (ANN) built with TensorFlow/Keras.
It is part of my #30Days30Projects – Day 15 learning challenge.

🚀 Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave their service.
In this project, we:

Clean and preprocess real-world customer data

Visualize churn patterns

Build and evaluate a deep learning model for binary classification

🛠️ Technologies Used

Python

Pandas & NumPy – data manipulation

Matplotlib & Seaborn – data visualization

Scikit-learn – preprocessing & evaluation

TensorFlow / Keras – deep learning model

📂 Dataset

Dataset: customer_churn.csv

Target column: Churn

Contains customer details such as:

Tenure

MonthlyCharges

TotalCharges

Contract type

Payment method

Internet services, etc.

🔧 Data Preprocessing Steps

Removed irrelevant column (customerID)

Converted TotalCharges to numeric and handled missing values

Replaced categorical values like:

"No internet service" → "No"

"No phone service" → "No"

Encoded binary categorical columns (Yes/No → 1/0)

Applied One-Hot Encoding for multi-class categorical features

Scaled numerical features using MinMaxScaler

📊 Exploratory Data Analysis (EDA)

Visualized:

Tenure vs Churn

Monthly Charges vs Churn

Identified churn trends using histograms

Analyzed feature distributions

🧠 Model Architecture (ANN)

Input layer: 26 features

Hidden layers:

Dense (26 units, ReLU)

Dense (15 units, ReLU)

Output layer:

Dense (1 unit, Sigmoid)

Compilation Details:

Optimizer: Adam

Loss: Binary Crossentropy

Metrics: Accuracy

Epochs: 100

📈 Model Evaluation

Train-Test Split: 80% / 20%

Evaluation Metrics:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

📌 Key Learnings

Data cleaning and preprocessing are crucial for model performance

Feature scaling improves neural network convergence

Simple ANN models can perform well with proper preprocessing

Visualization helps understand churn behavior clearly

▶️ How to Run the Project

Clone the repository

git clone <repository-url>


Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow


Run the notebook or Python script

📅 Part of Learning Challenge

This project is part of #30Days30Projects where I build and share one project every day to strengthen my data science and machine learning skills.

🤝 Feedback

Suggestions and improvements are always welcome!
Feel free to fork the repo or raise issues.

⭐ If you found this helpful, don’t forget to star the repository!
