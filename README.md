# Customer-Segmentation-Analysis

# Menyelesaikan permasalahan Superstore online dalam mengidentifikasi berbagai kelompok customer

## Bussiness Understanding
Sebuah toserba biasanya memiliki banyak pelanggan dengan karakteristik dan preferensi yang berbeda-beda. 
Hal ini tentunya mempersulit toserba tersebut dalam mengidentifikasi pelanggannya. 
Oleh karena itu, ia membutuhkan bantuan seorang data scientist untuk mengidentifikasi berbagai kelompok pelanggan sehingga dapat membuat strategi bisnis yang efektif untuk menjaga serta meningkatkan kepuasan pelanggan tersebut.

## Project Scope
pada proyek ini Saya akan menerapkan dua metode untuk melakukan customer segmentation yaitu RFM analysis dan machine learning. Algoritma machine learning yang digunakan akan disesuaikan dengan keadaan dataset (akan ditentukan pada Customer Segmentation dengan Machine Learning).

Selain itu, Saya juga akan melakukan sedikit proses Exploratory Data Analysis (EDA) untuk memperoleh gambaran terkait dataset yang akan kita gunakan. Pada prosesnya, Saya juga akan coba melihat karakteristik dari setiap kelompok data (berdasarkan beberapa kolom kategoris) yang terdapat dalam dataset. 

Berdasarkan cakupan proyek tersebut, Saya membutuhkan beberapa resource dan tool, yaitu:
- data transaksi setiap pelanggan [(superstore dataset)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final);
- bahasa pemrograman Python sebagai tool utama kita dalam proyek ini; serta
- berbagai library pendukung untuk pengolahan data dan pengembangan model machine learning.

## Setup Environment - Anaconda

1. Clone Repository
   ```bash
   git clone https://github.com/RozyRangkuti/Student-Dropout-Analysis-and-Prediction.git
   ```

2. Buka Terminal Anaconda, jalankan perintah berikut untuk membuat environment baru
   ```bash
   conda create --name myenv python=3.11
   ```
   
3. Aktifkan virtual environment dengan menjalankan perintah berikut ini
   ```bash
   conda activate myenv
   ```
   
4. Install semua requirements di dalam file "requirements.txt"
   ```bash
   pip install -r requirements.txt
