# Prediksi Customer Churn pada Data Telekomunikasi Menggunakan XGBoost dan Support Vector Machine #

Anggota Kelompok: 
1. Shakyla Andhara Chandraningtyas (24031554199)
2. Desnanty Ratna Aulia (24031554163)
3. Fajria Rasmi Ridha Rumkel (24031554191)

Proyek ini membangun model machine learning untuk memprediksi kemungkinan pelanggan berhenti menggunakan layanan telekomunikasi (customer churn). Dataset yang digunakan adalah Telco Customer Churn dari Kaggle, dengan fitur seperti usia pelanggan, lama berlangganan, jenis kontrak, metode pembayaran, biaya bulanan, dan total tagihan.

Tahapan proyek meliputi eksplorasi data, preprocessing (cleaning, encoding, handling outlier, dan balancing data dengan SMOTE), feature selection menggunakan SelectKBest, serta pembangunan model menggunakan XGBoost dan Support Vector Machine (SVM). Hyperparameter tuning dilakukan menggunakan GridSearchCV untuk meningkatkan performa model.

Hasil evaluasi menunjukkan bahwa model XGBoost dengan tuning GridSearchCV memberikan performa terbaik dengan accuracy sekitar 76% dan F1-score sekitar 61%. Analisis feature importance juga menunjukkan bahwa jenis kontrak pelanggan dan metode pembayaran merupakan faktor paling
