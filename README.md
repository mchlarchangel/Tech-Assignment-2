# Analisis Komparatif Model Machine Learning untuk Prediksi Pemeliharaan

## Deskripsi Proyek
Proyek ini berfokus pada evaluasi dan perbandingan kinerja dua model machine learning, Random Forest dan Gradient Boosting. Tujuan utamanya adalah menentukan model mana yang memberikan akurasi dan keandalan yang lebih baik dalam memprediksi kerusakan mesin.

## Dataset
Dataset yang digunakan dalam analisis ini adalah dataset `ai4i2020`, yang berisi berbagai fitur terkait kondisi operasi mesin:
- Air temperature [K]
- Process temperature [K]
- Rotational speed [rpm]
- Torque [Nm]
- Tool wear [min]
- Jenis Mesin
- Indikator Kegagalan Mesin (TWF, HDF, PWF, OSF, RNF)

## Pemodelan
Dua model utama yang diuji adalah:
- **Random Forest**
- **Gradient Boosting**

## Evaluasi Model
Model dievaluasi menggunakan data validasi dan data uji dengan metrik berikut:
- **Classification Report:** Laporan klasifikasi untuk melihat metrik seperti presisi, recall, dan F1-score.
- **Confusion Matrix:** Matriks kebingungan untuk melihat distribusi prediksi benar dan salah.
- **ROC-AUC Score:** Skor Area Under Curve untuk mengevaluasi kinerja model dalam hal prediksi probabilitas.

## Penyetelan Hyperparameter
Grid search digunakan untuk menemukan kombinasi hyperparameter terbaik untuk kedua model.

## Hasil dan Temuan
- Evaluasi awal dilakukan tanpa tuning hyperparameter.
- Setelah itu, model disetel menggunakan grid search untuk menemukan parameter terbaik.
- Hasil evaluasi model dibandingkan untuk menentukan model yang memberikan kinerja terbaik.

## Kesimpulan
Proyek ini memberikan wawasan tentang kinerja dua model machine learning dalam konteks prediksi pemeliharaan. Hasil menunjukkan model yang lebih unggul dalam hal akurasi dan keandalan berdasarkan metrik evaluasi yang digunakan.
