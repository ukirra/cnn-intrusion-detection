# 🛡️ Intrusion Detection Using Convolutional Neural Networks (CNN)

An Intrusion Detection System (IDS) is designed to identify malicious or suspicious activities within network traffic. In this project, a Convolutional Neural Network (CNN) is used to detect attack patterns in network traffic data, specifically using an intrusion dataset from Kaggle.

---

## 🗂️ Notebook Contents

This notebook includes:

1. **Library Imports**  
   Utilizing `pandas`, `numpy`, `seaborn`, `tensorflow`, `sklearn`, and more.

2. **Dataset Download via `opendatasets`**  
   Automatically downloads the dataset from Kaggle using the `opendatasets` library (requires Kaggle credentials).

3. **Data Preprocessing**  
   - Dropping irrelevant columns  
   - Normalizing features  
   - Label encoding  
   - Splitting the data

4. **CNN Architecture**  
   - Conv1D, Flatten, Dense, Dropout  
   - Sigmoid output for binary classification

5. **Training & Evaluation**  
   - Confusion Matrix  
   - Accuracy, Precision, Recall  
   - Result visualizations

---

## 📦 Dataset

The dataset used in this project:

🔗 [Network Intrusion Dataset](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset)  
📄 File: `Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv`

---
