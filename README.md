# WA Status Generator

Aplikasi untuk generate preview status WhatsApp secara otomatis dengan fitur download langsung (kustom nama file berdasarkan waktu).

====================== WAJIB INSTALL ======================
1. Install nodeJS
   * Download di situs resminya: https://nodejs.org

2. Install semua library (Puppeteer, Scraper, dll.)
   * Buka CMD/Terminal di folder proyek ini, lalu ketik:
   npm install

3. install puppeteer
 - npm i puppeteer

4. install open-graph-scraper
 - npm install open-graph-scraper --save

====================== CARA JALANKAN ======================

1. Hidupkan server dengan mengetik perintah ini di CMD:
   node server.js

2. Buka browser kamu dan akses alamat berikut:
   localhost:3000

====================== TIPS KUSTOMISASI ======================

* Cek file "foto.jpg" di folder utama:
  Ganti file "foto.jpg" tersebut dengan foto profil kamu sendiri jika ingin mengubah foto profil pada status WA yang di-generate.

* Jika ingin mengubah BULAN dan TANGGAL ACAK hasil download:
  1. Buka folder "public" -> buka file "index.html".
  2. Scroll ke paling bawah pada bagian `function downloadImage()`.
  3. Cari dan ubah angka pada baris `const bulanKustom` dan `tglMin` / `tglMax`.

!!!!!!!!!!!!!!!
DIINGATKAN SEKALI LAGI
JANGAN LUPA GANTI FOTO DAN NAMA FOTO PROFIL DIBUAT "foto.jpg"
!!!!!!!!!!!!!!!