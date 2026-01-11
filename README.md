# uas_kecerdasanbuatan2

Bedah Jurnal Machine Learning
Prediksi Harga Rumah Menggunakan Multiple Linear Regression

Repository ini berisi hasil **(analisis kritis (bedah jurnal)** dan **implementasi ulang (re-testing)** model Machine Learning berbasis regresi, menggunakan dataset yang sama dengan jurnal nasional Indonesia.

Informasi Jurnal
- **Judul Jurnal**: Analisis Prediksi Harga Rumah Sesuai Spesifikasi Menggunakan Multiple Linear Regression  
- **Penulis**: Muhammad Labib Mu’trashim, dkk.  
- **Jurnal**: Jurnal Informatik  
- **Volume & Nomor**: Vol. 17, No. 3  
- **Tahun**: 2021  
- **Bidang**: Machine Learning (Regresi)

Tujuan dari proyek ini adalah:
1. Melakukan implementasi ulang model Multiple Linear Regression.
2. Melakukan pengujian ulang menggunakan dataset yang sama dengan jurnal.
3. Membandingkan hasil eksperimen dengan hasil yang dilaporkan pada jurnal.
4. Melakukan analisis kritis terhadap perbedaan hasil yang diperoleh.

Dataset
- **Sumber Dataset**: Kaggle  
- **Jumlah Data**: 1001 data rumah  
- **Wilayah**: Jakarta Selatan  

Metode yang digunakan dalam penelitian ini adalah **Multiple Linear Regression** dengan tahapan sebagai berikut:
1. Data preprocessing
2. Pembagian data (80% data latih, 20% data uji)
3. Pelatihan model regresi
4. Evaluasi model menggunakan **R² Score**

Implementasi Ulang (Re-testing)
Model diimplementasikan ulang menggunakan bahasa pemrograman **Python** dengan bantuan library:
- pandas
- scikit-learn

Hasil dan Evaluasi
Perbandingan hasil antara jurnal dan implementasi ulang adalah sebagai berikut:

| Aspek | Jurnal | Re-testing |
|------|-------|------------|
| Metode | Multiple Linear Regression | Multiple Linear Regression |
| Jumlah Data | 1001 | 1001 |
| Pembagian Data | 80% : 20% | 80% : 20% |
| Akurasi (R² Score) | 0.66 | ± 0.65 |

Hasil implementasi ulang menunjukkan nilai akurasi yang mendekati hasil jurnal, sehingga model dapat direproduksi dengan baik.

Analisis Kritis
Perbedaan hasil antara jurnal dan implementasi ulang dapat disebabkan oleh beberapa faktor:
1. Pembagian data latih dan data uji yang bersifat acak (*random split*).
2. Adanya outliers ekstrem pada dataset.
3. Tidak dilakukan normalisasi atau standarisasi data.
4. Karakteristik data harga rumah yang bersifat non-linear.

Selain itu, jurnal tidak membandingkan performa metode ini dengan metode regresi lain.

Kesimpulan
Multiple Linear Regression mampu memprediksi harga rumah berdasarkan spesifikasi bangunan dengan akurasi yang cukup baik. Namun, model ini masih memiliki keterbatasan dan berpotensi ditingkatkan dengan metode Machine Learning lainnya.
