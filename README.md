# 📘 Project Analisis Data Kategorik: Model Regresi Logistic Biner

Repositori ini berisi implementasi analisis **Regresi Logistik Biner** pada data **Formasi CPNS 2024** menggunakan R. Analisis difokuskan pada pemodelan peluang sebuah formasi menerima pelamar disabilitas berdasarkan karakteristik formasi.

## 📄 Laporan RPubs
Hasil lengkap analisis dapat dilihat di RPubs melalui link berikut:

👉 **http://rpubs.com/Flyy/1375829**

## Isi Proyek

Proyek ini mencakup:

- Pemilihan variabel prediktor dari dataset CPNS 2024  
- Pembagian data menjadi *train set* dan *test set*  
- Pembangunan model logistik menggunakan `glm()`  
- Interpretasi koefisien melalui **Odds Ratio**  
- Uji goodness-of-fit (Hosmer–Lemeshow)  
- Evaluasi performa menggunakan **Confusion Matrix**, **ROC Curve**, dan **AUC**  
- Analisis ditulis dalam format **R Markdown** dan dapat direproduksi

## Dependensi

- `tidyverse`
- `caret`
- `broom`
- `pROC`
- `ResourceSelection`

## Tujuan

Menunjukkan bagaimana regresi logistik biner dapat digunakan untuk memahami faktor-faktor yang memengaruhi penerimaan pelamar disabilitas pada formasi CPNS.
