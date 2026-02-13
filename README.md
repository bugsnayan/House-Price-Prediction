🚀 Network Intrusion Detection using Random Forest
📌 Project Overview

This project builds a Machine Learning model using Random Forest to detect network attacks (DDoS / Intrusion) from network traffic data.
The goal is to classify whether network traffic is Benign or Malicious using the CICIDS dataset.

This project demonstrates the complete ML pipeline:

Data preprocessing

Feature cleaning

Model training

Evaluation & visualization

📂 Dataset

Dataset Used: CICIDS2017 (Network Intrusion Dataset)

The dataset contains network traffic features such as:

Packet size

Flow duration

Source/Destination ports

Protocol type

Various network behaviour metrics

Target variable:

Label → Benign or Attack

🛠️ Tech Stack

Python 🐍

Pandas & NumPy (Data processing)

Scikit-learn (Machine Learning)

Matplotlib (Visualization)

Jupyter Notebook

⚙️ Machine Learning Workflow
1️⃣ Data Loading

Loaded CSV dataset using Pandas

Checked dataset shape, columns and info

2️⃣ Data Cleaning

Removed infinite values

Handled missing values

Dropped columns with more than 50% null values

Stripped unwanted column spaces

3️⃣ Feature Preparation

Converted categorical labels to numeric

Split dataset into:

Training set

Testing set

Train Test Split → 80% Train | 20% Test

4️⃣ Model Building

We used:

🌳 Random Forest Classifier

Why Random Forest?

Works well for large datasets

Handles high-dimensional data

Reduces overfitting

Provides high accuracy

Model parameters:

Multiple decision trees

Ensemble learning approach

5️⃣ Model Evaluation

Performance evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

Metrics used:

Precision

Recall

F1-Score

📊 Results

The model successfully learned to detect malicious traffic patterns.

Key outcomes:

High classification accuracy

Effective detection of attacks

Demonstrates real-world cybersecurity ML application

📈 Visualization

Bar graph used to compare model accuracy.

The visualization helps understand model performance clearly.

💡 Key Learnings

This project helped in understanding:

Real-world cybersecurity dataset handling

Data cleaning for ML pipelines

Feature engineering

Random Forest algorithm implementation

Model performance evaluation

🔮 Future Improvements

Possible enhancements:

Try other models (XGBoost, SVM, Deep Learning)

Hyperparameter tuning

Deploy as a web app

Real-time intrusion detection system

▶️ How to Run the Project
Step 1 — Clone Repository
git clone https://github.com/your-username/network-intrusion-randomforest.git
cd network-intrusion-randomforest

Step 2 — Install Dependencies
pip install pandas numpy scikit-learn matplotlib

Step 3 — Run Notebook

Open Jupyter Notebook and run:

Random_Forest.ipynb
