# APT Detection using Hybrid Deep Learning

This repository implements hybrid deep learning models for detecting **Advanced Persistent Threats (APT)** from network traffic data.  
The project is designed for **research and educational purposes** in cybersecurity and machine learning.

---

## Objectives
- Detect multi-stage and long-term APT attacks
- Handle imbalanced and sequential network traffic data
- Evaluate hybrid deep learning architectures for intrusion detection

---

## Project Structure
APT_DL_Hybrid/
├── data/
│ ├── raw/ # Original datasets
│ ├── processed/ # Preprocessed data
│ └── splits/ # Train / validation / test sets
├── src/
│ ├── preprocess.py # Data preprocessing
│ ├── model.py # Model architectures
│ ├── train.py # Training pipeline
│ ├── evaluate.py # Evaluation metrics
│ └── utils.py # Utility functions
├── experiments/
│ ├── results/ # Experimental results
│ └── figures/ # Plots and visualizations
├── main.py
├── requirements.txt
└── README.md

yaml
Sao chép mã

---

## Datasets
The framework supports common intrusion detection and APT datasets:
- CIC-IDS2017 / CIC-IDS2018
- UNSW-NB15
- DAPT 2020
- CIC-APT-2024

---

## Models
- CNN
- LSTM / BiLSTM
- CNN–LSTM
- CNN–LSTM with Attention
- Optimization-based Hybrid Models (GA, SMA, etc.)

---

## Workflow
1. Data preprocessing and balancing
2. Feature extraction and sequence modeling
3. Model training
4. Performance evaluation

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Usage
Install dependencies:
pip install -r requirements.txt

Train the model:

python src/train.py

Evaluate the model:

python src/evaluate.py