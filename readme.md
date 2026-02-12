# 🛡 Intrusion Detection System (IDS) with Neural Networks  
*Detecting network intrusions using deep learning on the KDD dataset*

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/Deep%20Learning-TensorFlow%2FKeras-orange)](https://www.tensorflow.org/)  
[![Dataset: KDD Cup 99](https://img.shields.io/badge/Dataset-KDD%20Cup%2099-green)](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

---

## 📜 Table of Contents

- [Overview](#overview)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)   
  - [Installation](#installation)  
- [Usage](#usage)  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Screenshots](#screenshots)  
- [Contributing](#contributing)  
- [License](#license)

---

## 📖 Overview  
This project implements a **Neural Network-based Intrusion Detection System (IDS)** trained on the **KDD Cup 99** dataset.  
It aims to classify network traffic into normal activity or various intrusion categories using supervised learning.

**Key Highlights:**
- Utilizes **Multi-Layer Perceptron (MLP)** architecture.
- Trains on preprocessed **KDD Cup 99** dataset.
- Includes data preprocessing, normalization, and evaluation.
- Supports visualization of model performance.

Repository: [GitHub Link](https://github.com/Aditya-hub2k03/IDS_Neural_Networks_KDD)

---

## 🚀 Getting Started

### ✅ Prerequisites
- **Python 3.x**
- **TensorFlow/Keras**
- **Pandas, NumPy, Matplotlib**

### 📦 Installation
```bash
# Clone the repository
git clone https://github.com/Aditya-hub2k03/IDS_Neural_Networks_KDD.git
cd IDS_Neural_Networks_KDD

# Install dependencies
pip install -r requirements.txt
```

---

## 🛠 Usage
1. Download the **KDD Cup 99** dataset and place it in the designated folder.
2. Run the training script:
   ```bash
   python train_ids.py
   ```
3. View training metrics and evaluate model performance.

---

## 🔍 Features  
- Data preprocessing and feature scaling
- Training a deep learning model on network intrusion data
- Accuracy and loss visualizations
- Classification report for each attack category

---

## 📂 Project Structure
```
├── train_ids.py         # Main training script
├── preprocess.py        # Data preprocessing module
├── requirements.txt     # Dependencies
├── dataset/             # KDD dataset files
└── models/              # Saved model checkpoints
```

---

## 📷 Screenshots  

### 🔹 Model Training Progress  
![Training Graph](screenshots/training_progress.png)  

### 🔹 Confusion Matrix  
![Confusion Matrix](screenshots/confusion_matrix.png)  

### 🔹 Sample Predictions  
![Sample Predictions](screenshots/sample_predictions.png)  


---

## 🤝 Contributing
Contributions are welcome!  
- Open an **Issue**
- Submit a **Pull Request**

---

## 📜 License
Licensed under the repository's specified terms. See LICENSE file.
