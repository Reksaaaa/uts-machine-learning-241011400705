# UTS Machine Learning

## Identitas Mahasiswa
* **Nama** : Rheksa Pramatya Wijayanto
* **NIM**  : 241011400705

---

## Ringkasan Hasil Eksperimen

### 1. Bagian A – Linear Regression (Ads_Data.csv)
* **Persamaan Garis Regresi**: Menghasilkan nilai *slope* ($m$) dan *intercept* ($b$) untuk memprediksi tingkat penjualan berdasarkan biaya iklan.
* **Evaluasi Model**:
  * **MSE (Mean Squared Error)**: Mengukur rata-rata kuadrat kesalahan prediksi pada data testing.
  * **$R^2$ Score**: Menunjukkan seberapa baik varians variabel dependen dapat dijelaskan oleh biaya iklan.

---

### 2. Bagian B – Logistic Regression (Email_Data.csv)
* **Model Klasifikasi Spam**: Menggunakan fungsi *sigmoid* dan *Gradient Descent* untuk memprediksi email spam.
* **Evaluasi & Eksperimen Threshold**:
  * **Confusion Matrix** (pada threshold standard 0.5): Memiliki tingkat akurasi yang sangat baik.
  * **Akurasi Threshold 0.3**: 80.00%
  * **Akurasi Threshold 0.5**: 93.33% (Optimal)
  * **Akurasi Threshold 0.7**: 80.00%
* **Visualisasi**: Menggunakan *contourf* untuk menampilkan *Decision Boundary* pemisah antara email spam dan non-spam.

---

### 3. Bagian C & Bonus – Pemahaman Konsep & Scikit-Learn
* **Pemahaman Konsep**: Penjelasan mengenai perbedaan regresi vs klasifikasi, *Normal Equation* vs *Gradient Descent*, *Overfitting*, *MSE* vs *Log Loss*, dan penyebab variasi hasil antar praktikan.
* **Perbandingan Scikit-Learn**: Hasil koefisien manual konsisten dan selaras dengan implementasi bawaan pustaka `scikit-learn` (`LinearRegression` & `LogisticRegression`).

---

## Struktur Repositori
```text
uts-machine-learning-241011400705/
├── README.md         # Ringkasan hasil dan identitas
├── tugas_UTS.ipynb   # File notebook utama lengkap dengan output
├── Ads_Data.csv      # Dataset Linear Regression
└── Email_Data.csv    # Dataset Logistic Regression
