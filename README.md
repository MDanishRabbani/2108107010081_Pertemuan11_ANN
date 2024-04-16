# Tugas 3 - Muhammad Danish Rabbani - 2108107010081 - Machine Learning

## 1. Dataset Clasification : Dataset Database Diabetes Pima Indians

Link : https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
About:

- Konteks
  Dataset ini berasal dari Institut Nasional Diabetes dan Penyakit Pencernaan dan Ginjal. Tujuan dari dataset ini adalah untuk memprediksi secara diagnostik apakah seorang pasien menderita diabetes atau tidak, berdasarkan pengukuran diagnostik tertentu yang disertakan dalam dataset. Beberapa batasan ditempatkan pada pemilihan contoh-contoh ini dari basis data yang lebih besar. Secara khusus, semua pasien di sini adalah perempuan berusia minimal 21 tahun yang berasal dari suku Indian Pima.
- Konten
  Dataset ini terdiri dari beberapa variabel prediktor medis dan satu variabel target, Hasil. Variabel prediktor meliputi jumlah kehamilan yang pernah dialami pasien, BMI, insulin level, age, dan sebagainya.

## 2. Dataset Regression : Ice Cream Revenue

Link: https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue

## Klasifikasi

1. Menyiapkan library yang diperlukan
2. Melakukan preprocessing
3. Menerapkan metode Klasifikasi menggunakan ANN
4. Melihat akurasi MEA
5. Menampilkan confusion matrix

pada model yang dikerjakan kali ini pada saat melakukan klasifikasi terdapat perbedaan hasil akurasi dengan menggunakan metode SVM pada tugas sebelumnya dengan menggunakan metode ANN pada tugas kali ini, dimana

## Hasil akurasi dari metode SVM untuk klasifikasi adalah sebagai berikut:

- Akurasi: 0.7604166666666666

## sedangkan menggunakan metode ANN untuk klasifikasi adalah sebagai berikut:

Epoch 99/100
62/62 [==============================] - 0s 1ms/step - loss: 0.4935 - accuracy: 0.7638
Epoch 100/100
62/62 [==============================] - 0s 1ms/step - loss: 0.4957 - accuracy: 0.7638

Dalam kasus ini, model ANN dan SVM memberikan hasil yang relatif serupa dalam hal akurasi klasifikasi

## Regresi

1. Menyiapkan library yang diperlukan
2. Melakukan preprocessing
3. Menerapkan metode regresi menggunakan ANN
4. Melihat akurasi
5. Menampilkan visualisasi

pada model yang dikerjakan kali ini pada saat melakukan regresi terdapat perbedaan hasil akurasi dengan menggunakan metode SVM pada tugas sebelumnya dengan menggunakan metode ANN pada tugas kali ini, dimana

## Hasil akurasi dari metode SVM untuk regresi adalah sebagai berikut:

- MAE: 0.11025710845230546
- MSE: 0.021494845030519336
- RMSE: 0.1466112036323259

## sedangkan menggunakan metode ANN untuk regresi adalah sebagai berikut:

- Mean Absolute Error: 19.18818356885576
- Mean Squared Error: 653.2737205053053
- Root Mean Squared Error: 25.55921987278378

model SVM memberikan hasil yang lebih baik dalam hal Mean Absolute Error (MAE), Mean Squared Error (MSE), dan Root Mean Squared Error (RMSE) dibandingkan dengan model ANN. Oleh karena itu, untuk dataset dan masalah yang sama, SVM dapat dianggap sebagai pilihan yang lebih baik untuk memodelkan hubungan antara fitur dan target.
