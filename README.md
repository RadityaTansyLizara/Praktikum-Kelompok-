# 🩺 Aplikasi Prediksi Tingkat Obesitas Menggunakan Decision Tree

## 📖 Deskripsi Proyek

Aplikasi ini merupakan sistem klasifikasi tingkat obesitas yang dibangun menggunakan **Python**, **Streamlit**, dan algoritma **Decision Tree**. Tujuan dari aplikasi ini adalah untuk memprediksi kategori tingkat obesitas seseorang berdasarkan kebiasaan makan, aktivitas fisik, serta kondisi kesehatan yang terdapat pada dataset.

Aplikasi menyediakan antarmuka yang sederhana dan interaktif sehingga pengguna dapat melihat data, melatih model, serta menampilkan hasil evaluasi dan visualisasi secara langsung.

---

## 📊 Dataset

Dataset yang digunakan adalah:

**Estimation of Obesity Levels Based on Eating Habits and Physical Condition**

Dataset berisi berbagai atribut yang berkaitan dengan gaya hidup dan kondisi fisik seseorang, seperti:

- Gender (Jenis Kelamin)
- Age (Usia)
- Height (Tinggi Badan)
- Weight (Berat Badan)
- Family History with Overweight
- Frequent Consumption of High Calorie Food
- Frequency of Vegetable Consumption
- Number of Main Meals
- Water Consumption
- Physical Activity Frequency
- Transportation Used
- Dan atribut lainnya

### 🎯 Target Klasifikasi

Model akan mengklasifikasikan data ke dalam salah satu kategori berikut:

- Insufficient Weight
- Normal Weight
- Overweight Level I
- Overweight Level II
- Obesity Type I
- Obesity Type II
- Obesity Type III

---

## 🌳 Algoritma yang Digunakan

### Decision Tree Classifier

Decision Tree merupakan algoritma Machine Learning yang bekerja dengan membangun struktur pohon keputusan berdasarkan atribut yang paling berpengaruh terhadap data.

### Alasan Memilih Decision Tree

- Cocok untuk permasalahan klasifikasi.
- Dapat menangani data numerik dan kategorikal.
- Mudah dipahami dan diinterpretasikan.
- Memiliki performa yang baik pada dataset obesitas.
- Dapat digunakan untuk mengetahui fitur yang paling berpengaruh terhadap hasil prediksi.

---

## ✨ Fitur Aplikasi

### 1. Pengelolaan Dataset
- Upload dataset dalam format CSV.
- Menampilkan data asli (preview dataset).
- Menampilkan informasi dataset.

### 2. Pelatihan Model
- Preprocessing data.
- Encoding data kategorikal.
- Pembagian data training dan testing.
- Pelatihan model menggunakan algoritma Decision Tree.

### 3. Evaluasi Model
- Menghitung akurasi model.
- Menampilkan Confusion Matrix.
- Menampilkan hasil prediksi model.

### 4. Visualisasi Data
- Visualisasi distribusi tingkat obesitas.
- Visualisasi Confusion Matrix.
- Analisis hasil klasifikasi.

---

## 🛠️ Teknologi yang Digunakan

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## 🔄 Alur Kerja Sistem

1. Dataset diunggah atau dibaca oleh aplikasi.
2. Data kategorikal diubah menjadi data numerik menggunakan Label Encoding.
3. Dataset dibagi menjadi data training dan data testing.
4. Model Decision Tree dilatih menggunakan data training.
5. Model melakukan prediksi terhadap data testing.
6. Hasil prediksi dievaluasi menggunakan metrik evaluasi.
7. Hasil ditampilkan dalam bentuk tabel dan visualisasi.

---

## 📈 Hasil Implementasi

Model berhasil melakukan klasifikasi tingkat obesitas berdasarkan karakteristik fisik dan kebiasaan hidup seseorang.

Hasil evaluasi ditampilkan dalam bentuk:

- Distribusi kelas obesitas
- Confusion Matrix
- Akurasi model
- Visualisasi hasil klasifikasi

Visualisasi tersebut membantu pengguna memahami performa model secara lebih mudah dan informatif.

---

## 🚀 Cara Menjalankan Aplikasi

### 1. Clone Repository

```bash
git clone https://github.com/username/nama-repository.git
```

### 2. Masuk ke Folder Project

```bash
cd nama-repository
```

### 3. Install Dependency

```bash
pip install streamlit pandas numpy scikit-learn matplotlib seaborn
```

### 4. Jalankan Aplikasi

```bash
streamlit run praktikum.py
```

### 5. Buka Browser

```text
http://localhost:8501
```

---

## 📁 Struktur Project

```text
📦 Project
├── praktikum.py
├── dataset.csv
├── requirements.txt
└── README.md
```

---


## 🎓 Kesimpulan

Aplikasi Prediksi Tingkat Obesitas berhasil dibangun menggunakan algoritma Decision Tree dan framework Streamlit. Sistem mampu mengolah data kebiasaan makan dan kondisi fisik untuk mengklasifikasikan tingkat obesitas secara otomatis.

Selain memberikan hasil prediksi, aplikasi juga menyajikan visualisasi data yang membantu pengguna memahami distribusi data serta performa model dengan lebih mudah dan interaktif.

## Dokumentasi
<img width="959" height="435" alt="image" src="https://github.com/user-attachments/assets/c862dc83-921c-4c5c-af40-88fe7fac88c2" />

<img width="959" height="475" alt="image" src="https://github.com/user-attachments/assets/0fee18b5-a2b0-4bc9-8e86-560c06fe81f4" />

<img width="953" height="440" alt="image" src="https://github.com/user-attachments/assets/4ff8d4f5-eac7-4358-a031-fef5b969913a" />
