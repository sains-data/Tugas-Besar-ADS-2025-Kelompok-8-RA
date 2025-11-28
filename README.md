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
  
### Instalasi paket (jika belum terpasang):

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
Tugas-Besar-ADS-2025-Kelompok-8-RA/
│
├── code/
│   └── codeR_8_RA.R        # Script utama analisis menggunakan R
│
├── data/
│   └── ...                 # Dataset yang digunakan pada analisis
│
├── poster/
│   └── POSTER_8_RA.pdf     # Poster final tugas besar
│
├── output/                 # (akan ditambahkan)
│   └── ...                 # Output/visualisasi hasil running kode R
│
├── github/
│   └── CODEOWNERS          # Pengaturan reviewer & maintainer repo
│
├── README.md               # Dokumentasi utama (file ini)
└── README/README.md        # Dokumentasi tambahan (jika diperlukan)

🧠 Deskripsi Singkat Project

Tugas besar ini bertujuan melakukan analisis data menggunakan bahasa pemrograman R, meliputi:
- Pengolahan dan pembersihan data
- Eksplorasi data (EDA)
- Uji statistik sesuai kebutuhan analisis
- Visualisasi data
- Kesimpulan dan interpretasi

Semua tahapan dijalankan dan terdokumentasi di folder code/.

🧾 Poster

Poster final berada pada folder:
   poster/POSTER_8_RA.pdf
Berisi rangkuman hasil analisis dalam bentuk visual yang ringkas.

📤 Output (Akan Ditambahkan)

Folder output/ akan berisi:
- Grafik hasil analisis
- Tabel summary
- Export hasil uji statistik
- Hasil visualisasi yang digunakan pada laporan/poster

👥 Kontributor – Kelompok 8 RA
1. M. Alsi Syahrulloh
2. Wielman Itolo Halawa
3. Anash Tasya Ausyaqila
4. Lucia Advencia Rachel N.

Folder ini akan otomatis terisi ketika script R dijalankan.
