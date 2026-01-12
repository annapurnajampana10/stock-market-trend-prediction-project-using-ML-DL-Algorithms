# stock-market-trend-prediction-project-using-ML-DL-Algorithms Via Continuous and Binary Data a Comparative Analysis
Stock market trend prediction using ML and DL algorithms on historical price data.

# Project Overview
This project focuses on predicting stock market trends using a comparative analysis of multiple machine learning and deep learning algorithms. The system evaluates model performance on both continuous stock price data and binary-transformed data, highlighting the effectiveness of deep learning models—especially LSTM—for time-series prediction.
The application provides an end-to-end pipeline including dataset upload, preprocessing, model training, prediction, evaluation, and visualization through a user-friendly interface.

# Objectives
Predict future stock prices using historical data
Compare traditional ML algorithms with deep learning models
Analyze performance on continuous and binary datasets
Identify the most accurate and reliable prediction model

# Datasets Used
Multiple real-world stock datasets (e.g., Petrol stock data)
Two data representations:
Continuous Data – Original stock prices
Binary Data – Converted using indicators:
1 if current price > previous price
-1 otherwise

# Algorithms Implemented
🔹 Traditional Machine Learning Models
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Extreme Gradient Boosting (XGBoost)
AdaBoost
Naïve Bayes
Logistic Regression
Artificial Neural Network (ANN)

🔹 Deep Learning Models
Recurrent Neural Network (RNN)
Long Short-Term Memory (LSTM)

# System Workflow
Upload stock dataset
Handle missing values and preprocess data
Split data into training and testing sets
Train models on:
Continuous data
Binary-transformed data
Perform predictions on unseen test data
Evaluate models using performance metrics
Visualize results using graphs and comparison tables

# Evaluation Metrics
Accuracy
F-Score
ROC-AUC

# Key Results
LSTM consistently outperformed all other models
For continuous data:
LSTM achieved the highest F-score
For binary data:
LSTM achieved 100% accuracy, F-score, and ROC-AUC
ANN and LSTM performed better than traditional ML models
Predicted stock prices closely matched actual values in visual graphs

# Application Interface
GUI-based system
Buttons for:
Dataset upload
Preprocessing
Continuous prediction
Binary prediction
Comparison graphs
Performance tables

# How to Run the Project
Download the project files
Double-click on run.bat
Upload a stock dataset using the GUI
Click Preprocess Dataset
Run:
Continuous Prediction
Binary Prediction
View accuracy, graphs, and comparison tables

# Technologies Used
Python
Machine Learning & Deep Learning
ANN, RNN, LSTM
Data preprocessing & feature transformation
Performance evaluation and visualization

# Conclusion
This project demonstrates that deep learning models, particularly LSTM, are highly effective for stock market trend prediction. The comparative analysis clearly shows the superiority of LSTM over traditional machine learning approaches, especially when handling time-series financial data.
