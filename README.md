# Tugas-Besar-ADS-2025-Kelompok-8-RA
# Analisis Pengaruh Jarak Rumah ke Kampus terhadap Keterlibatan Mahasiswa dalam Organisasi

## Cara Menjalankan Script
1. Pastikan sudah menginstall **R** dan **RStudio**.
2. Clone atau download repository ini.
3. Buka file script utama (misalnya `analisis.R`) di RStudio.
4. Pastikan semua paket yang diperlukan telah terinstall (lihat bagian "Paket R yang Digunakan").
5. Jalankan script dengan:
   - Klik **Run**, atau
   - Tekan **Ctrl + Enter**, atau
   - Jalankan seluruh file dengan `source("analisis.R")`.

## Paket R yang Digunakan
Script ini memerlukan beberapa paket berikut:
- **tidyverse** – manipulasi data dan visualisasi (ggplot2, dplyr, tidyr)
- **readr** – membaca data CSV
- **ggplot2** – membuat visualisasi
- **forcats** – mengatur urutan faktor (opsional)
  
Instalasi paket (jika belum terpasang):
```r
install.packages(c("tidyverse", "readr", "ggplot2", "forcats"))

## Penjelasan Singkat Dataset

Dataset terdiri dari data mahasiswa yang mencakup:
Jarak rumah ke kampus (dalam kilometer) yang dibagi ke dalam kategori.
Status Keaktifan mahasiswa dalam organisasi (Aktif / Tidak Aktif).
Data digunakan untuk mengetahui apakah jarak rumah mempengaruhi partisipasi mahasiswa dalam kegiatan organisasi.
Struktur umum dataset:
jarak → kategori jarak (misal: "<1 km", "1–3 km", "3–5 km", "5–10 km", ">10 km")
status → status keaktifan organisasi ("Aktif", "Tidak Aktif")

## Struktur Repository
📁 root/
│
├── Dataset Kelompok&.xlsx
│   → Dataset utama yang digunakan untuk analisis.
│
├── Dataset Tugas Besar ADS 2025 - Karakteristik ....xlsx
│   → Dataset tambahan/mentah yang menjadi sumber awal pengolahan data.
│
├── codeR_8_RA.Rmd
│   → Script R Markdown berisi seluruh proses analisis, visualisasi, dan pengujian hipotesis.
│
├── POSTER_8_RA.pdf
│   → Hasil poster final yang dibuat berdasarkan output analisis.
│
└── README.md
    → Dokumentasi repositori yang berisi cara menjalankan script, paket yang digunakan, dan penjelasan struktur folder.
