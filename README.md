# Quranic Homeschooling

Landing page statis untuk kelas online gratis 1–30 Oktober 2026. Buka `index.html` untuk pratinjau. Upload seluruh isi folder ke root repositori GitHub Pages.

## Publikasi di GitHub Pages

1. Buat repositori publik `quranic-homeschooling`, lalu upload `index.html`, `style.css`, `script.js` dan `flyer.png` ke root.
2. Di Settings → Pages, pilih Deploy from a branch → `main` → `/ (root)` → Save.
3. Tambahkan custom domain `quranichomeschooling` yang lengkap dengan ekstensi TLD yang Anda miliki pada Settings → Pages. Buat file `CNAME` di root berisi domain lengkap tersebut setelah domain diketahui.
4. Pada DNS registrar, untuk subdomain buat CNAME ke `ngajiprivatlombok.github.io`. Untuk domain apex, gunakan A records GitHub Pages sesuai dokumentasi GitHub terbaru. Tunggu DNS dan sertifikat HTTPS aktif, lalu aktifkan Enforce HTTPS.

## Batasan pendaftaran

Form membuka pesan WhatsApp; tidak menyimpan data atau mengunci kursi. Kuota 5 siswa per mapel dan ketersediaan waktu harus diperiksa admin. Untuk membatasi otomatis, perlukan backend dengan penyimpanan data dan transaksi atomik, misalnya Apps Script/Sheets dengan LockService atau layanan database. Jangan tampilkan status kuota otomatis sebelum backend tersedia.

Waktu WITA (UTC+8). Setiap sesi 45 menit dengan jeda 5 menit; pilihan 2 sesi pada tanggal berbeda. Sabtu dan Ahad dimulai 10.00 WITA. Validasi tanggal dan usia di browser memudahkan pendaftaran tetapi admin tetap harus memverifikasinya.
