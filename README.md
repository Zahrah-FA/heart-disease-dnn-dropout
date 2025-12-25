# Penerapan Deep Neural Network untuk Klasifikasi Penyakit Jantung
## (Studi Kasus Binary Classification dengan Teknik Dropout)

## Deskripsi Proyek
Proyek ini merupakan tugas akhir mata kuliah Deep Learning yang bertujuan
menerapkan **Deep Neural Network (DNN)** untuk melakukan **klasifikasi penyakit jantung**
berdasarkan data medis pasien.

Model yang digunakan adalah **Deep Neural Network dengan teknik Dropout**
untuk mengurangi risiko overfitting pada proses pelatihan model.

---

## Tujuan
1. Membangun model Deep Neural Network untuk klasifikasi biner (penyakit jantung / tidak).
2. Menerapkan teknik **Dropout** sebagai regularisasi model.
3. Menganalisis performa model menggunakan grafik training dan validation.

---

## Dataset
Dataset yang digunakan adalah **Heart Disease Dataset (UCI / Kaggle)**.

### Struktur Dataset
- **Raw dataset**  
  `dataset/raw/heart_disease_raw.csv`  
  Dataset mentah yang masih mengandung data kategorikal dan nilai tidak konsisten.

- **Clean dataset**  
  `dataset/clean/heart_disease_clean.csv`  
  Dataset yang telah melalui proses:
  - Pembersihan data
  - Encoding data kategorikal
  - Normalisasi fitur numerik

---

## Metode Deep Learning
- Model: **Deep Neural Network (DNN)**
- Task: **Binary Classification**
- Regularization: **Dropout**
- Loss Function: Binary Crossentropy
- Optimizer: Adam

---

## Struktur Repository
heart-disease-dnn-dropout/
├── dataset/
│ ├── raw/
│ │ └── heart_disease_raw.csv
│ └── clean/
│ └── heart_disease_clean.csv
├── notebook/
│ └── heart_disease_dnn_dropout.ipynb
└── README.md

---

## Notebook
Seluruh proses eksplorasi data, preprocessing, pelatihan model,
dan evaluasi dilakukan pada notebook berikut:

`notebook/heart_disease_dnn_dropout.ipynb`

Notebook dibuat dan dijalankan menggunakan **Google Colab**.

## Cara Menjalankan Project
1. Clone repository
2. Buka notebook `notebook/heart_disease_dnn_dropout.ipynb`
3. Jalankan seluruh cell secara berurutan

---

## Author
Zahrah Fatimah Alhaq  
Program Studi / Mata Kuliah Deep Learning
