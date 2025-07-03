# 🛡️ Intrusion Detection Using Convolutional Neural Networks (CNN)

Intrusion Detection System (IDS) berfungsi untuk mengidentifikasi aktivitas berbahaya atau mencurigakan dalam lalu lintas jaringan. Dalam proyek ini, CNN digunakan untuk mengenali pola serangan dari data lalu lintas jaringan, khususnya berdasarkan dataset intrusi dari Kaggle.

---

## 🗂️ Isi Notebook

Notebook ini mencakup:

1. **Import Library**  
   Menggunakan `pandas`, `numpy`, `seaborn`, `tensorflow`, `sklearn`, dll.

2. **Download Dataset via `opendatasets`**  
   Dataset otomatis diunduh dari Kaggle melalui `opendatasets` (dengan kredensial).

3. **Preprocessing Data**  
   - Drop kolom tidak penting  
   - Normalisasi fitur  
   - Encoding label  
   - Split data

4. **CNN Architecture**  
   - Conv1D, Flatten, Dense, Dropout  
   - Output sigmoid untuk binary classification

5. **Training & Evaluasi**  
   - Confusion Matrix  
   - Accuracy, Precision, Recall  
   - Visualisasi hasil

---

## 📦 Dataset

Dataset yang digunakan:

🔗 [Network Intrusion Dataset](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset)  
📄 File: `Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv`

---
