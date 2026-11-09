# Kebun59 — Manajemen Kebun & Usaha Bibit

Aplikasi web responsif untuk mengelola inventaris tanaman, peralatan, stok bahan, perawatan, perbanyakan stek, produksi bibit, penjualan, dan pengeluaran.

## Menjalankan
Buka `index.html` melalui browser atau deploy repository ini ke GitHub Pages.

## Fitur
- Dashboard KPI kebun dan usaha bibit.
- CRUD data untuk 8 modul operasional.
- Pencarian, ekspor CSV per modul, backup JSON.
- Impor workbook Excel (.xlsx/.xls) melalui SheetJS.
- Penyimpanan lokal browser (localStorage).

## Catatan
Versi awal ini berjalan tanpa backend dan tanpa autentikasi. Data berada di browser/perangkat yang digunakan, bukan tersinkron antar perangkat. Lakukan backup secara berkala. Untuk penggunaan multi-user/online, integrasikan backend dan database.

## Deploy GitHub Pages
Repository Settings → Pages → Deploy from a branch → pilih `main` dan folder `/ (root)`.
