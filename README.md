<div align="center">

#  FRAUD DETECTION SYSTEM  
###  Ensemble Learning (CatBoost + LightGBM + ML Models)

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/ML-Ensemble%20Learning-orange?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-Synthetic%20Banking-purple?style=for-the-badge)

</div>

---

# Project Overview

Sistem ini merupakan **deteksi fraud transaksi perbankan** berbasis machine learning menggunakan pendekatan:

- Tree-based Models (Random Forest, XGBoost, LightGBM)
- Boosting (CatBoost sebagai model utama)
- Ensemble Learning (Soft Voting)
- Feature Selection (Random Forest Importance)
- Handling Imbalanced Data (RandomOverSampler)

---

# Objective

Membangun sistem yang mampu:

- Mendeteksi pelanggan berpotensi fraud / tidak
- Mengatasi imbalance dataset
- Mengoptimalkan performa model dengan ensemble
- Menyediakan interpretasi fitur penting

---

# Dataset

| Dataset | Jumlah Data | Fitur |
|--------|-------------|-------|
| Training | 22,916 | 21 fitur + target |
| Validation | 5,729 | 21 fitur |

📌 Target:
