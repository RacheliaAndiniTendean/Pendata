# Data Preparation

Tahap **Data Preparation** merupakan fase ketiga dalam model CRISP-DM yang berfokus pada proses pembersihan, transformasi, dan penyusunan data agar siap digunakan dalam tahap modelling. Data yang diperoleh pada tahap sebelumnya umumnya masih berupa data mentah (raw data) yang belum sepenuhnya memenuhi persyaratan kualitas dan struktur untuk analisis.

Pada tahap ini, praktisi data melakukan berbagai perlakuan terhadap data untuk memastikan bahwa data bersih, konsisten, dan sesuai dengan kebutuhan algoritma. Proses Data Preparation sering kali menjadi fase yang paling memakan waktu karena kualitas model sangat bergantung pada kualitas data yang dipersiapkan.

Secara umum, tujuan dari Data Preparation adalah menghasilkan dataset final yang siap digunakan dalam proses modelling.

## 1. Select Data

Proses ini mencakup kegiatan pemilihan data yang relevan dengan tujuan analisis. Tidak semua data yang tersedia perlu digunakan, sehingga diperlukan pertimbangan terhadap variabel maupun record yang akan disertakan.

### Contoh aktivitas:

* Memilih atribut yang relevan dengan tujuan modelling
* Mengeliminasi variabel yang tidak signifikan
* Menentukan subset data yang akan digunakan
* Mendokumentasikan alasan inklusi dan eksklusi data

Tahap ini memastikan bahwa analisis difokuskan pada data yang benar-benar diperlukan.

## 2. Clean Data

Tahap ini berfokus pada perbaikan masalah kualitas data yang dapat memengaruhi hasil analisis. Data mentah sering kali mengandung berbagai permasalahan yang perlu ditangani sebelum digunakan.

### Contoh aktivitas:

* Mengidentifikasi dan menangani missing values
* Menghapus data duplikat
* Memperbaiki inkonsistensi data
* Mengelola outlier
* Memeriksa validitas data

Masalah kualitas data yang umum ditemui antara lain:

* Missing values
* Outlier
* Noise data
* Kesalahan input
* Inkonsistensi nilai

Pembersihan data yang tepat sangat penting untuk menjaga keandalan model.

## 3. Construct Data

Proses ini mencakup pembangunan variabel turunan (derived attributes) yang dapat memperkaya informasi dalam dataset. Variabel baru sering kali membantu model menangkap pola yang lebih kompleks.

### Contoh aktivitas:

* Feature engineering
* Transformasi variabel
* Agregasi data
* Pembuatan atribut baru

Tahap ini bertujuan meningkatkan kualitas representasi data.

## 4. Integrate Data

Tahap ini melibatkan penggabungan data dari berbagai sumber untuk membentuk dataset yang lebih lengkap dan komprehensif.

Contoh aktivitas:

* Menggabungkan beberapa dataset
* Menyelaraskan struktur data
* Menangani perbedaan format data
* Mengintegrasikan data dari berbagai sistem

Integrasi data memastikan bahwa seluruh informasi relevan tersedia dalam satu dataset.

## 5. Format Data

Proses ini bertujuan menyesuaikan format dan struktur data agar kompatibel dengan teknik analisis atau algoritma modelling.

Contoh aktivitas:

* Mengonversi tipe data
* Normalisasi atau standarisasi data
* Encoding variabel kategorikal
* Reformatting dataset

Tahap ini memastikan bahwa data siap diproses oleh model.

## Dataset

Dataset merupakan hasil utama dari tahap Data Preparation. Dataset ini merepresentasikan data yang telah melalui proses seleksi, pembersihan, konstruksi, integrasi, serta pemformatan.

Dataset yang dihasilkan pada tahap ini umumnya memiliki karakteristik berikut:

* Data telah bersih dari kesalahan dan inkonsistensi
* Missing values telah ditangani
* Outlier telah dikelola
* Struktur data telah sesuai kebutuhan model
* Format data telah kompatibel dengan algoritma

Dataset selanjutnya digunakan dalam tahap modelling, dan dalam praktiknya sering kali dibagi menjadi:

* Training dataset
* Testing dataset

Kualitas dataset sangat menentukan performa model yang dibangun.

---

Secara keseluruhan, tahap Data Preparation bertujuan memastikan bahwa data telah memenuhi persyaratan kualitas, konsistensi, dan struktur sebelum memasuki tahap modelling. Dataset yang dihasilkan pada tahap ini menjadi fondasi utama dalam pembangunan model analitik.
