# Implementasi Algoritma SETM (Set-Oriented Mining) untuk Analisis Aturan Asosiasi Transaksi UMKM F&B

Repository ini berisi implementasi  algoritma **Set-Oriented Mining (SETM)** menggunakan bahasa pemrograman Python untuk menggali aturan asosiasi (*Association Rule Mining*) multi-dimensi dari data transaksi aktual UMKM kuliner (*Food & Beverage*) di Indonesia.


* **Sumber Dataset:** *Anonymous Transactional Dataset* — Mendeley Data ([DOI: 10.17632/kcgf45y24m.2](https://doi.org/10.17632/kcgf45y24m.2))
* **Ruang Lingkup Data:** Cabang `SHOP001`, periode `1 Januari 2025 – 31 Januari 2025`, khusus transaksi multi-item (`TotalItem = 2`).
* **Ukuran Sampel Terproses:** **406 transaksi unik** yang ditransformasikan menjadi tabel relasional datar $R_1$ sebanyak **1.526 baris** pasangan `<TID, Item>` (mencakup kategori menu, segmen waktu kunjungan, dan metode pembayaran).

