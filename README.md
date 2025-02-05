# Analisis Fluktuasi Harga Saham Indonesia Sektor Pertambangan

## Deskripsi
Penelitian ini menganalisis fluktuasi harga saham Indonesia pada sektor pertambangan menggunakan data harga saham PT Alumindo Light Metal Industry Tbk (ALMI.JK), PT Bayan Resources Tbk (BYAN.JK), PT Gunung Raja Paksi Tbk (GGRP.JK), dan PT Indal Aluminium Industry Tbk (INAI.JK). Data yang digunakan mencakup periode 1 Desember 2023 hingga 1 Desember 2024, yang diperoleh dari laman finance.yahoo.com. Data yang digunakan adalah harga penutupan yang disesuaikan (adjusted closing price).

## Tujuan
Analisis ini bertujuan untuk mempelajari perbedaan karakteristik fluktuasi nilai log return pada keempat saham, menganalisis normalitas data, dan melakukan estimasi risiko menggunakan metode Block Maxima (BM) dan Peaks Over Threshold (POT) untuk mengidentifikasi nilai ekstrem dalam log return saham.

## Metode
1. **Analisis Log Return:**
   - Menghitung rata-rata (mean) dan volatilitas (variansi) dari log return untuk masing-masing saham.
   - Menggunakan Boxplot untuk mengidentifikasi pencilan (outliers) pada data.
   - Uji normalitas menggunakan Kolmogorov-Smirnov untuk memverifikasi apakah data log return mengikuti distribusi normal.

2. **Metode Block Maxima (BM):**
   - Menggunakan distribusi Generalized Extreme Value (GEV) untuk mengestimasi parameter dan menguji kesesuaian distribusi data dengan GEV.

3. **Metode Peaks Over Threshold (POT):**
   - Menentukan nilai ekstrem berdasarkan ambang batas (threshold) dan mengestimasi parameter dengan menggunakan Generalized Pareto Distribution (GPD).
   - Uji kesesuaian distribusi GPD untuk memverifikasi apakah data ekstrem mengikuti distribusi GPD.

## Hasil
- **Fluktuasi Harga Saham:**
  - ALMI.JK menunjukkan potensi kerugian, sementara BYAN.JK dan GGRP.JK relatif stabil.
  - GGRP.JK memiliki volatilitas tertinggi, sementara BYAN.JK paling stabil.

- **Normalitas Data:**
  - Berdasarkan uji Kolmogorov-Smirnov, data log return keempat saham tidak berdistribusi normal, dengan P-Value < 0,05, menunjukkan adanya nilai ekstrem.

- **Estimasi Parameter BM:**
  - INAI.JK memiliki nilai parameter shape terbesar, menunjukkan potensi terjadinya nilai ekstrem yang lebih besar.

- **Estimasi Parameter POT:**
  - GGRP.JK menunjukkan nilai parameter shape terbesar pada pendekatan POT, yang mengindikasikan risiko ekstrem yang lebih tinggi.
