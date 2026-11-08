BARAMUDA PWA

ISI FOLDER
- index.html: aplikasi BARAMUDA versi terakhir
- manifest.webmanifest: identitas aplikasi dan ikon
- sw.js: cache offline untuk shell aplikasi
- icons/: ikon aplikasi

CARA ONLINEKAN
1. Upload seluruh isi folder ini ke hosting HTTPS (misalnya GitHub Pages, Netlify, atau Vercel).
2. Pastikan index.html berada di root folder website.
3. Buka URL website di Android menggunakan Chrome, lalu pilih Install app / Tambahkan ke layar utama.
4. Di iPhone, buka URL dengan Safari > Share > Add to Home Screen.
5. Di komputer, buka URL dengan Chrome/Edge lalu pilih Install.

CATATAN
- PWA membutuhkan hosting HTTPS agar install dan service worker aktif.
- Aplikasi dan cache shell dapat dibuka kembali offline setelah pertama kali berhasil dimuat.
- Data pertandingan masih tersimpan lokal pada browser/perangkat masing-masing. Belum ada sinkronisasi cloud antarperangkat.
