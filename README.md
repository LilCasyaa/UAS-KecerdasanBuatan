# UAS Kecerdasan Buatan

![Banner](images/banner.png)

## Analisis Klasifikasi Risiko Penyakit Jantung Menggunakan Algoritma Decision Tree dan Random Forest

## ✨ Informasi Proyek

- Mata Kuliah : Kecerdasan Buatan
- Kampus : Institut Teknologi Garut
- Program Studi : Teknik Informatika
- Semester : 4
- Nama : Aina Anastasya
- NIM : 2406123

---

## 📖 Deskripsi Proyek

Proyek ini merupakan tugas akhir mata kuliah **Kecerdasan Buatan** yang bertujuan untuk membangun model klasifikasi dalam memprediksi risiko penyakit jantung menggunakan teknik Machine Learning. Penelitian ini memanfaatkan **Heart Disease UCI Dataset** yang diperoleh dari Kaggle sebagai sumber data.

Dua algoritma klasifikasi, yaitu **Decision Tree** dan **Random Forest**, digunakan untuk membangun model prediksi. Kedua algoritma kemudian dibandingkan berdasarkan metrik evaluasi seperti **Accuracy, Precision, Recall, F1-Score**, dan **Confusion Matrix** untuk menentukan model dengan performa terbaik dalam mengklasifikasikan risiko penyakit jantung.

---

## 📂 Struktur Repository

```
UAS-KecerdasanBuatan/
│
├── README.md
├── Laporan_uas.md
├── UAS_KecerdasanBuatan_model.ipynb
│
└── data/
    ├── dataset/
    │   └── heart-disease.csv
    │
    └── jurnal/
        ├── [1] Decision Tree.pdf
        ├── [2] Random Forest.pdf
        ├── [3] Heart Disease.pdf
        ├── [4] Machine Learning.pdf
        └── [5] UCI Heart Disease.pdf
│
└── images/
```

---

## 🛠 Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 📂 Dataset

Dataset yang digunakan pada proyek ini adalah **Heart Disease UCI Dataset**, yang berisi data medis pasien untuk mengklasifikasikan risiko penyakit jantung.

**Informasi Dataset:**
- **Nama Dataset:** Heart Disease UCI
- **Jumlah Data:** 303 data pasien
- **Jumlah Fitur:** 13 fitur prediktor dan 1 target
- **Target:** Risiko penyakit jantung (0 = Tidak Berisiko, 1 = Berisiko)

**Sumber Dataset:**
https://www.kaggle.com/datasets/hartman/heart-disease-uci

---

## 📝 Langkah Pengerjaan

Proyek ini dikerjakan dengan tahapan sebagai berikut:

| Tahapan                                | Deskripsi                                                                                                                                                  |
| -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Business Understanding**          | Mengidentifikasi permasalahan prediksi penyakit jantung, menentukan tujuan penelitian, pengguna sistem, serta manfaat implementasi AI.                     |
| **2. Data Understanding**              | Mengumpulkan dataset Heart Disease UCI, memahami atribut, tipe data, dan target klasifikasi.                                                               |
| **3. Exploratory Data Analysis (EDA)** | Melakukan visualisasi distribusi data, histogram, boxplot, dan heatmap untuk memperoleh insight awal terhadap dataset.                                     |
| **4. Data Preparation**                | Melakukan pengecekan missing value, data duplikat, pembagian data latih dan data uji, serta menyiapkan dataset untuk proses pelatihan model.               |
| **5. Modeling**                        | Membangun model menggunakan algoritma Decision Tree dan Random Forest serta melakukan pelatihan model.                                                     |
| **6. Evaluation**                      | Mengevaluasi performa model menggunakan Accuracy, Precision, Recall, F1-Score, Confusion Matrix, dan Classification Report untuk menentukan model terbaik. |

---

## 📊 Ringkasan Model
| Model             | Alasan Pemilihan                                                                                                      |
| ----------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Decision Tree** | Mudah dipahami, mampu menghasilkan aturan keputusan yang jelas, serta memiliki proses pelatihan yang cepat.           |
| **Random Forest** | Memiliki akurasi yang lebih baik dan lebih tahan terhadap overfitting karena merupakan kumpulan banyak Decision Tree. |

---

## 📊 Hasil

Penelitian ini membandingkan performa algoritma Decision Tree dan Random Forest dalam mengklasifikasikan risiko penyakit jantung berdasarkan metrik Accuracy, Precision, Recall, F1-Score, serta Confusion Matrix. Hasil evaluasi menunjukkan performa masing-masing algoritma dan digunakan untuk menentukan model yang paling sesuai pada dataset yang digunakan.

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|---------:|----------:|-------:|---------:|
| Decision Tree | 0.786885	 | 0.750000	 | 0.909091	 | 0.821918 |
| Random Forest | 0.803279 | 0.756098	 | 0.939394 | 0.837838 |

---

## ▶️ Cara Menjalankan Proyek

### 1. Clone Repository

```bash
git clone https://github.com/USERNAME/UAS-KecerdasanBuatan.git
```

### 2. Masuk ke Folder Project

```bash
cd UAS-KecerdasanBuatan
```

### 3. Install Library

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Jalankan Notebook

Buka file `uas_model.ipynb` menggunakan Google Colab atau Jupyter Notebook, kemudian jalankan seluruh cell secara berurutan.

---

## Referensi
- Heart Disease UCI Dataset
- Scikit-learn Documentation
- WHO Cardiovascular Diseases

---

# 📄 Lisensi

Repository ini dibuat untuk memenuhi tugas UAS Mata Kuliah Kecerdasan Buatan.

---

<p align="center">
© 2026 Aina Anastasya 
</p>