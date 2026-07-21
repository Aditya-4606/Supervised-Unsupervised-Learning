# Supervised_Unsupervised_Learning: Analisis Penjualan Video Game

Repository ini dibuat sebagai pemenuhan Tugas Akhir mata kuliah Fundamen Sains Data. Proyek berfokus pada implementasi **Supervised Learning** dan **Unsupervised Learning** menggunakan dataset penjualan video game global.

## 👥 Anggota Kelompok
* **Muhammad Farhan Haafidh Abror** (245231105)
* **Ahmad Dzaky Al Farras** (24523280)
* **Aditya Muhammad** (24523107)

---

## 📝 Deskripsi Singkat Proyek
Proyek ini melakukan analisis data  mulai dari Exploratory Data Analysis (EDA), Preprocessing, hingga pemodelan Machine Learning. Terdapat dua studi kasus utama yang diselesaikan dalam proyek ini:
1. **Supervised Learning (Klasifikasi):** Menggunakan algoritma **Random Forest Classifier** untuk memprediksi apakah sebuah video game akan menguntungkan (`Is_Profitable`) atau tidak berdasarkan Platform, Genre, dan Tahun Rilis.
2. **Unsupervised Learning (Clustering):** Menggunakan algoritma **K-Means Clustering (K=3)** untuk melakukan segmentasi pasar game berdasarkan angka penjualan di berbagai wilayah (Amerika Utara, Eropa, Jepang, dll), yang menghasilkan 3 cluster: *Standard/Mass Market*, *Global Blockbuster*, dan *Western Market Heavy*.

---

## 📊 Sumber Dataset[cite: 2]
Dataset yang digunakan dalam proyek ini diunduh secara otomatis menggunakan pustaka `kagglehub`.
* **Nama Dataset:** Video Game Sales
* **Sumber:** Kaggle (diunggah oleh *anandshaw2001*)
* **Path Unduhan Kaggle:** `anandshaw2001/video-game-sales`
* **Informasi Fitur Utama:** Berisi informasi nama game, platform, tahun rilis, genre, penerbit (publisher), serta detail penjualan dalam jutaan kopi di berbagai wilayah (`NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`). 

---

## 🚀 Cara Menjalankan Notebook[cite: 2]

Untuk menjalankan source code pada repository ini, ikuti langkah-langkah berikut:

**1. Persiapan Lingkungan (Environment):**
Sangat disarankan untuk membuka dan menjalankan file notebook (`.ipynb`) menggunakan **Google Colab** karena tidak memerlukan instalasi lokal yang rumit.

**2. Instalasi Library (Dependensi):**
Pastikan environment Anda memiliki library berikut. Jika menggunakan Google Colab, Anda hanya perlu menjalankan *cell* instalasi Gradio yang ada di akhir notebook.
```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub gradio
