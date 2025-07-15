# 🏠 Boston Housing Price Analysis

Boston adalah ibu kota negara bagian Massachusetts, Amerika Serikat, dan merupakan salah satu kota tertua sekaligus pusat pendidikan, sejarah, dan budaya di wilayah New England. Dikenal dengan banyak universitas ternama seperti Harvard dan MIT, Boston memiliki daya tarik tersendiri baik untuk penduduk lokal maupun pendatang.

Seiring berkembangnya kota dan meningkatnya permintaan tempat tinggal, harga rumah di Boston terus mengalami perubahan. Namun, **harga rumah di kota ini tergolong tinggi dan tidak merata**, dipengaruhi oleh berbagai faktor sosial, ekonomi, dan lingkungan. Kondisi ini memunculkan pertanyaan penting: **apa saja yang benar-benar memengaruhi harga rumah di Boston?**

Melalui proyek analisis data ini, dilakukan eksplorasi dan visualisasi terhadap dataset Boston Housing dari tahun 1970 untuk memahami variabel-variabel yang berkontribusi terhadap nilai properti.

---

### 🎯 Research Question

1. Faktor apa saja yang paling berpengaruh terhadap harga rumah di Boston?  
2. Apakah tingkat kejahatan (CRIM) berpengaruh negatif terhadap harga rumah?  
3. Apakah rasio murid-guru (PTRATIO) berkorelasi dengan harga rumah?  
4. Apakah kedekatan dengan Sungai Charles (CHAS) berdampak signifikan terhadap harga rumah?  
5. Apakah rumah di area dengan pajak tinggi (TAX) memiliki harga jual lebih rendah?

---

### 📈 Model Prediksi

Selain analisis eksploratif, proyek ini juga menggunakan **Linear Regression** untuk memprediksi harga rumah. Model ini diuji menggunakan metrik evaluasi seperti:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Model diuji sebelum dan sesudah penghapusan outlier untuk melihat pengaruhnya terhadap performa prediksi. Hasil menunjukkan bahwa pembersihan data berdampak signifikan dalam meningkatkan akurasi model.

---

### 📦 Dataset

Dataset yang digunakan adalah **Boston Housing Dataset** dari Kaggle (https://www.kaggle.com/datasets/vikrishnan/boston-house-prices/data). Setiap baris data merepresentasikan satu kota atau desa di sekitar Boston, dengan berbagai atribut seperti:
- CRIM: Tingkat kejahatan per kapita
- RM: Jumlah rata-rata kamar
- TAX: Tingkat pajak properti
- PTRATIO: Rasio murid-guru
- CHAS: Kedekatan dengan Sungai Charles
- ... dan lainnya.

---

### 🚀 Tools & Library

- Python
- Pandas
- Seaborn & Matplotlib
- Scikit-learn

---

### 📊 Hasil Akhir

Hasil akhir menunjukkan bahwa:
- Harga rumah di Boston paling dipengaruhi oleh jumlah rata-rata kamar, diikuti oleh tingkat kejahatan dan rasio murid-guru. Semakin tinggi kejahatan, semakin rendah harga rumah. Rumah dekat sungai cenderung lebih mahal dan bervariasi, meskipun ada pengecualian pada rumah jauh dari sungai. Analisis juga menunjukkan bahwa rumah di area dengan pajak tinggi memiliki harga jual lebih rendah.
- Penghapusan outlier meningkatkan akurasi model secara signifikan: error menjadi lebih kecil dan model lebih baik dalam menjelaskan variasi harga. Hal ini membuktikan bahwa pembersihan data penting untuk performa model prediksi harga rumah.

---
