# Credit Card Fraud Detection – Federated Learning

This project showcases the use of **Federated Learning** via **TensorFlow Federated (TFF)** to detect fraudulent credit card transactions while preserving data privacy. It also compares the federated approach with traditional centralized training using **scikit-learn**.

---

## 🔍 Project Overview

Credit card fraud detection requires analyzing transaction patterns to identify suspicious behavior. However, centralized machine learning models may compromise user privacy. **Federated Learning (FL)** enables decentralized model training across multiple clients, allowing raw data to remain local.

This project is organized into two main Google Colab notebooks:

### 📂 Notebooks

1. **[Federated Learning Implementation](https://colab.research.google.com/drive/1whNq-11KH6dYNYRR9N0OkdwTXVhem2y_?usp=sharing)**  
   - Built using **TensorFlow Federated (TFF)**.  
   - Simulates multiple clients training a model collaboratively without sharing their raw data.  
   - Demonstrates secure and privacy-aware model training.

2. **[Centralized Credit Card Fraud Detection](https://colab.research.google.com/drive/19cBVO7eMBWpJgu-Gy4aqoctldn7s4e3U?usp=sharing)**  
   - Implements a baseline model using **scikit-learn**.  
   - Provides data preprocessing, training, and evaluation for comparison with the federated model.

---

## 📊 Dataset

- Dataset: [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- Features are anonymized for privacy.  
- Highly imbalanced dataset with only ~0.17% fraudulent transactions.

---

## ⚙️ Technologies Used

- **Python**  
- **TensorFlow Federated (TFF)**  
- **TensorFlow**  
- **scikit-learn**  
- **Google Colab**

---

## ✅ Features

- End-to-end implementation of federated learning for fraud detection.  
- Centralized vs. federated model performance comparison.  
- Emphasis on data privacy and decentralized training.

---

## 🚀 Future Enhancements

- Integrate advanced models ANN in the federated setup.  
- Apply class balancing techniques like SMOTE or weighted loss functions.  
- Explore differential privacy for added security.
