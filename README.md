# Loan_Default_Risk_Model

Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat mengidentifikasi probabilitas default kredit pelanggan. Probabilitas default adalah kemungkinan bahwa seorang pelanggan akan gagal membayar kredit tepat waktu.

## Deskripsi Proyek

Dalam proyek ini, kami akan menggunakan data historis tentang pelanggan, termasuk informasi demografis, riwayat kredit, dan data eksternal seperti skor kredit, untuk membangun model yang dapat memprediksi probabilitas default dengan akurasi tinggi. Model ini akan membantu lembaga keuangan dalam mengelola risiko kredit dan membuat keputusan pemberian pinjaman yang lebih baik.

## Langkah-Langkah Proyek

1. **Eksplorasi Data**: Lakukan analisis eksplorasi data untuk memahami karakteristik dan pola dalam data historis pelanggan.
2. **Pemrosesan Data**: Lakukan pemrosesan data termasuk penanganan missing values, encoding variabel kategori, dan penskalaan fitur numerik.
3. **Pembangunan Model**: Bangun dan latih model machine learning menggunakan algoritma yang sesuai seperti Logistic Regression, Random Forest, atau Gradient Boosting.
4. **Evaluasi Model**: Evaluasi performa model menggunakan metrik yang relevan seperti ROC-AUC score, precision, recall, dan F1-score.
5. **Optimisasi Model**: Lakukan penyetelan parameter (hyperparameter tuning) dan optimisasi model untuk meningkatkan performa.
6. **Penyimpanan Model**: Simpan model terbaik ke dalam direktori models/ untuk penggunaan di masa depan.
7. **Penerapan**: Terapkan model pada data baru untuk membuat prediksi probabilitas default.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, jupyter
