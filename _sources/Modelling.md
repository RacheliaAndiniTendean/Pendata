# Penambangan Data (Data Mining)

## Pengertian Penambangan Data

Penambangan data merupakan proses analitik yang bertujuan untuk mengekstraksi pola, hubungan, atau informasi yang bermakna dari kumpulan data berukuran besar. Proses ini memanfaatkan teknik statistika, machine learning, serta metode komputasional untuk mengidentifikasi pengetahuan tersembunyi yang tidak mudah terlihat melalui pengamatan biasa.

## Penerapan Penambangan Data

Dalam konteks pengolahan data modern, data mining berperan sebagai pendekatan sistematis untuk mengubah data mentah menjadi wawasan yang dapat digunakan dalam pengambilan keputusan. Dengan kata lain, data mining tidak hanya berfokus pada pengolahan data, tetapi juga pada penemuan informasi yang relevan dan bernilai.

Penambangan data banyak diterapkan di berbagai bidang, seperti bisnis, kesehatan, pendidikan, keuangan, hingga teknologi, karena kemampuannya dalam membantu organisasi memahami data secara lebih mendalam.

## Tujuan Penambangan Data

Secara umum, tujuan utama data mining adalah menemukan pola atau struktur dalam data yang dapat mendukung proses analisis dan pengambilan keputusan. Informasi yang diperoleh dapat digunakan untuk keperluan prediksi, segmentasi, klasifikasi, maupun identifikasi hubungan antar variabel.

Melalui data mining, organisasi dapat:

* Mengidentifikasi tren atau kecenderungan data
* Memahami perilaku pengguna atau pelanggan
* Memprediksi kejadian di masa depan
* Mendukung strategi bisnis berbasis data

## Metodologi CRISP-DM

CRISP-DM (Cross-Industry Standard Process for Data Mining) merupakan kerangka kerja yang banyak digunakan untuk memandu pelaksanaan proyek penambangan data secara sistematis. Model ini menggambarkan alur proses yang terstruktur namun bersifat iteratif, sehingga memungkinkan adanya evaluasi dan penyempurnaan pada setiap tahap. Secara konseptual, CRISP-DM terdiri dari enam fase utama yang saling berkaitan, mulai dari pemahaman bisnis hingga penerapan hasil analisis. Ilustrasi berikut menunjukkan siklus proses CRISP-DM:

![](https://cdn.mathpix.com/snip/images/o6ZUt_FeEaEHTJVxD9MUp3LVu7pcmiFnw4mUMvfhU8c.original.fullsize.png)

# Modelling

Tahap **Modelling** merupakan fase keempat dalam model CRISP-DM yang berfokus pada pembangunan model analitik, baik untuk tujuan prediktif maupun deskriptif. Pada tahap ini, data yang telah dipersiapkan digunakan untuk menerapkan teknik statistika dan Machine Learning guna menemukan pola, hubungan, atau membuat prediksi.

Proses modelling melibatkan pemilihan teknik data mining, algoritma yang sesuai, serta penggunaan perangkat lunak atau tools analitik. Pemilihan teknik modelling harus disesuaikan dengan tujuan bisnis dan karakteristik data yang tersedia.

Apabila dalam proses modelling ditemukan bahwa data belum sepenuhnya sesuai dengan kebutuhan algoritma, maka praktisi data dapat kembali ke tahap Data Preparation untuk melakukan penyesuaian.

Secara umum, tujuan dari tahap Modelling adalah menghasilkan model yang mampu merepresentasikan pola data secara akurat dan relevan dengan tujuan analisis.


## 1. Select Modelling Techniques

Tahap ini mencakup proses pemilihan teknik modelling yang sesuai dengan tujuan analisis dan jenis permasalahan yang dihadapi.

### Contoh aktivitas:

* Menentukan jenis teknik modelling (prediktif atau deskriptif)  
* Memilih algoritma yang relevan, seperti regresi, decision tree, atau neural network  
* Menyesuaikan teknik modelling dengan karakteristik data  
* Mendefinisikan asumsi modelling (*modelling assumptions*)  

Beberapa teknik modelling yang umum digunakan antara lain:

* Classification  
* Clustering  
* Ranking  
* Scoring  
* Finding Relation  
* Characterization  

Pemilihan teknik yang tepat akan memengaruhi kualitas model yang dihasilkan.


## 2. Generate Test Design

Tahap ini bertujuan merancang strategi evaluasi model untuk memastikan performa model dapat diukur secara objektif.

### Contoh aktivitas:

* Menentukan metode pembagian data (training dan testing)  
* Menentukan teknik validasi model  
* Menetapkan metrik evaluasi (akurasi, presisi, recall, dll.)  
* Menyusun test design  

Perancangan evaluasi yang baik penting untuk menghindari bias model.


## 3. Build Model

Pada tahap ini, teknik modelling yang telah dipilih diterapkan pada dataset menggunakan algoritma yang sesuai.

### Contoh aktivitas:

* Melatih model menggunakan training dataset  
* Menentukan parameter model (*parameter settings*)  
* Melakukan tuning parameter  
* Mengoptimalkan performa model  
* Mendokumentasikan model (*model description*)  

Tahap ini menghasilkan model awal yang siap dievaluasi.


## 4. Assess Model

Tahap ini berfokus pada evaluasi performa model untuk memastikan bahwa model telah memenuhi kriteria keberhasilan yang ditetapkan.

### Contoh aktivitas:

* Mengevaluasi model menggunakan testing dataset  
* Mengukur performa model dengan metrik evaluasi  
* Membandingkan beberapa model  
* Melakukan revisi parameter jika diperlukan (*revised parameter settings*)  

Jika model belum memenuhi ekspektasi, proses modelling dapat diulang atau kembali ke tahap Data Preparation.

---

Secara keseluruhan, tahap **Modelling** bertujuan menghasilkan model yang mampu menggambarkan pola data secara akurat dan mendukung pengambilan keputusan. Kualitas model sangat dipengaruhi oleh ketepatan pemilihan teknik, algoritma, serta kualitas dataset yang digunakan.
