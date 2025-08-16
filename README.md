# 🚨 Network Anomaly Detection using Isolation Forest & Autoencoder

This project applies **machine learning and deep learning** techniques to detect anomalies in network traffic using the **KDD Cup 1999 dataset**. The goal is to compare the performance of a **traditional ML approach (Isolation Forest)** with a **deep learning approach (Autoencoder)** for intrusion detection.

---


## 🎯 Objectives
- Preprocess the **KDD Cup 1999 dataset** for anomaly detection.
- Train an **Isolation Forest** model to detect anomalies.
- Train a **Deep Autoencoder** for unsupervised anomaly detection.
- Compare both models using standard evaluation metrics.

---

## ⚙️ Tech Stack
- **Python** (NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow/Keras)
- **Jupyter Notebook** for experimentation and visualization

---

## 📊 Results
- **Isolation Forest**  
  - Strength: Quick training and interpretable.  
  - Weakness: Lower accuracy on complex attack patterns.  

- **Autoencoder**  
  - Strength: Captures hidden patterns, better performance on high-dimensional data.  
  - Weakness: Higher computational cost.  

---

## 📌 Future Work
- Experiment with **Variational Autoencoders (VAE)** or **GAN-based anomaly detection**.  
- Extend analysis to other intrusion detection datasets like **NSL-KDD** or **UNSW-NB15**.  
- Deploy as a lightweight **real-time anomaly detection service**.
