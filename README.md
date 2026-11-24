hAlo ini fp ML kita :3

# Proposal Final Project

## 1. Judul, Anggota, dan Dataset

- **Judul** : Prediksi Hasil Panen Padi (Paddy Yield) Menggunakan Model Regresi Machine Learning
- **Anggota** :

1. Maria Putu Evelyne Corena Puryatma - 5054251011
2. Rafa Rizki Aira Swala - 5054251017
3. Dinnetza Araafya Yudetti - 5054251018
4. A. Toriq azhar - 5054251047
5. Kadek Nathania Gavrila Astika - 5054251050

- **Dataset** : Paddy Dataset (UCI Machine Learning Repository) - https://archive.ics.uci.edu/dataset/1186/paddy+dataset

## 2. Latar Belakang Singkat

Padi adalah makanan pokok masyarakat Indonesia, sehingga ketersediaannya sangat penting untuk ketahanan pangan. Produksi padi dipengaruhi banyak faktor, seperti cuaca, jenis tanah, dan pupuk, sehingga hasil panen sulit diperkirakan dengan cara konvensional. Prediksi hasil panen yang akurat membantu petani dan pemerintah dalam merencanakan produksi dan mengambil kebijakan pangan sebelum terjadi kekurangan. Karena itu, penerapan machine learning untuk memprediksi hasil panen menjadi hal yang mendesak.

## 3. Deskripsi Singkat Dataset

EDA first |

## 4. Rencana Metode

### 4.1 Model yang Dicoba

Model dipilih berdasarkan paper _Comparative Analysis of Machine Learning Regression Models for Paddy Yield Prediction_:

1. Linear Regression
2. Random Forest Regressor
3. Support Vector Regression (SVR)
4. K-Nearest Neighbors Regressor (opsional)
5. Decision Tree Regressor (opsional)

### 4.2 Desain Sistem (for Flowchart)

```text
Dataset Paddy
    -> Data Cleaning
    -> Encoding fitur kategorikal
    -> Standardisasi fitur
    -> Split data (train : test = [80 : 20])
    -> Training model (LR, RF, SVR, ...)
    -> Hyperparameter tuning ([placeholder])
    -> Evaluasi
    -> Perbandingan model dan kesimpulan
```

[Gambar Flowchart]

### 4.3 Skenario Uji Coba

| Skenario | Deskripsi                                                      |
| -------- | -------------------------------------------------------------- |
| 1        | Split 80:20, semua fitur, parameter default                    |
| 2        | [Placeholder: split lain, mis. 70:30]                          |
| 3        | [Placeholder: dengan hyperparameter tuning / cross-validation] |
| 4        | [Placeholder: dengan seleksi fitur]                            |

### 4.4 Metrik Evaluasi

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² (Koefisien determinasi)

# Source

- Dataset : https://archive.ics.uci.edu/dataset/1186/paddy+dataset (India Paddy)

- Paper :

1. Comparative Analysis of Machine Learning
   Regression Models for Paddy Yield Prediction
   10.65780/bima.v1i3.17
2. Panel Data Analysis on Rice (Paddy) Production in Indonesia2018-2021  
   10.46336/ijmsc.v1i3.27
