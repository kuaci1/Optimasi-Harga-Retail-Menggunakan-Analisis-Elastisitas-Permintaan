# Optimasi Harga Retail: Analisis Elastisitas Permintaan 

## Disclaimer Data
**Penting:** Dataset yang digunakan dalam proyek ini adalah **Data Sintetis** (*Synthetic/Generated Data*).
Data ini dibuat menggunakan simulasi Python dengan logika ekonomi (Hukum Permintaan) dan penambahan *random noise* untuk meniru perilaku pasar nyata. Tujuannya adalah untuk mendemonstrasikan kemampuan analisis statistik dan pemodelan strategi tanpa menggunakan data rahasia perusahaan.

## Ringkasan Eksekutif
Proyek ini bertujuan untuk menentukan titik harga optimal (*Sweet Spot*) guna memaksimalkan pendapatan (*Revenue Maximization*). Dengan mensimulasikan data penjualan selama 365 hari, kita menganalisis bagaimana perubahan harga mempengaruhi jumlah permintaan (*Price Elasticity of Demand*).

**Hasil Utama:**
Berdasarkan simulasi, produk ditemukan bersifat **Inelastis**. Model merekomendasikan kenaikan harga dari rata-rata **Rp 48.637** menjadi **Rp 62.000**, yang diproyeksikan menghasilkan pendapatan maksimal sebesar **Rp 7,7 Juta** (pada skala sampel harian).

## Metodologi Pembuatan Data
Karena dataset ini adalah simulasi, berikut adalah logika yang digunakan untuk men-generate data:
1.  **Rentang Waktu:** 365 hari.
2.  **Variabel Harga:** Diacak antara Rp 30.000 - Rp 70.000.
3.  **Fungsi Permintaan:** Menggunakan persamaan linear `Q = a - bP + noise`, di mana permintaan turun seiring kenaikan harga.
4.  **Noise:** Menambahkan distorsi acak (distribusi normal) agar data terlihat realistis dan tidak linear sempurna.

## Hasil Analisis & Visualisasi
### 1. Kurva Optimasi Revenue
Grafik di bawah ini menunjukkan hubungan antara Harga (Sumbu X) dan Total Pendapatan (Sumbu Y). Titik merah menandakan harga terbaik untuk profit maksimal.
### 2. Temuan Kunci dari Grafik
* **Current State:** Rata-rata harga saat ini adalah **Rp 48.637**.
* **Optimal Price:** Titik puncak kurva berada di **Rp 62.000**.
* **Max Revenue:** Potensi pendapatan tertinggi adalah **Rp 7.753.972**.
* **Gap:** Harga saat ini berada di sisi kiri puncak kurva (*underpriced*), yang berarti ada peluang untuk menaikkan harga guna meningkatkan margin keuntungan.
## Rekomendasi Bisnis (Simulasi)
Jika ini adalah skenario nyata, rekomendasi untuk manajemen adalah:
1.  **Penyesuaian Harga:** Naikkan harga secara bertahap menuju Rp 62.000.
2.  **Strategi:** Karena produk bersifat inelastis (volume penjualan tidak anjlok drastis saat harga naik), fokus perusahaan sebaiknya pada **profitability** daripada mengejar volume penjualan semata..
  
