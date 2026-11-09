# Kebun59 — Manajemen Kebun & Usaha Bibit

Aplikasi web responsif untuk pencatatan dan pemantauan operasional kebun serta usaha pembibitan.

## Modul aplikasi
- Dashboard: ringkasan tanaman, produksi stek, stok, omzet, dan pengeluaran.
- Inventaris Tanaman dan Inventaris Alat.
- Stok Bahan.
- Log Perawatan dan Log Stek.
- Produksi & Stok Bibit.
- Penjualan dan Pengeluaran.
- Laporan dan Panduan.

## Fitur
- Tambah, edit, hapus, dan cari data pada setiap modul.
- Impor workbook Excel (.xlsx/.xls) berdasarkan sheet pada template Kebun59.
- Ekspor seluruh data ke workbook Excel.
- Ekspor CSV per modul.
- Penyimpanan lokal melalui browser (localStorage).

## Menjalankan secara lokal
Buka `index.html` menggunakan browser modern. Fitur impor/ekspor Excel memerlukan koneksi internet untuk memuat SheetJS dari CDN.

## Deploy ke GitHub Pages
1. Buka **Settings → Pages** pada repository.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu proses deploy selesai. URL situs akan ditampilkan di halaman Pages.

## Penting tentang data
Versi ini adalah MVP frontend tanpa backend, login, atau sinkronisasi cloud. Data tersimpan di browser dan perangkat yang digunakan. Data tidak otomatis muncul di browser/perangkat lain. Ekspor workbook secara berkala sebagai cadangan. Jangan hapus data browser sebelum mengekspor data.

## Teknologi
HTML, CSS, JavaScript, localStorage, dan SheetJS (CDN).
