# 📘 Project Analisis Data Kategorik: Model Regresi Logistic Biner

Repositori ini berisi implementasi analisis **Regresi Logistik Biner** pada data **Formasi CPNS 2024** menggunakan bahasa pemrograman R. Analisis difokuskan pada pemodelan peluang sebuah formasi menerima pelamar disabilitas berdasarkan karakteristik formasi.

## Isi Proyek

Proyek ini mencakup:

- Pemilihan variabel prediktor dari dataset CPNS 2024  
- Pembagian data menjadi *train set* dan *test set* menggunakan `caret::createDataPartition()`  
- Pembangunan model regresi logistik biner menggunakan fungsi `glm()` dengan `family = binomial`  
- Interpretasi koefisien melalui **Odds Ratio** dan **Confidence Interval**  
- Evaluasi *goodness-of-fit* menggunakan uji **Hosmer–Lemeshow** (`ResourceSelection::hoslem.test`)  
- Evaluasi performa model dengan:
  - **Confusion Matrix** (`caret::confusionMatrix`)
  - **ROC Curve** dan **AUC** (`pROC::roc` dan `pROC::auc`)
- Seluruh analisis ditulis dalam format **R Markdown** dan dapat direproduksi.

## Dependensi

Analisis ini menggunakan beberapa paket R berikut:

- `tidyverse`
- `caret`
- `broom`
- `pROC`
- `ResourceSelection`

Pastikan paket-paket tersebut sudah terpasang sebelum menjalankan skrip.
