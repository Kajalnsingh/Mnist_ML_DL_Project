# Mnist_ML_DL_Project
📌 Overview
This project demonstrates the power of both traditional machine learning algorithms and deep learning models in recognizing handwritten digits using the classic MNIST dataset. Implemented in Google Colab, it covers everything from data preprocessing to model evaluation — providing a smooth learning experience for both beginners and intermediate practitioners.

🧰 Tools & Libraries
Python (Google Colab)
NumPy, Pandas, Matplotlib, Seaborn
Scikit-learn (Logistic Regression, Decision Tree, Random Forest)
TensorFlow / Keras (ANN & CNN)

🔍 Models & Accuracy Comparison

Model	Accuracy
Logistic Regression	92.04%
Decision Tree	86.96%
Random Forest	96.81%
ANN (Simple NN)	97.66% (val)
CNN	99.26% (val)
📈 Performance Breakdown
🧮 Logistic Regression
Accuracy: 92.04%

Performs well across all digits with an average f1-score ~ 0.92

🌲 Decision Tree
Accuracy: 86.96%

Decent baseline model but underperforms compared to ensemble or deep models

🌳 Random Forest
Accuracy: 96.81%

Powerful and well-balanced across all digits

f1-score ~ 0.97

🧠 Artificial Neural Network (ANN)
Training Accuracy: 99.29%

Validation Accuracy: 97.66%

Shows significant improvement over ML models

📸 Convolutional Neural Network (CNN)
Training Accuracy: 99.04%

Validation Accuracy: 99.15%

Best performance, ideal for image classification tasks

🧪 Dataset
The MNIST dataset consists of:

70,000 grayscale images (28x28 pixels)

60,000 training samples and 10,000 test samples

10 digit classes (0 to 9)

🚀 Project Highlights

📊 Data Preprocessing & Normalization
📉 Exploratory Data Analysis (EDA)
🧮 Training 3 ML models: Logistic Regression, Decision Tree, Random Forest
🤖 Training 2 Deep Learning models: ANN and CNN using Keras
📋 Model comparison using Accuracy, Precision, Recall, and F1-Score
🎯 Achieved 99.26% validation accuracy with CNN

⭐ Results Summary
CNN significantly outperformed traditional ML models, highlighting the effectiveness of deep learning in image-based tasks. This notebook serves as a great entry point into both machine learning fundamentals and deep learning applications.


