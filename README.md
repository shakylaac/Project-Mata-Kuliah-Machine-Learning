# Prediksi Customer Churn pada Data Telekomunikasi Menggunakan XGBoost dan Support Vector Machine

## Deskripsi Proyek
Proyek ini membahas penerapan *machine learning* untuk memprediksi *customer churn* pada data telekomunikasi. *Customer churn* merupakan kondisi ketika pelanggan berhenti menggunakan layanan yang disediakan oleh suatu perusahaan.
Prediksi churn dapat membantu perusahaan memahami karakteristik pelanggan yang berpotensi berhenti berlangganan sehingga dapat menjadi bahan pertimbangan dalam menyusun strategi retensi pelanggan.
Dalam proyek ini, dua algoritma yang digunakan adalah **XGBoost** dan **Support Vector Machine (SVM)**. Keduanya diterapkan untuk membangun model prediksi churn dan dianalisis untuk mengetahui kemampuan masing-masing model dalam mengklasifikasikan pelanggan.

## Dataset
- **Nama Dataset:** Telco Customer Churn Data
- **Sumber:** [Kaggle – Telco Customer Churn Data](https://www.kaggle.com/datasets/dhrubangtalukdar/telco-customer-churn-data)
- **Deskripsi:** Dataset berisi informasi pelanggan telekomunikasi yang dapat digunakan untuk menganalisis karakteristik pelanggan dan memprediksi kemungkinan terjadinya churn.
- **Tujuan Penggunaan:** Dataset digunakan untuk eksplorasi data, preprocessing, pembangunan model klasifikasi, serta evaluasi dan perbandingan performa XGBoost dan SVM.

## Tujuan Proyek
1. Memahami karakteristik data pelanggan telekomunikasi.
2. Melakukan pengolahan dan persiapan data sebelum pemodelan.
3. Membangun model prediksi *customer churn* menggunakan XGBoost dan SVM.
4. Mengevaluasi performa model berdasarkan metrik klasifikasi yang digunakan.
5. Membandingkan performa kedua algoritma untuk mengetahui model yang memberikan hasil lebih baik pada dataset yang digunakan.

## Metode yang Digunakan
### 1. XGBoost
XGBoost (*Extreme Gradient Boosting*) merupakan algoritma *ensemble learning* yang membangun model secara bertahap untuk meningkatkan kemampuan prediksi. Algoritma ini digunakan untuk mempelajari pola pada data pelanggan yang berkaitan dengan kemungkinan terjadinya churn.
### 2. Support Vector Machine (SVM)
Support Vector Machine merupakan algoritma yang membangun batas keputusan untuk memisahkan kelas berdasarkan pola pada data. SVM digunakan sebagai model pembanding untuk mengklasifikasikan pelanggan ke dalam kategori churn dan non-churn.

## Tahapan Pengerjaan
Alur pengerjaan proyek prediksi *customer churn* meliputi:
1. **Data Understanding** — memahami struktur, atribut, dan karakteristik dataset.
2. **Data Preprocessing** — menyiapkan data agar dapat digunakan dalam proses pemodelan, sesuai kebutuhan dataset.
3. **Exploratory Data Analysis (EDA)** — mengeksplorasi distribusi data dan pola yang berkaitan dengan churn.
4. **Model Development** — membangun model menggunakan XGBoost dan SVM.
5. **Model Evaluation** — mengevaluasi performa model menggunakan metrik klasifikasi.
6. **Model Comparison** — membandingkan hasil kedua model berdasarkan hasil evaluasi.

## Evaluasi Model
Evaluasi model dapat mencakup metrik berikut, apabila digunakan dalam pengerjaan proyek:
- **Accuracy** — proporsi prediksi yang benar dari seluruh data.
- **Precision** — ketepatan model ketika memprediksi pelanggan churn.
- **Recall** — kemampuan model dalam mengidentifikasi pelanggan yang benar-benar churn.
- **F1-Score** — keseimbangan antara precision dan recall.
- **Confusion Matrix** — ringkasan hasil prediksi berdasarkan kelas aktual dan kelas prediksi.
Hasil evaluasi dan perbandingan XGBoost dengan SVM akan dicantumkan berdasarkan hasil eksperimen yang diperoleh.

## Hasil Proyek
Bagian ini dapat dilengkapi dengan hasil evaluasi, perbandingan performa XGBoost dan SVM, visualisasi yang dihasilkan, serta kesimpulan mengenai model yang memberikan performa terbaik berdasarkan eksperimen.
