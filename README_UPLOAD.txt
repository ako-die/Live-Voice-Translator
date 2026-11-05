LIVE VOICE TRANSLATOR — V1.1
================================

CARA UPDATE GITHUB PAGES
1. Buka repository GitHub: live-voice-translator.
2. Ganti index.html dan manifest.webmanifest di folder utama.
3. Upload/ganti splash-screen.png di folder utama.
4. Upload/ganti icon-192.png, icon-512.png, dan favicon.png di folder icons.
5. Pertahankan struktur folder berikut:

/
  index.html
  manifest.webmanifest
  splash-screen.png
  .nojekyll
  icons/
    icon-192.png
    icon-512.png
    favicon.png

PERBAIKAN V1.1
- Validasi status dan isi respons MyMemory.
- Mencoba Apertium sebagai cadangan hanya bila pasangan bahasa tersedia.
- Hasil kosong atau pesan kegagalan tidak lagi ditampilkan sebagai terjemahan sukses.
- Jika kedua layanan gagal, aplikasi menampilkan peringatan dan tidak membacakan hasil keliru.
- Tema oranye, putih, navy serta splash/icon Created by dee dipertahankan.

CATATAN
Perbaikan ini meningkatkan pemeriksaan hasil, tetapi tidak menjamin seluruh pasangan bahasa akurat. Layanan gratis tanpa API key memiliki batas dan dukungan yang dapat berubah. Untuk terjemahan kerja yang konsisten lintas banyak bahasa, nantinya dibutuhkan layanan terkelola/berbayar atau backend sendiri.
Gunakan Chrome atau Edge terbaru, koneksi internet, dan izinkan mikrofon.
