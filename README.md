# README: Rigkasan dan Gambaran dari Proyek UAS

## 1. Judul / Topik Project dan Identitas Lengkap

**Judul Proyek**: Analisis Perbandingan Algoritma Logistic Regression, KNN, Naive Bayes, dan SVM dalam Mengotentikasi Uang Kertas

**Identitas**:
- Nama: Muhammad Abil Wildan Syachviar
- NIM: A11.2022.14784
- Kelompok: A11.4519

---

## 2. Ringkasan dan Permasalahan Proyek

**Ringkasan**:
Proyek ini bertujuan untuk menganalisis performa algoritma Logistic Regression, KNN, Naive Bayes, dan SVM dalam tugas mengotentikasi uang kertas berdasarkan karakteristik tertentu yang diperoleh dari dataset.

**Permasalahan**:
Bagaimana menentukan algoritma terbaik untuk mengotentikasi uang kertas secara akurat, efisien, dan andal?

**Tujuan**:
1. Mengevaluasi kinerja empat algoritma machine learning.
2. Menentukan model terbaik berdasarkan metrik evaluasi yang relevan.
3. Menyediakan rekomendasi untuk implementasi lebih lanjut dalam autentikasi uang kertas.

---

## 3. Penjelasan Dataset, EDA, dan Proses Features Dataset

**Dataset**:
Dataset yang digunakan berisi fitur-fitur numerik yang menggambarkan karakteristik fisik uang kertas, seperti varian, skewness, curtosis, dan entropi gambar uang kertas.

**Exploratory Data Analysis (EDA)**:
- Analisis deskriptif untuk memahami distribusi data dan outlier.
- Pemetaan hubungan antar fitur dengan matriks korelasi.
- Visualisasi data untuk mengidentifikasi pola dan distribusi.

**Proses Features Dataset**:
- Pembersihan data: Menghapus nilai yang hilang dan duplikasi.
- Normalisasi: Menstandarisasi fitur agar memiliki skala yang sama.
- Pembagian data: Dataset dibagi menjadi data latih dan data uji dengan proporsi 80:20.

---

## 4. Proses Learning / Modeling

**Algoritma yang Digunakan**:
1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Naive Bayes
4. Support Vector Machine (SVM)

**Langkah-Langkah**:
- Menerapkan setiap algoritma pada data latih.
- Menyimpan model terbaik untuk evaluasi selanjutnya.

---

## 5. Performa Model

**Metrik Evaluasi**:
- **Akurasi**: Proporsi prediksi yang benar terhadap total prediksi.
- **Precision**: Ketepatan prediksi positif.
- **Recall**: Kemampuan model mendeteksi semua nilai positif.
- **F1-Score**: Harmoni antara precision dan recall.
- **Confusion Matrix**: Matriks yang menunjukkan jumlah prediksi benar dan salah untuk masing-masing kelas.

---

## 6. Diskusi Hasil dan Kesimpulan

**Diskusi**:
- Algoritma yang unggul dalam presisi dan recall, cocok untuk aplikasi dengan toleransi rendah terhadap kesalahan prediksi positif.
- Algoritma yang memiliki performa konsisten di semua metrik.

**Kesimpulan**:
1. Algoritma terbaik dan terburuk untuk autentikasi uang kertas.
2. Proyek ini menunjukkan pentingnya evaluasi mendalam untuk memilih algoritma yang sesuai.


