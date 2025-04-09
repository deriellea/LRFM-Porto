# Store Bike LRFM Analysis Portofolio
Team Members:
JCDS 2602
- [Alfidhiya Amany R.](github.com/alfidhiya)
- [Derielle Aisyah Ahmad](github.com/deriellea)
- [Hasson Josia](github.com/hassonjosia)

## Table of Contents
- [Latar Belakang](https://github.com/deriellea/LRFM-Porto/edit/main/README.md#latar-belakang)
- [Rumusan Masalah](https://github.com/deriellea/LRFM-Porto/edit/main/README.md#rumusan-masalah)
- [LRFM Analysis](https://github.com/deriellea/LRFM-Porto/edit/main/README.md#lrfm-analysis)
- [Kesimpulan dan Rekomendasi](https://github.com/deriellea/LRFM-Porto/edit/main/README.md#kesimpulan-dan-rekomendasi)
- [File Content](https://github.com/deriellea/LRFM-Porto/edit/main/README.md#file-content)

## Latar Belakang
Portofolio ini menggunakan data transaksi dasri suatu toko sepeda yang melakukan penjualan secara *online* dan *offline*. Pembuatan portofolio ini adalah untuk melakukan analisis mengenai segmentasi konsumen pada toko sepeda dan memberikan rekomendasi bisnis berdasarkan segmentasi konsumen yang telah dibuat.

Toko sepeda dalam menghadapi persaingan bisnis yang ketat perlu memahami karakteristik dan perilaku pelanggannya secara lebih mendalam. Analisis LRFM dapat dilakukan untuk mengelompokkan pelanggan dari toko sepeda. Pengelompokkan konsumen dapat membantu toko sepeda dalam menentukan perlakuan bisnis yang sesuai dengan masing-masing kelompok konsumen.

## Rumusan Masalah
Segmentasi konsumen dilakukan untuk mengelompokkan pelanggan berdasarkan kesamaan tertentu seperti prefrensi, kebiasaan berbelanja ataupun demografi. Tanpa segmentasi yang tepat toko sepeda berisiko untuk mengambil keputusan bisnis yang kurang efektif. Pertanyaan yang perlu dijawab dalam analisis ini adalah:
1. Bagaimana cara mengelompokkan konsumen sehingga kita dapat membagi konsumen berdasarkan perilaku belanja mereka?
2. Keputusan bisnis seperti apa yang sesuai dengan setiap segmen konsumen yang telah dibuat?

Perumusan segmentasi konsumen perlu dilakukan secara optimal sehingga keputusan bisnis dapat disesuaikan dengan karakteristik masing-masing segmen konsumen.

## LRFM Analysis
Pada bagian ini, feature yang digunakan adalah *Length*, *Recency*, *Frequency*, dan *Monetary* dari konsumen. Keempat hal ini menggambarkan perilaku konsumen.
- *Length* : Durasi atau panjang waktu hubungan antara konsumen dan perusahaan
- *Recency* : Seberapa baru atau terkininya suatu transaksi yang dilakukan konsumen dimana semakin kecil nilainya maka semakin baru transaksi tersebut, yang menunjukkan bahwa pelanggan masih aktif
- *Frequency* : Jumlah transaksi yang telah dilakukan oleh konsumen pada periode waktu tertentu
- *Monetary* : Total nilai atau jumlah uang yang dihabiskan oleh pelanggan selama periode waktu tertentu. Semakin tinggi nilainya, semakin berharga pelanggan tersebut bagi perusahaan.

## Tableau Dashboard Visualization
- [**Store Bike Tableau Dashboard**](https://public.tableau.com/app/profile/alfidhiya.amany.ramli/viz/StoreBikeLRFMAnalysisDashboard/LRFMDashboard)


## Kesimpulan dan Rekomendasi
Analisis LRFM pada Store Bike bermanfaat untuk mengelompokkan konsumen berdasarkan perilaku transaksinya. Sehingga, dapat diperoleh rekomendasi bisnis yang sesuai untuk mempertahankan customer.

## File Content
- [**store_bike.csv**](https://github.com/deriellea/LRFM-Porto/blob/main/store_bike.csv) - dataset yang digunakan
- [**store_bike_clean.csv**](https://github.com/deriellea/LRFM-Porto/blob/main/store_bike_clean.csv) - dataset gabungan yang sudah melalui preprocessing
- [**Offline Complete.csv**](https://github.com/deriellea/LRFM-Porto/blob/main/Offline%20Complete.csv) - dataset transaksi offline yang sudah melalui preprocessing
- [**Online Complete.csv**](https://github.com/deriellea/LRFM-Porto/blob/main/Online%20Complete.csv) - dataset transaksi online yang sudah melalui preprocessing
- [**Offline Store Bike.csv**](https://github.com/deriellea/LRFM-Porto/blob/main/Offline%20Store%20Bike.csv) - dataset hasil analisis LRFM transaksi offline
- [**Online Store Bike.csv**](https://github.com/deriellea/LRFM-Porto/blob/main/Online%20Store%20Bike.csv) - dataset hasil analisis LRFM transaksi online
