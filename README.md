# UTS Machine Learning

## Prediksi Harga Sewa Akomodasi Airbnb di Bali Menggunakan Regresi Linear Sederhana dan Berganda

### 1. Identitas Mahasiswa

| Identitas | Keterangan |
|---|---|
| Nama | Anak Agung Gede Krisna Widiana Putra |
| NIM | 2301010589 |
| Kelas | XX |
| Program Studi | Informatika |
| Mata Kuliah | Machine Learning |
| Jalur | B – Regresi |
| Random State | 589 |

### 2. Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi harga sewa akomodasi Airbnb di Bali berdasarkan beberapa karakteristik penginapan, seperti jumlah kamar mandi, jumlah kamar tidur, jumlah tempat tidur, kapasitas tamu, dan jenis penginapan.

Metode regresi dipilih karena target yang ingin diprediksi berupa harga dalam bentuk numerik. Proyek ini dikerjakan menggunakan pendekatan CRISP-DM.

### 3. Dataset

- Nama dataset: listings_bali_201804.csv
- Tema: Pariwisata
- Periode data: April 2018
- Jumlah data awal: 12.228 baris
- Jumlah kolom awal: 29 kolom
- Sumber: https://github.com/daben/m2851-prac1
- Lisensi: CC BY-NC 4.0
- Tanggal akses: [Isi tanggal akses dataset]

Dataset yang disertakan dalam repository telah melalui proses penghapusan kolom yang mengandung identitas pribadi dan pemilihan fitur yang relevan.

### 4. Fitur dan Target

| Kolom | Keterangan |
|---|---|
| bathrooms | Jumlah kamar mandi |
| bedrooms | Jumlah kamar tidur |
| beds | Jumlah tempat tidur |
| person_capacity | Kapasitas tamu |
| room_type | Jenis penginapan |
| price_rate | Target harga penginapan per malam |

### 5. Metode Machine Learning

Model yang digunakan dalam proyek ini:

1. DummyRegressor sebagai baseline.
2. Regresi Linear Sederhana.
3. Regresi Linear Berganda.

Ketiga model dibandingkan menggunakan 5-fold cross-validation dengan random_state = 589.

### 6. Tahapan Pengerjaan

1. Pemahaman masalah dan dataset.
2. Exploratory Data Analysis (EDA).
3. Data cleaning dan preprocessing.
4. Pemodelan Machine Learning.
5. Evaluasi dan interpretasi model.
6. Kesimpulan dan rekomendasi.

### 7. Evaluasi Model

Evaluasi dilakukan menggunakan tiga metrik:

- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).
- R-Squared (R²).

Metrik tersebut digunakan untuk membandingkan performa model regresi dengan baseline serta menentukan model yang sesuai berdasarkan hasil pengujian.

### 8. Tools dan Library

- Google Colab
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

### 9. Cara Menjalankan Proyek

1. Unduh dataset asli melalui sumber yang dicantumkan.
2. Buka file notebook menggunakan Google Colab.
3. Unggah dataset ketika diminta oleh notebook.
4. Pilih Runtime → Run all.
5. Periksa hasil visualisasi, pemodelan, dan evaluasi.

### 10. Pernyataan Penggunaan AI

Dalam pengerjaan proyek ini, saya menggunakan ChatGPT sebagai alat bantu untuk memahami konsep Machine Learning, menyusun tahapan pengerjaan, membantu penulisan kode Python, memahami hasil evaluasi model, serta mempersiapkan materi presentasi.

Pemeriksaan hasil dilakukan dengan menjalankan kode pada Google Colab, memeriksa output yang dihasilkan, dan mempelajari fungsi serta tujuan setiap tahapan pengerjaan.

Penggunaan AI bertujuan membantu proses pembelajaran dan tidak menggantikan tanggung jawab saya dalam memahami serta menjelaskan hasil proyek.
