🔧 Predictive Maintenance for IoT Machines using Deep Learning
📌 Overview
This project implements a deep learning-based predictive maintenance system for industrial IoT machines. The model analyzes real-time sensor data to classify machine health as Normal or Failure, enabling early fault detection and reduced downtime.

The system is built using the AI4I 2020 Predictive Maintenance dataset and a Feed-Forward Neural Network (FNN) architecture.

🚀 Problem Statement
Traditional maintenance strategies (reactive and preventive) lead to unnecessary costs and unexpected breakdowns.
This project aims to develop a data-driven solution that predicts equipment failure before it occurs using IoT sensor data and deep learning techniques.

📊 Dataset
Dataset: AI4I 2020 Predictive Maintenance Dataset

Records: 10,000 machine instances

Features:

Air Temperature (K)

Process Temperature (K)

Rotational Speed (RPM)

Torque (Nm)

Tool Wear (min)

Failure Label (0 = Normal, 1 = Failure)

🧠 Model Architecture
Feed-Forward Neural Network (FNN)

Hidden layers with ReLU activation

Output layer with Sigmoid activation

Loss Function: Binary Cross-Entropy

Optimizer: Adam

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

⚙️ Implementation Steps
Data preprocessing (cleaning, encoding, normalization)

Train-test split (80:20)

Model training for 100 epochs

Performance evaluation using confusion matrix and classification metrics

Model saved as .h5 for deployment

📈 Results
Training Accuracy: 99.9%

Testing Accuracy: 99.8%

High precision and recall with minimal false alarms

Strong generalization without overfitting

🛠️ Tech Stack
Python

TensorFlow / Keras

NumPy

Pandas

Scikit-learn

Matplotlib

🏭 Applications
Smart Manufacturing

Industry 4.0 Systems

Industrial IoT Monitoring

Real-time Fault Detection

🔮 Future Enhancements
Implementation of LSTM/GRU for time-series modeling

Edge deployment for real-time inference

Integration with IoT dashboards

Explainable AI (XAI) for better interpretability
