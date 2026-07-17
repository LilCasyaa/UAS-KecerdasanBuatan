# UAS Kecerdasan Buatan

## Analisis Klasifikasi Risiko Penyakit Jantung Menggunakan Algoritma Decision Tree dan Random Forest

## 📖 Deskripsi Proyek

Proyek ini merupakan tugas akhir mata kuliah **Kecerdasan Buatan** yang bertujuan untuk membangun model klasifikasi dalam memprediksi risiko penyakit jantung menggunakan teknik machine learning. Penelitian ini memanfaatkan **Heart Disease UCI Dataset** yang diperoleh dari Kaggle sebagai sumber data.

Dua algoritma klasifikasi, yaitu **Decision Tree** dan **Random Forest**, digunakan untuk membangun model prediksi. Kedua algoritma kemudian dibandingkan berdasarkan metrik evaluasi seperti **Accuracy, Precision, Recall, F1-Score**, dan **Confusion Matrix** untuk menentukan model dengan performa terbaik dalam mengklasifikasikan risiko penyakit jantung.

---

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

1. Menentukan topik klasifikasi risiko penyakit jantung.
2. Mengumpulkan dataset Heart Disease UCI dari Kaggle.
3. Melakukan Data Understanding untuk memahami struktur dan karakteristik dataset.
4. Melakukan Exploratory Data Analysis (EDA) melalui visualisasi data.
5. Melakukan Data Preparation dengan memisahkan fitur dan target serta membagi data menjadi data latih dan data uji.
6. Membangun model klasifikasi menggunakan algoritma Decision Tree.
7. Membangun model klasifikasi menggunakan algoritma Random Forest.
8. Membandingkan performa kedua algoritma menggunakan metrik evaluasi.
9. Melakukan evaluasi model menggunakan Accuracy, Precision, Recall, F1-Score, Classification Report, dan Confusion Matrix.
10. Menentukan model terbaik berdasarkan hasil evaluasi.

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

## 📊 Hasil

Penelitian ini membandingkan performa algoritma Decision Tree dan Random Forest dalam mengklasifikasikan risiko penyakit jantung berdasarkan metrik Accuracy, Precision, Recall, F1-Score, serta Confusion Matrix. Hasil evaluasi menunjukkan performa masing-masing algoritma dan digunakan untuk menentukan model yang paling sesuai pada dataset yang digunakan.
